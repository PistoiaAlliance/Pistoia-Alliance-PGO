
# Class: Assay 

_"A planned process with the objective to produce information about the material entity that is the evaluant by physically examining it or its proxies. source: https://ontology.iedb.org/ontology/OBI:0000070."_


URI: [w3id:pgo.assay](https://w3id.org/pgo.assay)




<details>
<summary><b>Alternative Descriptions</b></summary>

<!--## Alternative Descriptions-->


* OBI |   | 



* alt_description_source |   | 





</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* Bioassay
* Observation

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value  | Description |
| --- |--- |
| [PCR-SSCP assay](http://purl.obolibrary.org/obo/OBI_0302737) |  Polymerase Chain Reaction Single Strand Conformation assay |
| [apoptosis assay](http://purl.obolibrary.org/obo/MAXO_0035080) |  A test to determine if cells are undergoing programmed cell death. |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://ontology.iedb.org/ontology/OBI:0000070 |
| definition_source_attribution | Ontology for Biomedical Investigations (OBI) |
| definition_source_licence | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |
| definition_access_date | 2025-06-02 |
| expert_approval_date | 2025-06-12 |
| conceptual_clarification | Participants discussed the semantic boundaries and overlaps between assay, bioassay, experiment, and test. Several distinctions and relationships were noted.
* An assay is generally defined as a planned process that measures a specific activity or property (e.g., biological, chemical, physiochemical, sequence-based), often following a defined protocol.
* An experiment is a broader, less formalized concept that may include multiple assays and can span various designs and methodologies.
* A study may encompass multiple experiments or be used synonymously with an experiment in some contexts.
* Runs refer to repeated executions of the same assay or experiment.
* A bioassay is considered a subset of assays involving biological materials or reagents, or measuring biological properties.
* The terms test and assay are sometimes used interchangeably in practical and regulatory contexts (e.g., pharmacopeial standards). |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* Summary of the “Assay/Bioassay” Alignment Meeting Date 2025-05-08 (May 8,2025) This meeting aimed to reach consensus on the appropriate ontological representation of the concept currently referred to as 'Assay' or 'Bioassay' within the Pistoia Alliance’s Pharma General Ontology (PGO). Discussions focused on definitions,hierarchical relationships with related terms (e.g., 'experiment', 'study','test'), and domain-specific applicability." -"Conceptual Clarification. Participants discussed the semantic boundaries and overlaps between assay, bioassay, experiment,and test. Several distinctions and relationships were noted. An assay is generally defined as a planned process that measures a specific activity or property (e.g.biological, chemical, physiochemical, sequence-based), often following a defined protocol. An 'experiment' is a broader, less formalized concept that may include multiple assays and can span various designs and methodologies. A study may encompass multiple experiments or be used synonymously with an experiment in some contexts. Runs refer to repeated executions of the same assay or experiment. A bioassay is considered a subset of assays involving biological materials or reagents, or measuring biological properties.The terms test and assay are sometimes used interchangeably in practical and regulatory contexts (e.g., pharmacopeial standards).
* Definition Evaluation. Several candidate were proposed and evaluated for suitability. * NCIT_C16341 (Assay), Widely used in cancer research and pharmacology is positively received by multiple experts for its comprehensiveness. Links conceptually to the PGO core concept 'substance'. Endorsed by multiple participants ([PMQ],[BM]). * BAO_15 (Bioassay Ontology), Proposed by at least two project partners.Critiqued for being overly complex or broad, especially with inclusion of SOP-level information. * NCIT_C60819, Considered too narrow, focused on measuring quantities or drug effects. * OBI_0000070, Used extensively in biomedical domains (Ontology for Biomedical Investigations), considered sufficiently flexible and formally defined. Ultimately, the group converged on the OBI 0000070 defnition to o represent the concept of 'Assay'- 'A planned process with the objective to produce information about the material entity that is the evaluant, by physically examining it or its proxies.
* Recommendations to the PGO Steering Group - 1.Change of Label- Update the existing core concept label from 'Bioassay' or 'Assay/Bioassay' to 'Assay' to improve clarity and generality.Adopt the definition from OBI_0000070 as the formal representation of 'Assay' in the PGO.3.Future Concept Expansion- 2.Consider the addition of a distinct core concept for 'Bioassay' in future ontology releases to better capture biological assay specificity.

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* none

</details>




### Schema Source

* from schema: https://w3id.org/PGO/assay


