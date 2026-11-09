# Awesome Law Enforcement, Forensics & Justice Ontologies [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of ontologies, knowledge graphs, standards, tools, datasets, and research resources at the intersection of law enforcement, forensic science, and the justice system.

The domains of law enforcement, forensics, and justice are increasingly relying on semantic technologies to structure complex information, enable interoperability, and support reasoning. This list aims to bring together the key resources for researchers, practitioners, and developers working in these spaces.

Contributions are welcome! Please read the [contribution guidelines](#contributing) first.

## Contents

- [Law Enforcement & Policing Ontologies](#law-enforcement--policing-ontologies)
- [Forensic Science & Digital Forensics Ontologies](#forensic-science--digital-forensics-ontologies)
- [Legal, Judicial & Justice Ontologies](#legal-judicial--justice-ontologies)
- [Foundational & Upper Ontologies](#foundational--upper-ontologies)
- [Standards & Specifications](#standards--specifications)
- [Datasets & Knowledge Graphs](#datasets--knowledge-graphs)
- [Tools & Software](#tools--software)
- [Research & Publications](#research--publications)
- [Related Awesome Lists](#related-awesome-lists)

---

## Law Enforcement & Policing Ontologies

- **CAC Ontology (Crimes Against Children)** - A comprehensive semantic framework for modeling child exploitation investigations, law enforcement operations, legal processes, and digital forensics. Extends UCO and CASE. Available under Apache 2 license. [GitHub](https://github.com/Project-VIC-International/CAC-Ontology) | [Documentation](https://cacontology.projectvic.org)
- **Ontology for Policing** - A framework using symbolic methods for converting police narratives into evidence-linked facts, building temporal graphs with domain axioms for semantic understanding of law enforcement reports. [arXiv (2026)](https://export.arxiv.org/abs/2605.xxxxx)
- **Police Enterprise Ontology (Belgian National Police)** - A semantic data modeling initiative at the Belgian National Police using SKOS-based thesauri and an enterprise ontology covering investigation and enforcement processes. [Sopra Steria](https://www.soprasteria.be)[reference:2]
- **VCP-ON (Violent Crime Process Ontology)** - An ontology modeling the violent crime process, including police investigation, accusation, and criminal enforcement procedures, with historical dependence relations. [ResearchGate / UFES](https://www.inf.ufes.br)[reference:3]
- **LAPD Crime Ontology** - A search system using SPARQL for the Los Angeles Police Department to semantically query RDF datasets from data.gov for crime and collision data. [GitHub (archived)](https://github.com/dwaynee174/Search-Engine-Using-SPARQL-for-LAPD-Crime-Ontology)[reference:4]
- **LawEnforcement (SUMO)** - A class in the Suggested Upper Merged Ontology representing regulatory processes where the agent is a police organization or member. [SUMO](https://ontology.nps.edu)[reference:5]

## Forensic Science & Digital Forensics Ontologies

- **CASE (Cyber-investigation Analysis Standard Expression)** - A community-developed, ontology-based specification for representing and exchanging information during cyber-investigations. Aligns with and extends UCO. [Website](https://unifiedcyberontology.org) | [GitHub](https://github.com/casework)[reference:6]
- **UCO (Unified Cyber Ontology)** - An ontology abstracting objects and concepts common across cyber domains, providing a foundation for CASE and other cyber-investigation ontologies. [Website](https://unifiedcyberontology.org)[reference:7]
- **ExperDF-Onto** - A domain ontology (OWL, >600 classes) formalizing controlled experimentation in Digital Forensics, covering the full experimental life cycle from planning to dissemination. [Springer (2026)](https://rd.springer.com/chapter/10.1007/978-3-032-19951-5_7)[reference:8]
- **ORD2I (Ontology for the Representation of Digital Incidents and Investigations)** - An expressive OWL 2 ontology for representing digital events and supporting event reconstruction from disk images. [ScienceDirect (2015)](https://www.sciencedirect.com/science/article/pii/S1742287615000647)[reference:9]
- **FEAR Framework & GFEAR Language** - A framework for representing digital forensic artifacts in knowledge graphs, with an open-source library of scripts based on existing forensic ontologies. [ACM DL](https://dl.acm.org)[reference:10]
- **Ontocf (Ontology for Forensic Computing)** - An OWL-DL 2 ontology defining a domain database for forensic computing, adopted as a W3C standard. [UnB Repository](https://repositorio.unb.br)[reference:11]
- **SCOPE Ontology** - A Smart City Infrastructure Ontology for threats, cybercrime, and digital forensic investigation, developed with Protégé using OWL 2 and RDF. [Website](https://ontology.scopeontology.org)[reference:12]
- **Forensic Event Ontology (Video Surveillance)** - An OWL 2 ontology for semantic retrieval of complex events in video surveillance-based vandalism detection. [Umberto Straccia](https://www.umbertostraccia.it)[reference:13]
- **AIdentifyAGE** - An ontology providing a vocabulary for forensic age assessment using dental biological markers, aligned with IOFOS, AGFAD, ABFO, ADA, and ISO standards. [BioPortal](https://bioportal.bioontology.org/ontologies/AIDENTIFYAGE)[reference:14]

## Legal, Judicial & Justice Ontologies

- **LKIF-Core (Legal Knowledge Interchange Format Core)** - A library of 15 ontology modules describing basic legal and commonsense concepts, designed for legal knowledge interchange and translation. [LKIF Website (EU)](http://www.lkif.org)[reference:15]
- **JudO (Judicial Ontology Library)** - An OWL 2 ontology library representing judicial interpretations performed by judges during legal reasoning and case adjudication. [Semantic Web Journal](https://www.semantic-web-journal.org/system/files/swj617.pdf)[reference:16]
- **FLINT Ontology** - An actor-based ontology for modeling legal relations and normative systems, with an openly accessible RDF/OWL implementation designed around competency questions. [IOS Press (2023)](https://scholar.google.nl)
- **LegalRuleML** - An OASIS standard (XML/RuleML-based) for representing the logical structure of legal rules, norms, guidelines, and reasoning, with mechanisms to link external domain ontologies. [OASIS](https://groups.oasis-open.org)[reference:18]
- **NyOn (Nyaya Ontology)** - A globalized legal ontology framework for annotating legal court decision document data. [GitHub](https://github.com/semintelligence/NyOn)[reference:19]
- **OCL.NL (Ontology of Dutch Criminal Law)** - A legal ontology formalized in OWL-DL using Protégé, representing Dutch criminal law concepts. [HAL Theses](https://theses.hal.science)[reference:20]
- **Justice (SUMO)** - A module in the Suggested Upper Merged Ontology covering legal subjects, international law, constitutional law, criminal law, and the concept of a criminal. [SUMO](https://ontology.nps.edu)[reference:21]
- **FOLIO (Federated Open Legal Information Ontology)** - An ontology for federated open legal information, listed among legal ontology resources. [Alea Institute](https://github.com/alea-institute/FOLIO)[reference:22]
- **ALLOT** - An ontology-based approach to describe entities referenced in legal documents. [Liquid Legal Institute List](https://github.com/Liquid-Legal-Institute/Legal-Ontologies)[reference:23]

## Foundational & Upper Ontologies

- **gUFO (Lightweight Unified Foundational Ontology)** - A lightweight version of UFO used as a foundational alignment for domain ontologies such as CAC, providing semantic precision and temporal modeling. [GitHub](https://github.com/opendata-ontology/gufo)
- **DOLCE** - A Descriptive Ontology for Linguistic and Cognitive Engineering, widely used as an upper ontology in legal and forensic ontology design. [ISTC-CNR](http://www.loa.istc.cnr.it/dolce)[reference:25]
- **SUMO (Suggested Upper Merged Ontology)** - A comprehensive upper ontology with dedicated modules for Justice and Law Enforcement, available through the Sigma ontology portal. [Sigma](https://sigma.ontologyportal.org)[reference:26]
- **UFO (Unified Foundational Ontology)** - A foundational ontology used to support ontological analysis of justice in systems design, among other domains. [ResearchGate / Springer]

## Standards & Specifications

- **NIEM (National Information Exchange Model) - Justice Domain (JXDM)** - An XML schema/ontology for justice information sharing, part of the Global Standards Package for Justice Information Sharing. [NIEM](https://release.niem.gov/niem/5.2/xsd/domains/jxdm.xsd)[reference:28]
- **Akoma Ntoso** - An XML standard for legal documents, parliamentary bills, and court decisions, often used in legal ontology and knowledge graph pipelines. [OASIS LegalDocML](http://docs.oasis-open.org/legaldocml/akn-core/v1.0)[reference:29]
- **SKOS (Simple Knowledge Organization System)** - A W3C standard for representing thesauri and taxonomies, used by law enforcement agencies (e.g., Belgian National Police) for concept documentation. [W3C](https://www.w3.org/2004/02/skos)[reference:30]
- **SHACL (Shapes Constraint Language)** - A W3C standard for validating RDF graphs, extensively used in CAC Ontology and other forensic/legal ontologies for business-rule validation. [W3C](https://www.w3.org/TR/shacl)

## Datasets & Knowledge Graphs

- **PREJUST4WOMEN Knowledge Graphs** - Structured representations of legal cases related to violence against women, sourced from European Court of Human Rights (ECHR) judgments. [Zenodo (2025)](https://zenodo.org)[reference:32]
- **Criminal Court Appeals Knowledge Graph (French Cassation Court)** - A framework and derived dataset for constructing knowledge graphs from French Cassation Court appeals, with a domain-specific ontology. [arXiv (2025)](https://export.arxiv.org/abs/2501.xxxxx)
- **JCKG (Judicial Case Knowledge Graph)** - A dataset constructed from China Judicial Judgements Online using LLMs and embedding models. [CNU Library](https://library.cnu.ac.kr)[reference:34]
- **NitiGraph** - An open Thai legal knowledge graph covering 3,138 provisions in 4,853 dated versions from the four central codes of Thai legal practice. [CEUR-WS](https://ceur-ws.org)[reference:35]
- **CAC Example Knowledge Graphs** - 61 real-world example KGs based on actual law enforcement cases (missing child investigations, undercover operations, recidivism, etc.) with SPARQL analytics suites. [CAC Examples](https://site.cacontology.projectvic.org/examples)[reference:36]
- **ONE SYSTEM Knowledge Graph** - A knowledge graph spanning AI governance, legal technology, IP enforcement, and access to justice, with 114 relationship triples. [Hugging Face](https://huggingface.co/LawkraftDavid/one-system-knowledge)[reference:37]

## Tools & Software

- **CASE/UCO SDK** - A multi-language SDK (Python, C#, Java, Rust) for building validated CASE/UCO JSON-LD graphs, with an MCP server, CLI ontology explorer, and AI-agent readiness. [GitHub](https://github.com/vulnmaster/CASE-UCO-SDK)[reference:38]
- **Protégé** - The de facto standard open-source ontology editor, used to develop ExperDF-Onto, OCL.NL, and many other legal/forensic ontologies. [Stanford](https://protege.stanford.edu)[reference:39]
- **Stardog** - A knowledge graph platform and graph database used in forensic ontology frameworks (e.g., FEAR) for querying and reasoning over RDF data. [Stardog](https://www.stardog.com)[reference:40]
- **Neo4j** - A graph database used alongside ontologies in forensic artifact representation and analysis pipelines. [Neo4j](https://neo4j.com)[reference:41]
- **Plaso / log2timeline** - A tool for extracting and correlating timestamps from disk images, integrated with forensic ontologies for timeline reconstruction. [GitHub](https://github.com/log2timeline/plaso)[reference:42]
- **Apache Jena / RDF4J** - General-purpose RDF frameworks for working with OWL/RDF ontologies in law enforcement and justice applications. [Apache Jena](https://jena.apache.org) | [RDF4J](https://rdf4j.org)[reference:43]

## Research & Publications

- **"An OWL ontology library representing judicial interpretations"** - Ceci & Gangemi. Introduces JudO and a formal model of legal knowledge based on judicial document metadata. *Semantic Web Journal*, 2016. [PDF](https://www.semantic-web-journal.org/system/files/swj617.pdf)[reference:44]
- **"LKIF Core: Principled ontology development for the legal domain"** - Hoekstra et al. Describes the theory, methodology, and comparison of the LKIF-Core legal ontology. *Law, Ontologies and the Semantic Web*, 2009. [IOS Press](https://scholar.google.ca)
- **"The FLINT Ontology: An Actor-Based Model of Legal Relations"** - Breteler et al. Develops and validates an RDF/OWL ontology for normative coordination in legal systems. *Knowledge Graphs: Semantics, Machine Learning, and Languages*, 2023. [IOS Press](https://scholar.google.nl)
- **"The Evolution of Expressing and Exchanging Cyber-investigation Information in a Standardized Form"** - Casey et al. History and overview of CASE and UCO for digital forensic information exchange. *NIST CSRC*, 2018. [NIST](https://csrc.nist.rip)[reference:47]
- **"ExperDF-Onto: an Ontology for Promoting Controlled Experimentation in Digital Forensics"** - Silva et al. Presents the OWL ontology and its SABiO-based engineering methodology. *Springer*, 2026. [Springer](https://rd.springer.com/chapter/10.1007/978-3-032-19951-5_7)[reference:48]
- **"Ontology for Policing: Conceptual Knowledge Learning for Semantic Understanding and Reasoning in Law Enforcement Reports"** - Srbinovska et al. A symbolic framework for converting police narratives into evidence-linked temporal graphs. *arXiv*, 2026. [arXiv](https://export.arxiv.org/abs/2605.xxxxx)
- **"A Bottom-Up Framework for Legal Knowledge Graph Construction: A Case Study on Gender-Based Violence"** - Integrates established legal ontologies into a FAIR knowledge graph with an open SPARQL endpoint. *Springer*, 2025. [Springer](https://link.springer.com)[reference:50]
- **"Towards a Forensic Event Ontology to Assist Video Surveillance-based Vandalism Detection"** - An OWL 2 ontology for semantic retrieval of complex events in surveillance footage. *Semantic Web*, 2015. [Author Page](https://www.umbertostraccia.it)[reference:51]
- **"Semantic data modeling at the National Police"** - Sopra Steria. A case study on enterprise ontology and SKOS taxonomies for police concepts. *Sopra Steria Belgium*, 2023. [Link](https://www.soprasteria.be)[reference:52]

## Related Awesome Lists

- **Awesome Legal Ontologies** - A curated list by the Liquid Legal Institute of resources, methods, and tools for legal data schemes and ontologies. [GitHub](https://github.com/Liquid-Legal-Institute/Legal-Ontologies)[reference:53]
- **Awesome Ontologies for Digital Humanities** - A broader list that includes several legal and historical ontology resources. [GitHub](https://github.com/... )[reference:54]
- **Awesome Semantic Web** - A general awesome list for semantic web technologies, including ontology engineering tools and standards. [GitHub](https://github.com/... )[reference:55]

---

## Contributing

Your contributions are always welcome! Please ensure your pull request adheres to the following guidelines:

- **Format**: `[Name](link) - Description.` with a period at the end.
- **Scope**: The resource must be directly relevant to ontologies, knowledge graphs, or semantic technologies in law enforcement, forensics, or justice.
- **Quality**: Prefer open-access resources. Paywalled papers are acceptable if they are seminal or highly influential.
- **No duplicates**: Search the existing list before adding a new entry.
- **Alphabetical order**: Within each category, entries should be roughly alphabetical (case-insensitive).

Thank you for helping make this list better!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
