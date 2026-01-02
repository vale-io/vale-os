\# HARD HALTS

This document defines conditions that require immediate and irreversible  
termination of execution.

Hard halts are absolute.  
They override execution rules, authority, lifecycle state, and recovery intent.

When a hard halt is triggered, execution must stop immediately.

\---

\#\# Canon Breach

Execution must hard halt if:  
\- Canon is contradicted  
\- Canonical meaning is redefined  
\- Canon references are missing or corrupted

Outputs produced during a canon breach are void.

\---

\#\# Immutable Violation

Execution must hard halt if:  
\- An immutable is bypassed, altered, or softened  
\- Immutable enforcement is disabled  
\- Execution attempts to override immutable constraints

There is no automatic recovery from immutable violation.

\---

\#\# Authority Escalation

Execution must hard halt if:  
\- Authority scope expands during execution  
\- Self-granted permissions are detected  
\- Override rules are violated

All actions associated with the escalation are invalid.

\---

\#\# Lifecycle Violation

Execution must hard halt if:  
\- Required lifecycle phases are skipped  
\- Promotion occurs without approval  
\- Archival is bypassed or reversed

Execution results are invalid regardless of outcome.

\---

\#\# Illegal State Transition

Execution must hard halt if:  
\- A forbidden state transition is attempted  
\- State becomes undefined or contradictory  
\- Transition occurs while halted

State must be frozen pending recovery or archive.

\---

\#\# Data Integrity Breach

Execution must hard halt if:  
\- Canonical data is modified  
\- Audit records are altered  
\- Execution history is corrupted or erased

Trust cannot be restored through execution continuation.

\---

\#\# Halt Finality

Once a hard halt is triggered:  
\- Execution cannot resume automatically  
\- Results are void  
\- Recovery requires explicit protocol eligibility

If recovery is not permitted, the execution attempt must be archived.

\---

\#\# Scope Limitation

This document defines hard halt triggers only.

It does not:  
\- Define soft halts  
\- Authorize recovery  
\- Permit retries

