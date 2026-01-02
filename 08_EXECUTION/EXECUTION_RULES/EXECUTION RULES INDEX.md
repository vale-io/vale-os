\# EXECUTION RULES — INDEX

This directory defines how execution behaves once it is permitted.

Execution rules apply only after all upstream conditions  
(canon, immutables, law, authority, lifecycle)  
have been satisfied.

Execution rules do not grant permission.  
They govern behavior within permission.

\---

\#\# Scope of Execution Rules

Execution rules define:  
\- How system state may change during execution  
\- What execution may modify  
\- What limits apply while execution is active

Execution rules do not define:  
\- Truth  
\- Authority  
\- Promotion  
\- Canonical meaning

\---

\#\# Runtime Behavior Authority

While execution is active:  
\- State transitions must conform to defined rules  
\- Execution limits must be enforced  
\- Mutability boundaries must be respected

Any execution that violates these rules is invalid,  
regardless of outcome.

\---

\#\# Enforcement Order

During runtime, execution enforcement follows this order:

1\. Canon  
2\. Immutables  
3\. Law  
4\. Authority  
5\. Lifecycle  
6\. Execution Rules

Execution rules may not override any upstream layer.

\---

\#\# Defined Execution Rule Domains

Execution behavior is defined exclusively in the following files:

\- \`STATE\_TRANSITIONS.md\`    
  Governs allowed and forbidden state changes.

\- \`EXECUTION\_LIMITS.md\`    
  Governs time, scope, and resource boundaries.

\- \`MUTABILITY\_RULES.md\`    
  Governs what execution may modify and when.

No other file may define runtime execution behavior.

\---

\#\# Invalid Runtime Behavior

If execution behavior:  
\- Exceeds defined limits  
\- Performs an illegal state transition  
\- Modifies restricted data

The execution is invalid and must be halted.

Recovery eligibility is determined by recovery protocols,  
not by execution success.

\---

\#\# Scope Limitation

This directory defines runtime behavior only.

It does not:  
\- Interpret canon  
\- Grant authority  
\- Approve promotion  
\- Archive artifacts

