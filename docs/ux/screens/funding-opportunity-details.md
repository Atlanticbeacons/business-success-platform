# Funding Opportunity Details

## Goal

The Funding Opportunity Details screen helps members understand a specific funding opportunity, determine whether it is relevant to their business, prepare for the application, and access the official application process.

Its purpose is to turn a funding opportunity from an abstract listing into a clear and actionable next step.

---

## User Questions

When members access this screen, they should be able to answer the following questions:

* What is this funding opportunity?
* Why is it relevant to my business?
* Am I eligible?
* What do I need to apply?
* When is the deadline?
* Where do I apply?
* Can someone help me prepare?

---

## Success Criteria

A successful Funding Opportunity Details experience enables members to:

* Quickly understand the opportunity.
* Clearly understand their eligibility status.
* Know what they need before applying.
* Understand the application deadline.
* Access the official application process confidently.
* Get support when they need additional guidance.

---

## Sections

### 1. Opportunity Overview

Provides a concise summary of the funding opportunity.

Information includes:

* Opportunity Name
* Funding Amount or Range
* Provider
* Opportunity Type
* Application Deadline
* Status

Purpose:

* Help members understand the opportunity at a glance.

---

### 2. Why This Is Recommended

Explains why the opportunity is relevant to the member's business.

Examples:

* Matches your funding goal.
* Your business meets the primary eligibility requirements.
* Your industry is included in the program.
* Your business is located within the eligible jurisdiction.

Purpose:

* Build confidence in the recommendation.
* Explain the connection between the opportunity and the member's business.

---

### 3. Eligibility

Provides a clear summary of eligibility requirements and the member's current status.

Eligibility status may include:

* Eligible
* Partially Eligible
* Not Yet Eligible
* Eligibility Unknown

Information includes:

* Requirements met
* Requirements still needed
* Requirements that cannot currently be verified

Primary Action:

* View Eligibility Details

---

### 4. Application Preparation

Helps members understand what they should prepare before applying.

Information may include:

* Required Documents
* Financial Information
* Certifications
* Business Information
* Application Steps

Primary Actions:

* View Preparation Checklist
* Book a Consultation

---

### 5. Application

Provides access to the official application process.

Information includes:

* Application Provider
* Official Application Website
* Application Deadline
* Application Method

Primary Action:

* Go to Official Application

The member must be clearly informed that the application will continue on an external website.

---

### 6. Related Support

Provides relevant support options that can help the member prepare.

Examples:

* Funding Advisor
* Business Advisor
* Certification Support
* Financial Guidance

Primary Actions:

* Find an Advisor
* Book Consultation

---

## Primary Actions

Members should be able to:

* Review eligibility.
* View the preparation checklist.
* Book a consultation.
* Go to the official application website.
* Save the opportunity.
* Share the opportunity.

---

## Business Rules

### Eligibility

* Eligibility status must be based on the most reliable information available.
* The platform must distinguish between verified eligibility and estimated eligibility.
* Requirements that cannot be verified should be clearly identified.
* The platform must never guarantee that a member will receive funding.

### Recommendations

* The reason for recommendation must be visible.
* Recommendation logic should use the member's active business context.
* If the member's business circumstances change, eligibility and recommendation status should be recalculated.

### Deadlines

* The official application deadline must be displayed when available.
* Deadlines should indicate the relevant time zone when necessary.
* Expired opportunities must not be presented as active application opportunities.

### External Applications

* The platform does not replace external government or organization application systems.
* Members must be clearly informed when they are leaving the platform.
* Application links must point to the official application source.
* The platform should never redirect members to an unofficial application provider.

### Advisors

* Advisors should only be recommended when their expertise is relevant to the opportunity or preparation need.
* Members can access advisor support without being required to book a consultation.

---

## Empty States

### Eligibility Cannot Be Determined

Message:

"We don't have enough information to determine your eligibility yet."

Primary Action:

Complete Business Information

---

### Preparation Information Unavailable

Message:

"We don't have a preparation checklist for this opportunity yet."

Primary Action:

Visit Official Program Website

---

### Application Link Unavailable

Message:

"The official application link isn't available right now."

Primary Action:

Contact NYWCC Support

---

## Wireframe

```text
------------------------------------------------------------
← Back to Funding

💰 Small Business Growth Grant

Up to $25,000
NYC Small Business Services

Application Deadline
September 30, 2026

[Eligible]
------------------------------------------------------------

Why This Is Recommended
------------------------------------------------------------
This opportunity matches your funding goal and your
business currently meets the main eligibility criteria.

✓ Funding goal aligned
✓ Business location eligible
✓ Industry eligible
------------------------------------------------------------

Eligibility
------------------------------------------------------------
Your eligibility

✓ Business location
✓ Business type
✓ Time in operation

○ MWBE Certification

Complete this requirement to strengthen your application.

[View Eligibility Details]
------------------------------------------------------------

Application Preparation
------------------------------------------------------------
Before applying, make sure you have:

□ Business registration
□ Financial statements
□ Tax documentation
□ Business plan

[View Preparation Checklist]

Need help preparing?

[Book a Consultation]
------------------------------------------------------------

Application
------------------------------------------------------------
Applications are completed on the official NYC SBS website.

Deadline:
September 30, 2026

[Go to Official Application ↗]
------------------------------------------------------------

Related Support
------------------------------------------------------------
Funding Advisor

Maria Rodriguez

[View Advisor] [Book Consultation]
------------------------------------------------------------
```

---

## Future Enhancements

Future versions of the Funding Opportunity Details experience may include:

* Personalized application readiness scores.
* AI-powered eligibility explanations.
* Interactive application preparation checklists.
* Document readiness validation.
* Application progress tracking.
* Deadline reminders.
* Personalized advisor recommendations.
* AI assistance with application preparation.
* Integration with official government application systems where technically and legally appropriate.
* Funding outcome tracking.
