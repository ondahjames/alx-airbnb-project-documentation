# Airbnb Clone — User Stories

## Overview

This document outlines key user stories derived from the core use cases of the Airbnb Clone backend project. Each story represents a user interaction that contributes to the platform’s functionality and user experience.

---

## User Stories

1. **User Registration**

   * As a **guest or host**, I want to be able to register an account so that I can access the platform and list or book properties.

2. **Property Listing**

   * As a **host**, I want to list my property with details such as location, price, amenities, and images so that potential guests can view and book it.

3. **Property Booking**

   * As a **guest**, I want to book available properties for specific dates so that I can secure accommodation for my trip.

4. **Payment Processing**

   * As a **guest**, I want to make secure payments for my bookings so that my reservation can be confirmed.

5. **Review and Rating**

   * As a **guest**, I want to leave a review and rating after completing a stay so that future guests can make informed decisions.

6. **Notifications**

   * As a **user**, I want to receive notifications about booking confirmations, cancellations, and payment updates so that I can stay informed about my activities.

7. **Admin Management**

   * As an **admin**, I want to manage users, listings, and bookings so that I can maintain the platform’s integrity and resolve issues promptly.

---

## Database Schema Reference

The backend database is designed with the following key tables:

* **Users**: Stores user details and roles (guest, host, admin)
* **Properties**: Manages property listings and related information
* **Bookings**: Tracks reservation details between guests and hosts
* **Payments**: Handles transaction data for completed bookings
* **Reviews**: Captures user feedback and ratings
* **Notifications**: Stores system-generated alerts for users
* **Admins**: Maintains admin access controls

Refer to the [DB Diagram Schema](./dbdiagram.sql) for full relationship details.

---

## Tools & Technologies

* **Backend Framework:** Node.js / Express.js
* **Database:** PostgreSQL
* **ORM:** Sequelize
* **Authentication:** JWT / OAuth
* **Payment Integration:** Stripe or PayPal
* **Deployment:** AWS or Render

---

## Author

**Ondah James**
Backend Developer | Tech Enthusiast | Cloud Learner

> Building scalable and user-centered backend systems.
