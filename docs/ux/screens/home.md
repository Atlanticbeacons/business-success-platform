# Home

## Goal

The Home is the primary entry point to the Business Success Platform.

Its purpose is to help members immediately understand the current state of their business, identify the most valuable actions they should take next, and quickly access the opportunities and support that will help them achieve their goals.

Rather than acting as a dashboard, the Home serves as a personalized business briefing that guides members toward meaningful progress.
## User Questions

When members access the Home, they should be able to answer the following questions within a few seconds:

- How is my business doing today?
- What should I do next?
- What opportunities are available for me?
- Do I have any upcoming events or consultations?
- What member benefits should I use?

## Success Criteria

A successful Home experience enables members to:

- Understand the current status of their business.
- Identify their next recommended actions.
- Discover relevant opportunities.
- Feel confident about their next steps.
- Take meaningful action within a few clicks.

## Sections

The Home is organized into six primary sections that guide members from understanding their current situation to taking meaningful action.

### 1. Welcome

A personalized greeting that welcomes the member and reinforces that the platform understands who they are.

Purpose:
- Create a welcoming experience.
- Reinforce personalization.

---

### 2. Your Business Today

#### Purpose

Your Business Today is the member's personalized business briefing.

Rather than presenting dashboards, reports, or disconnected metrics, this component interprets the member's current business situation and summarizes what matters most in a simple, encouraging, and actionable way.

Its purpose is to help members quickly understand where their business stands today and feel confident about their next steps.

The component should answer three questions:

- How is my business doing?
- What is the most important thing I should know today?
- Where can I learn more?

---

#### Information

The component should include:

- A personalized business summary.
- One key business insight.
- Overall Business Health.
- Business Readiness summary.
- A clear path to explore more details.

Business Health should always be accompanied by a short explanation that helps members understand what the score means.

---

#### Primary Action

View Business Details

---

#### Business Rules

- Start with an encouraging summary before showing any metrics.
- Explain the meaning of Business Health instead of displaying a score alone.
- Highlight only one key business insight.
- Keep all content easy to scan in less than 10 seconds.
- Use positive, supportive, and human language.
- Never overwhelm members with unnecessary metrics.
---

### 3. Recommended Actions

The three highest-impact actions the member should consider next, based on their business context, goals, and current opportunities.

Purpose:
- Guide members toward meaningful progress.
- Reduce decision fatigue.
### Recommended Actions

#### Purpose

Recommended Actions is the core guidance component of the Business Success Platform.

Its purpose is to help members understand the three most valuable actions they should take next based on their business goals, readiness, current opportunities, and business context.

Rather than presenting a task list, this component acts as a trusted business advisor by prioritizing the actions with the greatest potential impact.

---

#### Information

Each recommendation should include:

- A clear action title.
- A short explanation of why the recommendation is important.
- The expected business outcome.
- A single primary call to action.
- An optional priority indicator (High, Medium, or Low).

Example:

Apply for MWBE Certification

Unlock access to new funding opportunities and government contracts.

Expected Outcome:
Increase your eligibility for public and private programs.

[Start Application]

---

#### Primary Actions

Members should be able to:

- Start the recommended action.
- Learn more about the recommendation.
- Save the recommendation for later (future enhancement).
- Mark the recommendation as completed (when applicable).

---

#### Business Rules

- Display a maximum of three recommendations.
- Always rank recommendations by business impact.
- Every recommendation must explain why it appears.
- Every recommendation must lead to a single, clear action.
- Recommendations should update automatically as the member's business evolves.
- Completed recommendations should no longer appear.
- Avoid recommending actions the member is not eligible for.
- Recommendations should encourage progress rather than overwhelm the member.

---

### 4. Opportunities for You

A personalized collection of opportunities available to the member based on their business profile, goals, and current context.

This section includes:

- Funding Opportunities
- Upcoming Events & Consultations
- Your Benefits

