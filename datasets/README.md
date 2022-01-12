# Task 5.6 Issues in Providing Open Data in Heritage Science and Archaeology - Intial Datasets
This work has been examining methods of making Heritage Data more accessible and useable, more FAIR. One of the core aspects of this work has been to map to two existinging data structures to the standard [CIDOC CRM](http://www.cidoc-crm.org/) ontology. The work is based on models developed as part of the [IPERION-CH (H2020)](http://www.iperionch.eu/) Research Project.

## Data structure 1: The Raphael Research Resource

The study of paintings by Raphael has produced an exceptional collection of material over the 500 years since their creation in the sixteenth century, covering their history and provenance as well as the materials and techniques used in their making. The Raphael Research Resouce was presented in 2007 as a prototype of how complex digital documentaton, relating to the hostory, study and examination of the old master paintings could be organised and presented. The final [website](https://cima.ng-london.org.uk/documentation/) proved very sucessful and influenced subsequent work. Though the contents of the resource are accessable to human users to borwse and explore it was very difficult to cite or link to specific pieces of data or re-use the data for new presentations. In more recent years the data has been converted into a more machine readable format, to allow it to be directly queried via an open [SPARQL end-point](https://rdf.ng-london.org.uk/workshops/lcd/). However, as the data structure is defined by a bespoke ontology it is still quite difficult to directly connect the contents to other sources of data.

### Data structure 1: Mapping
The code used to map this data structure to the CIDOC CRM can be found at: https://github.com/jpadfield/crm_migration

## Data structure 1: The IPERION-CH Grounds Database 

The origin of this idea for a digital research resource on preparatory layers in paintings was the 1998 article by Jill Dunkerton and Marika Spring on the development of painting on coloured surfaces in sixteenth century Italy, presented at the IIC congress held in Dublin and published in the associated volume of preprints [1]. The paper included tables describing the preparatory layers and their composition on around 140 National Gallery paintings, and there had long been a desire to develop this into an online database or research resource, with all the enhancements that this would bring, and also to add to it new data accumulated over the intervening years. The original article had identified trends over time, and also geographical patterns, so the data would serve well to explore the development and value of timelines and maps to visualise the data. In addition during construction of the database it would be possible to address questions about standards and comparability of the metadata needed to be able to fully describe and document the data, and also to develop effective search functions. The data includes images and analyses so also explores how to combine and display different types of content.

[1] Dunkerton, J. & Spring, M., 1998, ‘The development of painting on coloured surfaces in sixteenth-century Italy’, Studies in Conservation, 43(Supplement-1), 120-130.

Details of the captured data along with screen shots from the current closed website can be found at: https://doi.org/10.5281/zenodo.5838339 

### Data structure 2: Mapping
The code used to map this data structure to the CIDOC CRM can be found at: https://github.com/jpadfield/grounds_sshoc
