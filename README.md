# Creating a FAIR-Compliant Metadata Framework for RNA Sequencing: A Case Study on Amyotrophic Lateral Sclerosis

This repository contains the description and progress reports for FAIR-Compliant metadata framework for RNA sequencing software development

<p align="center">
  <img src="https://github.com/user-attachments/assets/6c93af13-6b66-43a3-bdbb-5687dc207ae1" width="50%">
</p>
<p align="center">
  <span style="font-size: 10px; color: grey;">
    <em>Figure: Adapted from <a href="https://www.scholarhat.com/tutorial/systemdesign/system-design-life-cycle" target="_blank">ScholarHat – System Design Life Cycle</a></em>
  </span>
</p>

**1. Planning and Requirement Analysis**

In the initial phase, the project team was assembled, and a first draft of the Software Management Plan (SMP) was developed to ensure alignment with FAIR4RS principles. 
During the ongoing requirement analysis stage, researchers and data stewards are being engaged through interviews, with surveys also planned, to identify key challenges in 
RNA-seq metadata management. These efforts have already helped to pinpoint essential metadata fields, clarify usability expectations, and highlight opportunities for 
automation to reduce manual effort and enhance reproducibility.

**2. System Design**

Based on the collected requirements, the team has initiated the system design phase by defining the structure and functionality of the FAIR-Compliant Metadata Framework. 
Modeled after ELIXIR’s Data Stewardship Wizard (https://ds-wizard.org/), the design is planned to include a guided, question-based user interface, integration of standardized 
ontologies (e.g., MIAME/MINSEQE, DCMI/ISA, EDAM), and support for metadata output in both human-readable formats and machine-readable formats. The system will be designed 
to be modular, scalable, and user-friendly for users with varying levels of technical and domain expertise.

**3. Implementation**

Throughout the implementation, special attention is given to ensuring compliance with the FAIR principles for research software (FAIR4RS). The tool will incorporate these 
principles by enabling findability through persistent identifiers and structured metadata; accessibility via standardized, open formats; interoperability through the use of 
established ontologies such as EDAM and metadata formats like CodeMeta; and reusability through open licensing (MIT License) and comprehensive documentation. Additional 
FAIR4RS-aligned practices will include the use of container technologies (e.g., Docker), version control systems (e.g., Git), and deposition in platforms such as GitHub and
Zenodo, as well as tool registries including bio.tools and BioContainers. OpenEBench will be used to benchmark the tool and ensure its compliance with community standards 
and research software quality metrics.

**4. Testing**

In this phase, different types of testing methods will be applied to ensure the research software quality and user acceptance. Unit testing of the individual code units, 
will be followed by integration testing of the components, security and performance testing, as well as functional testing if the application meets the user expectations of 	
diverse user groups. Throughout the development process, we will maintain a continuous feedback loop involving regular meetings with users to discuss progress and gather 	
insights to adapt features according to real-world usage scenarios. Finally, we will also validate the tool’s compliance with FAIR4RS principles and community standards, 
as predefined in SMP. 

**5. Deployment and Maintenance**

We will share the software tool in a repository such as GitHub and/or Zenodo and register in a registry, such as bio.tools, BioContainers and EOSC Marketplace or Software 
Heritage to ensure interoperability with existing services and platforms. 

**Funding**
<p align="left">
  <img src="https://github.com/user-attachments/assets/e43183c4-3338-46af-8ecc-dec71c120584" width="20%">
</p>

**Project:** Multidimensional mechanistic investigations of trans spinal direct current stimulation in motor neuron disease (DC4MND) **Project/agreement** No. ES RTD/2023/18


