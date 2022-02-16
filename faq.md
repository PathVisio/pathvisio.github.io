# Frequently Asked Questions

* [Java Security Settings](#java-security-settings)
* [Using Java 8 in PV while maintaining other Java versions](#running-java-8)
* [General Questions](#general-questions) 
* [Pathway Diagrams](#pathway-diagrams)
* [Gene Expression / Omics Data](#gene-expression-/-omics-data)
* [Plugin Installation](#plugin-installation)
* [Troubleshooting](#troubleshooting)



## Java Security Settings
When starting PathVisio, you might see an error. In the latest Java update the security settings for self-signed applications have been [adapted (Java 7 Update 51)](http://java.com/en/download/faq/release7_changes.xml). Self-Signed applications, like Pathvisio, are blocked on high security level. **PathVisio is still safe to run.** We also are in the progress of registering a certificate which will allow users to also run PathVisio on high security level. Until then, you can either use the binary installation of PathVisio or lower the Java security settings. Instructions on how to set your security settings can be found [here](http://www.java.com/en/download/help/jcp_security.xml).

## Running Java 8
When you have more then one version of Java installed on your computer, you can keep all other Java versions, when you want to use PathVisio.
However, PathVisio (version 3.x) requires Java 8 and cannot work with other versions. Download and install Java 8, and find the folder where you have installed Java 8.

### Windows:
Open the pathvisio.bat file in a text editor.
Change the 3rd line:
```
java -Xmx1024m -jar -Dfile.encoding=UTF-8 pathvisio.jar "$@"
```
to the following line (where "C:\Program Files (x86)\Java\jre1.8.0_271\bin\java.exe" is an example of the folder location for a Java 8 installation):
```
call "C:\Program Files (x86)\Java\jre1.8.0_271\bin\java.exe" -Xmx1024m -jar -Dfile.encoding=UTF-8 pathvisio.jar "$@
```
Save the pathvisio.bat file, close it, and try running Pathvisio again (double click the pathvisio.bat file)
Adding this option allows PathVisio to find your Java 8 version (iso using another Java version which is installed on your computer).

### Mac:
Locate your Java 8 installation: in the Finder choose Go > Go to Folder, enter "/Library/Internet/Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/Bin" into the Go to Folder field, then click Go.
You can also check the Library in your Home folder. In the Finder choose Go > Go to Folder, enter "~/Library/Internet/Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/Bin" into the Go to Folder field, then click Go.

The example below shows the menu to see the location (listed under "where"): 
```
/Library/Internet/Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/Bin
```
![image](https://user-images.githubusercontent.com/26277832/153594709-4cb51cbd-1b85-4fe4-bd84-61c5baf259c7.png)

Open the pathvisio.sh file in a text editor.
Change the 7th line:

```
# Run PathVisio
java -jar -Dfile.encoding=UTF-8 pathvisio.jar "$@"
```
to the following line, using the example folder location for a Java 8 installation:

```
# Run PathVisio
/Library/Internet/Plug-Ins/JavaAppletPlugin.plugin/Contents/Home/Bin/java -jar -Dfile.encoding=UTF-8 pathvisio.jar "$@"
```
Save the pathvisio.sh file, close it, and try running Pathvisio again (double click the pathvisio.jar file).
Adding this option allows PathVisio to find your Java 8 version (iso using another Java version which is installed on your computer).


## General Questions

**1. Help! Where can I ask questions?**

You can just leave us an [issue](https://github.com/PathVisio/pathvisio.github.io/issues) in the Github repository and we will try to help you. 

**2. Can I run PathVisio when I'm offline?**

You can run PathVisio offline, but the plugin manager requires internet connection. 


**3. What is the relation between PathVisio and GenMAPP?**

PathVisio has grown out of a need to extend  [GenMAPP](http://www.genmapp.org/). GenMAPP had many good features, however was limited in terms of its flexibility to adapt to new needs. We cooperated closely with the GenMAPP group to share code and ideas. PathVisio borrows heavily from the good aspects of GenMAPP, such as its simplicity and usability, but tries to improve on other aspects, such as flexibility and expansion to other platforms (linux and Mac OS X). GenMapp is no longer funded or supported at the moment.


**4. What is the relation between PathVisio and Cytoscape?**

PathVisio and Cytoscape are very different programs, but after you install the WikiPathways App in Cytoscape, you will be able to open pathways created in PathVisio in Cytoscape. The WikiPathways App can be installed from the app manager menu within Cytoscape.


**5. What is the relation between PathVisio and WikiPathways?**

PathVisio and [WikiPathways](http://www.wikipathways.org/index.php/WikiPathways) are compatible. Pathways created in PathVisio can be shared on WikiPathways, and pathways from WikiPathways can be opened in PathVisio via the WikiPathways plugin. Also, some of the program code of PathVisio is embedded in WikiPathways, as a Java applet.


**6. How do I cite PathVisio?**

See [HowToCite](cite.md)


**7. Which system codes / data sources are supported for pathway elements?**

Check out the list of supported systems codes [here](https://bridgedb.github.io/pages/system-codes).

**8. How can find unconnected lines?**

Use the CTRL+L shortcut to highlight unconnected lines.

## Pathway Diagrams

**1. What is the meaning of each graphical symbol in pathways?**

See [Pathway Styles](http://pathvisio.org/wiki/PathwayStyles)


**2. Does PathVisio support dynamic layouts of pathways?**

No, PathVisio sees pathways as drawings, not as graphs. This makes the program less complex to use, but if you are more interested in graph-oriented features, we recommend you to take a look at [Cytoscape](https://cytoscape.org/)


**3. Does PathVisio support SBML? How About BioPAX?**

At the moment PathVisio only supports our custom GPML format and GenMAPP MAPP format. BioPAX import / export is currently supported through the [Biopax3 plugin](plugins/biopax.md). Support for SBML is planned.

## Gene Expression / Omics Data

**1. Which microarrays are supported by PathVisio**

Out of the box, common affymetrix, illumina and agilent microarrays are supported


**2. Can I use PathVisio for metabolomics data?**

Yes, you can use PathVisio for many types of large datasets, including metabolomics. PathVisio supports all types of data that can be linked to identifiers on your pathways.


**3. Are my dataset and visualization settings saved?**

Yes, PathVisio creates several files in the directory of your imported dataset.
* The .pgex file contains the dataset itself.
* The .pgex.xml file contains all the visualizations that you created for this dataset.
* The pgex.ex.txt contains possible warnings/errors that occurred when you imported the dataset.
If you want to reopen your dataset including the visualizations, just go to 'Data' -> 'Select expression dataset' and select the .pgex file.

## Plugin Installation

**1. Errors when installing a plugin**

As a first step you can try to clean the PathVisio bundle directory to make sure there are no old libraries that are making problems (be aware this will delete all installed plugins and you will need to re-install them!).
1. Close PathVisio
2. Go to your local PathVisio directory:
* Windows: in your home directory, go into the hidden directory "AppData"- "Roaming" - "PathVisio"
* MacOS / Linux: in your home directory, go into the hidden directory ".PathVisio"
3. Remove the .bundles directory
4. Restart PathVisio


**2. Can't connect to repository**

If you are online but can't connect to the repository, maybe due to proxy settings, follow the steps below to install a plugin. This is a lot more complex than using the plugin manager, so only use it if the plugin manager really doesn't work.
1. Go to http://repository.pathvisio.org/plugins/
2. Go into the directory of the plugin you want to install, then in the version you want to use and then download the jar file
3. Please be aware that you need to download all additional dependencies of the plugin as well. The plugin manager makes sure all dependencies are installed, but when installing it locally you will need to download them manually.
4. Save all jars in a directory.
5. Start PathVisio and go to "Plugins -> Install local plugins". Select the directory that contains all jar files.
6. Select the plugin you want to start.
7. Then the plugin should be installed in PathVisio.

## Troubleshooting

**1. The download link doesn't work**

Try clearing the Java webstart cache, you can find instructions [here](http://www.ngs.ac.uk/ukca/certificates/certwizard/clearwebstartcache). If that doesn't help, please contact our mailing list (see: [MailingLists](contact.md)).


**2. Where can you find the log file?**

You can find your pathvisio.log file in the local PathVisio directory:
* Windows: in your home directory, go into the hidden directory "AppData"- "Roaming" - "PathVisio"
* MacOS / Linux: in your home directory, go into the hidden directory ".PathVisio"

**3. The installation does not work on Linux, what now?**

Error message: 
```bash
bash: ./pathvisio.sh: Permission denied
```
Before being able to run PathVisio, you first need to make the .sh file executable.
From the command line, go to the folder where you have downloaded PathVisio.
Type the first line to make the file executable, and the second to run PathVisio:
```bash
chmod u+x deploy.sh
./pathvisio.sh
```

