---
description: >-
  This section covers the fields you need to fill out in the SEND_LIST sheet
  before sending emails through Gmail Blaster.
---

# Input Fields

#### Sending Criteria

* **Send Column**: Only the rows marked with an "X" in the **Send** column will be processed. If you do not wish to send an email from a particular row, simply remove the "X" by selecting the cell and pressing the "Delete" key.

#### Receiver, CC, and BCC

* **Receiver**: Enter the recipient's email address. If there are multiple recipients, separate them with semicolons (`;`).
* **CC/BCC**: You can include email addresses for CC and BCC as well. Similar to the Receiver field, separate multiple addresses with semicolons (`;`).
* **Important**: If the **Receiver** field is empty, that row will be skipped. If CC or BCC is empty, no email will be sent to these fields.

#### Subject

* Fill in the subject line for your email. You can also use placeholders (e.g., `{{Receiver_Name}}`) in the subject line to personalize it. Learn more about [placeholders here](placeholders.md).

#### Attachment

* For attachments, refer to the [Attachment Documentation.](attachments.md)

#### Status

* After sending, the **Status** column will display whether the email was sent successfully. If there is an error, the status message will inform you what went wrong
