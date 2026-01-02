  
\# VALE GOVERNANCE UNLOCK & CHANGE PROTOCOL — v1.1  
\#\# Purpose  
This document defines the only valid procedure for modifying files that were  
frozen under VALE Filesystem v1.0.  
No other method of change is recognized.  
\---  
\#\# Scope  
This protocol applies to all files marked as:  
\- Canonical  
\- Governance-defining  
\- Enforcement-defining  
\- Safety-defining  
Including but not limited to:  
\- 00\_CANON  
\- 01\_LAW  
\- 02\_AUTHORITY  
\- 03\_LIFECYCLE  
\- 06\_CANONICAL  
\- 08\_EXECUTION  
\- 09\_AUDIT index files  
\---  
\#\# Unlock Preconditions  
A frozen file may be unlocked only if all conditions are met:  
1\. A \*\*change necessity\*\* is identified  
2\. The change cannot be satisfied by:  
   \- WORK artifacts  
   \- PROMOTION flow  
   \- CONSTRAINT tuning  
   \- SYSTEM metadata  
3\. The change does not violate existing immutables  
4\. The change is forward-compatible  
If any condition fails, unlock is forbidden.  
\---  
\#\# Mandatory Unlock Sequence  
Unlocking must follow this order exactly:  
1\. \*\*Declare Intent\*\*  
   \- Create a decision record explaining why change is required  
2\. \*\*Temporary Unlock\*\*  
   \- Unlock only the minimum necessary file(s)  
   \- Unlock duration must be explicit and limited  
3\. \*\*Apply Change\*\*  
   \- Make the change deliberately  
   \- No batch edits  
   \- No opportunistic edits  
4\. \*\*Revalidation\*\*  
   \- Re-read all impacted layers  
   \- Confirm no cross-layer violation occurred  
5\. \*\*Version Increment\*\*  
   \- Increment system version (e.g., v1.1)  
   \- Update FREEZE\_DECLARATION with new version reference  
6\. \*\*Re-Freeze\*\*  
   \- Re-lock all modified files  
   \- Confirm filesystem enforcement is restored  
\---  
\#\# Prohibited Actions  
The following are invalid and void any change:  
\- Editing frozen files without declaration  
\- Unlocking entire folders unnecessarily  
\- Silent edits  
\- Retroactive canon rewriting  
\- “Quick fixes” during execution  
Violations must be archived and investigated.  
\---  
\#\# Versioning Rules  
\- v1.0 → v1.1 → v1.2 are \*\*forward-only\*\*  
\- No downgrade of governance versions  
\- Each version must have its own freeze declaration  
\---  
\#\# Authority  
Only the system architect or explicitly delegated authority  
may authorize an unlock.  
Execution, agents, or automation may never unlock governance files.  
\---  
\#\# Status  
This protocol is active once v1.0 is frozen.  
All future governance changes must comply.  
