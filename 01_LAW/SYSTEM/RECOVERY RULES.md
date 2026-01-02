\# RECOVERY RULES  
Runtime Layer: 01\_LAW / SYSTEM  
System: V.A.L.E (Variables Aligned Limits Execution)

This document defines how the system exits HALTED state.

\---

\#\# RECOVERY CONDITIONS

Recovery is permitted only when:

\- Violation cause is identified  
\- Corrective action is completed  
\- Audit entry is recorded

\---

\#\# RECOVERY PATHS

\#\#\# Motion Recovery  
Used when:  
\- Blocked motion attempted

Action:  
\- Return artifact to last valid folder  
\- Record incident

\---

\#\#\# Record Recovery  
Used when:  
\- Required file missing or malformed

Action:  
\- Restore required record  
\- Re-validate artifact

\---

\#\#\# Authority Recovery  
Used when:  
\- Unauthorized action attempted

Action:  
\- Escalate to authority  
\- Confirm permissions

\---

\#\# PROHIBITED RECOVERY

\- Automatic recovery without review  
\- Silent correction  
\- Canon modification during recovery

\---

\#\# POST-RECOVERY VALIDATION

After recovery:  
\- Re-check all constraints  
\- Confirm STABLE state  
\- Log resolution

Status: ACTIVE

