# Funding

## Goal

The Funding screen helps members discover, understand, and access funding opportunities that are relevant to their business.

Rather than presenting a directory of grants and programs, the Funding experience provides personalized guidance based on the member's business profile, goals, readiness, and eligibility.

Its purpose is to help members confidently identify the right funding opportunities and understand how to become eligible for more.

## User Questions

When members access this screen, they should be able to answer the following questions:

- Which funding opportunities are available to my business?
- Which opportunities am I eligible for today?
- What should I do to unlock additional funding?
- Which funding opportunities are closing soon?
- How do I apply?

## Success Criteria

A successful Funding experience enables members to:

- Quickly identify relevant funding opportunities.
- Understand why opportunities are recommended.
- Improve their funding readiness.
- Access official application processes with confidence.
- Track funding opportunities that matter to their business.

## Sections

The Funding screen is organized to help members understand their funding position before exploring available opportunities.

### 1. Funding Overview

Provides a personalized summary of the member's funding situation.

Purpose:
- Explain current funding eligibility.
- Highlight opportunities available today.
- Identify actions that unlock additional funding.

Information includes:
- Eligible Opportunities
- Potential Opportunities
- Funding Readiness
- Upcoming Deadlines

Primary Action:
- View Funding Readiness

---

### 2. Recommended Opportunities

Displays the funding opportunities with the highest relevance and potential impact.

Purpose:
- Help members focus on the opportunities that matter most.

Information includes:
- Opportunity Name
- Why it is recommended
- Deadline
- Eligibility Status

Primary Action:
- View Opportunity Details

---

### 3. All Opportunities

Allows members to browse and filter all available funding programs.

Purpose:
- Support discovery beyond personalized recommendations.

Primary Actions:
- Search
- Filter
- Sort

## Primary Actions

Members should be able to:

- View Funding Opportunity Details.
- Search funding opportunities.
- Filter opportunities.
- Save an opportunity for later.
- Share an opportunity.
- Access the official application website.
- Book a funding consultation.

## Business Rules

The Funding experience must provide personalized, accurate, and actionable funding recommendations.

### Recommendations

- Recommended Opportunities must always appear before All Opportunities.
- Recommendations should be based on the member's active business.
- Every recommendation must explain why it appears.

---

### Eligibility

- Eligibility should be clearly displayed.
- Opportunities should indicate whether the member is:
  - Eligible
  - Partially Eligible
  - Not Yet Eligible

- Opportunities that are not yet eligible should explain what is required to qualify.

---

### Deadlines

- Funding opportunities nearing their application deadline should be prioritized.
- Expired opportunities must never be displayed as active.

---

### Applications

- Applications managed by external organizations must redirect members to the official application website.
- The platform should clearly communicate when members are leaving the Business Success Platform.

---

### Funding Readiness

- Funding Readiness should be calculated automatically.
- Members cannot edit Funding Readiness directly.
- Recommended Actions should help members improve their Funding Readiness over time.

## Empty States

### No Recommended Opportunities

Message:

"There are no funding opportunities recommended for your business at this time."

Primary Action:

Improve Your Funding Readiness

---

### No Search Results

Message:

"No funding opportunities match your search criteria."

Primary Action:

Clear Filters

---

### No Eligible Opportunities

Message:

"Your business isn't currently eligible for any funding opportunities."

Primary Action:

View Funding Readiness

## Wireframe

```text
------------------------------------------------------------
💰 Funding

Find funding opportunities tailored to your business.
------------------------------------------------------------

Funding Overview
------------------------------------------------------------
Eligible Opportunities: 4

Potential Opportunities: 8

Funding Readiness: 75%

Next Deadline:
Small Business Growth Grant
Closes in 12 days

[View Funding Readiness]
------------------------------------------------------------

Recommended Opportunities
------------------------------------------------------------
Small Business Growth Grant

Eligible

Why recommended:
Matches your business profile and funding goals.

Deadline:
12 days remaining

[View Details]
------------------------------------------------------------

Women Entrepreneur Grant

Partially Eligible

Complete MWBE Certification to qualify.

[View Details]
------------------------------------------------------------

All Opportunities

Search

Filter

Sort

Opportunity List...
```

## Future Enhancements

Future versions of the Funding experience may include:

- AI-powered funding recommendations.
- Funding application tracking.
- Personalized funding calendars.
- Automatic deadline reminders.
- Saved funding opportunities.
- Funding success predictions based on business readiness.
- Integration with government funding databases.
- Advisor recommendations for complex applications.
