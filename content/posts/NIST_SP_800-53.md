---
author: ["Cassandra Pearson"]
title: "NIST SP800-53 Security and Privacy Controls"
date: "2024-21-09"
description: "NIST SP800-53 Security and Privacy Controls for Information Systems and Organizations"
summary: "NIST SP800-53 Security and Privacy Controls summary."
tags: ["security", "cybersecurity", "nist"]
series: ["NIST"]
ShowToc: true
TocOpen: true
---

## **Introduction**

---

Introduction

NIST SP800-53 is  related to SP800-37 and SP800-39 in the sense that it provides further  details into the controls implemented as part of the information  security architecture within level 3 of the NIST risk management  framework. I have made posts summarizing both of those documents and  recommend familiarizing yourself with them before continuing. SP800-53  differs from the previous two publications described by focusing  entirely on the security controls instead of on the risk management  framework or organizational structure. This document acts as a very  helpful reference when looking to implement any of the controls  described. It provides detailed information about when to apply the  control as well as a discussion of the control, related controls, and  sources for further information. When implementing any controls  described within the document, it should be consulted to ensure no  portion of the control is overlooked or necessary compensating or  accompanying controls are not missed. This post will serve as a guide  for how to utilize this document as a reference; providing the necessary  context and background for understanding the controls and their  descriptions.

Sources are cited below, original article available free from NIST [here](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf).

## **Purpose of Publication**

---

To quote directly from the publication:

"This  publication establishes controls for systems and organizations. The  controls can be implemented within any organization or system that  processes, stores, or transmits information.[1]

This document provides details on security controls that are common in any organization with information systems.

## **Control Structure and Example**

---

Each  control within the document is assigned a category referred to as a  family. To quote the publication: "Security and privacy controls may  involve aspects of policy, oversight, supervision, manual processes, and  automated mechanisms that are implemented by systems or actions by  individuals. Table 1 lists the security and privacy control families and  their associated family identifiers."[1]

![NISTSP80053_1](/images/NIST80053_table1.png "NIST SP800-53 Table 1")

When implementing any security control, it must be considered if  there are necessary accompanying base controls. Diving controls up into  families helps in this effort. When any specific control is desired,  closely related controls can quickly be determined. This allows for a  quick check to see if the desired control is a base or enhancement. In  practice, this is a good way to see if the desired control is sufficient  alone or if additional measures are needed. 

Every control provided has the same structure and is shown in the diagram below[1].  The structure is self explanatory, but I will highlight a few important  elements. First, the identifier; it is made up of the family  designation and a number. This makes it easy to find closely related  controls. Next, the organization-defined parameters. These parameters  differ based on the risk management strategy and resources allocated by  the implementing organization. Finally, the related controls sections  provides a list of closely related controls that should be considered  during implementation.

![NISTSP80053_2](/images/NIST80053_example1.bmp "NIST SP800-53 Example 1")

Now that the general structure is known, consider the following access control policy[1]:

![NISTSP80053_3](/images/NIST80053_example2.bmp "NIST SP800-53 Example 2")

As highlighted previously, the organizational parameters used  throughout have a substantial effect on the control itself. However, the  provided description is still information rich and useful as a guide  for implementing an access control procedure. Including further  references to best practices and risk management framework documents  that may be helpful in determining the organizational parameter values. 

## **Conclusion**

---

Although not a technical guide on use of the tools necessary to implement security policies, this publication is a very practical guide for  security controls. Each control is described in great detail and  discussed thoroughly. The only component missing from this document is  the technical "how" of applying the control, but that varies based on  the information system structure. This document provides detailed  guidelines for how these security controls should be implemented in  practice. Any organization could benefit from comparing these controls  with their documented control implementations. 

## **Sources**

---

[1]  Joint  Task Force Interagency Working Group, “Security and privacy  controls  for information systems and organizations,” National Institute  of  Standards and Technology, 2020.

## **Acronym Dictionary**

---

IR: Interagency Report
OMB: Office of Management and Budget
NIST: National Institute of Standards and Technology
SP: Special Publication