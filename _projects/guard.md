---
layout: page
title: GUARD Project
description: Ensuring Interoperable and Trustworthy Knowledge Graphs for Defence and National Security AI
img: assets/img/projects/alan-turing-institute-logo.png
importance: 2
category: projects
related_publications: logmapllm-eacl-2026, diso-iswc-2026, guard-report-phase1-2026
---

Project funded by [The Turing Defence and National Security Grand Challenge](https://www.turing.ac.uk/science-innovation/defence-and-national-security).

Knowledge graphs (KGs) and ontologies are vital for trustworthy AI, but their effectiveness is often limited by interoperability gaps and quality issues. Interoperability of ontologies at the upper- and mid-level has been advanced through initiatives such as the Basic Formal Ontology (BFO) and the Common Core Ontologies (CCO). However, achieving the same interoperability at the application level remains a major challenge, particularly in defence and national security, where broad conceptual coverage must be reconciled with specialised subdomains. An ontology foundry for this domain, such as that proposed by the US Department of Defence/War, must ensure interoperability, comprehensive coverage, and high quality. Without these guarantees, the deployment of ontologies and knowledge graphs (KGs) risks limiting their effectiveness in downstream applications.

Two key challenges must be addressed. The first challenge (CH1) is **interoperability and coverage**. Existing ontologies and KGs relevant to defence model overlapping domains, but their interoperability remains limited, and greater integration with linked data resources is required to extend coverage across geolocations, organisations, diseases, and environmental hazards. The second challenge (CH2) is **quality**. Although OWL, SHACL, and ShEx enable the detection of inconsistencies and definition of integrity constraints, their practical use is often limited by scalability issues, particularly when integrating large or multiple KGs.

The GUARD project has been split into two phases. Phase 1 (November 2025 to April 2026) has dealt with CH1 through a novel cost-effective utilisation of LLMs for knowledge graph integration. Phase 2 (June 2026 to May 2027) focus on addressing CH2, leveraging the use of efficient logic-based
reasoning for knowledge graph validation and the use of LLMs to provide (potential) solutions for the detected logical errors. LLMs will also be used to further enhance the integration of KGs.

#### The GUARD Team 

Team: [Ernesto Jimenez-Ruiz](https://ernestojimenezruiz.github.io/) (PI), [Jonathon Dilworth](https://github.com/jonathondilworth) (RA), and [Pedro Cotovio](https://pedrocotovio.github.io/) (RA from October).

Previous members: [Dave Herron](https://djherron.github.io/) (PDRA).

Advisory board: [Catia Pequita](https://www.di.fc.ul.pt/~catiapesquita/) (University of Lisbon), [Paul Cripps](https://www.linkedin.com/in/pauljcripps/) (Dstl).

Collaborators: [Sviatoslav Lushnei](https://www.linkedin.com/in/sviatoslav-lushnei-7a2722243/), [Dmytro Shumskyi](https://www.linkedin.com/in/dmytro-shumskyi-9489ab260/), [Severyn Shykula](https://www.linkedin.com/in/severyn-shykula-87a3aa23a/), and [Artur d'Avila Garcez](https://www.staff.city.ac.uk/~aag/).


#### Relevant resources (Phase 1: interoperability and coverage):

- Experiments with different LLMs (and prompts) as diagnostic tools (e.g., Oracles): [https://github.com/city-artificial-intelligence/rai-ukraine-kga-llm](https://github.com/city-artificial-intelligence/rai-ukraine-kga-llm)
- LogMapLLM (integrated pipeline): [https://github.com/city-artificial-intelligence/logmap-llm](https://github.com/city-artificial-intelligence/logmap-llm)
- LogMap Ontology Alignment System: [https://github.com/ernestojimenezruiz/logmap-matcher](https://github.com/ernestojimenezruiz/logmap-matcher)
- DISO: Defence, Intelligence and Security Ontologies: [https://github.com/city-artificial-intelligence/diso](https://github.com/city-artificial-intelligence/diso)
- DISO OAEI track: [https://city-artificial-intelligence.github.io/diso-oaei/](https://city-artificial-intelligence.github.io/diso-oaei/)

### Acknowledgements

This research was supported by Turing Innovations Limited and The Alan Turing Institute's Defence and Security. Sviatoslav Lushnei, Dmytro Shumskyi, Severyn Shykula collaborated with the GUARD team thanks to the [RAI for Ukraine program](https://r-ai.co/ukraine) of the NYU Center for Responsible AI. 

<br/>