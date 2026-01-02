\# TRACE REPORTS — INDEX

This directory records how actions propagate through the V.A.L.E system.

Trace reports connect intent to outcome.  
They do not decide, execute, or justify.

\---

\#\# Purpose of Trace Reports

Trace reports exist to reconstruct:  
\- The sequence of actions  
\- The relationships between actions  
\- The effects of actions across system layers

A trace report answers how an outcome occurred.

\---

\#\# What Requires a Trace Report

Trace reports are required for:  
\- Execution attempts  
\- Promotions and rejections  
\- Recovery actions  
\- Rollbacks and retries  
\- Canonical bindings

Any action with downstream effects must be traceable.

\---

\#\# Required Trace Elements

Each trace report must include:  
\- Entry point (triggering action)  
\- Decision references (if any)  
\- Execution references  
\- Change log references  
\- Final outcome

All references must be explicit and resolvable.

\---

\#\# Trace Boundaries

Trace reports must not include:  
\- Canon definitions  
\- Decision justification  
\- Execution logic  
\- Interpretive commentary

Trace reports describe linkage, not meaning.

\---

\#\# Directionality and Ordering

Trace reports must be:  
\- Directional (cause → effect)  
\- Time-ordered  
\- Non-circular

Cycles or unresolved branches invalidate trace integrity.

\---

\#\# Relationship to Other Audit Domains

\- Trace reports answer \*\*how actions propagated\*\*  
\- Decision records answer \*\*why actions were authorized\*\*  
\- Change logs answer \*\*what changed\*\*

Trace reports must reference both decision records and change logs where applicable.

\---

\#\# Integrity and Immutability

Trace reports are immutable once written.

Corrections require:  
\- A new trace report  
\- Explicit linkage to the prior report

Trace history is never rewritten.

\---

\#\# Scope Limitation

This directory defines trace reporting only.

It does not:  
\- Approve actions  
\- Execute logic  
\- Modify system state