Purpose:
- Surface the most relevant opportunities available through the NYWCC.
- Encourage members to discover and use services that support their business growth.

## Primary Actions

The Home should encourage members to take immediate action without requiring them to navigate through multiple pages.

Primary actions include:

- Start a recommended action.
- View funding opportunities.
- Book a consultation.
- Register for an upcoming event.
- Access available member benefits.
- Switch between businesses (if applicable).

## Business Rules

The Home must always provide a clear, focused, and personalized experience that helps members understand their business and confidently decide what to do next.

### Personalization

- The Home must always reflect the currently selected business.
- All recommendations must be personalized based on the member's business context.
- Members with multiple businesses can switch businesses from the Home.

### Recommended Actions

- Display a maximum of three Recommended Actions.
- Every recommendation must include a clear explanation of why it is being shown.
- Every recommendation must include one primary call to action.
- Recommended Actions should always appear above Funding Opportunities.

### Business Summary

- Your Business Today should always be visible without scrolling on desktop.
- Business insights should prioritize clarity over detail.
- Progress should be displayed using simple visual indicators whenever possible.

### Opportunities

- Show only opportunities that are relevant to the selected business.
- Time-sensitive opportunities should be prioritized.
- Expired opportunities must never be displayed.

### Member Experience

- The Home should avoid unnecessary information.
- Every section must encourage meaningful action.
- Empty states should always guide the member toward the next step.

## Empty States

Every empty state should guide members toward meaningful progress.

Rather than simply indicating that no information is available, the platform should explain why, what it means, and what the member can do next.

### No Recommended Actions

Message:
"You're all caught up! There are no high-priority actions at the moment."

Primary Action:
Explore Funding Opportunities

---

### No Funding Opportunities

Message:
"There are no funding opportunities available based on your current business profile."

Primary Action:
Improve your Funding Readiness

---

### No Upcoming Events

Message:
"There are no upcoming events scheduled for you."

Primary Action:
Browse All Events

---

### No Scheduled Consultations

Message:
"You don't have any upcoming consultations."

Primary Action:
Book a Consultation

---

### Incomplete Business Profile

Message:
"Complete your business profile to unlock more personalized recommendations."

Primary Action:
Complete Profile

## Wireframe

```text
┌────────────────────────────────────────────────────────────┐
│ 👋 Good morning, Sergio                                    │
│ Here's your business briefing for today.                   │
└────────────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────────────┐
│ 📈 Your Business Today                                     │
│                                                            │
│ Business Health         ████████░░ 80%                     │
│ Funding Readiness       ██████░░░░ 60%                     │
│ Digital Readiness       ███████░░░ 70%                     │
│ Contract Readiness      ████░░░░░░ 40%                     │
└────────────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────────────┐
│ 🎯 Recommended Actions                                     │
│                                                            │
│ 1. Apply for MWBE Certification                            │
│ 2. Schedule a Funding Consultation                         │
│ 3. Register for the Procurement Workshop                   │
└────────────────────────────────────────────────────────────┘

┌──────────────────────┬─────────────────────────────────────┐
│ 💰 Funding           │ 📅 Upcoming Events                  │
│                      │                                     │
│ • Small Business     │ • Women in Business Summit          │
│   Grant              │ • Procurement Workshop              │
│ • Digital Growth     │                                     │
│   Fund               │                                     │
└──────────────────────┴─────────────────────────────────────┘

┌────────────────────────────────────────────────────────────┐
│ 🎁 Your Benefits                                           │
│                                                            │
│ • 3 Consulting Sessions Remaining                          │
│ • Free Legal Consultation                                  │
└────────────────────────────────────────────────────────────┘
```

### 4. Opportunities for You

A personalized collection of opportunities available to the member based on their business profile, goals, and current context.

This section includes:

- Funding Opportunities
- Upcoming Events & Consultations
- Your Benefits

Purpose:
- Surface the most relevant opportunities available through the NYWCC.
- Encourage members to discover and use services that support their business growth.
