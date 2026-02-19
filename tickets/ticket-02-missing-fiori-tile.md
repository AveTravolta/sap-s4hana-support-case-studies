# Ticket 02 – Missing Fiori Tile

## User Issue
“Missing ‘Purchase Order Approval’ tile in Fiori”
### System
SAP S/4HANA
### Module
MM/Fiori Launch Pad
### Environment
PROD
### Priority
Medium
### Reported by
End User

## Investigation Steps
1) Verified user access and role assignment
2) Checked Fiori catalog and group assignments. 
3) Reviewed recent role or authorization changes. 
4) Validated Fiori cache and customization. 

## Root Cause
1) The users role was missing the required Fiori catalog assignment, preventing the ‘Purchase Order Approval’ tile from appearing in the Fiori Launchpad.

## Resolution
1) Added the correct Fiori catalog to the user’s role. 
2) Regenerated and reassigned the role.
3) User confirmed tile is now visible and functional.
4) Update internal knowledge base system with steps for similar cases. 
