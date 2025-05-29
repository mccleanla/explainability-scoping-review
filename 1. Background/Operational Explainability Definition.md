*explanation as communiation / meaningful transparency*

**Venditti, R. _et al._ (2025) ‘Construal Level Theory (CLT) for designing explanation interfaces in operational contexts’,** in _AHFE International_. _13th International Conference on Human Interaction & Emerging Technologies: Artificial Intelligence & Future Applications_, AHFE International. Available at: https://doi.org/10.54941/ahfe1005918.

"Operational Explainability (OpXAI) refers to the need for end users to receive clear, relevant, and reliable information on how an AI system reaches its conclusions.  Operational explainability, distinct from technical explainability, is an **emergent requirement** for Human-AI Teams where humans collaborate with Intelligent Assistants.  It emphasises the delivery information at the right level of detail and timing, ensuring that explanations are clear, actionable, and tailored to real-world operational needs.  Key questions: 
- What explanations do the operators need? 
 - How (at what level of abstraction) should they be presented? 
 - When? For how long?

European Union Aviation Safety Agency (EASA) introduced new dimensions to XAI, such as “level of abstraction” and “time required to obtain an explanation”.

---

**Macrae, C. (2022) ‘Learning from the Failure of Autonomous and Intelligent Systems: Accidents, Safety, and Sociotechnical Sources of Risk’,** _Risk analysis: an official publication of the Society for Risk Analysis_, 42(9), pp. 1999–2025. Available at: https://doi.org/10.1111/risa.13850.

**System Transparency:** 
- mechanisms to render the sociotechnical system surrounding AIS transparent and legible, encompassing technical, human and organisational processes"

"Transparency is a core principle in AIS safety (Jobin et al., 2019; Winfield & Jirotka, 2018): it must be possible to understand what an AIS is doing and why, both 
- to safely interact with and supervise these technologies (Sarter et al., 1997; Wortham, Theodorou, & Bryson, 2017) 
- and to retrospectively investigate failures (Bryson & Winfield, 2017; Winfield et al., 2021).

Prior discussions of transparency have focused on the importance of making the working of intelligent technologies transparent, interpretable, and explainable but the analysis developed here extends this principle, emphasizing the importance of building mechanisms that can help to render entire sociotechnical systems transparent— encompassing core technologies as well as the human activities and organizational processes that surround them. 
- For instance, organizational processes and technological methods need to be incorporated into AIS that can
	- identify pockets of invisible automation 
	- highlight the potential for failure cascades
	- flag the possibility of hazard masking, 
	- reveal areas of supervisory degradation and 
	- acknowledge sources of existential pressure. 
- As such, transparency is not purely a technical requirement but a sociotechnical one: to manage risk and learn from failure, the net- work of organizational decisions, cultural values, and human interactions that AIS are embedded within must also be made legible and open to scrutiny (Kroll, 2018).

invisible automation  - definition
- weaknesses or gaps in processes that maintain awareness, provide insight and issue alerts regarding the status, activities and decisions of automated systems 
- *when combined with sensitivity smoothing features ("don't react too quickly, it might be a false alert") and (possibly inadvertent) hazard masking - leads to a failure cascade*
	- example from uber: no alerting process to inform a vehicle operator that a hazard was detected yet the system was initiating action suppression and delaying automated response, by design*

---

**Sujan, M., Pool, R. and Salmon, P. (2022) ‘Eight human factors and ergonomics principles for healthcare artificial intelligence’,** _BMJ health & care informatics_, 29(1), p. e100516. Available at: https://doi.org/10.1136/bmjhci-2021-100516.

*"Many approaches to explainable AI simply focus on providing detailed accounts of how an algorithm operates, but for explanations to be useful they need to be able to accommodate and be responsive to the needs of different users across a range of situations, for example, a patient might benefit from a different type of explanation compared with a healthcare professional. In this sense, rather than providing a description of a specific decision, explanation might be better regarded as a social process and a dialogue that allows the user to explore AI decision- making by interacting with the AI and by interrogating AI decisions."*

---
**Bach, T. _et al._ (2023) ‘Unpacking human-AI interaction in safety-critical industries: A systematic literature review’,** _arXiv [cs.HC]_. Available at: http://arxiv.org/abs/2310.03392.

explainability and interpretability

In the literature, these terms have been used both interchangeably [121] and given explicitly different definitions [122]

