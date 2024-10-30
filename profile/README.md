# Enhanced MeliCERTes Ecosystem - EME

The Enhanced MeliCERTes Ecosystem (EME) is an open-source software platform designed to facilitate timely secure incident reporting and management, online communication and collaboration, and cyber threat intelligence (CTI) sharing among cybersecurity authorities, incident response teams, and critical infrastructure operators from within a single distributed platform. It integrates a  number of advanced tools to enhance the management, analysis and sharing of cybersecurity incidents and the structured communication of threat intelligence, thereby enhancing situational awareness, timely response and attack impact minimization.

The Enhanced MeliCERTes Ecosystem has resulted from the [EU-funded H2020 IRIS project, GA No: 101021727](https://cordis.europa.eu/project/id/101021727), presenting one of its resulting four Service Bundles. The IRIS project aimed to deliver a framework to support European CERT and CSIRT networks detecting, sharing, responding and recovering from cybersecurity threats and vulnerabilities of IoT and AI-driven systems within smart cities, interacting with the respective Critical Infrastructure Operators. The resulting platform, encompassing all tools and systems developed within the project, has been a distributed system with loosely coupled architecture, enabling:
* Automated diverse vulnerabilities and threat/attack detection on IoT and AI-driven infrastructures of smart cities (cross CI). 
* Semi-automated, secure and timely CTI and Incidents Information Sharing and Reporting among Need to Know Stakeholders (OES and CERTs/CSIRTs).  
* Enhanced and Timely Cyber Situational Awareness and Online Collaboration among Need to Know Stakeholders (OES and CERTs/CSIRTs) to manage a threat/incident
* Closing the loop: Semi-automated response policies execution and acknowledgement of detected vulnerabilities and threats

The Enhanced MeliCERTes Ecosystem capitalizes, among other, on three well known and used by the cybersecurity community open source software platforms:
* [MeliCERTes](https://melicertes.github.io/docs/)
* [MISP](https://www.misp-project.org/)  
* [Shuffle](https://github.com/Shuffle)

Its key innovations and value proposition concern the following:
* It enhances timely collaboration and information sharing among all involved cybersecurity stakeholders.
* It improves incident response times and timely situational awareness for all involved stakeholders. 
* It helps organisations to align with EC directives in cybersecurity (NIS2, CRA). 
* It provides interoperable APIs for the integration with most of the existing solutions in the market due to the adoption of widely used stands for cybersecurity information exchange (STIX, CACAO).
* It leverages open-source tools to provide a cost-effective, flexible, and extensible platform that can be widely adopted.

Specifically, it adopts, for interoperability purposes in information exchanges, relevant cybersecurity standards, such as [STIX v2.1](https://www.oasis-open.org/standard/stix-version-2-1/) which is used to describe CTI data enabling their sharing in a consistent way across different systems, guaranteeing interoperability (cross-domain and cross-sector), and [CACAO playbooks](https://docs.oasis-open.org/cacao/security-playbooks/v2.0/security-playbooks-v2.0.html) for the definition of standardized, scalable, and consistently effective incident response procedures for common threats.

In addition, the facilitation of alignment with relevant current cybersecurity regulations and policies is achieved as follows:
* **NIS2 Directive**: EME aligns with the obligation to report incidents and manage cybersecurity risks, as well as enable collaboration and information sharing among diverse stakeholders, as it provides such capabilities
* **Critical Entities Resilience Directive (CER)**: EME addresses the obligation to report incidents and define response procedures in case of cyber attacks to AI and IoT relevant components of the digital infrastructure of a smart city, thus ensuring business continuity
* **Cyber Resilience Act (CRA)**: A DevSecOps approach has been adopted for the development, testing and release of EME, incl. security testing (SAST, DAST) to ensure cybersecurity resilience of the produced software.
* **Cyber Solidarity Act**: The IRIS platform offers a variety of cyber threat detection tools interoperating with the distributed Enhanced MeliCERTes ecosystem, instances of which could be used by cross-border SOCs, for timely sharing detected threats and incidents among them.

<img width="943" alt="IRIS-EME-NIS2" src="https://github.com/user-attachments/assets/0304f190-8e4d-4962-9c60-3a825c102813">

The Enhanced MeliCERTes Ecosystem (EME) is composed of: 
* **The Enhanced MeliCERTes Ecosystem Platform**, that enhances threat intelligence and incident sharing with secure communication and collaboration features and presents a customized SIEM and dashboard for the two target users, [CERTs/CSIRTs](https://www.youtube.com/watch?v=4o5VuyfWAiE) and [Critical Infrastructure Operations](https://www.youtube.com/watch?v=oJFDFpszfX0). The platform has been developed/is owned by [Netcompany-Intrasoft](https://www.netcompany-intrasoft.com/) and its **Research and Innovation Development Dept.** and is offered as open source software, under [EUPL 1.2 license](https://commission.europa.eu/content/european-union-public-licence_en). The main contact persons for the Enhanced MeliCERTes Platform are [Dr. Sofia Tsekeridou](https://www.linkedin.com/in/sofia-tsekeridou-3928b12/), e-mail: sofia.tsekeridou@netcompany.com and Mr. Konstantinos Chisiridis, e-mail: konstantinos.chisiridis@netcompany.com
* **The APIs for Advanced Threat Intelligence Orchestrator**, for integrating threat detection and cyber-threat intelligence components to automate cyber-incident detection, reporting, and response. The know-how and expertise on the customization of the orchestrator workflows and relevant APIs, using the core open source software, Shuffle, in accordance to which other threat and attack detection tools are deployed at the infrastructure in question, is offered by **ICCS**. The main contact person is Ms. Giovana Bilali, e-mail: giovana.bilali@iccs.gr
* **Collaborative Threat Intelligence Sharing and Storage**, which automatically collects and enhances threat intelligence, providing a secure GUI for data presentation, editing, and configuration, that can be used optionally in EME, on top of MISP, providing advanced such functionalities. This component has been developed/is owned by **CERTH** and remains proprietary. The main contact persons are Dr. Eleni Darra, e-mail: e.darra@iti.gr, and Dr. Dimitris Kavalieros, e-mail: dim.kavallieros@gmail.com


## Other IRIS Project Exploitable Service Bundles
Further from the EME Service Bundle presented above, the IRIS project has resulted in another three Service Bundles, as shown collectively in the following figure along with a summary on the exploitation strategy per case.

<img width="663" alt="IRIS-ServiceBundles-2" src="https://github.com/user-attachments/assets/ccd54251-b763-459d-a46a-60896b41a8aa">


For anyone interested to receive more information on the proprietary primarily tools that comprise the other three Service Bundles, we list the developers/owners of these tools per Service Bundle along with their main person contact details: 

The **Automated Threat Analytics (ATA) Service Bundle**, is composed of: 
* Risk and Vulnerability Assessment modules: VDM (ATOS, Rodrigo Diaz and Susana Gonzalez Zarzosa) and BINSEC (CEA, Sebastien Bardin and Michael Marcozzi)
* AI Threat Analytics and Detection Engines: NIGHTWATCH (CLS, Irene Karapistoli), MAIGUARD (CEA, Gil Quijano Jesus-Javier and Michael Marcozzi), SiVi (SID, Charalampos Eleftheriadis, Zisis Batsos and Harris Saoulidis)
* Risk-based Response and Self-Recovery Tool (CLS, Irene Karapistoli)
* Digital Twin Honeypot Deception Models (SID, Charalampos Eleftheriadis, Zisis Batzos)

The **Virtual Cyber Range training (VCR) Service Bundle**, is composed of: 
* IRIS Cybersecurity Exercises and Training Scenarios (CyberTrap), KEMEA, Nikos Kapsalis and Sotiris Spantideas
* IRIS Cyber Range Environment Platform, THALES, Bruno Vidalenc
  
The **Add-ons Services Service Bundle (DPA module)**, which is offered for free to CERTs/CSIRTs upon request, is composed of: 
* DLT-based Control Services for Accountability, Traceability, and Auditing, INOV, Goncalo Cadete and TUD, Katai Liang
* Secure Crypto Functions for Data Management, INOV, Goncalo Cadete and TUD, Katai Liang




