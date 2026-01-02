\# CHANGE LOGS — INDEX

This directory records changes that occur within the V.A.L.E system.

Change logs document deltas.  
They do not explain intent, justification, or outcome.

\---

\#\# What Qualifies as a Change

A change is any modification to:  
\- System state  
\- Artifact state  
\- Canonical binding status  
\- Lifecycle position  
\- Execution status  
\- Configuration enforced by law or authority

If something is different after an action, it is a change.

\---

\#\# Required Change Log Elements

Each change log entry must record:  
\- The artifact or system component affected  
\- The prior state  
\- The new state  
\- The timestamp of change  
\- The triggering action or event

No interpretation or reasoning is permitted.

\---

\#\# Change Log Boundaries

Change logs must not include:  
\- Justification  
\- Decision rationale  
\- Authority explanation  
\- Execution narrative

Those belong in \`DECISION\_RECORDS\`.

\---

\#\# Ordering and Integrity

Change logs must be:  
\- Append-only  
\- Time-ordered  
\- Immutable once written

Corrections require a new entry that references the original.

\---

\#\# Relationship to Other Audit Domains

\- Change logs answer \*\*what changed\*\*  
\- Decision records answer \*\*why it changed\*\*  
\- Trace reports answer \*\*how it propagated\*\*

Change logs must be linkable to both decision records and trace reports.

\---

\#\# Scope Limitation

This directory defines change recording only.

It does not:  
\- Approve changes  
\- Explain decisions  
\- Execute actions

