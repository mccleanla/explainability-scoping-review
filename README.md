# How “Operational Explainability” is conceptualised, designed & evaluated

Repository
This repository contains a CSV with the papers used for a scoping review of literature that will be reviewed to answer the following initial research question:

_**In what ways are explanations conceptualised, designed, and evaluated to support users in operational human-ai systems across domains?**_

The unlabeled papers, as extracted directly from the academic search engines (Scopus, IEEE, ACM, PsycInfo, Medline), can be found in the subfolder "**Unlabeled Papers (all)**"

**Context**

Explanations have become an important research topic in AI research. 

Human–ai interactions in a safety-critical high stakes environment collaborating to achieve an outcome form a complex sociotechnical situation. Explanations systems containing "imperfect" AI components are necesssary for effective collaboration between humans and AI systems, and in particular to ensure timely updates and effective handover when humans need to swiftly adapt in a high-stakes situation to ensure safe outcomes.

Operational explainability (OpXAI), distinct from technical explainability (XAI), is an emergent requirement for Human-AI Teams where humans collaborate with intelligent systems, and has been recently defined by EASA as “the need for end users to receive clear, relevant, and reliable information on how an system reaches its conclusions.” EASA indicates an important evaluation characteristic is “time required to obtain an explanation”, emphasising the delivery of information at the right level of detail and timing, ensuring that explanations are clear, actionable, and tailored to real-world operational needs. 

To determine the operational explainability of a system requires asking questions such as: 
- What explanations do operators need when interacting with a deployed system that contains potentially multiple AI components, some of which may be acting more autonomously?
- How should they be communicated? When?
- How are overarching decision-making processes in an operational context considered, where they involve multiple stakeholders and roles?

No scoping review covers this topic explicitly, for example there is much less focus on temporal factors related to operational decision making environments and the multiple stakeholders involved in real world contexts of decision making beyond a single human-ai interaction. 

In this paper, I will map out how operational explainability is conceptualised, designed and evaluated, surveying the field via a scoping review. 

In addition to the typical introspective explanation tackled by explainability researchers, I will look at assistive explanations, aiming to support the user with their task. I will survey what causes the need for an explanation in the first place. 

