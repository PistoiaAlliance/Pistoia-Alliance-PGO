# Pistoia-Alliance-PGO

## Pistoia Alliance Pharma General Ontology (PGO): 

### Objective
The first objective of PGO is to define a set of agreed-upon core entities, the PGO "core concepts",  and recommendations for associating controlled terminologies to service data exchange of Research & Development (R&D) information among Pharmaceutical Industry stakeholders.

### Rationale

Information exchange within and across organizations in the pharmaceutical industry is hampered by insufficient or ambiguous asset descriptions.
These descriptions should ideally allow for validation, facilitation of discovery and promotion of interoperability. 
All of these have the potential to deliver significant gains for data exploitation and value delivery in the drug development pipeline, ultimately bringing better treatments to patients.

*The remit of PGO, rather than mandate the use of a resource over another, is to enable clarity when declaring which controlled terminologies are used and why*.

True to the FAIR principles of data management [1] and their use in the Pharmaceutical Industry [2], the PGO aims to
*reuse* existing semantic resources (ontologies and controlled terminologies) as well as open source community software, rather than creating new ones.

The initial goal of PGO is to provide enough coverage to represent essential entities, most frequently used or referred to when exchanging data.

**The key objectives are therefore**:
- [x] Unambiguously identifying essential entities
- [x] Specifying, when applicable, value-sets for key attributes by relying on community-agreed controlled terminologies
- [x] Creating machine actionable documentation.

On the issue of defining value-sets, PGO's intent is to provide clear mechanisms to enable unambiguous declaration of the resources used as well as capture the criteria used to select semantic artifacts. We will do so by following community best practices. 



### Technology

PGO is currently evaluating the [LinkML](https://linkml.io) for representing and documenting each of the types [3].

#### PGO list of core entities

| Concept | Definition | Status | 
|--|--|--|
|Assay (method)| | under development|
|Assay (biological)| | under development|
|Biomarker|| under development|
|Biospecimen|| under development|
|Cell line|| under development|
|Cell type|| under development|
|Clinical study|| under development|
|Compound|| under development|
|Equipment|| under development|
|Disease|| under development|
|Drug|| under development|
|Device|| under development|
|Gene|| under development|
|Indication|| under development|
|Molecular target|| under development|
|Product|| under development|
|Program|| under development|
|Project|| under development|
|Protein|| under development|
|Site|| under development|
|Gene|| under development|
|Species|| under development|
|Subject-Person|| under development|
|Target|| under development|
|Unit|| under development|
|Vocabulary|| under development|

### Roadmap

- 2023: initial scoping and identification of core concepts
- 2024: use case definition, expters consultation and alignment, formalization of core concepts 
- 2025: implementation and testing using LinkML, application and field testing 



### Participating Organizations:
- Astrazeneca
- Chiesi Farmaceutici
- Glaxo Smith Kline PLC
- Merck KgaA
- Novo Nordisk
- Pfizer
- Hoffman la Roche AG

- Pistoia Alliance

### References:
1. [https://www.nature.com/articles/sdata201618](https://www.nature.com/articles/sdata201618)
2. [https://pubmed.ncbi.nlm.nih.gov/35066138/](https://pubmed.ncbi.nlm.nih.gov/35066138/)
3. [https://pubmed.ncbi.nlm.nih.gov/36125173/](https://pubmed.ncbi.nlm.nih.gov/36125173/)
