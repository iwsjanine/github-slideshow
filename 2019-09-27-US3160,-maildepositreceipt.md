---
title: US3160, maildepositreceipt
layout: post
author: michelle.jones
permalink: /us3160,-maildepositreceipt/
source-id: 1Xdax3AXftqlXNNE_hfTMwwFQavaOe1iSb_PW6t4s89k
published: true
---
# Mail Deposit Receipt

### Advanced Setting

#### Admin Alerts

**Purpose:** With the **maildepositreceipt** advanced setting in the **admin-alerts** section, administrators can choose who receives an email alert when a deposit receipt is generated in one of two ways:

* A user clicks **Print Deposit Receipt** in Policies > Payments > Daily Cash Receipt in the Administrative portal.

* A deposit receipt displaying a batch's entered payments is generated. 

**Requirements:** This setting requires a list of comma-separated email addresses.

**[Setting Default]****:** This setting's default value is blank, so BriteCore does not send an email alert or create a note when a user clicks **Print Deposit Receipt** in Policies > Payments > Daily Cash Receipt in the Administrative portal or when a deposit receipt displaying a batch's entered payments is generated. 

**[Changing the Default]****:** Adding recipients' email addresse(s) to **maildepositreceipt** triggers BriteCore to send email alerts (*below*) to the designated recipients and create notes in the Policies module when a deposit receipt is generated. 

**Subject: ****Deposit Receipt Generated**

A deposit receipt has been generated in the amount of [Payment Amount].

**Adoption Considerations:** The **maildepositreceipt** advanced setting is the same as the **[Deposit Receipt Generated]** administrative alert on the Settings > System Wide > Administrative Alerts screen. If you add a new email address to one setting, BriteCore updates the other setting to match.

**Additional Topics of Interest:**

* [Verify Mail Deposit Receipt Email was not Sent] 

* [VerifyMail Deposit Receipt Email was Sent]

## Setting Default (Separate Topic)

The default value is blank, so BriteCore doesn't trigger an email or note. To verify that BriteCore didn't create a note, complete the following steps:

1. In the Policies module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore didn't create the **Deposit Receipt**** Gener****ated** note.

## Changing the Default (Separate Topic)

If you're not an email notification recipient, complete the following steps to verify BriteCore sent a notification email when a deposit receipt is generated in one of two ways mentioned above:

1. In the Policies module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore created the **Deposit Receipt**** Generated** note.

