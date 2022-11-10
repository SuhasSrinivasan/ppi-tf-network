## Comprehensive Human PPI network and TF network
A public resource for curated and comprehensive PPI network data.  
The benefit of such a public data resource allows additional information to be integrated based on research question.  
Effort will be made to update this resource every six months from upstream databases.

### 1. Human PPI Network
This comprehensive human PPI network was created from 15 databases.  
This network includes interactions from HuRI, iRefWeb (10 databases internally), IntAct, HPRD, MIPS and PDB.  
After merging the various datasets, the network was pruned to have only:
1. Unique interactions i.e., single edges
2. Remove isolated nodes
3. Remove self loops

Finally, there are 17,798 proteins and 254,214 interactions.  
The data is in CSV format indicating interactions (Gene_A, Gene_B).  


### 2. Human TF Network
1,639 TFs were mined from the The Human Transcription Factors database (PubMed: 29425488).  
With the comprehensive PPI network as background, a subnetwork was created to contain only the TFs.
The network was pruned to have only:
1. Unique interactions i.e., single edges
2. Remove isolated nodes
3. Remove self loops

Finally, there are 1,049 proteins and 3,686 interactions.  
The data is in CSV format indicating interactions (Gene_A, Gene_B). 
