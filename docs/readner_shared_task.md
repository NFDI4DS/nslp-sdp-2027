---
layout: default
title: READNER 2027 shared task
nav_order: 7
---

# READNER 2027: Named Entity Recognition in GitHub READMEs

READNER 2027 is a fine-grained Named Entity Recognition (NER) shared task at the Workshop on AI for the Scholarly Web (NSLP-SDP 2027). It addresses research-related GitHub README files, where metadata about datasets, software, experimental code, and other research artifacts is often embedded in free-form documentation. The task builds on the NERdME dataset [2].

NFDI4DataScience (NFDI4DS) supports the research data lifecycle in Data Science and Artificial Intelligence, from collecting and processing resources to publishing, archiving, and reusing them. GitHub repositories complement research papers by providing datasets, models, source code, and implementation details that help researchers explore and reproduce results. Their README files typically describe the project's purpose, setup, and usage, and link to related research resources. Extracting entities from these documents can enrich the NFDI4DS knowledge graph (NFDI4DS-KG) and help make research resources easier to discover and reuse.

## Task definition

Participants will develop systems that take a GitHub README file as input and identify entity mentions, their boundaries, and their types. The task covers the following ten entity types from the NFDI4DS Ontology (NFDI4DSO) [1]:

1. Conference
2. Dataset
3. Evaluation Metric
4. License
5. Ontology
6. Programming Language
7. Project
8. Publication
9. Software
10. Workshop

## Dataset

READNER builds on NERdME [2], a dataset of **200 manually annotated GitHub READMEs** containing **10,691 entity mentions** across **ten entity types**. By covering both paper-level and implementation-level research entities, NERdME connects scientific information extraction with software-repository documentation.

The READNER 2027 training/test split, annotation guidelines, file format, and download links are to be announced.

## Evaluation and submissions

Exact-boundary recognition is a particular challenge for existing LLM and transformer baselines on NERdME [2], leaving room for improved identification of entity mentions and their boundaries.

The evaluation metrics, matching rules, ranking procedure, and required submission format are to be announced with the READNER 2027 competition instructions.

## Competition platform

The [READNER 2027 CodaBench competition](https://www.codabench.org/competitions/18427/) is currently in organizer setup and has not yet opened for public participation.

## Important dates

| Milestone | Date |
| --- | --- |
| Release of NERdME training data | November 1, 2026 |
| Release of NERdME test data | December 15, 2026 |
| Evaluation/system submission deadline | December 29, 2026 |
| Earliest workshop paper submission date | January 4, 2027 |

December 29 is the deadline for participant system submissions. January 4 is the earliest date for submitting a workshop paper. Closing times and the time zone for the shared-task milestones are to be announced.

For the workshop paper submission deadline, notification, camera-ready deadline and workshop date, see the [workshop important dates]({{ '/docs/dates.html' | relative_url }}).

## Organizers

* Genet Asefa Gesese (FIZ Karlsruhe, Germany)
* Zongxiong Chen (Fraunhofer FOKUS, Germany)
* Mary Ann Tan (FIZ Karlsruhe, Germany)
* Sonja Schimmler (Fraunhofer FOKUS, Germany)

## Contact

For READNER shared-task enquiries, please contact:

* Genet Asefa Gesese (FIZ Karlsruhe, Germany): [genet-asefa.gesese@fiz-karlsruhe.de](mailto:genet-asefa.gesese@fiz-karlsruhe.de)
* Zongxiong Chen (Fraunhofer FOKUS, Germany): [zongxiong.chen@fokus.fraunhofer.de](mailto:zongxiong.chen@fokus.fraunhofer.de)
* Mary Ann Tan (FIZ Karlsruhe, Germany): [ann.tan@fiz-karlsruhe.de](mailto:ann.tan@fiz-karlsruhe.de)

## References

[1] Genet Asefa Gesese et al. [NFDI4DSO: Towards a BFO Compliant Ontology for Data Science](https://arxiv.org/abs/2408.08698). arXiv:2408.08698 (2024).

[2] Genet Asefa Gesese et al. [NERdME: a Named Entity Recognition Dataset for Indexing Research Artifacts in Code Repositories](https://doi.org/10.1145/3774904.3792934). In Proceedings of the ACM Web Conference 2026, pp. 8661-8664 (2026).
