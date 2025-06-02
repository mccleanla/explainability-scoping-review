# How “Operational Explainability” is conceptualised, designed & evaluated

This repository contains a CSV with the papers used for a scoping review of literature that will be reviewed to answer the following initial research question:

_**In what ways are explanations conceptualised, designed, and evaluated to support users in operational human-ai systems across domains?**_

PRISMA requires detailed reporting of the search for each source, including dates searched and any limits used. 

Search Strategy is here: [Search Strategy](2a.%20Search%20Query%20Development/Search%20Strategy.md)
Search Keywords are here: [Search Keywords](2a.%20Search%20Query%20Development/Search%20Keywords.md)
Per-database count of entries here: [Search Results](2b.%20Database%20Search%20Strings/Search%20Results.md)

Extracted results as extracted directly from the academic search engines (Scopus, Web of Science, IEEE, ACM, Medline, Proquest ) are in the folder  ["3. Extracted Papers"](https://github.com/mccleanla/explainability-scoping-review/tree/main/3.%20Extracted%20Papers)..  


**Context**

Explanations have become an important research topic in AI research, as a "tool" that can supports sense-making of algorithmic decisions. For example, robotics researchers have surveyed what causes the need for an explanation, and identified a variety of human–agent interaction-specific causes (https://github.com/lwachowiak/Explanation-Types-and-Need-Indicators-in-HAI/).

Operational explainability (OpXAI), distinct from technical explainability (XAI), is an emergent requirement for Human-AI Teams where humans collaborate with intelligent systems. This has been recently defined by EASA as “the need for end users to receive clear, relevant, and reliable information on how an system reaches its conclusions.” EASA indicates an important evaluation characteristic is “time required to obtain an explanation”, emphasising the delivery of information at the right level of detail and timing, ensuring that explanations are clear, actionable, and tailored to real-world operational needs. 

*source: EASA Artificial Intelligence (AI) Concept Paper Issue 2: Guidance for Level 1&2 machine learning applications, March 2024.*
https://www.easa.europa.eu/en/document-library/general-publications/easa-artificial-intelligence-concept-paper-issue-2

To determine the operational explainability of a system requires asking questions such as: 
- What explanations do operators need when interacting with a deployed system that contains potentially multiple AI components, some of which may be acting more autonomously?
- How should they be communicated? When?
- How are overarching decision-making processes in an operational context considered, where they involve multiple stakeholders and roles?

*Some background quotes from literature sources here*: [Operational Explainability Definition](1.%20Background/Operational%20Explainability%20Definition.md)

---
## Rationale for this work

Whilst much is written about XAI and HCXAI, it there are no surveys that articulate how operational explainability is treated in the AI lifecycle from conceptualisation to design to evaluation. I'm interested in determining what we understand about closing the gap between what is being explained to users and what they understand.
	- In other words, **minimizing miscommunication and misinterpretation.**

No scoping review covers this topic explicitly.  Preliminary reading also suggests potential gaps in the literature, for example there is much less focus on temporal factors related to operational decision making environments and the multiple stakeholders involved in real world contexts of decision making beyond a single human-ai interaction. 

In this work, I will map out a perspective on how operational explainability is currently conceptualised, designed and evaluated, surveying the field via a scoping review. 


