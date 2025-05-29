# How “Operational Explainability” is conceptualised, designed & evaluated

This repository contains a CSV with the papers used for a scoping review of literature that will be reviewed to answer the following initial research question:

_**In what ways are explanations conceptualised, designed, and evaluated to support users in operational human-ai systems across domains?**_

PRISMA requires detailed reporting of the search for each source, including dates searched and any limits used. 

Search Strategy is here: [1. Search Strategy](<1. Search Strategy>)
Search Strings and per-database count post keyword piloting are here: [0. Search Results](<0. Search Results>)

Extracted results as extracted directly from the academic search engines (Scopus, Web of Science, IEEE, ACM, Medline, Proquest ) are in the folder  [https://github.com/mccleanla/explainability-scoping-review/tree/main/3.%20Extracted%20Papers](https://github.com/mccleanla/explainability-scoping-review/tree/main/3.%20Extracted%20Papers)..  


**Context**

Explanations have become an important research topic in AI research. 

Human–ai interactions in a safety-critical high stakes environment collaborating to achieve an outcome form a complex sociotechnical situation. Explanations systems containing "imperfect" AI components are necesssary for effective collaboration between humans and AI systems, and in particular to ensure timely updates and effective handover when humans need to swiftly adapt in a high-stakes situation to ensure safe outcomes.

Operational explainability (OpXAI), distinct from technical explainability (XAI), is an emergent requirement for Human-AI Teams where humans collaborate with intelligent systems, and has been recently defined by EASA as “the need for end users to receive clear, relevant, and reliable information on how an system reaches its conclusions.” EASA indicates an important evaluation characteristic is “time required to obtain an explanation”, emphasising the delivery of information at the right level of detail and timing, ensuring that explanations are clear, actionable, and tailored to real-world operational needs. 

To determine the operational explainability of a system requires asking questions such as: 
- What explanations do operators need when interacting with a deployed system that contains potentially multiple AI components, some of which may be acting more autonomously?
- How should they be communicated? When?
- How are overarching decision-making processes in an operational context considered, where they involve multiple stakeholders and roles?

Some background quotes from literature sources here: [Operational Explainability Definition](<Operational Explainability Definition>)

---
## Rationale for this work

Whilst much is written about XAI and HCXAI, it is not clear how operational explainability is treated in the AI lifecycle from conceptualisation to design to evaluation.

No scoping review covers this topic explicitly, for example there is much less focus on temporal factors related to operational decision making environments and the multiple stakeholders involved in real world contexts of decision making beyond a single human-ai interaction. 

In this paper, I will map out how operational explainability is conceptualised, designed and evaluated, surveying the field via a scoping review. 

In addition to the typical introspective explanation tackled by explainability researchers, I will look at assistive explanations, aiming to support the user with their task. I will survey what causes the need for an explanation in the first place. 


