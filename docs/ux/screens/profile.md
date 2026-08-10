# Profile

## Goal

The Profile screen allows members to manage their personal information, membership information, account preferences, and communication settings.

Its purpose is to give members control over their personal account while keeping business-specific information within the relevant business profile.

---

## User Questions

When members access this screen, they should be able to answer the following questions:

* Is my personal information up to date?
* What membership do I have?
* What are my account and communication preferences?
* How can I manage my account?
* How can I get help with my membership or account?

---

## Success Criteria

A successful Profile experience enables members to:

* Easily review and update personal information.
* Understand their current membership.
* Manage account and communication preferences.
* Access membership-related information.
* Find support when they have account or membership questions.

---

## Sections

### 1. Personal Information

Allows members to view and manage their personal information.

Information includes:

* Full Name
* Email Address
* Phone Number
* Preferred Language
* Profile Photo

Primary Action:

* Edit Personal Information

---

### 2. Membership

Provides information about the member's current NYWCC membership.

Information includes:

* Membership Status
* Membership Type
* Membership Start Date
* Membership Renewal Date
* Member Since

Primary Actions:

* View Membership Details
* Get Membership Support

---

### 3. Account Preferences

Allows members to manage their account and communication preferences.

Information includes:

* Email Notifications
* Event Notifications
* Funding Alerts
* Recommendation Notifications
* Language Preferences

Primary Action:

* Update Preferences

---

### 4. Security

Provides access to account security settings.

Primary Actions:

* Change Password
* Manage Login Methods
* Sign Out

---

### 5. Support

Provides access to help for account or membership-related issues.

Primary Actions:

* Contact NYWCC Support
* View Help Center

---

## Primary Actions

Members should be able to:

* View personal information.
* Edit personal information.
* View membership details.
* Manage notification preferences.
* Manage account security.
* Contact support.
* Sign out.

---

## Business Rules

### Personal Information

* Members can edit their own personal information.
* Personal information must be kept separate from business information.
* Changes to personal information should not automatically modify business profiles unless explicitly required.

### Membership

* Membership information should reflect the member's current membership status.
* Members cannot modify membership status directly.
* Membership-related changes should be handled through authorized NYWCC processes.

### Notifications

* Members can control eligible communication preferences.
* Critical account or security communications cannot be disabled.

### Security

* Sensitive account changes may require additional authentication.
* Members must be able to securely sign out of the platform.

### Support

* Account and membership issues should be routed through authorized NYWCC support channels.
* Members should not be given administrative permissions through the Profile experience.

---

## Empty States

### Incomplete Personal Information

Message:

"Complete your profile to make sure we have the right information to support you."

Primary Action:

Complete Profile

---

### Membership Information Unavailable

Message:

"We couldn't display your membership information right now."

Primary Action:

Contact NYWCC Support

---

### No Notification Preferences

Message:

"Your notification preferences haven't been configured yet."

Primary Action:

Set Preferences

---

## Wireframe

```text
------------------------------------------------------------
👤 Profile

Manage your personal information, membership, and preferences.
------------------------------------------------------------

Personal Information
------------------------------------------------------------
Sergio Hernández

sergio@example.com
+1 555 555 5555

Preferred Language:
English

[Edit Personal Information]
------------------------------------------------------------

Membership
------------------------------------------------------------
Membership Status
Active

Membership Type
Business Member

Member Since
2026

[View Membership Details]
------------------------------------------------------------

Account Preferences
------------------------------------------------------------
Email Notifications        ON
Event Notifications        ON
Funding Alerts              ON
Recommendation Alerts      ON

[Update Preferences]
------------------------------------------------------------

Security
------------------------------------------------------------
[Change Password]

[Manage Login Methods]

[Sign Out]
------------------------------------------------------------

Support
------------------------------------------------------------
Need help with your account or membership?

[Contact NYWCC Support]
[Visit Help Center]
------------------------------------------------------------
```

---

## Future Enhancements

Future versions of the Profile experience may include:

* Two-factor authentication management.
* Login activity and security history.
* Connected account management.
* Personalized communication preferences.
* Membership documents and certificates.
* Membership renewal management.
* Digital membership card.
* Account activity history.
* Privacy and data management controls.
