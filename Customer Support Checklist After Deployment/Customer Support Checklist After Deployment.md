# Customer Support

## Core Functionality Check List:


| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------------ |
| CS-001 | Create Ticket | Send Email from Outlook to Support mail | Ticket - New | Email has sent to the Customer & Coordinator |
| CS-002 |  | Send Email from System | Ticket - New | Email has sent to the Customer & Coordinator |
| CS-003 | Assign (Action) | Ticket Assgin to Test User | Ticket - New | Email has sent to Assigned user |
| CS-004 | Pickup (Action) | Ticket Assign himself (User) | Ticket - New | Email has sent to Pickuped user (Assigned mail) |
| CS-005 | Send Approval | Send Approval to Test user | Ticket - New, Approval - Pending | Email has sent to the Assgined Approver & CC to sender |
| CS-006 | Take Action to Approval Request | Take Approve Action for Approval request | Approval - Approved | Email has sent to Approval request Sender & CC to Approver |
| CS-007 |  | Take Reject Action for Approval Request | Approval - Rejected | Email has sent to Approval request sender & CC to Approver |
| CS-008 | Schedule the Ticket | Schedule (Action) to Schedule & Assign the ticket | Ticket - Scheduled | Email has sent to Assigned user (Assigned mail) |
| CS-009 | Start Action | Take Start (Action) to Inprogress | Ticket - Inprogress | - |
| CS-010 | Create Helpdesk Ticket | Create HSK Ticket from CS, instead of Task | - | - |
| CS-011 | Reply to Mail from System | Reply to Test User Mail from System without Attachment | - | Email Received by Test User |
| CS-012 |  | Reply to Test User Mail from System with Attachments | - | Email Received by Test User with Attachments |
| CS-013 | Forward to Mail from System | Forward to Test User Mail from System without Attachment | - | Email Received by Test User |
| CS-014 |  | Forward to Test User Mail from System with Attachments | - | Email Received by Test User |
| CS-015 | Ticket Comments | Add Comments in Ticket details page | - | - |
| CS-016 |  | Add Mentioned Comments in Ticket details page | - | Email sent to Mentioned User & CC to Commented user |
| CS-017 | Approval Comments | Add Comments in Approval details page | - | Email sent to Approval Sender & Assigned Approver |
| CS-018 |  | Add Mentioned Comments in Approval details page | - | Email sent to Mentioned User, Approval Sender & Assigned Approver |
| CS-020 | Add Notes | Add Notes in the Ticket details page | - | - |
| CS-021 | Close Ticket | Close the Ticket | - | Email sent to Customer |
| CS-022 | ReOpen Ticket | ReOpen the Ticket manually | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS-023 |  | ReOpen Ticket by Sending Reply to closed ticket | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS-024 | Escalation mail to Supervisor | Ticket is not assigned for 4 hours until from ticket created | - | Email sent to the Reporting Supervisor |
| CS-025 |  | Ticket assigned to Coordinator, but no action taken for 4 hours until ticket assigned | - | Email sent to the Reporting Supervisor |
| CS-026 |  | Ticket assgined to Supervisor, but no action taken for 4 hours until ticket assigned | - | Email sent to that Supervisor |
| CS-027 | Escalation mail to Project Manager | Ticket assigned to Coordinator, but no action taken for 8 hours until ticket assigned | - | Email sent to Project Manager |
| CS-028 | Escalation mail to Alshammari | Ticket assigned to Coordinator, but no action for 12 hours from assigned | - | Email sent to Alshammari |
