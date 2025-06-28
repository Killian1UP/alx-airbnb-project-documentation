# 🧾 Airbnb Clone - Use Case Diagram (Backend)

This document outlines the **use case interactions** between users and the system in the **Airbnb Clone backend**. The system is designed to handle major functionalities of a rental marketplace such as user management, property listing, booking management, payment processing, and administrative operations.

---

## 🔑 Key Actors

- **Guest** – A user who books properties.
- **Host** – A user who lists properties.
- **Admin** – A privileged user who manages the platform.

---

## 🧩 Use Case Summary

### 👤 Guest Actions

- **Register**: Sign up using email/password or OAuth.
- **Log in**: Access the platform securely.
- **Authenticate (JWT)**: Maintain secure sessions.
- **Browse Properties**: Search by filters like location, price, amenities.
- **Book Property**: Reserve a stay by selecting dates.
- **Cancel Booking**: Cancel existing reservations.
- **Make Payment**: Pay for a booking using Stripe/PayPal.
- **Leave Review**: Rate a property after a completed stay.
- **Send Message**: Communicate with host or admin.
- **Receive Notifications**: Be notified of updates and changes.

### 🏘️ Host Actions

- **Add Property**: Create new listings with title, description, location, price, amenities, availability.
- **Edit/Delete Property**: Modify or remove a listing.
- **View Bookings**: Monitor who has booked and their details.
- **Respond to Reviews**: Reply to guest feedback.
- **Receive Payments**: Get payouts after booking completion.
- **Update Profile**: Manage personal or business information.
- **Respond to Message**: Communicate with guests or admin.

### 🛡️ Admin Actions

- **Manage Users**: View, edit, or disable user accounts.
- **Moderate Content**: Review and manage listings or reviews.
- **Monitor Payments**: Track transactions and resolve disputes.
- **Resolve Conflicts**: Act on guest-host conflicts.
- **View Listings**: Monitor property listings on the platform.
- **Monitor Bookings**: Track booking activities across users.
- **View Logs**: Access system logs for auditing and debugging.

---

## 📊 Use Case Diagram

This visual diagram illustrates the interactions between users and system use cases:

![Use Case Diagram](./Use%20case%20diagram.png)

---