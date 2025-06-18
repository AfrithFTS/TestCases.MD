# Agent Contract

## Contract Template Workflow:-

Draft > Recruiter GM Approval > Legal Department Approval > Approved > CEO Approval > Active > Rejected

## Flow Check List:

  1. Create Contract Template of Contract Type as "Contract".

  2. Create Contract Template of Contract Type as "Appendix".

  3. Move Draft to Recruiter GM Approval - Submit action.
  
  4. Move Recruiter GM Approval to Legal Department Approval - Approve action.

  5. Move Recruiter GM Approval to Rejected - Reject action.

  6. Move Recruiter GM Approval to Draft - Correction action.

  7. Move Legal Department Approval to Approved - Approve action.

  8. Move Legal Department Approval to Rejected - Reject action.

  9. Move Legal Department Approval to CEO Approval - Sent CEO Approval action.

  10. Move Approved to Active - Active action.

  11. Move Approved to Rejected - Reject action.

  12. Move Approved to CEO Approved - Sent CEO Approval action.

  13. Move CEO Approval to Active - Active action.

  14. Move CEO Approval to Rejected - Reject action.

  15. Move CEO Approval to Draft - Correction action.

  16. Move Active to Rejected - Reject action.

## Check List in Detail :

### Contract Template Create:

| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------ |
| AG001 | Create Contract Template | Create Contract Template in Contract Type as Contract | Draft | - |
| AG002 |  | Create Contract Template in Contract Type as Appendix | Draft | - |


### Contract Template Flow:

| TC ID | Workflow Stage | Actions | After Action Stage |
| ----- | -------------- | ------- | ------------------ |
| AG003 | Draft | Submit (Action) to move data to | Recruiter GM Approval |
| AG004 | Recruiter GM Approval | Approve (Action) to move data to | Legal Department Approval |
| AG005 |  | Reject (Action) to move data to | Rejected |
| AG006 |  | Correction (Action) to move data to | Draft |
| AG007 | Legal Department Approval | Approve (Action) to move data to | Approved |
| AG008 |  | Reject (Action) to move data to | Rejected |
| AG009 |  | Sent CEO Approval (Action) to move data to  | CEO Approval |
| AG010 | Approved | Active (Action) to move data to | Active |
| AG011 |  | Reject (Action) to move data to | Rejected |
| AG012 |  | Sent CEO Approval (Action) to move data to| CEO Approval |
| AG013 | CEO Approval | Active (Action) to move data to | Active |
| AG014 |  | Reject (Action) to move data to | Rejected |
| AG015 |  | Correction (Action) to move data to | Draft |
| AG016 | Active | Reject (Action) to move data to | Rejected |

## Contract Workflow:-

Draft > Recruiter GM Approval > Legal Department Approval > Document Signature > Approved > Agency Approved > CEO Approval > Active > Rejected

## Flow Check List:

  1. Create Contract of Type as "Template".

  2. Create Contract of Type as "Edit".

  1. Move Draft to Recruiter GM Approval - Submit action.

  2. Move Recruiter GM Approval to Legal Department Approval (if type is "Edit") - Approve action.

  3. Move Recruiter GM Approval to Document Signature stage (if type is "Template") - Approve action.

  4. Move Recruiter GM Approval to Rejected - Reject action.

  5. Move Recruiter GM Approval to Draft - Correction action.

  6. Once the Document got Approved in DM, it will move to the Active stage (No Actions in this stage).

  7. Move Approved to Agency Approved - Agency Approved action.

  8. Move Approved to Rejected - Reject action.

  9. Move Approved to Draft - Correction action.

  10. Move Agency Approved to CEO Approval - Send CEO Approval action.

  11. Move Agency Approved to Active - Active action.

  12. Move CEO Approval to Active - Active action.

  13. Move CEO Approval to Rejected - Reject action.

  14. Move CEO Approval to Draft - Correction action.

  15. Active stage - `No more Actions`

## Check List in Detail :

### Contract Create:

| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------ |
| AG0017 | Create Contract | Create Contract in Type of Template | Draft | - |
| AG0018 |  | Create Contract in Type of Edit | Draft | - |  

### Contract Flow:

| TC ID | Workflow Stage | Actions | After Action Stage |
| ----- | -------------- | ------- | ------------------ |
| AG019 | Draft | Submit (Action) to move data to | Recruiter GM Approval |
| AG020 | Recruiter GM Approval | Approve (Action) to move data to | If Type is `"Edit"` - Legal Department Approval |
| AG021 |  |  | If Type is `"Template"` - Send to Document Signature |
| AG022 |  | Reject (Action) to move data to | Rejected |
| AG023 |  | Correction (Action) to move data to | Draft |
| AG024 | Document Signature | No Actions | Once the Document got Approved in DM, it will move to the Active |
| AG025 | Approved | Agency Approved (Action) to move data to | Agency Approved |
| AG026 |  | Reject (Action) to move data to | Rejected |
| AG027 |  | Correction (Action) to move data to | Draft |
| AG028 | Agency Approved | Send CEO Approval (Action) to move data to | CEO Approval |
| AG029 |  | Active (Action) to move data to | Active |
| AG030 | CEO Approval | Active (Action) to move data to | Active |
| AG031 |  | Reject (Action) to move data to | Rejected |
| AG032 |  | Correction (Action) to move data to | Draft |
| AG033 | Active | **No Actions** |  |  |