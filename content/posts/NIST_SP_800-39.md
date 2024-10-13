---
author: ["Cassandra Pearson"]
title: "NIST SP800-37 Risk Management Framework"
date: "2024-10-10"
description: "NIST SP 800-39 Managing Information Security Risk: Organization, Mission, and Information System View"
summary: "NIST SP 800-39 Managing Information Security Risk summary"
tags: ["security", "cybersecurity", "nist"]
series: ["NIST"]
ShowToc: true
TocOpen: true
---

## **Introduction**

---

The National Institute of Standards and Technology maintains several important publications about risk management and security as part of its mission to promote innovation and industrial competitiveness[1]. There are several important publications from NIST, but this post will summarize special publication (SP) 800-39 'Managing Information Security Risk: Organization, Mission, and Information System View'. The target audience for this document is any individual or organization associated with the design, development, implementation, assessment, operation, maintenance, and disposition of information systems [2].  This document focuses on providing guidance for an integrated, organization wide program for managing information security risk to organizational operations (function, image, and reputation)[2]. It lays out more details on the organizational side of the risk management framework (RMF) described in NIST SP800-37 'Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy'. There is another post I made summarizing that article and I recommend becoming familiar with that article before continuing. 

Sources are cited below, original article available free from NIST [here](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-39.pdf).

## **Purpose of Publication**

---

To quote directly from the publication: 

"The purpose of Special Publication 800-39 is to provide guidance for an integrated, organization-wide program for managing information security risk to organizational operations (i.e., mission, functions, image, and reputation), organizational assets, individuals, other organizations, and the Nation resulting from the operation and use of federal information systems. Special Publication 800-39 provides a structured, yet flexible approach for managing risk that is intentionally broad-based, with the specific details of assessing, responding to, and monitoring risk on an ongoing basis provided by other supporting NIST security standards and guidelines."[2]

This document is intended to provide details on the NIST RMF from an organizational risk perspective. It focuses less on the specific tasks and organizational structure than SP800-37 and more on the general ideas and principles behind the RMF. This document includes more information on the tasks within each tier of the RMF, more details on specific terms and functions used previously (i.e. risk executive and enterprise architecture), and more information on risk management strategies.

## **Fundamentals and Organizational Architecture**

---

The three tier model introduced in NIST SP800-37 includes arrows showing the flow of communication among components. The terms used changed slightly with NIST800-37 calling the tiers levels, but the concept is the same[3]. To review this model, consider figure 2. 

![NISTSP80039_Figure2](/images/NIST80039_Fig2.png "NIST SP800-39 Figure 2")

To summarize the tiers in figure 2:
- Organization
	- This tier has a primary focus on governance and program-related risk management[1]. This level encompasses activities critical to preparing the organization to execute the RMF[3]. This is the level at which important decisions linked to the business objectives, system modernization, enterprise architecture, and resource allocation are made. The primary responsibilities at this level are to understand risk, assign roles, identify critical functions, and prioritize security requirements. 
- Mission/Business Process
	- This tier focuses on the business or mission objectives. For example, defining the criticality of information flows between the organization and its partners[1]. This tier is closely related to the level one, but focuses more on information flow, communication, and assigning task criticality. 
- Information System
	- This is the risk at the information technology level. This is where risk to physical and digital information becomes less organizational and more practical.
In figure 2 above, the arrows are not shown to be bidirectional as in NIST SP800-37; this clarifies what information is flowing up and what information is flowing down. There is a continuous feedback loop for risk management policies and strategies. But the ultimate organizational decisions on strategic risk are meant to made transparently by the stakeholders in the organizational tier. While the detailed implementation of the specific tactics used to address the risk, based on the resources allocated at the strategic level, are left to the stakeholders at the information system tier.

The following diagram (figure 1) describes the communication between tiers in more detail. The bidirectional nature of the arrows indicates that the information and communication flows are flexible and responsive to the dynamic nature of the process.[2]

![NISTSP80039_Figure1](/images/NIST80039_Fig1.png "NIST SP800-39 Figure 1")

There are four components that describe the communication between the levels of an organization[1]:
1. Frame risk
	- Framing risk defines the context in which all other risk activities take place. What are the constraints of the system? What are the organizational priorities?
2. Assess risk
	- This is the most critical aspect. Assessment of risks must be continuous, thorough, and show awareness of the threat landscape.
3. Respond to risk
	- In responding, the threat is known as well as the acceptable scope of response. Now limited resources must be put to use to stop the most critical and likely of threats.
4. Monitor risk
	- No system is perfect, no assessment can cover all threats. Monitoring for new threats is critical. As is monitoring the efficaciousness of current controls.

Combining figures 1 and 2, we obtain figure 4[2] which demonstrates in more detail how each tier is responsible for communication and feedback within the organization.

![NISTSP80039_Figure4](/images/NIST80039_Fig4.png "NIST SP800-39 Figure 4")

Once a risk management strategy is decided upon and communicated to all tiers, the strategy needs to be put into place. This is accomplished through the enterprise architecture, information security architecture, and finally specific technical security controls. The enterprise architecture of an organization is a management practice employed by organizations to maximize the effectiveness of mission/business processes and information resources in helping to achieve mission/business success[2]. The information security architecture is then the portion of the enterprise architecture specifically addressing information system resilience and providing architectural information for the implementation of security[2]. Finally, information security controls are the specific technical components that are in place in the environments of operation to enforce the security objectives. The following diagram (figure 3) shows how risk management considerations are addressed as part of the enterprise architecture[2].

![NISTSP80039_Figure3](/images/NIST80039_Fig3.png "NIST SP800-39 Figure 3")


Figure 3 describes how a risk management strategy decision made at tier 1 flows into operation at tier 3 through the enterprise architecture of an organization. The strategy and mission inform the enterprise architecture which creates specific secure requirements and allocates resources through the information security architecture. Finally, the technical security control is implemented based on the architecture and put into place in the operation environment.

## **Conclusion**

---

NIST SP800-39 provides details on the organizational concepts and structures necessary for successfully implementing the RMF. Although it has less focus on the stakeholder and tasks at each level, it provides better descriptions of the ideas used to determine and address risk than SP800-37. This summary provides only a very broad conceptual outline of the information that is covered within this document. This document includes specific tasks and guidance for carrying out each step discussed in figure 1 as well as more information on each of the RMF tiers, and detailed descriptions of related concepts such as establishing trust. This publication provides clarity to the concepts and ideas that lay behind the NIST RMF. Finally, similarly to NIST SP800-37, any organization could benefit from ensuring all tasks described are covered in their RMF. 

## **Sources**

---

1. B. Chapman and F. Maymi, CompTIA CySA+ cybersecurity analyst certification all-in-one exam guide, second edition (exam CS0-002), 2nd ed. Columbus, OH: McGraw-Hill Education, 2020.
2. Joint Task Force Transformation Initiative, “Managing information security risk  :: Organization, mission, and information system view,” National Institute of Standards and Technology, Gaithersburg, MD, 2011.
3. Joint Task Force Transformation Initiative, “Risk management framework for information systems and organizations:: A system life cycle approach for security and privacy,” National Institute of Standards and Technology, Gaithersburg, MD, 2018.

## **Acronym Dictionary**

---

NIST: National Institute of Standards and Technology
RMF: Risk Management Framework
SP: Special Publication