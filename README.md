
![Build Status](https://github.com/brain-bican/bican_application_ontology/workflows/CI/badge.svg)
# BICAN Application Ontology

Overview: This is the developers’ repository for an application ontology to support work affiliated with BRAIN Initiative Cell Atlas Network (BICAN).  

The focus of the BICAN Application Ontology (bao) is research, subjects of research, and the results of research in BICAN. It is a link between scientific knowledge gained through experimentation and the distribution/dissemination of that knowledge. It aims to help scientists annotate data and communicate about their work by defining a set of terms relevant to BICAN efforts. 

Development of this ontology draws on and integrates previous work done on standardization in BICCN and Brain Data Standards projects and aims to interoperate with the larger biomedical ontology community. The development team adheres, as much as possible, to the standards of best practices in ontology development as outlined by the OBO Foundry. The team members are also responsible for reviewing changes in the ontology to be sure that they accurately reflect the best current understandings of brain science.  

The team works in conjunction with a team of software developers to ensure that the ontology and its applications are consistent and up to date. More information can be found at https://github.com/brain-bican/bican_application_ontology 

## Versions

There are a few different versions of the ontology.
### Stable Release Versions

The latest version of the ontology can be found [here](/bao.owl)

### Editors' Version

Editors of this ontology should use the edit version, [src/ontology/bao-edit.owl](src/ontology/bao-edit.owl)

### Older Versions

Older (non-current) release artifacts can be viewed [here](/releases)

## Editing

Following best practices for ontology development, we attempt to reuse as many terms as we are able and attempt a rather modular approach to development. Although there are many ways to add to or edit the ontology, we try to stick to three main methods: 

1. When adding external terms (from other ontologies): Use ODK import functionality for importing terms. Simply create a branch, add the terms you would like to the .txt file of the source ontology of the term you wish to add, and make a pull request. If you are not comfortable with this process, simply provide a term request through our issue tracker. 

2. When adding new terms: Edit owl file in Protege. 

3. When adding many new terms: Edit a template, create a pull request. 

If you aren’t sure which method is best for you or how to proceed, please contact the editors.

### Editors

Patrick L. Ray (Allen Institute for Brain Science) [email](patrick.ray@alleninstitute.org)
Shawn Tan (EBI-EBML)
## Contact

Please use this GitHub repository's [Issue tracker](https://github.com/brain-bican/bican_application_ontology/issues) to request new terms/classes or report errors or specific concerns related to the ontology.

## Citation Information

BRAIN Initiative Cell Atlas Network (2022). BICAN Application Ontology. Available from https://github.com/brain-bican/bican_application_ontology RRID:SCR_xxxxx 
## Terms of Use

These materials are provided under the Attribution International 4.0 (CC-BY-4.0) license, which is available at https://creativecommons.org/licenses/by/4.0/ 

## Acknowledgements

This ontology repository was created using the [Ontology Development Kit (ODK)](https://github.com/INCATools/ontology-development-kit).

Creation and maintenance of the ontology were supported by: 

    National Institutes of Mental Health under award number U24MH130919 (PIs Michael Hawrylycz and Carol Thompson)  

    National Institutes of Mental Health under award number U24MH114827 (PIs Michael Hawrylycz, Lydia Ng, Maryann Martone, Timothy Tickle, Paul Yushkevich) 

    Allen Institute for Brain Science.