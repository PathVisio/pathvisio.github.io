# Interaction Panel to MIM and SBGN

The [new Interaction Panel](Whats-New-GPML2021.md#new-interaction-panel) introduced in GPML2021 is extensible with ArrowHead type plugins: 
* [Molecular Interaction Map (MIM)](#equivalent-mim-arrowhead-types) 
* [Systems Biology Graphical Notation (SBGN)](#equivalent-sbgn-arrowhead-types)

The GPML Interaction Panel ArrowHead types can be mapped to equivalent Old ArrowHead Types and MIM ArrowHead types.  

Because there are many more SBGN ArrowHead types, they are not mapped to the GPML Interaction Panel. The SBGN Plugin handles SBGN Arrowhead types. 

### Equivalent Old ArrowHead Types  

| Interaction Panel ArrowHead type| MIM ArrowHead type |
|:---|:---|
|Undirected (default)|  Line |
|Directed|  Arrow |
|Conversion|  |  
|Inhibition| TBar |
|Catalysis|  |
|Stimulation|  |
|Binding|  |
|Translocation|  |
|Transcription-translation|  |

### Equivalent MIM ArrowHead Types  

| Interaction Panel ArrowHead type| MIM ArrowHead type |
|:---|:---|
|Undirected (default)|  |
|Directed|  |
|Conversion| mim-conversion;  mim-modification, mim-cleavage, mim-gap, mim-branching-right, mim-branching-left |  
|Inhibition| mim-inhibition |
|Catalysis| mim-catalysis |
|Stimulation| mim-stimulation; mim-necessary-stimulation |
|Binding| mim-binding; mim-covalent-bond |
|Translocation| mim-translocation |
|Transcription-translation| mim-transcription-translation |
