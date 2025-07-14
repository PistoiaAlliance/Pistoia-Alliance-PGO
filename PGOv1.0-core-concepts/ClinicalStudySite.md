

# Class: ClinicalStudySite 


_A healthcare organization, an institution, a facility, a healthcare provider, or a part or a constituent of any of the above entities directly involved in conducting a particular clinical study. https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C15206_







<details>
<summary><b>Alternative Descriptions</b></summary>

</details>


<details open>
<summary><b>Aliases</b></summary>

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
| [Basel, BS, Switzerland, 4051 UPK Transkulturelle Ambulanz](https://clinicaltrials.gov/study/NCT07015567?locStr=Basel,%20Switzerland&country=Switzerland&state=Basel%20City&city=Basel&rank=1#locations) | Contacts and Locations. This section provides contact details for people who can answer questions about joining this study, and information on where this study is taking place. |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C70777 |
| definition_source_attribution | NCI-Thesaurus (NCIT) |
| definition_source_licence | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |
| definition_access_date | 2025-05-30 |
| expert_approval_date | 2025-06-12 |
| conceptual_clarification | nan |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* The PGO expert group convened to assess candidate definitions for the core ontological concept of 'Site', with specific focus on its relevance for pharmaceutical research and development (R&ED). The discussion revealed significant conceptual complexity around the term 'site,' which spans anatomical, geographic, institutional, and procedural domains. Consequently, experts distinguished between a high-level generic concept and more context-specific subtypes.
* 1. High-Level Concept-- 'Site'Several ontological sources were considered for defining 'Site'. * [BFO--0000029] Defines a site as a 'three-dimensional immaterial entity… bounded by a material entity.' While philosophically rigorous and broadly applicable, its abstractness was perceived as a barrier to practical implementation in PGO.* in OMG Commons 'Site' is  defined as 'a place, setting, or context in which something is situated or to which something is, or may be, bound.' This was generally preferred for its clarity and pragmatic scope. However, its implementation is currently impeded by unresolved IRIs (Issue 48), rendering it unsuitable for immediate adoption in the PGO.
* 2. Domain-Specific Concepts for 'Site'. Recognizing the limitations of a generic 'Site' definition for some practicl use cases in the R&ED domain, the experts proposed a stratified approach based on domain specificity. * 'Study_Site'  example source – [NCIT_C80403], described as a generic facility or institution where study-related activities occur. Experts found this definition sufficiently flexible for both clinical and non-clinical research contexts. * 'Clinical_Study_Site' example source – [NCIT_C70777], which defines a site as 'a healthcare organization, an institution, a facility, a healthcare provider, or a part or a constituent of any of the above entities directly involved in conducting a particular clinical study.' This definition was strongly endorsed for representing the real-world entities engaged in clinical research and was considered well aligned with industry practices. - Recommendations to the PGO Steering Committee. 1.    Defer the adoption of a high-level 'Site' definition until a resolvable and implementable URI is available (notably for the OMG Site) with a definition such as--  'place, setting, or context in which something is situated or to which something is, or may be, bound'. 2.    Adopt a new core concept labeled 'Clinical_Study_Site', with the definition from NCIT_C70777-- A healthcare organization, an institution, a facility, a healthcare provider, or a part or a constituent of any of the above entities directly involved in conducting a particular clinical study.3.    Include Phase 2 additional context-specific core concepts--* 'Study_Site'-- as per NCIT_C80403. * 'Anatomical_Site'-- relevant for study subjects and tissue-specific applications.* 'Binding_Site'-- applicable to molecular and compound interaction contexts.* These labels are provisional and may require revision during expert alignment discussions.

<details>
<summary><b>TODOs</b></summary>
## TODOs

* Review preferred sources

</details>






