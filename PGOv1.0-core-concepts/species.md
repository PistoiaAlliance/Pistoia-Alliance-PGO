

# Class: Species 


_"An element of a taxonomy for classifying life forms." definition_source: "https://purl.uniprot.org/html/index-en.html#Taxon" version: "1"_




URI: [w3id:pgo.species](https://w3id.org/pgo.species)




<details>
<summary><b>Alternative Descriptions</b></summary>

</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* Organism

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
| [Homo sapiens](https://www.uniprot.org/taxonomy/9606) | HUMAN - Homo sapiens (species) |
| [Mus musculus](https://www.uniprot.org/taxonomy/10090) | MOUSE - Mus musculus (species) |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://purl.uniprot.org/html/index-en.html#Taxon |
| definition_source_attribution | UniProt |
| definition_source_licence | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |
| definition_access_date | 2025-06-09 |
| expert_approval_date | 2025-06-12 |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* Meeting notes 2024-08-29 (August 29 2024). A series of expert consultations and meetings were conducted to refine the definition of the core concept 'Species' within the Pharma General Ontology (PGO).The discussions focused particularly on the challenge of inclusively representing viruses, which are critical to pharmaceutical contexts yet often excluded by conventional species definitions.
* Several concerns were raised regarding existing definitions-- * The criterion 'capable of breeding and producing fertile offspring' was deemed overly restrictive, particularly in the context of microorganisms and viruses. * The use of the term 'living' risks excluding viruses, which are not universally considered living entities but are nonetheless central to pharmaceutical research. * The inclusion of viruses in the concept of species was emphasized as essential. Additional questions arose concerning taxonomic rank granularity (e.g., Phylum, Class, Species) and the appropriateness of existing ontology references for accommodating viruses.
* Experts from the PGO Expert Group were consulted on 30 August 2024. They were asked to recommend a reference definition of 'species' that could inclusively represent viruses. Respondents included representatives from Bayer and Novo Nordisk. * Bayer noted the philosophical complexity of virus inclusion and advocated for a pragmatic solution that accepts viruses within the concept of species despite their taxonomic ambiguity (e.g., as  discussed in https--//www.ncbi.nlm.nih.gov/pmc/articles/PMC4222810/). *  Novo Nordisk indicated reliance on the NCBITaxon vocabulary, although acknowledging its limitations regarding explicit virus inclusion.
* Second Meeting notes , 2024-09-11 (September 11 2024) The follow-up meeting addressed persistent ambiguities-- * The NCBITaxon vocabulary, while globally recognized, does not provide a formal definition of 'species' and inherently excludes viruses in its definition but includes them in practice. * Attempts to reference conceptual frameworks such as Kevin De Queiroz’s work on species delimitation were found insufficient due to their self-referential nature.  Systematic Biology, Volume 56, Issue 6, December 2007, Pages 879–886.  - [(https--//doi.org/10.1016%2Fj.sjbs.2017.04.013)](https--//doi.org/10.1080/10635150701701083) * A proposed definition — 'a type of taxonomic rank qualifying a living entity or virus' — lacks a citable public reference.
* Recommendation to the PGO Steering Group.1. To reconcile conceptual inclusivity with practical needs, the expert group recommends adopting the UniProt definition Uniprot_Taxon for the PGO core concept labelled 'species',   'An element of a taxonomy for classifying life forms.' 2.  It is also advised that the inclusion of viruses be explicitly acknowledged in the PGO’s application of the concept.

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* none

</details>


### Schema Source


* from schema: https://w3id.org/PGO/species

