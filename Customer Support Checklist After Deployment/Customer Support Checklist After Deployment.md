# Customer Support

## Core Functionality Check List:


| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------------ |
| CS001 | Create Ticket | Send Email from Outlook to Support mail | Ticket - New | Email has sent to the Customer & Coordinator |
| CS002 |  | Send Email from System | Ticket - New | Email has sent to the Customer & Coordinator |
| CS003 | Assign (Action) | Ticket Assgin to Test User | Ticket - New | Email has sent to Assigned user |
| CS004 | Pickup (Action) | Ticket Assign himself (User) | Ticket - New | Email has sent to Pickuped user (Assigned mail) |
| CS005 | Send Approval | Send Approval to Test user | Ticket - New, Approval - Pending | Email has sent to the Assgined Approver & CC to sender |
| CS006 | Take Action to Approval Request | Take Approve Action for Approval request | Approval - Approved | Email has sent to Approval request Sender & CC to Approver |
| CS007 |  | Take Reject Action for Approval Request | Approval - Rejected | Email has sent to Approval request sender & CC to Approver |
| CS008 | Schedule the Ticket | Schedule (Action) to Schedule & Assign the ticket | Ticket - Scheduled | Email has sent to Assigned user (Assigned mail) |
| CS009 | Start Action | Take Start (Action) to Inprogress | Ticket - Inprogress | - |
| CS010 | Create Helpdesk Ticket | Create HSK Ticket from CS, instead of Task | - | - |
| CS011 | Reply to Mail from System | Reply to Test User Mail from System without Attachment | - | Email Received by Test User |
| CS012 |  | Reply to Test User Mail from System with Attachments | - | Email Received by Test User with Attachments |
| CS013 | Forward to Mail from System | Forward to Test User Mail from System without Attachment | - | Email Received by Test User |
| CS014 |  | Forward to Test User Mail from System with Attachments | - | Email Received by Test User |
| CS015 | Ticket Comments | Add Comments in Ticket details page | - | - |
| CS016 |  | Add Mentioned Comments in Ticket details page | - | Email sent to Mentioned User & CC to Commented user |
| CS017 | Approval Comments | Add Comments in Approval details page | - | Email sent to Approval Sender & Assigned Approver |
| CS018 |  | Add Mentioned Comments in Approval details page | - | Email sent to Mentioned User, Approval Sender & Assigned Approver |
| CS020 | Add Notes | Add Notes in the Ticket details page | - | - |
| CS021 | Close Ticket | Close the Ticket | - | Email sent to Customer |
| CS022 | ReOpen Ticket | ReOpen the Ticket manually | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS023 |  | ReOpen Ticket by Sending Reply to closed ticket | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS024 | Escalation mail to Supervisor | Ticket is not assigned for 4 hours until from ticket created | - | Email sent to the Reporting Supervisor |
| CS025 |  | Ticket assigned to Coordinator, but no action taken for 4 hours until ticket assigned | - | Email sent to the Reporting Supervisor |
| CS026 |  | Ticket assgined to Supervisor, but no action taken for 4 hours until ticket assigned | - | Email sent to that Supervisor |
| CS027 | Escalation mail to Project Manager | Ticket assigned to Coordinator, but no action taken for 8 hours until ticket assigned | - | Email sent to Project Manager |
| CS028 | Escalation mail to Alshammari | Ticket assigned to Coordinator, but no action for 12 hours from assigned | - | Email sent to Alshammari |
