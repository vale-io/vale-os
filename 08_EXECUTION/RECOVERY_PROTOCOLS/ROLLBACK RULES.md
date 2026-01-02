\# ROLLBACK RULES

This document defines the rules governing rollback after execution halts.

Rollback restores a previous valid state.  
Rollback does not erase history or legitimize invalid execution.

\---

\#\# Rollback Eligibility

Rollback may occur only when:  
\- Execution has halted  
\- The halt cause permits rollback  
\- A prior valid state exists  
\- Rollback is explicitly allowed by recovery protocols

Rollback is not automatic.

\---

\#\# Rollback Scope

Rollback may restore:  
\- Runtime state  
\- Temporary execution context  
\- Non-canonical working data

Rollback may not restore:  
\- Canonical definitions  
\- Immutables  
\- Law definitions  
\- Authority definitions  
\- Lifecycle definitions  
\- Audit records

These are permanently immutable.

\---

\#\# Rollback Depth

Rollback depth is limited to:  
\- The last known valid state  
\- The most recent stable checkpoint

Rollback may not skip over invalid states to reach convenience.

\---

\#\# Rollback Finality

Once rollback completes:  
\- The restored state becomes the active state  
\- Invalid execution artifacts are discarded  
\- Further rollback requires a new halt event

Rollback does not imply retry eligibility.

\---

\#\# Rollback Failure

If rollback fails:  
\- Execution must not resume  
\- The attempt must be archived  
\- Manual intervention may be required

Rollback failure is terminal for the execution attempt.

\---

\#\# Scope Limitation

This document defines rollback rules only.

It does not:  
\- Grant retry permission  
\- Authorize execution resumption  
\- Override halt conditions

