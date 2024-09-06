---
author: ["Cassandra Pearson"]
title: "CIA and DAD Triads"
date: "2024-08-05"
description: "Overview of the CIA and DAD triads."
summary: "Overview of the CIA and DAD triads."
tags: ["security", "cybersecurity"]
series: []
ShowToc: true
TocOpen: true
---


## CIA and DAD Triads

---

The CIA and DAD are cybersecurity concepts describing the essential objectives and threats to a system. 

The CIA triad describes the three major objectives in securing a system. These are confidentiality, integrity, and availability. Confidentiality is important when considering access to data. Unauthorized actors should not be given access to data even if it seems harmless to do so. Integrity refers to the structure of the system itself. If a component of the infrastructure is compromised, then the entire system could be damaged. This objective is about protecting against data, hardware, system, and intellectual property loss. Finally, availability concerns the uptime of a system. In any mission critical environment, it is essential that the system is accessible at all times. This is increasingly important for web applications deployed in the cloud. DDoS attacks can prevent users from accessing the application costing money or endangering mission critical operations. The CIA triad defines a scope for robust goals. 

The DAD triad describes the three major threats against a system. These are disclosure, alteration, and denial. Each of these is the threat to the corresponding members of the CIA triad. That is to say, disclosure threatens confidentiality, alteration threatens integrity, and denial threatens availability. This direct mapping provides a convenient tool for considering issues with cybersecurity. For instance, the triads can be turned into questions helpful when considering if an objective was achieved: "Does the public server have the potential to disclose confidential information to unauthorized individuals?" Although not comprehensive of all potential issues to be considered in risk assessment, the DAD triad is useful when determining potential threat vectors.

These triads are guidelines rather than rigid categories. Most objectives and threats will fall into all of the categories. However, they are still helpful in scoping and creating a goal. When considering that a DDoS attack could jeopardize availability and integrity, the impact of the threat may be considered elevated. This could cause a decision to be made that more money should be spent on a commercial solution or that additional safeguards need to be placed to ensure system integrity in the event of an attack.

## Sources

---

M. Chapple and D. Seidl, CompTIA security+ study guide: Exam SY0-601, 8th ed. Indianapolis, IN: Sybex, 2021.