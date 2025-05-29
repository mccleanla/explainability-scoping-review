
```
(
("explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "explanation need" OR "explanation mechanism" OR "explanation requirement" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR HCXAI OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR "legib*")
AND
("real world" OR "real-world" OR "stakeholders" OR "industry" OR "in-the-wild" OR deploy* OR "field study" OR "control room" OR operational* OR integrat* or "work system" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")
AND
("human-AI" OR "human-XAI" OR "HAI" OR "hybrid intelligence" OR "human-machine" OR supervisor* OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision*" OR "AI-augmented")
)
NOT
("technique" OR "post-hoc")
```


---

```
"explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "operational explanat" OR "AI explanation" OR "human-centred XAI" OR HCXAI OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR interpretab*)
AND
"real world" OR "real-world" OR "industry" OR "in-the-wild" OR deploy* OR implement* OR "field study" OR operational* OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")
AND
"human-AI" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision*" OR "AI-augmented")
```


---


```
("explan*" OR "explainable AI" OR "explainable agent" OR "human-centred XAI" OR "HCXAI"  OR "transparen*" OR "interpretab*")

AND
("real world" OR "real-world" OR "industry" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "operational*" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")

AND
("human-AI" OR "HAI" OR "human-machine" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision*")

```


**v2 -> changes on v 1**
widen to explainab*
make transparent more explicit/narrow

```
("explan*" OR "explainable" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR "interpretab*")

AND

("real world" OR "real-world" OR "industry" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "operational*" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes")

AND
"human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "algorithmic decision*" 

AND [E-Publication Date: (01/01/2016 TO 31/12/2025)]

```


**v3 -> changes on v 1**
 explainability explicit/narrow
 transparent  explicit/narrow

```
("explan*" OR "explainable" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR "interpretab*")

AND

("real world" OR "real-world" OR "industry" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "operational*" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes")

AND
"human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "human-centered AI" OR "user-centered AI" OR "mental model*" OR  "awareness" OR "cognitive load" OR "action*

AND [E-Publication Date: (01/01/2016 TO 31/12/2025)]

```




v4 
 - split out time-sensitive & highstakes as an additional pillar, adding in some options around what the explanation should support as ways to be less restrictive 
```
("explan*" OR "explainable AI" OR "explainable agent" OR "human-centred XAI" OR "HCXAI"  OR "transparen*" OR "interpretab*")

AND
("real world" OR "real-world" OR "industry" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "operational*" OR "socio-technical" OR "sociotechnical")

AND
("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "human-AI" OR "human-in-the-loop" OR "HAI" OR "human-machine" OR "human-agent" OR "AI-assisted")

AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*")

AND [E-Publication Date: (01/01/2016 TO 31/12/2025)]

```


---
extra options


"human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "algorithmic decision*")

"human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "human-centered AI" OR "user-centered AI" OR "mental model*" OR  "awareness" OR "cognitive load" OR "action*


("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "human-AI" OR "human-in-the-loop" OR "HAI" OR "human-machine" OR "human-agent" OR "AI-assisted")
OR "human-centered AI" OR "user-centered AI" OR "mental model*" OR  "awareness" OR "cognitive load" OR "action*


