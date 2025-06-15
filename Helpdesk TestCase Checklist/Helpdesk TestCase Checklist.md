# Helpdesk

## Flow Check List:

  1. Create Ticket with and without attachments - Verify Reply Email

  2. Take Actions and Check Ticket Status:

    - Assign - Verify Email
    - Pickup - Verify Email
    - Accept (Schedule) - Verify Email
    - Start - Verify Email
    - Cancel - Verify Email
    - Close - Verify Email
    - ReOpen - Verify Email

  3. Send Approval Request - Verify Email

  4. Take Actions on Approval Request - Verify Email

  5. Assign Task - Verify Email

  6. Take Actions on Tasks - Verify Email

  7. Add Ticket Comments

  8. Add Mentioned Comments in Ticket - Verify Email

  9. Add Approval Comments - Verify Email

  10. Add Mentioned Comments in Approvals - Verify Email

  11. Add Task Comments - Verify Email

  12. Add Mentioned Comments in Tasks - Verify Email

  13. Verify Escalation Mail for Team Lead

  13. Check SLA status with Ticket:

    - SLA Status Flow - No Action > Goal > Dead
    - "No Action" - Default SLA Status for New Ticket
    - "Goal" - SLA Status will update for Assign/Pickup
    - "DeadLine" - If no action on ticket for 4 hours

## Check List in Detail :

| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------ |
| HD001 | Create Ticket | Create Ticket with and without attachments | Ticket - New | Email Sent to the User & Team Members |
| HD002 | Assign (Action) | Ticket Assign to Test User | Ticket - New | Email Sent to Assigned User |
| HD003 | Pickup (Action) | Ticket Assign himself | Ticket - New | Email Sent to Pickuped user (Assigned mail) |
| HD004 | Send Approval | Send Approval to Test User | Ticket - Waiting for Approval, Approval - Pending | Email Sent to Assigned Approver & CC to Sender |
| HD005 | Take Action to Approval Request | Take Approve Action for Approval request | Ticket - Approved, Approval - Approved | Email Sent to Approval Request Sender & CC to Approver |
| HD006 |  | Take Reject Action for Approval Request | Ticket - Waiting for Approval, Approval - Rejected | Email Sent to Approval Request Sender & CC to Approver |
| HD007 | Schedule the Ticket | Accept (Action) to Schedule the Ticket | Ticket - Scheduled | Email Sent to the Request Created User |
| HD008 | Start Action| Start (Action) to Inprogress the Ticket | Ticket - Inprogress | Email Sent to the Request Created User |
| HD009 | Assign Task | Assign Task to Test User | Task - ToDo | Email Sent to the Task Assigned User & CC to Task Created User |
| HD010 | Take Action on Task | Take Doing Action on Task | Task - Doing | Email Sent to the Task Created User & CC to Task Assigned User |
| HD011 |  | Take Done Action on Task | Task - Done | Email Sent to the Task Created User & CC to Task Assigned User |
| HD012 | Ticket Comments | Add Comments in Ticket details page | - | - |
| HD013 |  | Add Mentioned Comments in Ticket details page | - | Email sent to Mentioned User & CC to Commented user |
| HD014 | Approval Comments | Add Comments in Approval details page | - | Email sent to Approval Sender & Assigned Approver |
| HD015 |  | Add Mentioned Comments in Approval details page | - | Email sent to Mentioned User, Approval Sender & Assigned Approver |
| HD016 | Task Comments | Add Comments in Task details page | - | - |
| HD017 |  | Add Mentioned Comments in Task details page | - | Email sent to Mentioned User, Approval Sender & Assgined Approver |
| HD018 | Add Notes	| Add Notes in the Ticket details page | - | - |
| HD019 | Cancel Ticket | Cancel the Ticket | - | Email sent to Ticket Created User |
| HD020 | Close Ticket | Close the Ticket | - | Email sent to Ticket Created User |
| HD021 | ReOpen Ticket | ReOpen the Ticket | Ticket - Closed | Email sent to Ticket Created User |
| HD022 | Escalation Mail to Team Lead | If no action taken for 4 hours from ticket created | - | Email sent to Team Lead of the Ticket Category |
| HD023 |  | If no action taken for 8 hours from ticket created | - | Email sent to Team Lead of the Ticket Category |