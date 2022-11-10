[![DOI](https://zenodo.org/badge/564119806.svg)](https://zenodo.org/badge/latestdoi/564119806)

## Comprehensive Human PPI Network and TF Network
A public resource for curated and comprehensive PPI network data.  
The benefit of such a public data resource allows additional information to be integrated based on research question.  
Effort will be made to update this resource every six months from upstream databases.  

The data is in CSV format representing interactions (Gene_A, Gene_B).  

Each network was pruned to have only:
1. Unique interactions i.e., single edges
2. Remove isolated nodes
3. Remove self loops

| Network | Proteins | Interactions |
| ------------- | ------------- | ------------- |
| PPI | 17,798 | 254,214 |
| TF | 1,049 | 3,686 |
   
     
**Protein-protein Interaction Network**  
This comprehensive human PPI network was created from 15 databases.  
This network includes interactions from HuRI, iRefWeb (10 databases internally), IntAct, HPRD, MIPS and PDB.  

**Transcription Factor Network**  
1,639 TFs were mined from the The Human Transcription Factors database (PubMed: 29425488).  
With the comprehensive PPI network as background, a subnetwork was created to contain only the TFs.

 
