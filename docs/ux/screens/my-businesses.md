# My Businesses

## Goal

The My Businesses screen allows members to manage all businesses associated with their NYWCC membership.

Its purpose is to provide a clear overview of each business, allow members to switch between businesses, and manage the information that powers the Business Success Intelligence (BSI).

Every business should have its own profile, goals, progress, and personalized recommendations.

## User Questions

When members access this screen, they should be able to answer the following questions:

- Which businesses do I currently manage?
- Which business is currently active?
- How is each business progressing?
- Can I edit my business information?
- Can I add another business?

## Success Criteria

A successful My Businesses experience enables members to:

- View all their businesses in one place.
- Quickly switch between businesses.
- Understand the status of each business.
- Update business information easily.
- Add new businesses when eligible.

## Sections

The My Businesses screen is organized around the member's active business while providing easy access to all other businesses associated with their account.

### 1. Current Business

Displays the business currently selected across the platform.

Purpose:
- Clearly indicate which business is active.
- Provide a quick summary of its current status.
- Allow members to access and edit business information.

Information includes:
- Business Name
- Industry
- Business Health
- Business Readiness
- Primary Goal
- Current Status

Primary Actions:
- View Business Details
- Edit Business
- Switch Business

---

### 2. Other Businesses

Displays all additional businesses associated with the member.

Purpose:
- Provide visibility into every business.
- Allow members to quickly change the active business.

Information includes:
- Business Name
- Industry
- Business Health
- Business Status

Primary Action:
- Switch to this Business

---

### 3. Add a Business

Allows eligible members to register an additional business.

Purpose:
- Support members who manage multiple businesses.
- Guide members through the onboarding process for a new business.

Primary Action:
- Add New Business

## Primary Actions

Members should be able to:

- View Business Details.
- Edit Business Information.
- Switch the Active Business.
- Add a New Business (up to three businesses per member).
- Archive an inactive business.

## Business Rules

The My Businesses screen must always maintain a clear relationship between the member and their active business.

### Active Business

- A member can have a maximum of three businesses.
- Only one business can be active at a time.
- The active business determines the context for the entire platform.

### Business Information

- Every business has its own profile.
- Every business has its own Business Health.
- Every business has its own Business Readiness.
- Every business has its own Goals and Milestones.

### Switching Businesses

- Switching the active business updates all personalized information across the platform.
- The Home, Recommended Actions, Funding, Events, Benefits, and Resources must refresh automatically.

### Business Management

- Members may edit their business information at any time.
- Businesses cannot be permanently deleted by members.
- Archived businesses remain available for administrators.

## Empty States

### No Businesses

Message:

"Let's get started by adding your first business."

Primary Action:

Add Your First Business

---

### Maximum Businesses Reached

Message:

"You've reached the maximum number of businesses allowed under your membership."

Primary Action:

Contact NYWCC Support

---

### No Active Business

Message:

"Select a business to continue using the platform."

Primary Action:

Choose Business

## Wireframe

```text
----------------------------------------------------------
🏢 My Businesses
Manage the businesses associated with your membership.
----------------------------------------------------------

⭐ Current Business
----------------------------------------------------------
ABC Bakery

Industry:
Food & Beverage

Business Health
82%

Business Readiness
Funding: 80%
Digital: 70%

Primary Goal
Access Funding

[View Details]   [Edit]   [Switch]
----------------------------------------------------------

Other Businesses

----------------------------------------------------------
XYZ Consulting

Professional Services

Business Health
74%

[Switch]
----------------------------------------------------------

----------------------------------------------------------
Creative Studio

Marketing

Business Health
68%

[Switch]
----------------------------------------------------------

➕ Add New Business
```

## Future Enhancements

Future versions of the My Businesses experience may include:

- Business portfolio overview.
- Compare progress across businesses.
- Shared opportunities between businesses.
- AI-generated business summaries.
- Business collaboration with partners or team members.
- Import business information from external systems.
- Business timeline showing milestones and achievements.
