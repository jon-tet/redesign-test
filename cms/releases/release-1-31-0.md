---
f_release-date: '2024-09-20T00:00:00.000Z'
f_version: 1.31.0
title: Sprint 53 - 20 Sep, 2024
slug: release-1-31-0
updated-on: '2024-09-20T16:41:54.384Z'
created-on: '2024-09-20T16:39:29.555Z'
published-on: '2024-09-20T16:42:05.476Z'
f_bug-fixes: "**Inactive Status Color:** \_The inactive status color has been changed to red across the product for consistency.\n\n**Remediation Status Update:** \_The status will now display as “Risk Accepted” if a created remediation is deleted and an expiry date exists, instead of changing to “Not Started” as it did previously.\n\n‍"
f_improvements: "**Sticky Table Headers:** \_Table headers for the Remediation, Events, and Risk pages are now sticky at the top during page scroll, improving user experience and navigation.\n\n**Dashboard Loading Experience:** \_The dashboard will initially load widgets with skeleton screens and will re-render them once the data is ready, providing a smoother user experience.\n\n**Consistent Naming:** \_The \"Source\" and \"Service Name\" fields have been renamed to \"Cybersecurity Domain\" and standardized throughout the product.\n\n**Auto-Submission for One-Time Passwords (OTP):** \_The form will now auto-submit upon entering the complete OTP, and the entered code will automatically clear when the \"Resend New Code\" button is clicked.\n\n‍"
layout: '[releases].html'
tags: releases
---

**User Management Page:**  Added a User Management page with integration to Microsoft Entra (Azure AD), streamlining user administration. This page provides visibility into key fields such as Asset, Tool, Last Check-in, Last Login User, IP Address, MAC Address, and Status. With this information, customers can easily identify users who have not logged in for an extended period or those who are no longer employed but still have access, enhancing security and management oversight.

**Audit Logs:**  A new Audit Logs tab has been added to the Company Management page, providing a comprehensive history of user activity for security and compliance purposes. This feature enhances accountability by tracking key actions such as inviting users, editing user details, and enabling/disabling MFA.
