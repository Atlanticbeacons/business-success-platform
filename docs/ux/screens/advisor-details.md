# Advisor Details

## Goal

The Advisor Details screen helps members understand an advisor's expertise, areas of support, jurisdiction, and availability before deciding whether to request a consultation.

Its purpose is to give members confidence that they are connecting with the right person for their specific business need.

---

## User Questions

When members access this screen, they should be able to answer the following questions:

* What can this advisor help me with?
* Is this advisor relevant to my business need?
* Does this advisor serve my jurisdiction?
* When is the advisor available?
* How do I book a consultation?
* What should I prepare before the consultation?

---

## Success Criteria

A successful Advisor Details experience enables members to:

* Understand the advisor's expertise quickly.
* Confirm that the advisor can support their business need.
* Understand the advisor's applicable jurisdiction.
* See available consultation times.
* Book a consultation confidently.
* Know what to prepare before the consultation.

---

## Sections

### 1. Advisor Overview

Provides a concise introduction to the advisor.

Information includes:

* Advisor Name
* Profile Photo
* Area of Expertise
* Jurisdiction
* Short Biography
* Languages, when applicable

Purpose:

* Help members understand who the advisor is and what they specialize in.

---

### 2. Areas of Support

Displays the business needs and topics the advisor can support.

Examples:

* Funding
* Government Contracting
* Certifications
* Business Strategy
* Marketing
* Hiring
* Operations

Purpose:

* Help members confirm that the advisor is relevant to their specific need.

---

### 3. Why This Advisor Is Recommended

Explains why the advisor has been recommended to the member.

Examples:

* Matches your funding goal.
* Supports businesses in your jurisdiction.
* Specializes in government contracting.
* Recommended based on your current business needs.

Purpose:

* Build confidence in the advisor recommendation.

---

### 4. Availability

Displays the advisor's available consultation times.

Information includes:

* Available Dates
* Available Times
* Consultation Duration
* Time Zone

Primary Action:

* Select Time

---

### 5. Consultation Preparation

Provides guidance on what the member should prepare before meeting with the advisor.

Information may include:

* Recommended Documents
* Suggested Questions
* Business Information
* Relevant Goals
* Relevant Recommended Actions

Purpose:

* Help members make the most of their consultation.

---

## Primary Actions

Members should be able to:

* Review advisor information.
* View areas of expertise.
* View available consultation times.
* Select a consultation time.
* Book a consultation.
* Cancel or return without booking.
* Access relevant preparation guidance.

---

## Business Rules

### Advisor Matching

* Advisors are matched based on their area of expertise and applicable jurisdiction.
* An advisor may support any eligible member within their jurisdiction who requires their area of expertise.
* Advisor recommendations should consider the member's active business and current need.
* Members should not be shown advisors who cannot support their jurisdiction or requested area of expertise.

### Availability

* Only available consultation times should be displayed.
* Availability must reflect the advisor's current schedule.
* Consultation times must clearly display the relevant time zone.
* A time slot cannot be booked by more than one member.

### Consultation Booking

* Members must confirm the consultation details before booking.
* The platform should display the advisor, topic, date, time, and duration before confirmation.
* A successful booking should generate a consultation record.
* The consultation should appear in My Consultations.

### Privacy and Access

* Advisors should only have access to information necessary to provide their assigned support.
* Members should not be able to access another member's advisor interactions.
* Staff permissions must follow the member, advisor, staff, and super-user role definitions established by the platform.

### External Support

* External organizations do not receive an advisor role within the platform.
* Any external support must be coordinated through authorized NYWCC administrators.

---

## Empty States

### No Available Times

Message:

"This advisor doesn't have any available consultation times right now."

Primary Action:

Explore Other Advisors

---

### Advisor Temporarily Unavailable

Message:

"This advisor is currently unavailable."

Primary Action:

Find Another Advisor

---

### No Preparation Guidance

Message:

"There's no specific preparation guidance for this consultation yet."

Primary Action:

Book Consultation

---

## Wireframe

```text
------------------------------------------------------------
← Back to Get Help

🤝 Maria Rodriguez

Funding Advisor
New York

Helping small businesses access funding and prepare
stronger funding applications.
------------------------------------------------------------

Areas of Support
------------------------------------------------------------
✓ Funding
✓ Business Finance
✓ Grant Applications
✓ Funding Readiness
------------------------------------------------------------

Why This Advisor Is Recommended
------------------------------------------------------------
Your current goal is to access funding, and Maria
specializes in helping businesses prepare for funding
opportunities.

------------------------------------------------------------

Availability
------------------------------------------------------------
Select a time

Mon Aug 17     Tue Aug 18     Wed Aug 19

10:00 AM       9:00 AM        2:00 PM
11:00 AM       10:00 AM       3:00 PM

[Select Time]
------------------------------------------------------------

Before Your Consultation
------------------------------------------------------------
Recommended preparation:

✓ Review your funding goals
✓ Prepare basic financial information
✓ Review your recommended funding opportunities

[View Preparation Guidance]
------------------------------------------------------------

Selected Consultation
------------------------------------------------------------
Advisor:
Maria Rodriguez

Topic:
Funding Consultation

Date:
August 18, 2026

Time:
10:00 AM

Duration:
45 minutes

[Confirm Consultation]
------------------------------------------------------------
```

---

## Future Enhancements

Future versions of the Advisor Details experience may include:

* AI-powered advisor matching.
* Real-time advisor availability.
* Advisor ratings and member feedback.
* In-platform messaging.
* Advisor introduction videos.
* Personalized consultation preparation.
* AI-generated consultation agendas.
* Post-consultation summaries.
* Follow-up recommendations generated by the Business Success Intelligence (BSI).
* Advisor specialization recommendations based on member progress.
