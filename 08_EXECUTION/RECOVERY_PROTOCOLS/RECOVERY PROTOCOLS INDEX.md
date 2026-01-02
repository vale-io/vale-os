\# RECOVERY PROTOCOLS — INDEX

This directory defines how the system responds after execution halts.

Recovery restores operability.  
Recovery does not legitimize invalid execution.

All recovery actions are bounded by canon, immutables, and law.

\---

\#\# Scope of Recovery

Recovery protocols apply only after:  
\- Execution has halted  
\- State is frozen  
\- Halt cause is identified

Recovery may not occur during active execution.

\---

\#\# Recovery Authority

Recovery is permitted only when:  
\- Halt conditions allow recovery  
\- Recovery eligibility is explicitly defined  
\- Required authority is present

Recovery may not be initiated by execution logic itself.

\---

\#\# Recovery Outcomes

Recovery protocols may result in:  
\- Rollback to a previous valid state  
\- Controlled retry of execution  
\- Permanent termination and archival

No other outcomes are valid.

\---

\#\# Recovery Boundaries

Recovery may:  
\- Restore state within defined limits  
\- Resume execution under strict conditions

Recovery may not:  
\- Rewrite canon  
\- Alter immutables  
\- Modify audit history  
\- Validate invalid results

\---

\#\# Recovery Protocol Domains

Recovery behavior is defined exclusively in the following files:

\- \`ROLLBACK\_RULES.md\`    
  Defines what may be restored and to what depth.

\- \`RETRY\_ELIGIBILITY.md\`    
  Defines when execution may be retried and how often.

\- \`RESUME\_CONDITIONS.md\`    
  Defines when and how execution may resume.

No recovery logic may exist outside these domains.

\---

\#\# Recovery Sequencing

Recovery follows this order:  
1\. Halt analysis  
2\. Eligibility determination  
3\. State restoration (if allowed)  
4\. Validation  
5\. Controlled resume or termination

Skipping any step invalidates recovery.

\---

\#\# Failure of Recovery

If recovery fails or is disallowed:  
\- Execution must not resume  
\- The attempt must be archived  
\- No further recovery is permitted

\---

\#\# Scope Limitation

This directory defines recovery control only.

It does not:  
\- Authorize execution  
\- Define halt conditions  
\- Archive artifacts directly

