![screen-shot](screen-shot.png)

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Demo](#demo)

## General info

Built on Next.js, eventhub is a full-stack platform for managing events. It serves as a hub, spotlighting diverse events. Featuring payment processing through Stripe, you have the capability to purchase tickets for any event or even initiate and manage your own events.
Features: Host events, manage yours events, book tickets.

## Technologies

- Next.js
- Clerk
- Uploadthing
- Stripe
- Radix UI

## Features

- Authentication: User management through Clerk, ensuring secure and efficient authentication.
- Events (CRUD): Comprehensive functionality for creating, reading, updating, and deleting events.
  - Create Events: Users can generate new events, providing essential details such as title, date, location, and any additional information.
  - Read Events: Access to a detailed view of all events, allowing users to explore event specifics, including descriptions, schedules, and related information.
  - Update Events: Allows users to modify their event details dynamically, ensuring that event information remains accurate and up-to-date.
  - Delete Events: A straightforward process for removing events from the system, giving administrators the ability to manage and curate the platform effectively.
- Related Events: Smartly connects events that are related and displaying on the event details page.
- Organized Events: Efficient organization of events, ensuring a structured and user-friendly display for the audience.
- Search & Filter: Empowering users with a robust search and filter system, enabling them to easily find the events that match their preferences.
- New Category: Dynamic categorization allows for the seamless addition of new event categories.
- Checkout and Pay with Stripe: Smooth and secure payment transactions using Stripe, enhancing user experience during the checkout process.
- Event Orders: Comprehensive order management system, providing a clear overview of all event-related transactions.
- Search Orders: Quick and efficient search functionality for orders, facilitating easy tracking and management.

## Setup

To run this project locally:

```
$ npm install
$ npm run dev
```

Open http://localhost:3000 to view client in your browser.

## Demo

Vist [EventHub](https://event-hub-neon.vercel.app)
