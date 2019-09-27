---
title: US3175, reinsurancePerRiskXL
layout: post
author: michelle.jones
permalink: /us3175,-reinsuranceperriskxl/
source-id: 1y_eCGvekwiZxo2BaadC-o-DORT2LeztMotDiwbVoE_Q
published: true
---
# Reinsurance Per Risk XL 

### Advanced Setting

#### Admin Alerts

**Purpose:** With the **reinsurancePerRiskXL** advanced setting in the **admin-alerts** section, administrators can choose who receives an email alert when changes are made to a claim that is being monitored for reinsurance purposes.

**Requirements:** This setting requires a **True**/**False** toggle button.

**[Setting Default]****:** This setting's default value is blank, so BriteCore does not send an email alert or create a note when changes are made to a claim that is being monitored for reinsurance purposes.

**[Changing the Default]****:** Changing the **reinsurancePerRiskXL** setting to **True **triggers BriteCore to send email alerts (*below*) to the designated recipients and create notes in the Claims module when changes are made to a claim that is being monitored for reinsurance purposes.

**Note: **Changing the setting to **False **is the same as leaving the setting blank and produces the default behavior described above.

**Subject: "Attention Required: Changes to Claim"**

Claim [Claim Number] is being monitored for reinsurance purposes. Changes have been made to the claim that may need to be reviewed. Please visit the Notes tab for this claim to review the recent changes. 

If you would like to stop receiving notifications, please uncheck the "Monitored for Reinsurance" checkbox located on the claim under the Information > Options section.

**Adoption Considerations:**

The **reinsurancePerRiskXL **advanced setting is the same as the **[Reinsurance Per Risk XL Threshold Reached]** administrative alert on the Settings > System Wide > Administrative Alerts screen. If you add a new email address to one setting, BriteCore updates the other setting to match.

**Additional Topics of Interest:**

* [Set Up Email Notifications]

* [Set Up Reinsurance]

* [Claim Reinsurance Reports]

* [Claim Reports]

* [Set Up Claim Permissions]

## Setting Default (Separate Topic)

The default value is blank, so BriteCore doesn't trigger an email or note. To verify that BriteCore didn't create a note, complete the following steps:

1. In the Claims module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore didn't create the **Changes to Claim** note.

## Changing the Default (Separate Topic)

If you're not an email notification recipient, complete the following steps to verify BriteCore sent a notification email when [briefly describe setting function]:

1. In the Claims module, navigate to the Notes tab.

2. In the All Notes section, verify BriteCore created the **Changes to Claim** note.

