
Used IEE and ACM to pilot study as both these databases were expected to show a mix of technical articles and HCI studies. 

then I tuned the search further with web of science and scopus, before returning to formally extract based on the final search keywords selected.  The search terms were tuned primarily based on these databases and then tested with the remainder.

The first search clause focused on synonyms that would capture operational explainability as a concept, including transparency and interpretability to increase the net.  Rather than XAI as the focus, I chose HCXAI and "explainable agent" to focus on operational use over post-hoc explanation or explanation for technical assurance purposes, which are both exclusion criteria.

For the second search term, I did not search for the full term “safety critical,” “industry” or “safety critical industry” alone because the pilot searches excluded too many relevant articles; Rather I added in various alternatives that would capture as many ecologically valid studies of real-world system deployment research as possible, that considered high-stakes or fast-paced decision making requiring explanatory feedback from an AI system/ autonomous system, to meet the inclusion criteria.  The inclusion criteria was designed to find studies also outside of safety-critical industries that are more advanced in evaluation of the value of explanation in operational use, for example in social robots, manufacturing or financial services.

For the third search term, my intention was to ensure that operational interaction was front and centre in the literature by including synonyms for human-in-the-loop and human-ai interaction.   
- A recent 2023 scoping review found commonly used terms [[What terms are used to describe the interaction between humans and an AI-enabled system?]]


### SCOPUS 



(V1) - 700+
```
TITLE-ABS-KEY ( ( ( "explan*" OR "explainable AI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*" ) 
AND ( "real world" OR "real-world" OR "operational*" OR "frontline" OR "front line" OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical" ) 
AND ( "human-AI*" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR "human-in-the-loop" ) ) ) 
AND PUBYEAR > 2015
```

V2 - 262

```
TITLE-ABS-KEY ( 

( "explainable AI" OR "explainable agent" OR explainability OR "explainable artificial intelligence" OR "explanation interface" OR "explanation need" OR "explanation mechanism" OR "explanation requirement" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR hcxai OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR legib* ) 
AND 
( "real world" OR "real-world" OR "in-the-wild" OR deploy* OR "field study" OR "control room" OR operational* OR "work system" OR socio-technical OR sociotechnical OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes" ) 
AND 
( "human-AI" OR "human-XAI" OR hai OR "hybrid intelligence" OR "human-machine" OR supervisor* OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision*" OR "AI-augmented" ) 

) 
AND NOT TITLE-ABS-KEY ( "technique" OR "post-hoc" ) 
AND PUBYEAR > 2015 AND PUBYEAR < 2026
```


## Web of Science

215 results - https://www.webofscience.com/wos/woscc/summary/21e2c0c1-e0fc-4bff-8f3b-a672be4a9bff-01655e9732/times-cited-descending/1 

```
(TS=("explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "explanation need" OR "explanation mechanism" OR "explanation requirement" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR HCXAI OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR "legib*")
AND
TS=("real world" OR "real-world" OR "stakeholders" OR "industry" OR "in-the-wild" OR deploy* OR "field study" OR "control room" OR operational* OR integrat* or "work system" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")
AND
TS=("human-AI" OR "human-XAI" OR "HAI" OR "hybrid intelligence" OR "human-machine" OR supervisor* OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision*" OR "AI-augmented"))
NOT
TS=("technique" OR "post-hoc")
```

---


