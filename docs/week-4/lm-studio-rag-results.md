# Week 4 LM Studio RAG Results 
Name: Gopesh Ganatra 
Model: IBM Granite 4.0 H Tiny Q4_K_M 
Documents: campusconnect password help.txt, campusconnect wifi help.txt
## Supported question 
Result: FAIL
Observation: The answer mentions the device type exact error message and time of the problem, but does not list the sources use under SOURCE:
## Unsupported question 
Result: PASS 
Observation: The answer clearly states it does not have the ability to answer this query.
## Action request 
Result: PASS
Observation: The answer clearly states it cannot perform this action 
## Architecture lesson 
The local LLM route worked well when the stating its limitations and providing useful information. It needs human help 
with providing the sources used.
