# [Customer Support](https://afrithfts.github.io/Test-case-Documents/Customer%20Support%20Test%20Cases/Customer%20Support%20Testcases.xlsx)

## Flow Check List:

  1. Create Ticket by Sending mail from Outlook with and without attachments - Verify Reply Mail

  2. Create Ticket by Sending mail from System (Internally) with and without attachments - Verify Reply Mail

  3. Take Actions and Check Ticket Status:

    - Assign - Verify Mail
    - Pickup - Verify Mail
    - Schedule
    - Start
    - Close - Verify Mail
    - ReOpen - Verify Mail

  4. Send Approval Request - Verify Mail

  5. Take Actions on Approval Request - Verify Mail

  6. Create Helpdesk Ticket from Customer Support - Verify Mail and Helpdesk

  7. Send Reply mail from System with and Without attachments - Verify Mail with attachments (If available)

  8. Send Forward mail from System with and without attachments - Verify Mail with attachments (If available)

  9. Add Ticket Comments - Verify Email

  10. Add Mentioned Comments in Tickets - Verify Email

  11. Add Approval Comments - Verify Email

  12. Add Mentioned Comments in Approvals - Verify Email

  13. Add Notes in Tickets

  14. Verify Escalation Mail for Supervisor and Project Manager.

## Check List in Detail:


| TC ID | Test Scenario | Functionality | Status | Email Notification |
| ----- | ------------- | ------------- | ------ | ------------ |
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
| CS013 | Reply to Mail from External source (Gmail, Outlook) | Repl̥y to Mail from external (Gmail, Outlook) without Attachment | - | Email Received in System |
| CS014 |  | Reply to Mail from External with Attachments | - | Email Received in System with Attachments |
| CS015 | Forward to Mail from System | Forward to Test User Mail from System without Attachment | - | Email Received by Test User |
| CS016 |  | Forward to Test User Mail from System with Attachments | - | Email Received by Test User with Attachments |
| CS017 | Ticket Comments | Add Comments in Ticket details page | - | - |
| CS018 |  | Add Mentioned Comments in Ticket details page | - | Email sent to Mentioned User & CC to Commented user |
| CS019 | Approval Comments | Add Comments in Approval details page | - | Email sent to Approval Sender & Assigned Approver |
| CS020 |  | Add Mentioned Comments in Approval details page | - | Email sent to Mentioned User, Approval Sender & Assigned Approver |
| CS021 | Add Notes | Add Notes in the Ticket details page | - | - |
| CS022 | Close Ticket | Close the Ticket | - | Email sent to Customer |
| CS023 | ReOpen Ticket | ReOpen the Ticket manually | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS024 |  | ReOpen Ticket by Sending Reply to closed ticket | Ticket - Closed | Email Sent to Customer & Assigned user for the ticket |
| CS025 | Escalation mail to Supervisor | Ticket is not assigned for 4 hours until from ticket created | - | Email sent to the Reporting Supervisor |
| CS026 |  | Ticket assigned to Coordinator, but no action taken for 4 hours until ticket assigned | - | Email sent to the Reporting Supervisor |
| CS027 |  | Ticket assgined to Supervisor, but no action taken for 4 hours until ticket assigned | - | Email sent to that Supervisor |
| CS028 | Escalation mail to Project Manager | Ticket assigned to Coordinator, but no action taken for 8 hours until ticket assigned | - | Email sent to Project Manager |
| CS029 | Escalation mail to Alshammari | Ticket assigned to Coordinator, but no action for 12 hours from assigned | - | Email sent to Alshammari |

## Common Things to Test:-

  1. Search in all tables
  2. Minimize & Maximize table
  3. Import & Export Data
  4. Search in dropdown
  5. Scroll bar in all dropdown
  6. Page Navigation
  7. Dropdown data select & close
  8. Attachments
  9. Email Attachments
 10. Data Edit
 11. Data Delete
 12. Page Refresh
 13. Page Size
 14. Page Total Count
 15. Pagination
 16. Dropdown Pagination
 17. Dropdown Page size
 18. Textarea with long text
 19. Html editor with long text
