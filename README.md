# Pistoia-Alliance-PGO

## Pistoia Alliance Pharma General Ontology: 

### Objective
Defining a set of agreed-upon core entities and recommendations for associating controlled terminologies to service data exchange of Research & Development (R&D) information among Pharmaceutical Industry stakeholders.

### Rationale

Information exchange within and across organizations in the pharmaceutical industry is hampered by insufficient or ambiguous asset description.
These descriptions should ideally allow for validation, facilitation of discovery and promotion of interoperability. 
All of these have the potential to deliver significant gains for data exploitation and value delivery in the drug development pipeline, ultimately bringing better treatments to patients.

*The remit of PGO, rather than mandate the use of a resource over another, is to enable clarity when declaring which semantic resources are used and why*.

True to the FAIR principles of data management [1] and their use in the Pharmaceutical Industry [2], the PGO aims to
*reuse* existing semantic resources (ontologies and controlled terminologies) as well as open source community software, rather than creating new ones.

The initial goal of PGO is to provide enough coverage to represent essential entities, most frequently used or referred to when exchanging data.

**The key objectives are therefore**:
- [x] Unambiguously identifying essential entities
- [x] Specifying, when applicable, value-sets for key attributes by relying on community-agreed controlled terminologies
- [x] Documenting them in a machine actionable form will be the primary outputs of the project.

On the issue of defining value-sets, PGO's intent is to provide clear mechanisms to enable unambiguous declaration of the resources used as well as capture the criteria used to select semantic artifacts. We will do so by following community best practices. 



### Technology

PGO is currently evaluating and using the [LinkML](https://linkml.org) for representing and documenting each of the types [3].

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

- 2023: scoping and use case definition
- 2024: identification formalization of core concepts, testing using LinkML
- 2025: application and field testing with real life scenarios



### Participating Organizations:
- Astrazeneca
- Chiesi Farmateuci
- Glaxo Smith Kline PLC
- Merck Group
- Novo Nordisk
- Pfizer
- Pistoia Alliance
- Hoffman la Roche AG

### References:
1. [https://www.nature.com/articles/sdata201618](https://www.nature.com/articles/sdata201618)
2. [https://pubmed.ncbi.nlm.nih.gov/35066138/](https://pubmed.ncbi.nlm.nih.gov/35066138/)
3. [https://pubmed.ncbi.nlm.nih.gov/36125173/](https://pubmed.ncbi.nlm.nih.gov/36125173/)
