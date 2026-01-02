\# BLOCKED MOTIONS  
Runtime Layer: 01\_LAW / MOTION  
System: V.A.L.E (Variables Aligned Limits Execution)

This document explicitly lists forbidden movements.  
Any attempt triggers enforcement halt.

\---

\#\# FORBIDDEN MOTIONS

1\. Scratch → Intake    
Reason: Reverse motion not allowed.

2\. Build → Scratch    
Reason: Backward motion invalidates integrity.

3\. Review → Build    
Reason: Review is terminal for build state.

4\. Canonical → Any Work State    
Reason: Bound artifacts are immutable.

5\. Promotion Bypass    
Example: Build → Approved    
Reason: Skips mandatory review.

6\. Parallel State Existence    
Example: Same artifact in multiple folders    
Reason: Violates singular motion law.

\---

\#\# ENFORCEMENT ACTIONS

On blocked motion attempt:

\- Motion denied  
\- Artifact halted  
\- Audit entry created  
\- Review required

Status: ACTIVE

