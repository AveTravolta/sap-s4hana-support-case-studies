# Ticket 01 – Purchase Requisition Stuck in Approval

## User Issue
“This application worked yesterday, now it’s broken.”
### System: 
SAP S/4HANA
### Environment 
PROD
### Priority: 
Medium
### Reported by: 
End User

## Investigation Steps
1) Checked for any recent transports from QA
2) Verify transport status in PROD
3) Compared behavior between QA and PROD
4) Checked authorization and role changes

## Root Cause
1) The transport updated the application logic but did not include the required user authorization role update, causing users in PROD to lose access after deployment.

## Resolution
1) Updated the missing user authorization role in PROD
2) Reassigned role to the affected users.
3) Confirmed application was fully restored.
4) Update internal knowledge base system with steps for similar cases. 
