# Blockchain Risk Assessment Framework

This repository contains an initiative for producing a comprehensive blockchain risk assessment framework. It is built on Cyber Threat Intelligence (CTI) and threat modeling, consisting of two main phases:

## 1. Cyber Threat Intelligence (CTI)

In this step, information about cyberattacks on blockchain systems is collected, processed, and analyzed to understand a threat actor’s motives, targets, and attack behaviors. This intelligence enables us to make faster, more informed, data-backed security decisions and shift from a reactive to a proactive stance in combating threat actors. By identifying specific threats to be included in our threat modeling process, we can enhance our cybersecurity posture. This process involves:

- Tracking Indicators of Compromise (IoCs) of common attacks.
- Aggregating cybersecurity news.
- Providing detailed analyses of malware strains.
- Scraping social media and the dark web for discussions about emerging blockchain cyberthreats.
- Understanding the threat actors’ tactics, techniques, and procedures (TTPs) to anticipate and mitigate potential attacks on the organization.

The CTI exercise can be conducted using automated tools or manually. The insights from this exercise are documented in an XLSX matrix.

## 2. Threat Modeling

The output of the CTI phase is used to conduct threat modeling for blockchain applications. Threat modeling is a systematic approach to identifying, evaluating, and prioritizing potential threats or risks to a system, organization, or application. It helps in understanding potential vulnerabilities and their impact, enabling informed decisions about security measures and mitigation strategies. Threat modeling for blockchain involves considering the unique security challenges and risks associated with blockchain technology. The process includes:

1. **Define the scope:** Determine the boundaries of the system or application to analyze, identifying the assets, components, and interactions to be included in the threat model.
2. **Identify assets:** Identify valuable assets needing protection, such as data, intellectual property, hardware, and software.
3. **Create a threat model:** Develop a representation of the system, such as data flow diagrams, architectural diagrams, or process flow diagrams. This model should capture the different components, data flows, trust boundaries, and external dependencies of the system.
4. **Identify potential threats:** Brainstorm potential threats and vulnerabilities that could exploit weaknesses in the system. Consider both technical and non-technical threats, such as physical attacks, social engineering, or insider threats. Common threat sources include hackers, malware, unauthorized access, data breaches, and denial-of-service attacks.
5. **Assess likelihood and impact:** Evaluate the likelihood and impact of each identified threat. Likelihood refers to the probability of a threat occurring, while impact refers to the potential damage it can cause. This assessment helps prioritize the most critical threats.
6. **Determine countermeasures:** Identify and evaluate potential countermeasures or security controls that can mitigate or reduce the identified threats. These may include preventive measures like access controls, encryption, or firewalls, as well as detective measures like intrusion detection systems or log monitoring.
7. **Document and communicate:** Document the results of the threat modeling process, including the identified threats, their likelihood and impact ratings, and the recommended countermeasures. Share this information with relevant stakeholders, such as developers, architects, or security teams.
8. **Iterative process:** Threat modeling is an iterative process that should be revisited regularly to account for changes in the system or emerging threats. As the system evolves, it is important to update the threat model and reassess the risks.

The threat modeling in this work uses the STRIDE, MITRE ATT&CK, DREAD, and NIST SP800-53 frameworks and standards. The STRIDE model classifies potential attack vectors on the system, mapping them to the MITRE ATT&CK framework and rating them using the DREAD model. Several countermeasures and mitigations are suggested and mapped to the NIST SP 800-53 Rev 5 list to address these attack vectors. The proposed model is a fully indexed, scalable, adjustable, and exploitable threat model for an e-health use case and may serve as the foundation for a new standard for the security of blockchain architectures.
