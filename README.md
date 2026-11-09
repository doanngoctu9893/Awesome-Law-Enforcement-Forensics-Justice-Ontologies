# Awesome Law Enforcement, Forensics & Justice Ontologies 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of ontologies, knowledge graphs, standards, tools, datasets, and research resources at the intersection of law enforcement, forensic science, and the justice system—spanning multiple languages and legal traditions.

The domains of law enforcement, forensics, and justice are increasingly relying on semantic technologies to structure complex information, enable interoperability, and support reasoning. This list brings together key resources for researchers, practitioners, and developers worldwide. Contributions are welcome! Please read the [contribution guidelines](#contributing) first.

## Contents

- [Law Enforcement & Policing Ontologies](#law-enforcement--policing-ontologies)
- [Forensic Science & Digital Forensics Ontologies](#forensic-science--digital-forensics-ontologies)
- [Legal, Judicial & Justice Ontologies](#legal-judicial--justice-ontologies)
- [Multilingual & Regional Resources](#multilingual--regional-resources)
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
- **Police Enterprise Ontology (Belgian National Police)** - A semantic data modeling initiative at the Belgian National Police using SKOS-based thesauri and an enterprise ontology covering investigation and enforcement processes. [Sopra Steria](https://www.soprasteria.be)
- **VCP-ON (Violent Crime Process Ontology)** - An ontology modeling the violent crime process, including police investigation, accusation, and criminal enforcement procedures, with historical dependence relations. [ResearchGate / UFES](https://www.inf.ufes.br)
- **LAPD Crime Ontology** - A search system using SPARQL for the Los Angeles Police Department to semantically query RDF datasets from data.gov for crime and collision data. [GitHub (archived)](https://github.com/dwaynee174/Search-Engine-Using-SPARQL-for-LAPD-Crime-Ontology)
- **LawEnforcement (SUMO)** - A class in the Suggested Upper Merged Ontology representing regulatory processes where the agent is a police organization or member. [SUMO](https://ontology.nps.edu)

## Forensic Science & Digital Forensics Ontologies

- **CASE (Cyber-investigation Analysis Standard Expression)** - A community-developed, ontology-based specification for representing and exchanging information during cyber-investigations. Aligns with and extends UCO. [Website](https://unifiedcyberontology.org) | [GitHub](https://github.com/casework)
- **UCO (Unified Cyber Ontology)** - An ontology abstracting objects and concepts common across cyber domains, providing a foundation for CASE and other cyber-investigation ontologies. [Website](https://unifiedcyberontology.org)
- **ExperDF-Onto** - A domain ontology (OWL, >600 classes) formalizing controlled experimentation in Digital Forensics, covering the full experimental life cycle from planning to dissemination. [Springer (2026)](https://rd.springer.com/chapter/10.1007/978-3-032-19951-5_7)
- **ORD2I (Ontology for the Representation of Digital Incidents and Investigations)** - An expressive OWL 2 ontology for representing digital events and supporting event reconstruction from disk images. [ScienceDirect (2015)](https://www.sciencedirect.com/science/article/pii/S1742287615000647)
- **FEAR Framework & GFEAR Language** - A framework for representing digital forensic artifacts in knowledge graphs, with an open-source library of scripts based on existing forensic ontologies. [ACM DL](https://dl.acm.org)
- **Ontocf (Ontology for Forensic Computing)** - An OWL-DL 2 ontology defining a domain database for forensic computing, adopted as a W3C standard. [UnB Repository](https://repositorio.unb.br)
- **SCOPE Ontology** - A Smart City Infrastructure Ontology for threats, cybercrime, and digital forensic investigation, developed with Protégé using OWL 2 and RDF. [Website](https://ontology.scopeontology.org)
- **Forensic Event Ontology (Video Surveillance)** - An OWL 2 ontology for semantic retrieval of complex events in video surveillance-based vandalism detection. [Umberto Straccia](https://www.umbertostraccia.it)
- **AIdentifyAGE** - An ontology providing a vocabulary for forensic age assessment using dental biological markers, aligned with IOFOS, AGFAD, ABFO, ADA, and ISO standards. [BioPortal](https://bioportal.bioontology.org/ontologies/AIDENTIFYAGE)
- **On-Chain Address Clustering Ontology (Chainalysis)** - A proposed ontology for standardizing blockchain forensic methods, specifically address clustering, aimed at law enforcement agencies for on-chain tracking. [Bitget News (2026)](https://www.bitget.site)

## Legal, Judicial & Justice Ontologies

- **LKIF-Core (Legal Knowledge Interchange Format Core)** - A library of 15 ontology modules describing basic legal and commonsense concepts, designed for legal knowledge interchange and translation. [LKIF Website (EU)](http://www.lkif.org)
- **JudO (Judicial Ontology Library)** - An OWL 2 ontology library representing judicial interpretations performed by judges during legal reasoning and case adjudication. [Semantic Web Journal](https://www.semantic-web-journal.org/system/files/swj617.pdf)
- **FLINT Ontology** - An actor-based ontology for modeling legal relations and normative systems, with an openly accessible RDF/OWL implementation designed around competency questions. [IOS Press (2023)](https://scholar.google.nl)
- **LegalRuleML** - An OASIS standard (XML/RuleML-based) for representing the logical structure of legal rules, norms, guidelines, and reasoning, with mechanisms to link external domain ontologies. [OASIS](https://groups.oasis-open.org)
- **NyOn (Nyaya Ontology)** - A globalized legal ontology framework for annotating legal court decision document data. [GitHub](https://github.com/semintelligence/NyOn)
- **OCL.NL (Ontology of Dutch Criminal Law)** - A legal ontology formalized in OWL-DL using Protégé, representing Dutch criminal law concepts. [HAL Theses](https://theses.hal.science)
- **Justice (SUMO)** - A module in the Suggested Upper Merged Ontology covering legal subjects, international law, constitutional law, criminal law, and the concept of a criminal. [SUMO](https://ontology.nps.edu)
- **FOLIO (Federated Open Legal Information Ontology)** - An ontology for federated open legal information, listed among legal ontology resources. [Alea Institute](https://github.com/alea-institute/FOLIO)
- **ALLOT** - An ontology-based approach to describe entities referenced in legal documents. [Liquid Legal Institute List](https://github.com/Liquid-Legal-Institute/Legal-Ontologies)
- **LRI-Core** - An "upper" legal ontology used as a foundation for domain ontologies such as e-Court (Portuguese criminal documents) and OCL.NL. [JURIX](https://jurix.nl)

## Multilingual & Regional Resources

This section highlights ontologies, frameworks, and datasets that are either developed for a specific legal/linguistic tradition or explicitly address non-English materials.

### Spanish & Portuguese

- **SPCO (Spanish Property Crime Ontology)** - An ontology developed for the Spanish legal system to guide information extraction from police reports and assist judges in classifying property crimes. Validated with judges and prosecutors in Spain. [Springer (2024)](https://link.springer.com/article/10.1007/s12599-024-00886-3) | [PDF](https://zaguan.unizar.es/record/147715/files/texto_completo.pdf)
- **e-Court Ontology** - An ontology based on the LRI-Core framework, developed to index archived criminal legal documents (including audio and video) in Portuguese, generating metadata such as crime type and hearing phase. [Buscalegis UFSC](https://www.buscalegis.ufsc.br/revistas/index.php/observatoriodoegov/article/download/311/207)
- **LEGIS Ontology (Brazilian Criminal Law)** - A set of domain ontologies (OntoProperty, ontology of crimes against life) formalizing part of the Brazilian Penal Code to support legal reasoning and simulation of legal actions. [UFPE Repository](https://repositorio.ufpe.br/bitstream/123456789/33904/1/TESE%20Cleyton%20M%C3%A1rio%20de%20Oliveira%20Rodrigues.pdf)
- **Agatha Project Ontology** - A Linked Data approach to representing and reasoning over Portuguese criminal investigation documents, using ontologies and a criminal law micro-thesaurus. [arXiv / LISP](https://ar5iv.labs.arxiv.org)

### French

- **French Cassation Court Knowledge Graph Framework** - A framework including a domain-specific ontology for constructing knowledge graphs from appeals to the French Court of Cassation, enabling structured representation of criminal court decisions. [arXiv (2025)](https://export.arxiv.org/abs/2501.14579)
- **Ontology for Legal Reasoning on Data Sharing (Law Enforcement)** - Research on an ontology supporting legal reasoning about data sharing and processing between law enforcement agencies, conducted within French institutional contexts. [IMT Atlantique HAL](https://imt-atlantique.hal.science)

### Italian

- **LexOnt-IT** - An OWL 2 DL ontology for the formal semantic representation of Italian Supreme Court of Cassation case law, modeling decisions, legal institutes, statutory provisions, judicial panels, and citation networks. Aligns with ELI, ECLI, Akoma Ntoso, and NIR standards. Accompanied by the LexQuery natural-language interface. [Zenodo (2026)](https://zenodo.org/records/21643127)
- **Italian Crime Ontology** - A domain ontology designed for reuse in Italian and Polish criminal law within the European e-COURT project, representing agents, processes, and factors involved in crime commission. [UPV Repository](https://riunet.upv.es)

### German

- **Ontology for Mobile Communication in Digital Forensics (CASE Extension)** - A German thesis investigating the suitability of an ontology based on CASE/UCO for representing mobile communication data in digital forensics, with an experimental mapping to the MoNA analysis platform. [HS Mittweida](https://monami.hs-mittweida.de/frontdoor/deliver/index/docId/14771/file/MA_46842_Lukas-Jaeckel.pdf)
- **Digital Forensics Ontology Scoping Review (INFORMATIK 2022)** - A systematic review of ontological formalization attempts in the digital forensics domain, presented at the German Informatics Society conference. [GI Digital Library](https://dl7-productive.gi.de)

### Dutch

- **Dutch Criminal Law Ontology (OCL.NL)** - An OWL-DL ontology representing concepts of Dutch criminal law, developed using Protégé and rooted in the LRI-Core upper ontology. [JURIX / HAL](https://jurix.nl)

### Chinese

- **JCKG (Judicial Case Knowledge Graph)** - A dataset and construction method for a judicial case knowledge graph derived from China Judicial Judgements Online, using LLMs and embedding models. [CNU Library](https://library.cnu.ac.kr)

### Japanese

- **Application of Ontologies and AI to Legal Domain** - A Japanese-language resource discussing how ontologies can be applied in the legal field to organize and share legal information, automate legal processes, and improve efficiency. [Deus Ex Machina](https://deus-ex-machina-ism.com)

### Korean

- **Legal Ontology Construction Apparatus and Method (Patent KR101664454B1)** - A Korean patent describing a method for constructing a legal ontology based on legal hierarchy and converting legal sentences into triples using predefined patterns. [Google Patents](https://patents.google.com/patent/KR101664454B1)
- **Study on Extracting Ontologies from Legal Terminology** - A Korean dissertation on building legal ontologies from structural definitions of legal terms and using them for semantic retrieval. [Korea University Library](https://library.korea.ac.kr)

### Vietnamese

- **ViLO (Vietnamese Legal Documents Core Ontology)** - A core ontology for Vietnamese legal documents covering the general legal domain, including institutions of the Vietnamese political system and types/structures of legal documents. [Google Patents / NU Find](https://patents.google.com) | [NU Library](https://nufind.nu.edu.sa)

### Thai

- **NitiGraph (Thai Legal Knowledge Graph)** - An open Thai legal knowledge graph covering 3,138 provisions in 4,853 dated versions from the four central codes of Thai legal practice. [CEUR-WS](https://ceur-ws.org)

### Cross-Lingual & Comparative

- **e-COURT European Project Ontologies** - A European project that produced ontologies for criminal law and judicial cooperation reusable across Italian, Polish, and other legal systems, built on the LRI-Core framework. [UPV Repository](https://riunet.upv.es)
- **MAGNETO Ontology** - A common representational model and ontology for law enforcement agencies (LEAs) to manage, analyze, correlate, and reason over large, heterogeneous datasets, with applications in cross-border law enforcement. [World Scientific](https://www.worldscientific.com)

## Foundational & Upper Ontologies

- **gUFO (Lightweight Unified Foundational Ontology)** - A lightweight version of UFO used as a foundational alignment for domain ontologies such as CAC, providing semantic precision and temporal modeling. [GitHub](https://github.com/opendata-ontology/gufo)
- **DOLCE** - A Descriptive Ontology for Linguistic and Cognitive Engineering, widely used as an upper ontology in legal and forensic ontology design. [ISTC-CNR](http://www.loa.istc.cnr.it/dolce)
- **SUMO (Suggested Upper Merged Ontology)** - A comprehensive upper ontology with dedicated modules for Justice and Law Enforcement, available through the Sigma ontology portal. [Sigma](https://sigma.ontologyportal.org)
- **UFO (Unified Foundational Ontology)** - A foundational ontology used to support ontological analysis of justice in systems design, among other domains. [ResearchGate / Springer]
- **LRI-Core** - A legal "upper" ontology developed at the University of Amsterdam as part of the e-COURT European project, providing a social and communicative foundation for domain legal ontologies. [JURIX](https://jurix.nl)

## Standards & Specifications

- **NIEM (National Information Exchange Model) - Justice Domain (JXDM)** - An XML schema/ontology for justice information sharing, part of the Global Standards Package for Justice Information Sharing. [NIEM](https://release.niem.gov/niem/5.2/xsd/domains/jxdm.xsd)
- **Akoma Ntoso** - An XML standard for legal documents, parliamentary bills, and court decisions, often used in legal ontology and knowledge graph pipelines. [OASIS LegalDocML](http://docs.oasis-open.org/legaldocml/akn-core/v1.0)
- **SKOS (Simple Knowledge Organization System)** - A W3C standard for representing thesauri and taxonomies, used by law enforcement agencies (e.g., Belgian National Police) for concept documentation. [W3C](https://www.w3.org/2004/02/skos)
- **SHACL (Shapes Constraint Language)** - A W3C standard for validating RDF graphs, extensively used in CAC Ontology and other forensic/legal ontologies for business-rule validation. [W3C](https://www.w3.org/TR/shacl)

## Datasets & Knowledge Graphs

- **PREJUST4WOMEN Knowledge Graphs** - Structured representations of legal cases related to violence against women, sourced from European Court of Human Rights (ECHR) judgments. [Zenodo (2025)](https://zenodo.org)
- **French Cassation Court Knowledge Graph Dataset** - A derived dataset accompanying the framework for constructing knowledge graphs from French Cassation Court appeals, based on a domain-specific ontology. [arXiv (2025)](https://export.arxiv.org/abs/2501.14579)
- **JCKG (Judicial Case Knowledge Graph)** - A dataset constructed from China Judicial Judgements Online using LLMs and embedding models. [CNU Library](https://library.cnu.ac.kr)
- **NitiGraph** - An open Thai legal knowledge graph covering 3,138 provisions in 4,853 dated versions from the four central codes of Thai legal practice. [CEUR-WS](https://ceur-ws.org)
- **CAC Example Knowledge Graphs** - 61 real-world example KGs based on actual law enforcement cases (missing child investigations, undercover operations, recidivism, etc.) with SPARQL analytics suites. [CAC Examples](https://site.cacontology.projectvic.org/examples)
- **ONE SYSTEM Knowledge Graph** - A knowledge graph spanning AI governance, legal technology, IP enforcement, and access to justice, with 114 relationship triples. [Hugging Face](https://huggingface.co/LawkraftDavid/one-system-knowledge)

## Tools & Software

- **CASE/UCO SDK** - A multi-language SDK (Python, C#, Java, Rust) for building validated CASE/UCO JSON-LD graphs, with an MCP server, CLI ontology explorer, and AI-agent readiness. [GitHub](https://github.com/vulnmaster/CASE-UCO-SDK)
- **Protégé** - The de facto standard open-source ontology editor, used to develop ExperDF-Onto, OCL.NL, and many other legal/forensic ontologies. [Stanford](https://protege.stanford.edu)
- **Stardog** - A knowledge graph platform and graph database used in forensic ontology frameworks (e.g., FEAR) for querying and reasoning over RDF data. [Stardog](https://www.stardog.com)
- **Neo4j** - A graph database used alongside ontologies in forensic artifact representation and analysis pipelines. [Neo4j](https://neo4j.com)
- **Plaso / log2timeline** - A tool for extracting and correlating timestamps from disk images, integrated with forensic ontologies for timeline reconstruction. [GitHub](https://github.com/log2timeline/plaso)
- **Apache Jena / RDF4J** - General-purpose RDF frameworks for working with OWL/RDF ontologies in law enforcement and justice applications. [Apache Jena](https://jena.apache.org) | [RDF4J](https://rdf4j.org)
- **LexQuery** - A natural-language querying engine that uses ontology schema grounding and LLMs to translate questions into SPARQL queries, demonstrated on the LexOnt-IT Italian case law knowledge graph. [Zenodo](https://zenodo.org/records/21643127)

## Research & Publications

- **"An OWL ontology library representing judicial interpretations"** - Ceci & Gangemi. Introduces JudO and a formal model of legal knowledge based on judicial document metadata. *Semantic Web Journal*, 2016. [PDF](https://www.semantic-web-journal.org/system/files/swj617.pdf)
- **"LKIF Core: Principled ontology development for the legal domain"** - Hoekstra et al. Describes the theory, methodology, and comparison of the LKIF-Core legal ontology. *Law, Ontologies and the Semantic Web*, 2009. [IOS Press](https://scholar.google.ca)
- **"The FLINT Ontology: An Actor-Based Model of Legal Relations"** - Breteler et al. Develops and validates an RDF/OWL ontology for normative coordination in legal systems. *Knowledge Graphs: Semantics, Machine Learning, and Languages*, 2023. [IOS Press](https://scholar.google.nl)
- **"The Evolution of Expressing and Exchanging Cyber-investigation Information in a Standardized Form"** - Casey et al. History and overview of CASE and UCO for digital forensic information exchange. *NIST CSRC*, 2018. [NIST](https://csrc.nist.rip)
- **"ExperDF-Onto: an Ontology for Promoting Controlled Experimentation in Digital Forensics"** - Silva et al. Presents the OWL ontology and its SABiO-based engineering methodology. *Springer*, 2026. [Springer](https://rd.springer.com/chapter/10.1007/978-3-032-19951-5_7)
- **"Ontology for Policing: Conceptual Knowledge Learning for Semantic Understanding and Reasoning in Law Enforcement Reports"** - Srbinovska et al. A symbolic framework for converting police narratives into evidence-linked temporal graphs. *arXiv*, 2026. [arXiv](https://export.arxiv.org/abs/2605.xxxxx)
- **"A Bottom-Up Framework for Legal Knowledge Graph Construction: A Case Study on Gender-Based Violence"** - Integrates established legal ontologies into a FAIR knowledge graph with an open SPARQL endpoint. *Springer*, 2025. [Springer](https://link.springer.com)
- **"Towards a Forensic Event Ontology to Assist Video Surveillance-based Vandalism Detection"** - An OWL 2 ontology for semantic retrieval of complex events in surveillance footage. *Semantic Web*, 2015. [Author Page](https://www.umbertostraccia.it)
- **"Semantic data modeling at the National Police"** - Sopra Steria. A case study on enterprise ontology and SKOS taxonomies for police concepts. *Sopra Steria Belgium*, 2023. [Link](https://www.soprasteria.be)
- **"Ontology-Driven Automated Reasoning About Property Crimes"** - Navarrete et al. Describes the SPCO ontology for the Spanish legal system, used to classify police reports of property crimes with probabilistic inference, validated in a real judicial environment. *Business & Information Systems Engineering*, 2024. [Springer](https://link.springer.com/article/10.1007/s12599-024-00886-3)
- **"LexOnt-IT & LexQuery: An OWL 2 DL Ontology and a Natural-Language Interface for Italian Case Law"** - Presents an OWL 2 DL ontology for Italian Supreme Court of Cassation case law and a natural-language SPARQL query engine, with a benchmark evaluation. *Zenodo*, 2026. [Zenodo](https://zenodo.org/records/21643127)
- **"Knowledge Graphs Construction from Criminal Court Appeals: Insights from the French Cassation Court"** - Belikov & colleagues. A framework including a domain-specific ontology and dataset for structuring French criminal court appeals. *arXiv*, 2025. [arXiv](https://export.arxiv.org/abs/2501.14579)
- **"ViLO — A Core Ontology of Vietnamese Legal Documents"** - Nguyen et al. Proposes a core ontology for Vietnamese legal documents covering the general legal domain, institutions, and document structures. [Google Patents / NU Library](https://nufind.nu.edu.sa)
- **"Common Representational Model and Ontologies for Effective Law Enforcement Solutions"** - Introduces the MAGNETO ontology for law enforcement agencies to manage heterogeneous datasets. *World Scientific*. [World Scientific](https://www.worldscientific.com)

## Related Awesome Lists

- **Awesome Legal Ontologies** - A curated list by the Liquid Legal Institute of resources, methods, and tools for legal data schemes and ontologies. [GitHub](https://github.com/Liquid-Legal-Institute/Legal-Ontologies)
- **Awesome Ontologies for Digital Humanities** - A broader list that includes several legal and historical ontology resources. [GitHub](https://github.com/... )
- **Awesome Semantic Web** - A general awesome list for semantic web technologies, including ontology engineering tools and standards. [GitHub](https://github.com/... )

---

## Contributing

Your contributions are always welcome! Please ensure your pull request adheres to the following guidelines:

- **Format**: `[Name](link) - Description.` with a period at the end.
- **Scope**: The resource must be directly relevant to ontologies, knowledge graphs, or semantic technologies in law enforcement, forensics, or justice.
- **Language**: Resources in languages other than English are explicitly encouraged. Please indicate the language or regional focus in the description.
- **Quality**: Prefer open-access resources. Paywalled papers are acceptable if they are seminal or highly influential.
- **No duplicates**: Search the existing list before adding a new entry.
- **Alphabetical order**: Within each category, entries should be roughly alphabetical (case-insensitive).

Thank you for helping make this list better!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
