# Benefit Details

## Goal

The Benefit Details screen helps members understand a specific membership benefit, determine how it can support their business, and access or redeem it.

Its purpose is to turn membership benefits into clear, usable value rather than simply listing what is included with membership.

---

## User Questions

When members access this screen, they should be able to answer the following questions:

* What is this benefit?
* How can it help my business?
* Is this benefit available to me?
* How do I use or redeem it?
* Are there any limits or expiration dates?
* Who provides the benefit?
* Do I need to complete anything before using it?

---

## Success Criteria

A successful Benefit Details experience enables members to:

* Quickly understand the value of the benefit.
* Confirm that they are eligible to use it.
* Understand how to access or redeem it.
* Know any relevant limits or expiration dates.
* Confidently use the benefit.

---

## Sections

### 1. Benefit Overview

Provides a concise summary of the benefit.

Information includes:

* Benefit Name
* Benefit Category
* Provider
* Availability Status
* Usage Status
* Expiration Date, when applicable

Purpose:

* Help members understand the benefit at a glance.

---

### 2. Why This Benefit Is Recommended

Explains why the benefit is relevant to the member.

Examples:

* Supports your current business goal.
* Helps address an area where your business needs support.
* Included with your membership.
* Relevant to your current Recommended Actions.

Purpose:

* Make personalized benefit recommendations transparent.

---

### 3. What You Get

Explains the value and scope of the benefit.

Information may include:

* Description
* Services Included
* Number of Uses
* Benefit Value
* Limitations
* Eligibility Requirements

Purpose:

* Help members understand exactly what they receive.

---

### 4. How to Use This Benefit

Provides clear instructions for accessing or redeeming the benefit.

Information may include:

* Steps to Access
* Required Information
* Required Documents
* Redemption Code, when applicable
* Provider Instructions

Primary Action:

* Access Benefit

---

### 5. Provider Information

Provides information about the organization delivering the benefit.

Information includes:

* Provider Name
* Description
* Website
* Contact Information, when available

Purpose:

* Build confidence and make it clear who delivers the service.

---

### 6. Related Support

Displays relevant advisors, resources, events, or other benefits that may help the member.

Primary Actions:

* Find Support
* View Related Resource
* Explore Related Benefits

---

## Primary Actions

Members should be able to:

* Access or redeem the benefit.
* Review eligibility requirements.
* View provider information.
* Contact the provider when applicable.
* Save the benefit for later.
* Share the benefit.
* Find related support.

---

## Business Rules

### Availability

* Only benefits available to the member's current membership should be presented as available.
* Eligibility requirements must be clearly communicated.
* Expired benefits must not be presented as available.

### Usage

* Usage status must be displayed clearly.
* Benefits with limited usage must display remaining availability when applicable.
* Benefits that have been fully used must indicate that no additional usage is available.
* Reusable benefits must clearly communicate usage limits.

### Recommendations

* The reason for recommending a benefit should be displayed when the benefit is personalized.
* Recommendations should consider the member's active business, goals, and current context.

### External Providers

* The provider must be clearly identified when the benefit is delivered by an external organization.
* External access or redemption processes should use the official provider website or process.
* Members must be informed when they are leaving the Business Success Platform.

### Access and Security

* Benefit access must be limited to eligible members.
* Redemption codes or sensitive benefit information must only be visible to authorized members.
* Members must not be able to access another member's benefit information.

---

## Empty States

### Benefit Unavailable

Message:

"This benefit isn't currently available to you."

Primary Action:

Explore Available Benefits

---

### Benefit Expired

Message:

"This benefit has expired."

Primary Action:

Explore Available Benefits

---

### Benefit Fully Used

Message:

"You've used all available uses for this benefit."

Primary Action:

Explore Related Benefits

---

### Redemption Unavailable

Message:

"We can't access the benefit right now."

Primary Action:

Contact NYWCC Support

---

## Wireframe

```text
------------------------------------------------------------
← Back to Benefits

🎁 Free Business Legal Consultation

Legal Support
Provided by: ABC Legal Services

Available
3 consultations remaining
------------------------------------------------------------

Why This Benefit Is Recommended
------------------------------------------------------------
You're preparing for new business opportunities and legal
guidance may help you review your business documents before
moving forward.

------------------------------------------------------------

What You Get
------------------------------------------------------------
✓ 3 legal consultations
✓ 45 minutes per consultation
✓ Business-related legal guidance
✓ Available to active members

Benefit Value:
$XXX

------------------------------------------------------------

How to Use This Benefit
------------------------------------------------------------
1. Select "Access Benefit"
2. Choose an available consultation time
3. Provide your business information
4. Confirm your consultation

[Access Benefit]
------------------------------------------------------------

Provider
------------------------------------------------------------
ABC Legal Services

Specializes in supporting small businesses with legal
and compliance matters.

[Visit Provider Website ↗]
------------------------------------------------------------

Related Support
------------------------------------------------------------
Funding Consultation

[View Support]

Business Legal Resources

[View Resource]
------------------------------------------------------------
```

---

## Future Enhancements

Future versions of the Benefit Details experience may include:

* Digital benefit cards.
* One-click benefit redemption.
* Automatic usage tracking.
* Real-time benefit availability.
* Provider ratings and member feedback.
* Personalized benefit value tracking.
* Automated expiration reminders.
* Direct provider integrations.
* Benefit usage recommendations based on Business Success Intelligence (BSI).
* Post-benefit feedback and follow-up recommendations.
