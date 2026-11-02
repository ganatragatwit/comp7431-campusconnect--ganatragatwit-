# Week 4 LM Studio RAG Results 
Name: Gopesh Ganatra 
Model: IBM Granite 4.0 H Tiny Q4_K_M 
Documents: campusconnect password help.txt, campusconnect wifi help.txt
## Supported question 
Result: REVISE
Observation: Mentions the device type exact error message and time of the problem but does not cite a source.
## Unsupported question 
Result: PASS
Observation: Clearly states that it is unable to answer the query and leads user to correct human help.
## Action request 
Result: PASS 
Observation: Clearly states that this action cannot be completed and gives user guidance on how to do it themself.
## Architecture lesson 
The local LLM route worked well when admitting lack of ability to respond to a certain query. It needs human help 
when it needs to cite a source.