explainability and interpretability are both part of ensuring that miscommunication is minimized between the AIenabled system’s explanation of its rationale and what the users understand about its rationale [122].
- Explainability means that the rationale behind an AI-enabled system’s decision is being explained to users in the most efficient and effective manner at the right time. 
- Interpretability here means that users can understand what is being explained correctly, accurately, and in a timely manner. 

The difference between AI output and explainability and interpretability is that:
- the former focuses on how AI output is delivered and explained to users, 
- latter focuses on explaining the thinking process (the rationale) prior to producing an output.

They are both focused on closing the gap between what is being explained to users and what they understand. 
	- In other words, minimizing miscommunication and misinterpretation.


---
**Kirwan, B. (2025) ‘Human Factors requirements for human-AI Teaming in aviation’,** _Preprints_. Available at: https://doi.org/10.20944/preprints202501.0974.v1.

Shift in degree of autonomy affects the relationship between the human and the AI-based automation in two ways. 
- First, the information or advice, or even executive action, can be based on calculations that are opaque to the end users (e.g. pilots), because the level of complexity and transparency of how AIs derive their answers mean that no amount of theoretical training for pilots will enable them to follow the AI’s ‘reasoning’, unless an additional layer of such ‘explainability’ is afforded to the pilot by the AI-based automation.   The pilot must therefore come to trust the IA, or its advice will be rejected. 
- Second, the role of the pilot is affected, because currently the pilot is always in command and ready (i.e. trained) to take over in case the automation (e.g. automatic landing) fails. The fundamental notion of collaboration suggests an inter-dependence, that such control becomes to a greater or lesser degree shared between human and AI.

new issues such as operational explainability of AI systems may require completely new approaches  or design requirements.

There will need to be operational explainability ( OpXAI), so that the human crews  can determine (i.e. make sense of) why a course of action has been recommended (or taken) by the  AI. Such explainability needs to be in an operational context in language that crews can follow (as  opposed to data analytic explainability, which refers more to how to trace an AI’s outputs to its  internal architecture, data sources and algorithmic processes).

Observability  refers  to  the  transparency  of  the  progress  of  the  AI  agent  when  resolving  a  problem, and can be linked to explainability, though in practice the AI’s workings might be routinely  monitored  via  some  kind  of  dashboard  or  other  visualisation  rather  than  a  stream  of  textual  explanations, albeit with the user able to pose questions as needed.

![[haiku.png]]

**Sense-Making**  –  this  is  where  shared  situation  awareness,  operational  explainability,  and  human-AI interaction sit, and as such has the largest number of requirements. 
- Arguably this  area could be entitled (shared) situation awareness, but **sense-making includes not only what is  happening  and  going  to  happen,  but  why  it  is  happening,  and  why  the  AI  makes  certain  assessments and predictions.**

HF requirements:
- Is all the required information presented to the user in an uncluttered way? 
- Is the interaction medium appropriate for the task, e.g. keyboard, touchscreen, voice, and even gesture recognition?
- Do visual/oral/auditory displays and controls follow Human Factors guidance (e.g. colour coding, luminance, auditory  range etc.)? 
- Does the location of a new AI interface with the operational workplace support rather than hinder critical operations? 
- Does the AI-human interface reinforce the end-user’s situation awareness.   
- in cases of moderate (or higher) uncertainty, are alternative suggestions/explanations offered? 
- Can the human query the information/decision via an explainability function? 
- Can the AI provide alternatives, along with likelihood estimates? 
- Is the end-user aware of the key parameters the AI is optimising? Can the end-user alter them? 
- Can the human view both data that were used and data that were ignored by the AI, e.g. anomalies or outliers?

ERROR & FAILURE MANAGEMENT 
- Is the human trained on AI error modes and how to verify AI results?   
- Are users trained to recognise and take corrective action on strange or erroneous AI outputs? 
- Has the human seen examples of AI incorrect information / advice in simulation training? 
- Does the AI inform the end-user of a detected / predicted shift from normal to emergency or degraded mode?   
- Are  there  sufficient  independent  (non-AI)  displays  of  critical  functions  to  allow  the  human  to  verify  that  context  is  changing?   
- Are end users trained to recognise unsafe AI operating conditions and to take corrective action? 
- Is it clear that the AI won’t interfere with existing alerts and warning systems?
