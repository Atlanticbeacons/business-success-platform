# Get Help

## Goal

The Get Help screen connects members with the right support, expertise, and guidance based on their business needs.

Its purpose is to help members identify the type of support they need, find relevant advisors or services, and take the next step toward resolving a business challenge.

The experience should make asking for help feel simple, accessible, and relevant to the member's current business context.

## User Questions

When members access this screen, they should be able to answer the following questions:

- What kind of help can I get?
- Who can help me with my specific need?
- Can I speak with an advisor?
- How do I book a consultation?
- What other support options are available?

## Success Criteria

A successful Get Help experience enables members to:

- Quickly identify the type of support they need.
- Find advisors or services relevant to their business needs.
- Understand what each advisor or service can help with.
- Book a consultation easily when appropriate.
- Feel confident that they are contacting the right person or service.

## Sections

The Get Help screen is organized around the member's business need rather than around individual advisors.

### 1. Help Overview

Provides a simple entry point to the different types of support available to members.

Purpose:
- Help members identify what kind of support they need.
- Make the available support options easy to understand.

Examples:
- Funding
- Government Contracting
- Certifications
- Business Strategy
- Marketing
- Legal
- Hiring
- Operations

Primary Action:
- Find Help

---

### 2. Recommended Support

Displays support options that are relevant to the member's current business context and needs.

Purpose:
- Connect members with the most relevant support without requiring them to search through all available options.

Information includes:
- Support Type
- Why it is recommended
- Relevant Business Goal or Challenge
- Recommended Advisor or Service

Primary Action:
- Get Support

---

### 3. Advisors

Allows members to discover advisors based on their area of expertise and jurisdiction.

Purpose:
- Connect members with qualified advisors who can support their specific business needs.

Information includes:
- Advisor Name
- Area of Expertise
- Jurisdiction
- Areas They Can Support
- Availability

Primary Actions:
- View Advisor
- Book Consultation

---

### 4. My Consultations

Displays the member's upcoming and previous consultations.

Purpose:
- Give members visibility into their scheduled support.
- Make it easy to manage upcoming consultations.

Information includes:
- Advisor
- Consultation Topic
- Date and Time
- Status

Primary Actions:
- View Consultation
- Reschedule
- Cancel

## Primary Actions

Members should be able to:

- Find support based on their business need.
- View recommended support options.
- Browse advisors by area of expertise.
- View advisor details.
- Book a consultation.
- View upcoming consultations.
- Reschedule a consultation.
- Cancel a consultation.

## Business Rules

The Get Help experience must make it easy for members to find the right support while maintaining clear roles and permissions across the platform.

### Support Matching

- Support should be recommended based on the member's business needs, goals, readiness, and current context.
- Members should be able to browse support options independently.
- Every recommended support option should explain why it is relevant.

### Advisors

- Advisors are assigned to specific areas of expertise and jurisdictions.
- An advisor may support any member within their applicable jurisdiction who requires their area of expertise.
- Members do not need to select an advisor before identifying their business need.
- Advisor availability should be displayed when scheduling a consultation.

### Consultations

- Members can book consultations with eligible advisors.
- Members can view, reschedule, or cancel their consultations.
- Consultation details must include the advisor, topic, date, time, and status.

### Roles and Permissions

- Advisors can access only the information and functions required to provide their assigned support.
- Staff users have administrative permissions according to their assigned role.
- Only authorized staff users may have super-user permissions.
- External partners do not have a platform role.
- External support is coordinated through authorized NYWCC administrators.

### Personalization

- Recommended support should reflect the currently selected business.
- Changing the active business should update recommended support accordingly.

## Empty States

### No Recommended Support

Message:

"We don't have a specific recommendation for your business right now."

Primary Action:

Explore All Support

---

### No Advisors Available

Message:

"There are no advisors currently available for this type of support."

Primary Action:

Explore Other Support

---

### No Upcoming Consultations

Message:

"You don't have any upcoming consultations."

Primary Action:

Find an Advisor

---

### No Consultation History

Message:

"You haven't had any consultations yet."

Primary Action:

Find Help

## Wireframe

```text
------------------------------------------------------------
🤝 Get Help

Find the right support for your business.
------------------------------------------------------------

What do you need help with?
------------------------------------------------------------
[ Funding ]        [ Government Contracting ]

[ Certifications ] [ Marketing ]

[ Hiring ]         [ Business Strategy ]

[ Legal ]          [ Operations ]
------------------------------------------------------------

Recommended Support
------------------------------------------------------------
Funding Consultation

Why recommended:
You're working toward your funding goal and your
Funding Readiness is currently 75%.

Recommended Advisor:
Maria Rodriguez
Funding Advisor

[View Advisor]    [Book Consultation]
------------------------------------------------------------

Advisors
------------------------------------------------------------
Maria Rodriguez
Funding

John Smith
Government Contracting

Ana Lopez
Business Strategy

[View All Advisors]
------------------------------------------------------------

My Consultations
------------------------------------------------------------
Upcoming

Funding Consultation
Maria Rodriguez
Aug 18 · 10:00 AM

[View Consultation]
------------------------------------------------------------

## Future Enhancements

Future versions of the Get Help experience may include:

- AI-powered support matching.
- Personalized advisor recommendations based on business needs.
- Advisor availability in real time.
- In-platform messaging between members and advisors.
- Automated consultation preparation.
- AI-generated summaries after consultations.
- Advisor recommendations triggered by Business Success Intelligence (BSI).
- Follow-up recommendations after a consultation.
