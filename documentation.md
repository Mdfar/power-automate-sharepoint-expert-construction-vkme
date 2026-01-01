Setup Instructions

SharePoint: Create a list named 'Bid Invites Log' with the columns defined in sp_list_schema.xml.

Power Automate:

Create a new 'Automated Cloud Flow'.

Use 'Office 365 Outlook' trigger for the Shared Mailbox.

Add a 'Get items' action to check if MessageID already exists.

Use a 'Condition' to stop the flow if a duplicate is found.

Use 'Create new folder' for the Project directory.

Loop through attachments and 'Save file' to the new directory.

Teams: Add the 'Post an Adaptive Card' action to notify the Estimating team.