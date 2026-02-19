# Ticket 03 – Purchase Requisition Stuck in Approval

## User Issue: 
“My purchase requisition shows as submitted, but it hasn’t moved to approval. It’s been stuck for two days.”
### System: 
SAP S/4HANA
### Module:
MM/Fiori Launch Pad
### Environment: 
PROD
### Priority: 
Medium
### Reported by: 
End User

## Investigation Steps:
1) Verified user access and role assignment
2) Checked for an assigned approver
3) Confirmed the purchase amount aligned with the user’s approval threshold
4) Checked for required vendor quotation attachments needed for approval routing
5) Validated expected approval behavior by comparing to a successfully approved requisition.

## Root Cause:
1) The purchase requisition that was submitted exceeded the user’s approval threshold, requiring additional approval before the workflow could proceed.

## Resolution:
1) Informed the user that the purchase requisition exceeded their approval threshold
2) Confirmed that the requisition was automatically routed for additional approval per standard workflow rules
3) Documented the scenario for future reference
