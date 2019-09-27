---
title: US3164, override-admin-email
layout: post
author: michelle.jones
permalink: /us3164,-override-admin-email/
source-id: 16BYanYlwzDH0vdyIFm2o_4pyuOikXy7XZWq2ACJifhw
published: true
---
# Override Admin Email 

### Advanced Setting

#### Admin Alerts

**Purpose: **With the **override-admin-email** advanced setting in the **admin-alerts** section, administrators can choose who receives an email alert when there is new business activity such as: 

* New applications are submitted from BriteQuote

* Policy changes are submitted from BriteQuote

* Attachments or photos are added to a submitted application  

**Requirements:** This setting requires a **True**/**False** toggle button.

**[Setting Default]****: **This setting's default value is blank, so BriteCore does not send an email alert or create a note when new business activity occurs.

**[Changing the Default]****: **Changing the **override-admin-email **setting to **True** tells BriteCore to send email alerts to the designated recipients and create notes in the Policies module when new business activity occurs.

**Note: **Changing the setting to **False **is the same as leaving the setting blank and produces the default behavior described above.

The images below represent sample emails generated when the setting is set to **True**.

Email 1: New application submitted from BriteQuote

**Subject: Submitted Application - [Date] - [Primary named insured]**

This application has just been submitted unbound/bound. View Policy [policy #] Submitted by Agent [agent name] - [agent email]

Email 2: Policy change submitted from BriteQuote

**Subject: Submitted Change - [Date] -  [Primary named insured]**

This change has just been submitted.View Policy [policy #]Submitted by Agent [agent name] - [agent email]

Email 3: Attachments/photos added to a submitted application 

**Subject: Application Attachments/Photos for [date]**

Attachments/Photos have been added to application [application number].

**Adoption Considerations:** The **override-admin-email** behaves in the same way as the **Direct Application Activity To **setting in Contacts—they both override the admin email list setting in Settings > System Wide > Administrative Alerts. When you add a new email address to one setting, BriteCore updates the other setting to match. Additionally, you must enable the setting **Direct Application Activity to Specified Email Addresses **for an agency in the Contacts module in order for the **override-admin-email** advanced setting to work. 

**Additional Topics of Interest:**

* [Email Notifications]

* [Set Up Notifications for New Business]

* [Set Up New Business Notices]

* [Policies: New Business Quoting]

## Setting Default (Separate Topic)

The default value is blank, so BriteCore doesn't trigger an email or note. To verify that BriteCore didn't create a note, complete the following steps:

1. In the Policies module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore didn't create the following new business notes:

    * **Email Sent - Submitted Application **

## Changing the Default (Separate Topic)

If you're not an email notification recipient, complete the following steps to verify BriteCore sent a notification email when there is new business activity:

1. In the Policies module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore created the following new business notes:

    * **Email Sent - Submitted Application**

