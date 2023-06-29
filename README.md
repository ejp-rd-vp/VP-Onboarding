# VP-Onboarding
Your resource's complete guide to join the EJP RD Virtual Platform (VP).

The Virtual Platform network is an ecosystem of data resources and services that allows researchers and other stakeholders to easily find, access, and use data for different purposes, such as discovering and analysing it. To be part of this ecosystem, resources need to implement specifications that make them 'Findable, Accessible, Interoperable, and Reusable (FAIR) for humans and machines'. We call those resources 'VP compliant'. The more specifications a resource implements, the larger the contribution and empowerment to the functionality of the VP, and to research benefiting the rare disease community. 

| Description | Contributes to | Technology requirements | Access condition options | Example queries |
| :--- | :--- | :--- | :--- | :--- |
| **Level 1 - Resource discovery** |
| At this level, the provider commits to make descriptive metadata of the offered resource available to the Virtual Platform via the VP Index. | Resource discoverability | FAIR Data Point specification, EJP-RD metadata schema | Open access |  |
| **Level 2 - Content discovery** |
| At this level, the provider answers questions regarding the presence (yes/no) and the amount (counting) of information in the resource based on selected filters. The questions are answered against individual records of the resource's data and the content of catalogues and their metadata. | Content discoverability (catalogue and catalogue content and individual record) | Beacon API - Individual endpoint, Catalog endpoint, CDE | Open access, Authentication | How many patients with Autosomal recessive polycystic kidney disease [ORPHANET:731] had symptom´s onset before 8 years old? |
| **Level 3 - Data analysis** |
| At this level, the provider commits to support analysis on its resource's content. | Data reuse and analysis | SPARQL, FAIR Data Train, Data available according to the CDEs, Data described with semantic data model (from metadata) | Open access, Authentication, Authorization | Training a prediction model on distributed data. |

## Requirements to achieve Level 1: Resource Discovery
Level 1 connection is the initial and required step for a resource to contribute to the VP and serves as a foundation for higher connection levels. When a resource onboards at level 1, it provides basic information about itself in a standardised, machine-interpretable way (i.e., ‘metadata for machines’).  

The VP utilizes a metadata model based on the ‘Data Catalogue Vocabulary’ (DCAT) for describing this minimal information for computers. DCAT is a widely used vocabulary, recommended by the World Wide Web Consortium (W3C). More details on the EJP RD Metadata Schema can be found at [this GitHub repository](https://github.com/ejp-rd-vp/resource-metadata-schema).
