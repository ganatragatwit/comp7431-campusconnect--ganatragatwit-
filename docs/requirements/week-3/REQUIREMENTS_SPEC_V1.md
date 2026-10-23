# CampusConnect Requirements Specification v1 
  
Status: Draft — Week 3 
Student: Gopesh Ganatra 
Branch: docs/week-3-requirements-ai 
  
## 1. Problem statement 
Students who need IT Support information need a reliable way to find the correct 
next step because the current experience may be scattered, difficult to search, or 
hard to verify as current. 
  
## 2. Evidence carried forward from Week 2 
- E-01: I see this ticket is in [status], but I wonder what happened in [department].
- E-02: Cannot see downstream results
- A-01: The departments might not provide enough detailed information on the handling of tickets for Elena. 
  
## 3. One user journey inside the MVP 
A student asks one typed IT Support question. CampusConnect searches only approved 
IT Support material, returns a short answer with a visible source, or says the 
available sources do not support an answer.

## 4. Four requirements 
- FR-01 — The system shall accept one typed IT Support question.
- GR-01 — Every factual answer shall identify the approved source used.
- SF-01 — If approved sources are insufficient, the system shall not invent an 
answer and shall provide a helpful IT Support next step.
- NFR-01 — A keyboard user shall be able to submit a question and read the result. 
  
## 5. MVP boundary 
IN: one typed question, approved IT Support material, one grounded answer, visible 
source, safe failure, and helpful next step. 
OUT: password resets, ticket creation, personal student records, voice, automatic 
actions, and answers from unapproved material. 
  
## 6. AI critique and human decision 
- ChatGPT suggestion: Add: “For every response, display at least one approved source supporting the answer, or explicitly state that the approved sources do not support an answer.”
- Claude suggestion: Replace Section 1 with a problem claim the evidence supports, or add evidence for it: either (a) “Students who submit IT tickets cannot see what happened after handoff to another department (E-01, E-02),” with the Section 3 journey revised to match, or (b) keep the current statement and add at least one real Week 2 observation showing students failed to find or verify IT Support information, with the E-01 placeholders filled in.
- My decision:
  - ChatGPT suggestion: Approved.
  - Claude suggestion: Approved (a).
- My reason: ChatGPT correctly emphasized the need for an approved source as evidence in support of the conclusion. Claude's option (a) correctly emphasizes to base the problem claim off the evidence available.
