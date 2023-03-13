## Reference Ontologies

BICANO makes use of reference ontologies to reuse existing ontological entities in an effort to avoid duplication. Since BICANO is not itself a reference ontology but often contains important and valuable ontological entities, the BICANO curation team 'shepherds' these entities to their appropriate reference ontologies when we are able. In an effort to streamline and systematize this process, we have appointed reference ontology shepherds for the following term types and domains:

### Assays and Experimental Techniques

Experimental techniques are ontologically classified as assays. Assays and experimental techniques should be shepherded to the Ontology for Biomedical Investigations [OBI](obi-ontology.org). 

The shepherd for OBI terms is [TBD](email@email.com).

### Cell Types and Cell Features

For Cell Types identified through BICAN, all cell type work is coordinated through the [Brain Data Standards Ontology](https://github.com/obophenotype/brain_data_standards_ontologies). BICANO imports cell types through BDSO, so no cell type identification is done through BICANO. The BDSO integrates into the [Cell Ontology](https://cell-ontology.github.io).

If you have any questions regarding BICAN cell types, please contact [David Osumi-Sutherland](davidos@ebi.ac.uk).

### Anatomy

BICAN anatomical entities are neuroanatomical entities pinned to the [Allen Brain Atlas Ontology](https://github.com/obophenotype/ABA_Uberon). Anatomical atlases developed as part of the BICAN will be mapped to the ABA and UBERON. 

If you have any questions about these neuroanatomy ontologies, please contace [Patrick Ray](patrick.ray@alleninstitute.org).

### Genes

For gene annotations, we recommend using the [Gene Ontology](geneontology.org). 

## Good Practice Elements

Each new term requested in a reference ontology should be submitted to the BICAN Applicaiton Ontology first, so that the development team is able to verify the term internally. Once the term has been vetted by the BICANO curatorial team and added to BICANO, it will be assigned a shepherd to make the term in the appropriate reference ontology. The shepherd will ensure that each entity/term is documented as originating from BICAN products with appropriate citations and references. 

Once the term is accepted and published by a reference ontology, the term will be deprecated in BICANO and replaced with the new reference ontology term with a new ID. All of these steps and processes will be tracked through our GitHub issue tracker. 