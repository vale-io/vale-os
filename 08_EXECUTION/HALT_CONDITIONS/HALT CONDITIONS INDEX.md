\# HALT CONDITIONS — INDEX

This directory defines the conditions under which execution must stop.

Halt conditions supersede execution rules.  
Halt conditions prevent or terminate execution to preserve system validity.

Execution may not ignore, defer, or override a halt condition.

\---

\#\# Scope of Halt Conditions

Halt conditions apply:  
\- Before execution begins  
\- During execution  
\- After execution attempts

If a halt condition is met at any point,  
execution must not proceed.

\---

\#\# Categories of Halts

Halt conditions are classified into the following categories:

\- \*\*Hard Halts\*\*  
  Non-negotiable stops triggered by invalid states,  
  canon violations, immutable breaches, or system corruption.

\- \*\*Soft Halts\*\*  
  Conditional suspensions triggered by recoverable issues,  
  pending requirements, or correctable violations.

\- \*\*Invalid State Detection\*\*  
  Detection of incoherent, contradictory, or undefined system states  
  that invalidate execution.

\---

\#\# Halt Enforcement

When a halt condition is triggered:  
\- Execution stops immediately  
\- State is frozen  
\- No further transitions are allowed

Execution results produced after a halt trigger are void.

\---

\#\# Halt Priority

If multiple conditions apply:  
\- Hard halts take precedence over all others  
\- Invalid state detection overrides soft halts  
\- Soft halts may defer to recovery protocols

No halt condition may be bypassed by authority or execution rules.

\---

\#\# Resolution Path

Resolution of a halt is not automatic.

All halts must be resolved by:  
\- Satisfying recovery protocols, or  
\- Archival of the execution attempt

Execution may resume only if explicitly permitted by recovery rules.

\---

\#\# Scope Limitation

This directory defines halt logic only.

It does not:  
\- Authorize execution  
\- Define recovery behavior  
\- Archive artifacts