TS=("explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR HCXAI OR transparen* OR interpretab*)
- 205000 results


TS=("explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR HCXAI OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR interpretab*)
- 48,298 results

---

"operational explainability" - smart search - 188 entries. not all relevant
- OR WITH ABOVE  - NO INCREASE
---

TS=("human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "algorithmic decision*")
- 26,604 ENTRIES

----
TS=("real world" OR "real-world" OR "industry" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "operational*" OR "socio-technical" OR "sociotechnical" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")
- 2million results

---

EXTRA SEARCH TERM OPTIONS BANK

"human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "algorithmic decision*"

"AI-augmented" "human-centered AI" OR "user-centered AI" 
OR "mental model*" OR  "awareness" OR "cognitive load" OR "action*
OR "decision*" OR "handover*" OR "attention" OR "collaborat*" 
OR "human-centered AI" OR "user-centered AI" OR "mental model*" OR  "awareness" OR "cognitive load" OR "action*

TS=("explainable AI" OR "explainable agent" OR "explainability" OR "explainable artificial intelligence" OR "explanation interface" OR "operational explanat**" OR "AI explanat*" OR "human-centred XAI" OR HCXAI OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR interpretab*)
AND
TS=("human-AI*" OR "HAI" OR "human-machine" OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR  "human-in-the-loop" OR "algorithmic decision*")



### piloting search terms - acm/iee

("explainable AI" OR "explainable agent" OR explainability OR "explainable artificial intelligence" OR "explanation interface" OR "explanation need" OR "explanation mechanism" OR "explanation requirement" OR "operational explanation" OR "AI explanation" OR "human-centred XAI" OR hcxai OR "AI transparency" OR "transparency in AI" OR "algorithmic transparency" OR "system transparency" OR legib*)
AND
("real world" OR "real-world" OR "in-the-wild" OR deploy* OR "field study" OR "control room" OR operational* OR "work system" OR socio-technical OR sociotechnical OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "safety critical" OR "high stakes" OR "high-stakes")
AND
("human-AI" OR "human-XAI" OR hai OR "hybrid intelligence" OR "human-machine" OR supervisor* OR "human-autonomy" OR "human-agent" OR "AI-assisted" OR "human-in-the-loop" OR "algorithmic decision" OR "AI-augmented")
NOT
("technique" OR "post-hoc")




102 RESULTS - standard DB - The ACM Full-Text Collection (789,750 records)
274 RESULTS - enhanced DB - The ACM Guide to Computing Literature (3,893,830 records

Decisions for part 1:
1) focus on abstract containing the core concept of explanation rather than relying on full text search, to ensure adequate focus:
	1) 1276 results (w or without "transparen")
2) don't use "interpret*" synonym - it goes too wide, "interpretab*" focuses on the technology concept



```
("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpretab*")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical")

AND
("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonom*")

AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*")
AND [E-Publication Date: (01/01/2016 TO 31/12/2025)]





```


"query": { Abstract:("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpretab*") AND AllField:("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonom*") AND AllField:("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical") AND AllField:("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*") } 
"filter": { E-Publication Date: (01/01/2016 TO 12/31/2025), ACM Content: DL }



1449 RESULTS:
```
("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*" OR "imperfect" OR "uncertain*")
AND
("decision*" OR "handover*" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonom*")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical")
```




Abstract:("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*" OR "imperfect" OR "uncertain*") 
AND 
AllField:(("decision*" OR "handover*" OR "operational*" OR "procedur*" OR "frontline" OR "front line") AND ("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "field study") AND ("human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "human-in-the-loop" OR "autonomous system*") AND ("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical"))


"query": { Abstract:((("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*")) AND AllField:((("decision*" OR "handover*" OR "operational*" OR "procedur*" OR "frontline" OR "front line") AND ("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "field study") AND ("human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "human-in-the-loop" OR "autonomous system*") AND ("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical"))) } 
"filter": { E-Publication Date: (01/01/2016 TO 12/31/2025), ACM Content: DL }



**539 results**

("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*")
AND
("decision*" OR "handover*" OR "operational*" OR "procedur*" OR "frontline" OR "front line")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "field study")
AND
("human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "human-in-the-loop" OR "autonomous system*")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical")



("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*")
AND
("decision*" OR "handover*" OR "operational*"  OR "procedur*" OR "frontline" OR "front line" )
AND
("real world" OR "real-world"  OR "in-the-wild" OR "deploy*" OR "field study")
AND
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR  "human-in-the-loop" OR "autonomous system*")
AND
( "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical")


### IEEE


245 RESULTS (FULL TEXT):**

(("explainable AI" OR "explan*" OR "interpretable" OR "interpretability" OR "transparen*" OR "human-centred XAI" OR "HCXAI" OR "explainable agent") 
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical") AND 
("human-in-the-loop" or "interaction" OR "operational" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted") 
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*") NOT "XAI")


# 412 RESULTS
("explainable AI" OR "explan*" OR "user-centr* XAI" OR "HCXAI" OR "explainable agent")
AND
("real-world OR "in the wild" OR "field study" OR "socio-technical" OR "sociotechnical")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "imperfect" OR "decision*" OR "error detection" OR "failure recovery") 
NOT
("technique") NOT ("algorithm")


# 175 RESULTS

(("explainable AI" OR "explan*" OR "user-centr* XAI" OR "HCXAI" OR "explainable agent") 
AND 
("real-world OR "in the wild" OR "in-the-wild" OR "field study" OR "socio-technical" OR "sociotechnical") 
AND 
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "imperfect" OR "decision*" OR "error detection" OR "failure recovery") 
AND ("user" OR "human" OR "understand") 
NOT ("technique") NOT ("algorithm"))


# 64 RESULTS

(("explainable AI" OR "explan*" OR "HCXAI" OR "explainable agent") 
AND ("real-world OR "in the wild" OR "in-the-wild" OR "field study" OR "socio-technical" OR "sociotechnical") 
AND ("time-sensitive" OR "time pressure" OR "real-time" OR "operational" OR "real time" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "imperfect" OR "error detection" OR "failure recovery") 
AND ("user" OR "human" OR "understand") 
NOT ("technique") NOT ("algorithm"))

**



(("explainable AI" OR "explan*" OR "user-centr* XAI" OR "HCXAI" OR "explainable agent") 
AND
("real-world OR "in the wild" OR "in-the-wild" OR "field study" OR "socio-technical" OR "sociotechnical") 
AND 
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "imperfect" OR "decision*" OR "error detection" OR "failure recovery")
AND
("human-in-the-loop" OR "human-AI" OR "HAI" OR "human-agent teaming") 
NOT ("technique") NOT ("algorithm"))


## 305 results

("explan*" OR "explainable AI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*")
AND
("real world" OR "real-world" OR "operational*" OR "frontline" OR "front line" OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical")
AND
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR  "human-in-the-loop")






(Abstract:"explan*" OR Abstract:"explainable AI" OR Abstract:"human-centred XAI" OR Abstract:"HCXAI" OR Abstract:"explainable agent" OR Abstract:"transparen*" OR Abstract:"interpretab*" OR Abstract:"interpretation")
AND
("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonom*")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*")

(Abstract:"explainable AI" OR Abstract:"explan" OR Abstract:"interpretable" OR Abstract:"interpretability" OR Abstract:"transparen*cy*" OR Abstract:"human-centred XAI" OR Abstract:"HCXAI" OR Abstract:"explainable agent")
AND
("decision" OR "decisions" OR "handover" OR "attention" OR "human-in-the-loop" OR "operational" OR "procedure" OR "procedural" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonomy" OR "autonomous")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy" OR "deployment" OR "implement" OR "implementation" OR "field study" OR "socio-technical" OR "sociotechnical")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "error detection" OR "failure recovery" OR "workaround")




("explan*" OR "explainable AI" OR "human-centred XAI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpretab*" OR "interpretation")
AND
("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "frontline" OR "front line" OR "human-AI" OR "HAI" OR "human machine" OR "human-agent teaming" OR "AI-assisted" OR "autonom*")
AND
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*")



(("Abstract":"explan*" OR "Abstract":"explainable ai" OR "Abstract":"human-centred xai" OR "Abstract":"hcxai" OR "Abstract":"explainable agent" OR "Abstract":"transparen*" OR "Abstract":"interpretab*") 
AND 
("decision*" OR "handover*" OR "attention" OR "human-in-the-loop" OR "operational*" OR "procedur*" OR "collaborat*" OR "frontline" OR "front line" OR "human-ai" OR "hai" OR "human machine" OR "human-agent teaming" OR "ai-assisted" OR "autonom*") 
AND 
("real world" OR "real-world" OR "in-the-wild" OR "deploy*" OR "implement*" OR "field study" OR "socio-technical" OR "sociotechnical") 
AND 
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "regulated" OR "critical infrastructure" OR "imperfect" OR "uncertain*" OR "error detection" OR "failure recovery" OR "workaround*")) 
AND ("Publication Year":2016:2025)




## 305 results

("explan*" OR "explainable AI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "interpret*")
AND
("real world" OR "real-world" OR "operational*" OR "frontline" OR "front line" OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" OR "socio-technical" OR "sociotechnical")
AND
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR  "human-in-the-loop")





## 225 results 


(("explan*" OR "explainable AI" OR "HCXAI" OR “explainable agent” OR "transparen*" OR "decision rationale) 
AND 
("real world" OR "real-world" OR "operational*" OR "last mile" OR “frontline” OR “front line” OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR “high stakes” or “high-stakes” ) 
AND 
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" ==OR "multi-agent"== OR "situated action" OR "task support" OR "human-in-the-loop" ==OR "sociotechnical system"== ))


Filters Applied: 
2016 - 2025


## 147 results - 2025-05-20

("explan*" OR "explainable AI" OR "HCXAI" OR "explainable agent" OR "transparen*" OR "explanatory feedback" OR "decision rationale") 
AND 
("real world" OR "real-world" OR "operational*" OR "frontline" OR "front line" OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" ==OR "multi-agent"== OR "time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes" ==OR "socio-technical"==) 
AND 
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR "situated action" OR "task support" OR "human-in-the-loop")


## 144 results - 2025-05-20
("explan*" OR "explainable AI" OR "HCXAI" OR “explainable agent” OR "transparen*" OR "explanatory feedback" OR "decision rationale) 
AND 
("real world" OR "real-world" OR "operational*" OR “frontline” OR “front line” OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR “high stakes” or “high-stakes” OR "socio-technical") 
AND 
("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR "situated action" OR "task support" OR "human-in-the-loop" )



---
arcive


# 27 RESULTS

"explan*" OR "explainable AI" OR "explainable agent" OR "interpret*" OR "transparen*" OR "AI transparency" OR "sense-mak*" OR "sensemak*")
AND
("real world" OR "real-world" OR "operational*" OR "frontline" OR "front line" OR "in-the-wild" OR "deployed" OR "field study" OR "applied" OR "in-use")
AND
("human-AI" OR "HAI" OR "human-machine" OR "human-agent" OR "AI-assisted" OR "autonomous system*" OR "multi-agent")
AND
("time-sensitive" OR "time pressure" OR "safety-critical" OR "high stakes" OR "high-stakes")


# 82 RESULTS

(("explan*" OR “explainable agent” OR "sensemak*" OR "sense-mak*") 
AND 
("real world" OR "real-world" OR "operational*" OR “frontline” OR “front line” OR "in-the-wild" OR "deployed" OR "field study" OR "applied" OR "in-use" ) 
AND
("AI-assisted" OR "human-agent" OR "human operator" OR "human-AI" OR "HAI" OR "time-sensitive" OR "time pressure" OR “high stakes” or “high-stakes” OR "handover"))


## 299 RESULTS

("explan*" OR "explainable AI" OR “explainable agent” OR "transparen*" OR "explanatory feedback" OR "decision rationale) 

AND 

("real world" OR "real-world"  OR "operational*" OR “frontline” OR “front line” OR "in-the-wild" OR "deploy*" OR "field study" OR "autonomous system*" OR "time-sensitive" OR "time pressure" OR "safety-critical" OR “high stakes” or “high-stakes” )

AND 

("human-AI" OR "HAI" OR "human-machine" OR "human-agent teaming" OR "AI-assisted" OR "multi-agent" OR "situated action" OR "task support" OR "human-in-the-loop" OR "sociotechnical system" )



---




## Initial Brainstorm
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


