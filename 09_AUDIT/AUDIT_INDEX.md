\# AUDIT — INDEX

This directory defines the audit layer of the V.A.L.E system.

Audit exists to preserve truth about system activity.  
Audit does not execute, decide, or enforce.  
Audit records.

\---

\#\# Audit Mandate

All meaningful system activity must be auditable.

Audit applies to:  
\- Canonical binding  
\- Authority decisions  
\- Lifecycle transitions  
\- Execution attempts  
\- Recovery actions  
\- Promotion outcomes

Any action that cannot be audited is invalid.

\---

\#\# Non-Bypass Rule

Audit cannot be bypassed, disabled, or deferred.

No authority, execution path, or recovery protocol  
may suppress audit recording.

An action without an audit record is treated as non-existent.

\---

\#\# Audit Scope

Audit records must capture:  
\- What occurred  
\- When it occurred  
\- Who or what authorized it  
\- Which artifacts were affected

Audit records must not interpret or justify actions.  
Interpretation belongs in decision records.

\---

\#\# Audit Layers

Audit evidence is organized into the following domains:

\- \`CHANGE\_LOGS/\`  
  Records what changed.

\- \`DECISION\_RECORDS/\`  
  Records why a change or action was approved.

\- \`TRACE\_REPORTS/\`  
  Records how actions propagated through the system.

No audit evidence may exist outside these domains.

\---

\#\# Audit Integrity

Audit records are immutable once written.

Audit records may not be:  
\- Altered  
\- Deleted  
\- Rewritten

Correction requires a new audit entry, not modification.

\---

\#\# Audit Timing

Audit recording must occur:  
\- Before execution (intent)  
\- During execution (activity)  
\- After execution (outcome)

Delayed or retroactive audit recording is invalid.

\---

\#\# Audit Consumption

Audit records are for:  
\- Verification  
\- Forensic review  
\- Compliance validation

Audit records are not optimized for readability or narrative.

\---

\#\# Scope Limitation

This directory defines audit requirements only.

It does not:  
\- Define execution behavior  
\- Grant authority  
\- Approve promotion  
\- Archive artifacts

