---
title: Sprint 48 - 11 July, 2024
slug: release-1-26-0
updated-on: '2024-07-26T08:27:46.987Z'
created-on: '2024-07-11T15:35:22.316Z'
published-on: '2024-07-26T12:38:56.113Z'
f_bug-fixes: "**Remediation Creation Issue:** \_Resolved an issue where users were unable to create remediation for assets if the old remediation was deleted, enabling seamless remediation management.\n\n**Bulk Risk Operation Fix:** \_Fixed an issue preventing users from performing bulk risk operations across different pages, allowing users to create, accept, and create remediation for risks across pages seamlessly.\n\n**Location Activation/Deactivation Error:** \_Fixed an error where activating or deactivating a location without facilities resulted in an error, ensuring smooth functionality.\n\n**Pagination Navigation Fix:** \_Fixed an issue where actions performed on pages other than page 1 would navigate the user back to page 1, ensuring users remain on the same page after any action on risks."
f_improvements: "**Sorted Display of Risk Data:** \_Risk data will now be displayed in sorted order: by Criticality (High, Medium, Low), Status (Not Started, In Remediation, Risk Accepted, Resolved), and then by Discovered Date (descending order), improving usability and clarity.\n\n**Dashboard Risk and Remediation Counts:** \_Added total Risk and Remediation counts on the Dashboard for quick overview and management insights.\n\n**Compliance Search Enhancement:** \_Enhanced compliance search capabilities by allowing search by question number and question text, facilitating easier navigation and audit readiness.\n\n**Reset Password Error Messaging:** \_Improved the error messaging for the Reset Password link to display proper messages upon expiry, enhancing user experience and clarity."
f_release-date: '2024-07-11T00:00:00.000Z'
f_version: 1.26.0
layout: '[releases].html'
tags: releases
---

**Microsoft Defender Integration:**  Integrated Microsoft Defender into the Events and Tools pages, enhancing security monitoring capabilities directly within the Trust Portal.

**Auto-Populate License Utilization Data:**  Automated the population of license utilization data for Darktrace, improving accuracy and efficiency in license management.

**Enhanced Risk Filtering:**  Users can now filter Risks by Discovered Date, enabling more precise risk management and analysis.
