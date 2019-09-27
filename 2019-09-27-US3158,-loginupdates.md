---
title: US3158, loginupdates
layout: post
author: michelle.jones
permalink: /us3158,-loginupdates/
source-id: 1RI29Fomomoq1jNCMV-FSnbx0hnsGi2Yd0-Rs_NClNj4
published: true
---
Login Updates

Advanced Setting

#### Admin Alerts

**Purpose:** With the **loginupdates** advanced setting in the **admin-alerts** section, administrators can choose who receives an email alert when an agent updates his/her login from the Agent Portal, or when a user's login information is updated on his/her contact in the Contacts module of the Administrative Portal**.**

**Requirements:** This setting requires a list of comma-separated email addresses.

**[Setting Default]****:** This setting's default value is blank, so BriteCore does not send an email alert or create a note when a user updates their login information in the Agent or Administrative portals.

**[Changing the Default]****:** Adding recipients' email(s) to **loginupdates** triggers BriteCore to send email alerts (*below*) to the designated recipients and create notes in the Contacts module when an agent updates his/her login from the Agent Portal, or when a user's login information is updated on his/her contact in the Contacts module of the Administrative Portal**.**

**Email 1: A User's Login is Updated in Contacts**

**Subject: BriteCore Alert: User Login Created**

The contact, [old user], has updated his or her username to [new user].

**Email 2: An Agent Updates his/her Login**

**Subject: ****BriteCore Alert: User Login Created**

Your login has been updated successfully. Your username is [new username] and your password is [new password]. Please keep this email for future reference. 

**Adoption Considerations:** The **loginupdates** advanced setting is the same as the [**Login Updates**] administrative alert on the Settings > System Wide > Administrative Alerts screen. If you add a new email address to one setting, BriteCore updates the other setting to match.

**Additional Topics of Interest:**

* [Set Up Email Correspondence]

* [Set Up Email Notifications]

* [Set Up Login Parameters]

* [Set Up Agent Logins]

## Setting Default (Separate Topic)

The default value is blank, so BriteCore doesn't trigger an email or note. To verify that BriteCore didn't create a note, complete the following steps:

1. In the Contacts module, navigate to the Notes section.

2. In the Notes section, verify BriteCore didn't create the **Email Sent: BriteCore Message: Login Created** note.

## Changing the Default (Separate Topic)

If you're not an email notification recipient, complete the following steps to verify BriteCore sent a notification email when an agent updates his/her login from the Agent Portal, or when a user's login information is updated on his/her contact in the Contacts module of the Administrative Portal:

1. In the Contacts module, navigate to the Notes section.

2. In the Notes section, verify BriteCore created the **Email Sent: BriteCore Message: Login Created** note.

