## Contract Template Workflow:-

Draft > Recruiter GM Approval > Legal Department Approval > Approved > CEO Approval > Active > Rejected

## Check List:-

####  1. Move Contract Template from `Draft stage to Recruiter GM Approval stage` by using `Submit` action.
  
####  2. Move Contract Template from `Recruiter GM Approval to Legal Department Approval stage` by using `Approve` action.

####  3. Move Contract Template from `Recruiter GM Approval to Rejected stage` by using `Reject` action.

####  4. Move Contract Template from `Recruiter GM Approval to Draft stage` by using `Correction` action.

####  5. Move Contract Template from `Legal Department Approval to Approved stage` by using `Approve` action.

####  6. Move Contract Template from `Legal Department Approval to Rejected stage` by using `Reject` action.

####  7. Move Contract Template from `Legal Department Approval to CEO Approval stage` by using `Sent CEO Approval` action.

####  8. Move Contract Template from `CEO Approval to Active stage` by using `Active` action.

####  9. Move Contract Template from `CEO Approval to Rejected stage` by using `Reject` action.

####  10. Move Contract Template from `CEO Approval to Draft stage` by using `Correction` action.

| TC ID | Workflow Stage | Actions | After Action Stage | Status |
| ----- | -------------- | ------- | ------------------ | ------ |
| [CT001](#1-move-contract-template-from-draft-stage-to-recruiter-gm-approval-stage-by-using-submit-action) | Draft | Submit (Action) to move data to | Recruiter GM Approval | PASS |
| [CT002](#2-move-contract-template-from-recruiter-gm-approval-to-legal-department-approval-stage-by-using-approve-action) | Recruiter GM Approval | Approve (Action) to move data to | Legal Department Approval | PASS |
| [CT003](#3-move-contract-template-from-recruiter-gm-approval-to-rejected-stage-by-using-reject-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT004](#4-move-contract-template-from-recruiter-gm-approval-to-draft-stage-by-using-correction-action) |  | Correction (Action) to move data to | Draft | PASS |
| [CT005](#5-move-contract-template-from-legal-department-approval-to-approved-stage-by-using-approve-action) | Legal Department Approval | Approve (Action) to move data to | Approved | PASS |
| [CT006](#7-move-contract-template-from-legal-department-approval-to-ceo-approval-stage-by-using-sent-ceo-approval-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT007](#7-move-contract-template-from-legal-department-approval-to-ceo-approval-stage-by-using-sent-ceo-approval-action) |  | Sent CEO Approval (Action) to move data to  | CEO Approval | PASS |
| [CT008](#8-move-contract-template-from-ceo-approval-to-active-stage-by-using-active-action) | CEO Approval | Active (Action) to move data to | Active | PASS |
| [CT009](#9-move-contract-template-from-ceo-approval-to-rejected-stage-by-using-reject-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT010](#10-move-contract-template-from-ceo-approval-to-draft-stage-by-using-correction-action) |  | Correction (Action) to move data to | Draft | PASS |


## Contract Workflow:-

## Check List:-

#### 1. Move Contract from `Draft to Recruiter GM Approval stage` by using `Submit` action.

#### 2. Move Contract from `Recruiter GM Approval to Legal Department Approval stage (if type is "Edit")` by using `Approve` action.

#### 3. Move Contract from `Recruiter GM Approval to Document Signatire stage (if type is "Template")` by using `Approve` action.

#### 4. Move Contract from `Recruiter GM Approval to Rejected stage` by using `Reject` action.

#### 5. Move Contract from `Recruiter GM Approval to Draft stage` by using `Correction` action.

#### 6. Once the Document got Approved in DM, it will move to the Active stage (No Actions in this stage).

#### 7. Move Contract from `Approved to Agency Approved stage` by using `Agency Approved` action.

#### 8. Move Contract from `Approved to Rejected stage` by using `Reject` action.

#### 9. Move Contract from `Approved to Draft stage` by using `Correction` action.

#### 10. Move Contract from `Agency Approved to CEO Approval stage` by using `Send CEO Approval` action.

#### 11. Move Contract from `Agency Approved to Active stage` by using `Active` action.

#### 12. Move Contract from `CEO Approval to Active stage`    by using `Active` action.

#### 13. Move Contract from `CEO Approval to Rejected stage` by using `Reject` action.

#### 14. Move Contract form `CEO Approval to Draft stage` by using `Correction` action.

#### 15. Active stage - `No more Actions`

Draft > Recruiter GM Approval > Legal Department Approval > Document Signature > Approved > Agency Approved > CEO Approval > Active > Rejected

| TC ID | Workflow Stage | Actions | After Action Stage | Status |
| ----- | -------------- | ------- | ------------------ | ------ |
| [CT011](#1-move-contract-from-draft-to-recruiter-gm-approval-stage-by-using-submit-action) | Draft | Submit (Action) to move data to | Recruiter GM Approval | PASS |
| [CT012](#2-move-contract-from-recruiter-gm-approval-to-legal-department-approval-stage-if-type-is-edit-by-using-approve-action) | Recruiter GM Approval | Approve (Action) to move data to | If Type is `"Edit"` - Legal Department Approval | PASS |
| [CT013](#3-move-contract-from-recruiter-gm-approval-to-document-signatire-stage-if-type-is-template-by-using-approve-action) |  |  | If Type is `"Template"` - Send to Document Signature | PASS |
| [CT014](#4-move-contract-from-recruiter-gm-approval-to-rejected-stage-by-using-reject-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT015](#5-move-contract-from-recruiter-gm-approval-to-draft-stage-by-using-correction-action) |  | Correction (Action) to move data to | Draft | PASS |
| [CT016](#6-once-the-document-got-approved-in-dm-it-will-move-to-the-active-stage-no-actions-in-this-stage) | Document Signature | No Actions | Once the Document got Approved in DM, it will move to the Active | PASS |
| [CT017](#7-move-contract-from-approved-to-agency-approved-stage-by-using-agency-approved-action) | Approved | Agency Approved (Action) to move data to | Agency Approved | PASS |
| [CT018](#8-move-contract-from-approved-to-rejected-stage-by-using-reject-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT019](#9-move-contract-from-approved-to-draft-stage-by-using-correction-action) |  | Correction (Action) to move data to | Draft | PASS |
| [CT020](#10-move-contract-from-agency-approved-to-ceo-approval-stage-by-using-send-ceo-approval-action) | Agency Approved | Send CEO Approval (Action) to move data to | CEO Approval | PASS |
| [CT021](#11-move-contract-from-agency-approved-to-active-stage-by-using-active-action) |  | Active (Action) to move data to | Active | PASS |
| [CT022](#12-move-contract-from-ceo-approval-to-active-stage----by-using-active-action) | CEO Approval | Active (Action) to move data to | Active | PASS |
| [CT023](#13-move-contract-from-ceo-approval-to-rejected-stage-by-using-reject-action) |  | Reject (Action) to move data to | Rejected | PASS |
| [CT024](#14-move-contract-form-ceo-approval-to-draft-stage-by-using-correction-action) |  | Correction (Action) to move data to | Draft | PASS |
| [CT025](#15-active-stage---no-more-actions) | Active | **No Actions** |  |  |