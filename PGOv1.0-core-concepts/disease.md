

# Class: Disease 


_a disease or condition for which a drug, device, or procedure is used_





URI: [w3id:pgo.disease](https://w3id.org/pgo.disease)





<details>
<summary><b>Alternative Descriptions</b></summary>

<!--## Alternative Descriptions-->


* alt_description_text |   | 




* alt_description_source |   | 





</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* Disease
* Medical Condition

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
| [Angina pectoris](https://hpo.jax.org/browse/term/HP:0001681) | A type of chest pain caused by reduced blood flow to the heart. It is often described as a feeling of pressure |
| [Parkinson disease](https://monarchinitiative.org/MONDO:0005180) | A progressive neurodegenerative disorder characterized by motor symptoms such as tremors, rigidity, and bradykinesia. |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://meshb.nlm.nih.gov/record/ui?ui=D004194 |
| definition_source_attribution | National Library of Medicine (NLM) - MESH |
| definition_source_licence | [https://www.nlm.nih.gov/databases/download/terms_and_conditions_mesh.html) |
| definition_access_date | 2025-05-30 |
| expert_approval_date | 2025-06-12 |
| conceptual_clarification | The working group evaluated  different proposed sources which are currently used within pharmaceutical contexts--
* NCIT--C2991 (National Cancer Institute Thesaurus) is widely used in the clinical domain.
* DOID--4 (Disease Ontology) is used in the research domain and supported by at least two steering group members.
* MeSH D004194 (Medical Subject Headings) is used to a lesser extent across both domains but is valued for the clarity of its definition.
	
The MeSH D004194 was generally preferred for its concise and clinically meaningful text definition--
'A definite pathologic process with a characteristic set of signs and symptoms. It may affect the whole body or any of its parts, and its etiology, pathology, and prognosis may be known or unknown.'
* NCIT C2991, while favored by three steering group members for its ontological hierarchy and integration in clinical workflows, was criticized for being overly generic and potentially conflating 'disease' with broader 'conditions'.
* DOID--4 was supported for its relevance to the research domain, but its definition was not discussed in depth during this session. |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* The purpose of this alignment meeting was to evaluate existing definitions of the concept 'disease' across multiple biomedical ontologies and controlled vocabularies, with the goal of recommending a harmonized definition suitable for adoption within the Pharmaceutical Global Ontology (PGO). The discussion also addressed the potential need to distinguish 'disease' from the related but broader concept of 'condition.'
* Key Discussion Points. The working group evaluated  different proposed sources which are currently used within pharmaceutical contexts-- * NCIT--C2991 (National Cancer Institute Thesaurus) is widely used in the clinical domain. * DOID_4 (Disease Ontology) is used in the research domain and supported by at least two steering group members. * MeSH D004194 (Medical Subject Headings) is used to a lesser extent across both domains but is valued for the clarity of its definition.The MeSH D004194 was generally preferred for its concise and clinically meaningful text definition--'A definite pathologic process with a characteristic set of signs and symptoms. It may affect the whole body or any of its parts, and its etiology, pathology, and prognosis may be known or unknown.' * NCIT C2991, while favored by three steering group members for its ontological hierarchy and integration in clinical workflows, was criticized for being overly generic and potentially conflating 'disease' with broader 'conditions'. * DOID_4 was supported for its relevance to the research domain, but its definition was not discussed in depth during this session.
* The expert group highlighted persistent ambiguity in the use of 'disease' and 'condition' in biomedical contexts. This led to a consensus that these concepts should be explicitly distinguished within the PGO to avoid confusion and improve semantic precision in downstream applications.Further (after conversation that occured in April 2025), 'disease' and 'condition' are not to be considered 'material entities' (also referred informally as 'things' in the expert exchanges) or 'roles', but rather as 'processes'.  This distinction my play a role in further versions of PGO.
* Recommendations to the PGO Steering Group.1. Definition Selection-- Adopt the MeSH D004194 definition as the core definition of 'disease' in the PGO, due to its clarity, clinical relevance, and expert consensus.2.    Conceptual Separation-- Introduce a distinct core concept labeled 'Condition', with a separate definition, to better capture broader or less well-defined health states that may not meet the criteria of a pathologic process.

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* none

</details>




### Schema Source


* from schema: https://w3id.org/PGO/disease


