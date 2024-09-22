---
author: ["Cassandra Pearson"]
title: "NIST SP800-37 Risk Management Framework"
date: "2024-08-09"
description: "NIST SP800-37 Risk Management Framework summary."
summary: "NIST SP800-37 Risk Management Framework summary."
tags: ["security", "cybersecurity", "nist"]
series: ["NIST"]
ShowToc: true
TocOpen: true
---

## **Introduction**

---

The National Institute of Standards and Technology maintains several important publications about risk management and security as part of its mission to promote innovation and industrial competitiveness [1]. One of the most notable is special publication (SP) 800-37 'Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy'. The target audience for this document is any individual or organization associated with the design, development, implementation, assessment, operation, maintenance, and disposition of information systems [2].  As stated, this document provides a  Risk Management Framework (RMF) for any information systems. This is primarily focused on digital information systems and integration into modern cybersecurity, but not exclusively. 

Sources are cited below, original article available free from NIST [here](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-37r2.pdf).

## **Purpose of Publication**

---

To quote directly from the publication [2]: 

"  
The guidelines have been developed:
- To ensure that managing system-related security and privacy risk is consistent with the mission and business objectives of the organization and risk management strategy established by the senior leadership through the risk executive (function);
- To achieve privacy protections for individuals and security protections for information and information systems through the implementation of appropriate risk response strategies;
- To support consistent, informed, and ongoing authorization decisions, reciprocity, and the transparency and traceability of security and privacy information;
- To facilitate the integration of security and privacy requirements and controls into the enterprise architecture, SDLC processes, acquisition processes, and systems engineering processes;
- To facilitate the implementation of the Framework for Improving Critical Infrastructure Cybersecurity [NIST CSF] within federal agencies.    

"

The design of this publication is to provide means for handling organizational risks to information systems. This includes establishing rules for data privacy, data owners, data transparency, secure software development, and secure systems engineering. The details are not meant to establish specific security measures to counter known risks, but rather provide an organizational framework for addressing, understanding, mitigating, and accepting risk.

## **Fundamentals and the Risk Management Process**

---

This publication takes a three tiered approach to managing risk as demonstrated in the following diagram [2]:

![NISTSP80037](/images/NIST80037_Fig1.png "NIST SP800-37 Figure 1")

To summarize figure 1:
- Organization
	- This level has a primary focus on governance and program-related risk management [1]. This level encompasses activities critical to preparing the organization to execute the RMF [2]. This is the level at which important decisions linked to the business objectives, system modernization, enterprise architecture, and resource allocation are made. The primary responsibilities at this level are to understand risk, assign roles, identify critical functions, and prioritize security requirements.  
- Mission/Business Process
	- This level focuses on the business or mission objectives. For example, defining the criticality of information flows between the organization and its partners [1]. This tier is closely related to the level one, but focuses more on information flow, communication, and assigning task criticality. 
- Information System
	- This is the risk at the information technology level. This is where risk to physical and digital information becomes less organizational and more practical.

Communication of risks and priorities will flow down the diagram and incident reporting will flow up. Feedback will be provided from the information system level up to the organization level to make sure every keyholder is up to date on the critical threats. New directives and priorities will flow down back to the information system level after careful consideration of the reports and threat intelligence collected. 

Once a conceptualization of the framework is understood, stakeholders should execute the process. The NIST RMF isolates seven key steps to ensure that activities are successfully executed [2]:
1. Prepare
	- Both organization and system level preparation is needed to establish a context and priorities for managing security and privacy risks.
2. Categorize
	- The system and information processed, stored, and transmitted should be categorized based on the impact of loss. 
3. Select
	- Select an initial set of controls and tailor the controls as needed to reduce risk to an acceptable and manageable level.
4. Implement
	- Implement the controls and document thoroughly.
5. Assess
	- Determine if all controls are implemented correctly, operating as intended, and producing desirable outcomes.
6. Authorize
	- Authorize system controls based on a risk assessment. 
7. Monitor
	- Monitor control efficaciousness, perform ongoing maintenance, and document all changes, assessments, feedback, and analysis. 

NIST provides more details in the special publication including the minimum set of required tasks to ensure each step is successfully implemented. This includes potential inputs, executed outputs, and the primary role responsible for the task. Any organization could benefit from reviewing this set of tasks and ensuring that there is corresponding coverage within their risk management framework. 

## **Conclusion**

---

This publication provides more than just the fundamentals for organizational risk management. Topics including supply chain risk management, security and privacy, authorization boundaries, and requirements and controls are covered. I have only provided a conceptual framework for the key ideas behind risk management as outlined by NIST. In any security environment, an understanding of the conceptual framework for determining and addressing risk is critical. NIST RMF is by no means a one size fits all solution to risk management, but it provides a framework and highlights crucial ideas in the field. This publication can provide great benefit to any organization's information infrastructure and data security. 

## **Sources**

---

1. B. Chapman and F. Maymi, CompTIA CySA+ cybersecurity analyst certification all-in-one exam guide, second edition (exam CS0-002), 2nd ed. Columbus, OH: McGraw-Hill Education, 2020.
2. Joint  Task Force Transformation Initiative, “Risk management framework for  information systems and organizations: A system life cycle approach for  security and privacy,” National Institute of Standards and Technology,  Gaithersburg, MD, 2018.

## **Acronym Dictionary**

---

NIST: National Institute of Standards and Technology  
RMF: Risk Management Framework  
SP: Special Publication  