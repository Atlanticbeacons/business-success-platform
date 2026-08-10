# Events

## Goal

The Events screen helps members discover and participate in events that can support their business growth, learning, networking, and access to opportunities.

Its purpose is to surface relevant events based on the member's business context and make it easy to understand, register for, and manage upcoming events.

## User Questions

When members access this screen, they should be able to answer the following questions:

- What events are relevant to my business?
- What events are happening soon?
- What will I gain by attending?
- When and where is the event?
- How do I register?

## Success Criteria

A successful Events experience enables members to:

- Quickly discover relevant events.
- Understand why an event may be valuable to their business.
- See important event details at a glance.
- Register easily.
- Keep track of upcoming events they have registered for.

## Sections

The Events screen is organized to help members discover relevant events, understand their value, and manage their participation.

### 1. Recommended Events

Displays events that are most relevant to the member's business context, goals, and interests.

Purpose:
- Surface events that can provide meaningful value to the member.
- Reduce the need to search through the entire event catalog.

Information includes:
- Event Name
- Date and Time
- Location or Online
- Event Type
- Why it is recommended

Primary Action:
- View Event

---

### 2. Upcoming Events

Displays upcoming events available to the member.

Purpose:
- Help members discover and plan for upcoming opportunities.

Information includes:
- Event Name
- Date and Time
- Location or Online
- Registration Status

Primary Actions:
- View Event
- Register

---

### 3. My Events

Displays events the member has registered for.

Purpose:
- Give members a clear view of their upcoming commitments.
- Make event management easy.

Information includes:
- Event Name
- Date and Time
- Location or Online
- Registration Status

Primary Actions:
- View Event
- Cancel Registration

---

### 4. All Events

Allows members to browse the complete event catalog.

Purpose:
- Support discovery beyond personalized recommendations.

Primary Actions:
- Search
- Filter
- Sort

## Primary Actions

Members should be able to:

- View event details.
- Register for an event.
- Cancel an event registration.
- Search events.
- Filter events by category, date, format, or location.
- Sort events.
- Add a registered event to their calendar.

## Business Rules

The Events experience must help members discover relevant events while making registration and event management simple and reliable.

### Recommendations

- Recommended Events must be based on the member's active business, goals, interests, and relevant business context.
- Every recommended event should explain why it is relevant when appropriate.
- Events that are no longer relevant should not be prioritized.

### Event Information

- Every event must display its date, time, format, and location when applicable.
- Online events must clearly indicate how members will access them.
- Events with limited capacity should display availability when possible.
- Past events must not appear as upcoming events.

### Registration

- Members can register for eligible events directly from the platform when registration is managed by NYWCC.
- When registration is managed by an external organization, the member should be clearly redirected to the official registration process.
- Registration status must be visible to the member.
- Members should not be able to register twice for the same event.

### My Events

- Registered events should appear in My Events.
- Members should be able to cancel their registration when cancellation is permitted.
- Registered events should remain accessible after registration so members can review event details.

### Personalization

- Changing the active business should update event recommendations where business context affects relevance.
- Events should never be presented as relevant solely because they are available; relevance should be based on the member's context whenever possible.

## Empty States

### No Recommended Events

Message:

"We don't have any events specifically recommended for your business right now."

Primary Action:

Browse All Events

---

### No Upcoming Events

Message:

"There are no upcoming events available at the moment."

Primary Action:

Browse All Events

---

### No Registered Events

Message:

"You haven't registered for any events yet."

Primary Action:

Explore Recommended Events

---

### No Search Results

Message:

"No events match your search or filters."

Primary Action:

Clear Filters

## Wireframe

```text
------------------------------------------------------------
📅 Events

Discover events that can help your business grow.
------------------------------------------------------------

Recommended Events
------------------------------------------------------------
Women in Business Summit

Why recommended:
Connect with other business owners and expand your network.

Aug 24 · 9:00 AM
In Person · New York

[View Event]
------------------------------------------------------------

Government Contracting Workshop

Why recommended:
Supports your goal of winning government contracts.

Aug 28 · 2:00 PM
Online

[View Event]
------------------------------------------------------------

My Events
------------------------------------------------------------
Funding Workshop

Aug 18 · 10:00 AM
Registered

[View Event]
------------------------------------------------------------

Upcoming Events
------------------------------------------------------------
Search [________________]

[All] [Networking] [Workshops] [Training]

Small Business Growth Workshop
Aug 30 · Online

[View Event] [Register]
------------------------------------------------------------

## Future Enhancements

Future versions of the Events experience may include:

- Personalized event recommendations powered by the Business Success Intelligence (BSI).
- Calendar synchronization.
- Event reminders and notifications.
- Personalized event agendas.
- Post-event resources and follow-up recommendations.
- Event attendance tracking.
- AI-generated event summaries.
- Networking recommendations based on member interests and business goals.
