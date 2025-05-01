<h1>**Scheduler App**</h1>

<h2>Table of Contents</h2>

- Overview
- Product Spec
- Wireframes
- Schema

<h2>
    Overview
</h2>

**Description**

Scheduler App is a mobile travel and event coordination tool that helps users plan events with friends by adding shared events with time and location. The app integrates with Google Maps to provide directions and real-time location tracking. It's ideal for friend groups who struggle with event planning and coordinating meetups in one centralized app.

<h2>
    App Evaluation
</h2>

- Category: Travel / Productivity

- Mobile: Makes use of mobile features such as Google Maps API, real-time toggles, and location-based services.

- Story: Helps solve the common problem of disorganized group planning with a clear and useful interface.

- Market: Useful for friend groups, college students, and social planners — particularly niche, but highly valuable.

- Habit: Users are expected to check back frequently to update plans, toggle events, or view schedules.

- Scope: MVP includes event creation, toggling, and viewing event details; future plans involve user accounts and map integration.

<h2>
    Product Spec
</h2>

1. User Stories

**Required Must-have Stories**

- Users can create a new event with a title, date, time, and location.

- Users can view a list of upcoming events.

- Users can toggle events as "complete".

- Users can view event details including time, location, and attendees.

- Navigation between pages (main → events → event detail).

**Optional Nice-to-have Stories**

* Integrate Google Maps to show event location.

* Ability to edit or delete events.
 
* User login and authentication.
 
* Share events to social platforms.
 
* Notify users about upcoming events via push notifications.
 
**2. Screen Archetypes**

**Main Page**

Displays a summary of upcoming and completed events.

**Events Page**

Lists active events with a toggle for completion status.

**Event Detail Page**

Shows full event information: time, location, attendees.

(Optional) **Event Edit Page**

Allows editing of event details, changing participants, and location.

**3. Navigation**

Tab Navigation (Tab to Screen)
Main Tab → Main Page (home feed of events)

Events Tab → Event List Page

Create Tab → Event Creation Page

Flow Navigation (Screen to Screen)
Main Page → Events Page

Events Page → Event Detail Page

Event Detail Page → (Optional) Event Edit Page

Event Edit Page → Event Detail Page (via Save)
