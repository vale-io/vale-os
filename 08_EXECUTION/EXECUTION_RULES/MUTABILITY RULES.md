\# MUTABILITY RULES

This document defines what execution may modify.

Mutability is constrained to preserve system integrity.

\---

\#\# Mutable During Execution

Execution may modify:  
\- Active runtime state  
\- Temporary execution context  
\- Non-canonical working data

All mutations must be traceable.

\---

\#\# Immutable During Execution

Execution must not modify:  
\- Canon  
\- Immutables  
\- Law definitions  
\- Authority definitions  
\- Lifecycle definitions  
\- Audit history

Any attempt to modify immutable data invalidates execution.

\---

\#\# Freeze Conditions

Once execution begins:  
\- Canonical references are frozen  
\- Authority scope is frozen  
\- Lifecycle state is frozen

Changes to these require execution halt and recovery.

\---

\#\# Mutation Finality

All valid mutations:  
\- Persist only if execution completes successfully  
\- Are discarded if execution is invalidated  
\- Are subject to rollback rules

