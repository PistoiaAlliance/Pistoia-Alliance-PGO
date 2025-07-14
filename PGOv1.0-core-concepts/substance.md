

# Class: Substance 


_A material or chemical used in the development of pharmaceuticals https://meshb.nlm.nih.gov/record/ui?name=Substance, MESH, 2024_





<details>
<summary><b>Alternative Descriptions</b></summary>

<!--## Alternative Descriptions-->


* alt_description_text |   | 




* alt_description_source |   | 




* CHEBI |   | 




* FHIR |   | 




* IDMP-O |   | 





</details>


<details open>
<summary><b>Aliases</b></summary>

<!-- ## Aliases -->


* Pharmaceutical Substance
* Material

</details>

<details open>
<summary><b>Examples</b></summary>

<!-- ## Examples -->

| Value | Description
| --- | --- |
| [water](https://www.ebi.ac.uk/chebi/searchId.do?chebiId=CHEBI:15377) | H20, a chemical substance composed of two hydrogen atoms and one oxygen atom, in liquid form at room temperature |
| [butter](https://www.wikidata.org/wiki/Q34172) | a dairy product made from the fat and protein components of milk or cream, typically used as a spread or in cooking |

</details>

<details>
<summary><b>Annotations</b></summary>

<!-- ### Annotations -->

| property | value |
| --- | --- |
| definition_source | https://evsexplore.semantics.cancer.gov/evsexplore/concept/ncit/C45306 |
| definition_source_attribution | NCI-Thesaurus (NCIT) |
| definition_source_licence | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |
| definition_access_date | 2025-05-30 |
| expert_approval_date | 2025-06-12 |
| conceptual_clarification | The concept of 'Substance' plays a foundational role in biomedical ontologies and regulatory vocabularies, yet its precise definition varies by context. Participants acknowledged the term’s broad use—ranging from material sciences to regulated pharmaceutical entities—and emphasized the need for a definition that balances scientific accuracy, regulatory relevance, and practical applicability.

The discussion addressed several  tensions--
* Material vs. informational definitions-- The IDMP-O representation of 'Substance' appears to frame it as a specification or information entity, diverging from ontologies such as NCIT that treat it as a material entity.
* Semantic overlap with related terms such as Compound, Drug, and Product, which may act as roles or subclasses depending on usage and context.
* The customary and functional use of 'substance' in research settings (e.g., a 'plastic' cup, a tongue suppressor made of 'wood' ) to address materials. |


</details>

<details>
<summary><b>Comments</b></summary>
<!-- ## Comments -->

* The purpose of these alignment meetings was to evaluate candidate definitions for the concept of 'Substance' within the Pharma General Ontology (PGO), in order to ensure semantic consistency and interoperability across pharmaceutical research, development, and regulatory domains. The meetings on 2025-03-27 and 2025-05-23 examined the definitions of 'Compound' and  'Product; (later relabelled 'pharamceutical Product'), respectively.
* Scope and Conceptual Considerations The concept of 'Substance' plays a foundational role in biomedical ontologies and regulatory vocabularies, yet its precise definition varies by context. Participants acknowledged the term’s broad use—ranging from material sciences to regulated pharmaceutical entities—and emphasized the need for a definition that balances scientific accuracy, regulatory relevance, and practical applicability.
* The discussion addressed several  tensions-- * Material vs. informational definitions-- The IDMP-O representation of 'Substance' appears to frame it as a specification or information entity, diverging from ontologies such as NCIT that treat it as a material entity. * Semantic overlap with related terms such as Compound, Drug, and Product, which may act as roles or subclasses depending on usage and context. * The customary and functional use of 'substance' in research settings (e.g., a 'plastic' cup, a tongue suppressor made of 'wood' ) to address materials.
* Evaluation of Candidate Definitions. The following sources were critically reviewed-- * IDMP-O_Substance-- Utilized in regulated medicinal product contexts. Two partners indicated active use of this definition. Concern raised regarding its conceptual shift from material to specification-based definition. * NCIT_C1913-- Broad inclusion but limited by scope (focused on naturally occurring substances). Intended for use in structural categorization within the NCIt hierarchy. * CHEBI_24431-- Extensive chemical coverage but deemed too expansive; includes atoms as substances, which participants found semantically unsuitable for PGO use. * schema.org_Substance Appears to reuse the NCIT definition; no additional unique value identified. * FHIR_Substance-- 'A homogeneous material with a definite composition.' Considered too broad yet lacking  specificity. * NCIT_C45306-- Gained broad support from participating experts. Three partners confirmed alignment with existing usage. Considered both inclusive and sufficiently precise to support PGO implementation. Preferred over alternatives due to clarity, material-based interpretation, and resolvable URI.
* Related Discussions. The experts noted that-- * 'Substance' should be distinguished from Compound and Product, though overlaps exist. * 'Compound' was evaluated in a follow-up session on 27 March 2025, confirming that while some 'substances' are 'compounds', not all are. * The evaluation of ""Product"" in relation to 'Substance' was addressed on 23 May 2025, indicating that whilke there is semantic overlap, not all 'Substances' are 'Products' (re-labelled 'pharmaceutical product'). Further examples are needed to illustrate substances that are not compounds, drugs, or pharmaceutical products, to clarify usage boundaries.
* Text Definition preferred-- NCIT_C45306  'Any matter of defined composition that has discrete existence, whose origin may be biological, mineral or chemical.' This definition offers both breadth and specificity, suitable for research and regulated domains alike.
* Recommendations to the PGO Steering Group 1.  Retain 'Substance' as a core concept, recognizing its general relevance across the R&D continuum. 2.    Adopt NCIT_C45306 as the  definition of 'Substance' for the Pharma General Ontology. 3.    Acknowledge semantic relationships with Compound and Product, which may be further modelled in future version of PGO but maintained as distinct concepts.

</details>

<details>
<summary><b>TODOs</b></summary>
## TODOs

* Review preferred sources

</details>

