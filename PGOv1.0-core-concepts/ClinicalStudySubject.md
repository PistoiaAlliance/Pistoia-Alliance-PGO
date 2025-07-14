

# Class: ClinicalStudySubject 


_A living person who is observed, analyzed, examined, investigated, experimented upon, and/or treated in the course of a clinical study. This includes studies where an investigator obtains identifiable private information or data through the intervention or interaction with the individual. https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C70668_








<details>
<summary><b>Alternative Descriptions</b></summary>

<!--## Alternative Descriptions-->


* SNOMED_CT |   | 





</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* clinical trial participant
* study subject

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
|  [SAMN16822870](https://www.ebi.ac.uk/biosamples/samples/SAMN16822870) |  Non-tumor DNA sample from blood of a human female participant in the dbGaP study A Phase I/II Trial of T Cell Receptor Gene Therapy Targeting HPV-16 E7 for HPV-Associated Cancers   |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| annotation_1 | this is an example of an annotation |
| annotation_2 | this is another example of an annotation |
| conceptual_clarification | The group noted that the term 'Study Subject' must be sufficiently general to encompass a wide range of entities observed or manipulated in the course of a scientific study. These entities may include--
* Human participants (clinical trials)
* Animal models
* Environmental systems (e.g., soil, water, air)
* Microbiome-related samples
* Cell cultures and other laboratory models
Thus, the term 'subject' should not be restricted to humans. This led to consensus that the existing label 'Subject-Person' is overly narrow and should be replaced.

Multiple ontological sources were reviewed--
* OMG (Object Management Group) term 'subject' was dismissed as unsuitable due to its narrow interpretation as an 'area of interest or expertise'.
* NCIT_C14225 and NCIT_C25190 were considered too broad or not directly applicable to the investigative context of studies.
* NCIT_C70668 (Clinical Study Subject, from CDISC) was endorsed for the clinical domain but seen as overly specific for broader R&ED purposes.
* NCIT_C41189 was recommended as the most appropriate definition for general study subject use, with the text--
'A matter or an individual that is observed, analyzed, examined, investigated, experimented upon, or/and treated in the course of a particular study.' |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* The purpose of this alignment meeting was to evaluate appropriate ontological definitions and labels for the concept currently referred to as 'Subject-Person' within the context of the Pharma General Ontology (PGO). The expert group aimed to harmonize terminology relevant to both research and early development (R&ED) and clinical domains, while accounting for use cases involving non-human entities.
* Label Clarification and Scope clarification. The group noted that the term 'Study Subject' must be sufficiently general to encompass a wide range of entities observed or manipulated in the course of a scientific study. These entities may include-- * Human participants (clinical trials) * Animal models * Environmental systems (e.g., soil, water, air) * Microbiome-related samples * Cell cultures and other laboratory models. Thus, the term 'subject' should not be restricted to humans. This led to consensus that the existing label 'Subject-Person' is overly narrow and should be replaced.
* Definition Selection. Multiple ontological sources were reviewed-- * OMG (Object Management Group) term 'subject' was dismissed as unsuitable due to its narrow interpretation as an 'area of interest or expertise'. * NCIT_C14225 and NCIT_C25190 were considered too broad or not directly applicable to the investigative context of studies. * NCIT_C70668 (Clinical Study Subject, from CDISC) was endorsed for the clinical domain but seen as overly specific for broader R&ED purposes. * NCIT_C41189 was recommended as the most appropriate definition for general study subject use, with the text-- 'A matter or an individual that is observed, analyzed, examined, investigated, experimented upon, or/and treated in the course of a particular study.'
* Conceptual Separation Between Domains. It was agreed that a distinction should be made between general 'Study Subjects' and 'Clinical Study Subjects' due to domain-specific requirements-- * 'Study_Subject' will serve as a general core concept for R&ED, inclusive of all types of observed entities. * 'Clinical_Study_Subject' will be added as a distinct core concept to represent human participants in clinical trials, adopting NCIT_C70668 as its definition.
* Data Provenance Considerations. The importance of provenance tracking for study subjects was emphasized. It was recommended that identifiers for 'Study_Subject' should be structured to capture associations with study protocols, samples, data sets, and dates (e.g., using concatenated Subject_ID and Study_ID values to create unique identifiers).
* Proposed for PGO phase 2 using NCIT_C70668 as a definition

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* Review preferred sources

</details>

