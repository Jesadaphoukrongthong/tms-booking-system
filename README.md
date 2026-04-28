# Timetable and Management System (TMS)

## Overview

A centralized booking system designed to integrate reservations from multiple channels such as LINE, website, and walk-in into a single unified timetable interface.

This system is built to solve real-world booking management problems where data is fragmented across platforms and prone to scheduling conflicts.

---

## Problem

Many rental and booking-based businesses face:

* Fragmented booking data across multiple channels
* High risk of time conflicts and double booking
* Lack of centralized visibility for resource usage
* Difficulty in analyzing business performance

---

## Solution

The Timetable and Management System (TMS) provides:

* A single timetable view for all bookings
* Conflict detection for time-based reservations
* Multi-channel booking integration
* Centralized customer and membership management
* Data collection for analytics and reporting

---

## Key Features

* Multi-channel booking (LINE, Web, Walk-in, Phone)
* Real-time timetable interface
* Booking conflict detection
* Customer & membership management
* Booking status tracking (Booked / Used / Cancelled / Unknown)
* Data analytics & reporting (CSV export supported)

---

## Tech Stack

**Frontend**

* React
* Next.js

**Backend**

* Node.js
* Express.js

**Database**

* MySQL (TiDB Cloud)

**Integration**

* LINE Messaging API

**Infrastructure**

* Docker
* Nginx

---

## System Architecture

> (Insert your architecture diagram here)

Example components:

* Frontend (Next.js)
* Backend API (Express)
* Database (MySQL / TiDB)
* External Integration (LINE API)
* Reverse Proxy (Nginx)

---

## Screenshots

> (Insert UI images here)

Suggested:

* Timetable view
* Booking form
* Dashboard / analytics

---

## Booking Flow (Simplified)

1. User sends booking request via LINE or Web
2. System creates reservation (Pending)
3. User confirms booking
4. System assigns available room automatically
5. Booking is stored and displayed in timetable
6. Usage updates status to "Used"

---

## Note

This repository is created for **demonstration and portfolio purposes only**.
The actual source code is maintained in a private repository.

---

## License

See LICENSE file for more details.
