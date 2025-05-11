# Airbnb Clone Backend - Use Case Diagram

This directory contains the use case diagram for the Airbnb Clone Backend project. The diagram visualizes the main features and functionalities of the system, as well as the interactions between different user roles (actors) and the backend.

## Use Case Diagram

![Use Case Diagram] (use_case.png)

This diagram illustrates how the following key actors interact with the main functionalities of the Airbnb Clone Backend:

## Key Actors

* **Guest:** Represents users who browse and book accommodations. Their main interactions include:
    * Registers for an account.
    * Logs into the system.
    * Searches for properties based on various criteria.
    * Views property details.
    * Books properties for specific dates.
    * Manages their bookings (e.g., cancellation).
    * Makes payments for bookings.
    * Writes reviews for properties they have stayed in.
    * Manages their user profile.

* **Host:** Represents users who list their properties for rent. Their main interactions include:
    * Registers for an account.
    * Logs into the system.
    * Creates new property listings (including details, pricing, availability).
    * Manages their existing listings (edits, deletes, updates availability).
    * Views and manages booking requests.
    * Responds to guest reviews.
    * Receives payouts for completed bookings.
    * Manages their user profile.

* **Admin:** Represents the system administrator who manages the platform. Their main interactions include:
    * Logs into the admin dashboard.
    * Manages user accounts (guests and hosts).
    * Manages property listings (approves, edits, removes).
    * Manages bookings.
    * Manages payment configurations and transactions.
    * Potentially generates reports and analytics.

* **Email Service:** An external system responsible for sending various notifications to users, such as booking confirmations, cancellation updates, and payment receipts.

* **Payment System:** An external system (e.g., Stripe, PayPal) that handles the processing of payments from guests and the payouts to hosts.

## Main Functionalities

The use case diagram depicts how the actors interact with the following core functionalities of the Airbnb Clone Backend:

* **User registration and login:** Allows guests and hosts to create accounts and securely log in.
* **Property search and booking:** Enables guests to find and book available properties based on their criteria.
* **Profile management:** Allows users (guests and hosts) to manage their personal information.
* **Listing creation and management:** Enables hosts to create, update, and manage their property listings.
* **Review system:** Allows guests to leave reviews for hosts and properties, and hosts to respond.
* **Payment processing:** Handles the secure transfer of funds between guests and hosts.
* **Notifications:** Provides timely updates and confirmations to users via email.

