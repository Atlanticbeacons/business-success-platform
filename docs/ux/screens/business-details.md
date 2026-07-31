# Business Details

## Goal

The Business Details screen serves as the central source of truth for a member's business.

Its purpose is to allow members to view, manage, and update the information that powers the Business Success Intelligence (BSI), ensuring that recommendations remain accurate, personalized, and relevant.

This screen also helps members understand their business profile, current goals, readiness, milestones, and overall progress.

## User Questions

When members access this screen, they should be able to answer the following questions:

- Is my business information up to date?
- What are my current business goals?
- How prepared is my business in key areas?
- What milestones have I already achieved?
- What information should I update to receive better recommendations?

## Success Criteria

A successful Business Details experience enables members to:

- Easily understand their business profile.
- Keep business information up to date.
- Review goals, milestones, and readiness.
- Identify missing information.
- Improve the quality of personalized recommendations.

## Sections

The Business Details screen is organized to help members first understand their business and then manage the information that supports personalized recommendations.

### 1. Business Overview

Provides a high-level summary of the business, including its current health, primary goal, and key insights.

Purpose:
- Help members quickly understand the current state of their business.
- Surface the most important information at a glance.

Information includes:
- Business Name
- Industry
- Business Health
- Primary Business Goal
- Business Summary
- Last Updated

Primary Action:
- View Business Progress

---

### 2. Business Goals

Displays the business's current goals and allows members to update their priorities.

Purpose:
- Ensure recommendations remain aligned with the business's objectives.

Information includes:
- Primary Goal
- Secondary Goals
- Goal Status

Primary Actions:
- Edit Goals
- Add Goal

---

### 3. Business Readiness

Shows how prepared the business is across key business dimensions.

Purpose:
- Help members understand where they are ready to move forward and where improvements are needed.

Information includes:
- Funding Readiness
- Digital Readiness
- Hiring Readiness
- Government Contracting Readiness

Primary Action:
- View Readiness Details

---

### 4. Business Milestones

Displays important achievements completed by the business.

Purpose:
- Help members visualize progress and identify the next milestones.

Information includes:
- Completed Milestones
- Upcoming Milestones
- Recently Completed Milestones

Primary Action:
- View All Milestones

---

### 5. Business Profile

Contains the business's core information.

Purpose:
- Allow members to manage the information that powers the Business Success Intelligence (BSI).

Information includes:
- Business Name
- Industry
- Address
- Business Size
- Year Founded
- Website
- Contact Information

Primary Actions:
- Edit Business Information

---

### 6. Certifications & Documents

Displays certifications, licenses, and important business documents.

Purpose:
- Keep essential business credentials organized and available for future opportunities.

Information includes:
- Active Certifications
- Uploaded Documents
- Expiration Dates

Primary Actions:
- Upload Document
- Add Certification
- Update Information

## Primary Actions

Members should be able to:

- View Business Progress.
- Edit Business Information.
- Update Business Goals.
- Review Business Readiness.
- View Business Milestones.
- Upload or manage business documents.
- Add or update certifications.

## Business Rules

The Business Details screen is the authoritative source of information for each business.

### Business Information

- Every business maintains its own independent profile.
- Changes to business information should immediately update the Business Success Intelligence (BSI).
- Members can only edit businesses they own.

---

### Business Goals

- Every business must have one primary goal.
- Businesses may have multiple secondary goals.
- Goal changes should automatically influence future recommendations.

---

### Business Readiness

- Readiness is calculated by the platform and cannot be edited directly.
- Members improve readiness by completing recommended actions and milestones.
- Every readiness score should include a clear explanation.

---

### Business Milestones

- Completed milestones become part of the business history.
- Milestones should never be deleted.
- New milestones may unlock recommendations and opportunities.

---

### Certifications & Documents

- Members may upload supporting documentation.
- Expired certifications should be clearly identified.
- Documents should be securely stored and accessible only to authorized users.

## Empty States

### No Business Goals

Message:

"No business goals have been defined yet."

Primary Action:

Set Your First Goal

---

### No Milestones

Message:

"You haven't reached any business milestones yet."

Primary Action:

Explore Recommended Actions

---

### No Certifications

Message:

"No certifications have been added."

Primary Action:

Add Certification

---

### No Documents

Message:

"You haven't uploaded any business documents yet."

Primary Action:

Upload Document

## Wireframe

```text
------------------------------------------------------------
🏢 ABC Bakery

Helping businesses grow with confidence.
------------------------------------------------------------

Business Overview
------------------------------------------------------------
Business Health: 82%

Primary Goal:
Access Funding

Business Summary:
Your business is progressing well and is ready to pursue new
funding opportunities.

[View Business Progress]
------------------------------------------------------------

Business Goals
------------------------------------------------------------
Primary Goal:
Access Funding

Secondary Goals:
• Improve Digital Presence
• Hire First Employee

[Edit Goals]
------------------------------------------------------------

Business Readiness
------------------------------------------------------------
Funding                 ████████░░ 80%

Digital                 ██████░░░░ 60%

Hiring                  █████░░░░░ 50%

Government Contracting  ███░░░░░░░ 30%

[View Readiness Details]
------------------------------------------------------------

Business Milestones
------------------------------------------------------------
✓ Business Registered

✓ Website Launched

✓ Business Bank Account

Next:
MWBE Certification

[View All]
------------------------------------------------------------

Business Profile

[Edit Business Information]

------------------------------------------------------------

Certifications & Documents

MWBE Certification
Not Started

Business License
Uploaded

Insurance Certificate
Uploaded

[Manage Documents]
```

## Future Enhancements

Future versions of the Business Details experience may include:

- AI-generated business profile summaries.
- Readiness improvement plans.
- Business timeline visualization.
- Automatic milestone detection.
- Integration with government and certification databases.
- Document expiration reminders.
- Business benchmarking against similar organizations.
- Collaboration with advisors through shared notes and recommendations.
