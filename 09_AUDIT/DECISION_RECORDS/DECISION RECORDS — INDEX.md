\# DECISION RECORDS — INDEX

This directory records decisions made within the V.A.L.E system.

Decision records capture intent and authorization.  
They do not execute actions or record state changes.

\---

\#\# What Qualifies as a Decision

A decision is any explicit approval, denial, selection, or escalation that:  
\- Authorizes or blocks an action  
\- Determines promotion or rejection  
\- Selects a recovery path  
\- Grants or denies override  
\- Confirms or revokes authority

If an action required intent or judgment, it is a decision.

\---

\#\# Required Decision Record Elements

Each decision record must include:  
\- The decision made  
\- The authority responsible  
\- The artifact or scope affected  
\- The timestamp of the decision  
\- The basis or criteria used

Decision records must be explicit and attributable.

\---

\#\# Decision Boundaries

Decision records must not include:  
\- Execution steps  
\- State transition logs  
\- Change deltas  
\- Outcome interpretation

Those belong in change logs or trace reports.

\---

\#\# Authority Traceability

Every decision must be traceable to:  
\- A valid authority role  
\- A defined permission scope  
\- Applicable law and lifecycle constraints

Decisions without valid authority are invalid.

\---

\#\# Relationship to Other Audit Domains

\- Decision records answer \*\*why an action was taken\*\*  
\- Change logs answer \*\*what changed\*\*  
\- Trace reports answer \*\*how effects propagated\*\*

Decision records must reference related change logs and trace reports.

\---

\#\# Integrity and Finality

Decision records are immutable once written.

Amendments require:  
\- A new decision record  
\- Explicit reference to the prior decision

Historical decisions are not rewritten.

\---

\#\# Scope Limitation

This directory defines decision recording only.

It does not:  
\- Execute actions  
\- Modify state  
\- Archive artifacts

