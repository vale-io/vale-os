\# RETRY ELIGIBILITY

This document defines the conditions under which a halted execution  
may be retried.

Retry is a controlled exception.  
Retry does not legitimize prior failure.

\---

\#\# Eligibility Requirement

An execution attempt is eligible for retry only if:  
\- The halt cause explicitly allows retry  
\- No hard halt was triggered  
\- Canon and immutables remain intact  
\- A valid rollback has completed successfully

If any condition is unmet, retry is forbidden.

\---

\#\# Retry-Eligible Halt Types

Retry may be permitted after:  
\- Soft halts caused by missing inputs  
\- Temporary resource saturation  
\- External dependency interruption  
\- Recoverable state incoherence

Retry eligibility must be explicitly confirmed.

\---

\#\# Retry-Prohibited Halt Types

Retry is prohibited after:  
\- Canon breach  
\- Immutable violation  
\- Authority escalation  
\- Lifecycle violation  
\- Data integrity breach  
\- Failed rollback

These conditions permanently disqualify retry.

\---

\#\# Retry Limits

Retries are finite.

Retry constraints include:  
\- Maximum retry count  
\- Required delay between retries  
\- Mandatory revalidation before retry

Exceeding retry limits invalidates further attempts.

\---

\#\# Retry Preconditions

Before retry may occur:  
\- Rollback must restore a valid state  
\- Preconditions must be revalidated  
\- Authority must be re-confirmed  
\- Halt conditions must be cleared

Retry without revalidation is invalid.

\---

\#\# Retry Finality

Each retry is a new execution attempt.

Failure of a retry:  
\- Does not reset retry limits  
\- Does not erase prior audit traces  
\- May escalate to permanent termination

\---

\#\# Scope Limitation

This document defines retry eligibility only.

It does not:  
\- Guarantee retry success  
\- Override halt conditions  
\- Permit indefinite retries

