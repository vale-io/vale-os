\# STATE TRANSITIONS

This document defines allowed and forbidden state changes during execution.

State transitions occur only while execution is active.  
All transitions must preserve system validity.

\---

\#\# Allowed Transitions

Execution may transition state only when:  
\- The current state is valid  
\- The target state is defined  
\- Required preconditions are met  
\- No halt condition is active

Transitions must be explicit and recorded.

\---

\#\# Forbidden Transitions

Execution must not:  
\- Skip required intermediate states  
\- Reverse lifecycle state  
\- Enter an undefined or ambiguous state  
\- Transition while halted

Any forbidden transition invalidates execution.

\---

\#\# Transition Preconditions

Before a transition may occur:  
\- Canon alignment must remain intact  
\- Authority must remain valid  
\- Lifecycle constraints must still apply  
\- Execution limits must not be exceeded

Failure of any precondition blocks the transition.

\---

\#\# Transition Finality

Once a state transition completes:  
\- The previous state is no longer active  
\- Rollback eligibility is governed by recovery protocols  
\- Silent reversal is forbidden

