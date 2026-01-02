\# ALLOWED MOTIONS  
Runtime Layer: 01\_LAW / MOTION  
System: V.A.L.E (Variables Aligned Limits Execution)

This document enumerates all permitted artifact movements.  
Any motion not listed here is forbidden by default.

\---

\#\# WORKFLOW MOTIONS (PERMITTED)

1\. Intake → Scratch    
Path: \`04\_WORK/00\_INTAKE\` → \`04\_WORK/01\_SCRATCH\`    
Condition: Artifact initialized with ARTIFACT\_RECORD.

2\. Scratch → Build    
Path: \`04\_WORK/01\_SCRATCH\` → \`04\_WORK/02\_BUILD\`    
Condition: Scope defined and record present.

3\. Build → Review    
Path: \`04\_WORK/02\_BUILD\` → \`04\_WORK/03\_REVIEW\`    
Condition: Build marked complete.

4\. Review → Promotion Candidate    
Path: \`04\_WORK/03\_REVIEW\` → \`05\_PROMOTION/CANDIDATE\`    
Condition: Review checklist completed.

\---

\#\# PROMOTION MOTIONS (PERMITTED)

5\. Candidate → Approved    
Path: \`05\_PROMOTION/CANDIDATE\` → \`05\_PROMOTION/APPROVED\`    
Condition: Reviewer approval recorded.

6\. Approved → Canonical    
Path: \`05\_PROMOTION/APPROVED\` → \`06\_CANONICAL/BOUND\_ARTIFACTS\`    
Condition: Binding authority present.

\---

\#\# TERMINAL MOTIONS (PERMITTED)

7\. Any Work State → Archive (Failed)    
Path: \`04\_WORK/\*\` → \`07\_ARCHIVE/FAILED\`    
Condition: Explicit rejection recorded.

8\. Canonical → Archive (Deprecated)    
Path: \`06\_CANONICAL/BOUND\_ARTIFACTS\` → \`07\_ARCHIVE/DEPRECATED\`    
Condition: Deprecation authority invoked.

\---

\#\# RULES

\- Motion is directional only.  
\- Motion is singular.  
\- Motion requires condition satisfaction.  
\- Motion is logged.

Status: ACTIVE

