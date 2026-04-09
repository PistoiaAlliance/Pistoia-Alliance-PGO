

# Class: Device 


_a manufactured physical or digital device used in Pharma R&D and therapy development | https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C62103_











<details>
<summary><b>Alternative Descriptions</b></summary>

<!--## Alternative Descriptions-->


* OBI |   | 




* alt_description_text |   | 




* alt_description_source |   | 





</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* instrument
* laboratory instrument

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
| [thermal cycler](http://purl.obolibrary.org/obo/OBI_0000989) | an instrument used for perform a polymerase chain reaction (PCR) |
| [centrifuge](http://purl.obolibrary.org/obo/OBI_0400106) | an instrument used to separate components of a mixture based on density |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C62103 |
| definition_source_attribution | NCI-Thesaurus (NCIT) |
| definition_source_licence | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |
| definition_access_date | 2025-05-30 |
| expert_approval_date | 2025-06-12 |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* Given the heterogeneity of devices used across laboratory research, diagnostics, therapeutics, and manufacturing processes, the working group acknowledged the need for a broad and inclusive treatment of the term 'Device'.
* Scope and Context for 'device'. The term 'Device' was reaffirmed as a necessary high-level entry point within the PGO structure. Participants emphasized that this concept should not be limited to medical or investigational contexts alone but should instead encompass a wide array of equipment and tools—including laboratory instruments, production machinery, and diagnostic platforms. A more specific concept such as 'Medical Device' could be modeled as a subclass within this hierarchy. The discussion also acknowledged the critical role of context in interpreting device-related data in R&ED workflows, especially in relation to regulatory, clinical, and manufacturing use cases.
* Evaluation of Candidate Definitions. Six definitions from established ontologies were evaluated for suitability-- * OBI_0000968 (Ontology for Biomedical Investigations)-- Recognized for BFO alignment but criticized for being overly narrow, tied to research investigations, and not easily generalizable to manufacturing or therapeutic devices. * NCIT_C62103 (NCI Thesaurus)-- Broadly defined and pragmatic. Considered sufficiently flexible to accommodate a wide range of device types, including research and medical contexts. Seen as the most appropriate candidate for the core concept 'Device' due to its existing vocabulary structure and potential for subclassing. * IDMP-O_Medical_device-- Offers an FDA-aligned definition suitable for 'Medical Device' as a subclass. Detailed and specific, but viewed as too narrow for the overarching 'Device' concept. * NCIT_C16830 (Medical Device)-- Suitable as a child class under the broader NCIT_C62103 'Device' definition. * FHIR--Device-- Considered broad but potentially too imprecise in its scope, with overlapping non-medical interpretations. * NCIT_C19238-- Describes manufactured objects used in diagnostic, therapeutic, or research activities. Excludes manufacturing equipment, and thus not considered comprehensive enough for the PGO core concept.
* The Preferred text Definition (NCIT_C62103) is 'A device used in medical, surgical, laboratory, or production settings, including instruments, apparatus, implements, or machines involved in diagnostic, therapeutic, or research activities.' This definition provides adequate breadth to accommodate the multifunctional nature of devices in pharmaceutical settings, while also supporting future hierarchical expansion.

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* Review preferred sources

</details>


