# SweetManager

**SweetManager** is a comprehensive hotel management software that streamlines operations for hotel administrators and workers. The platform allows for easy management of room details, booking processes, staff communication, and inventory supplies. SweetManager ensures efficient hotel management by assigning specific roles to administrators and workers, with a system that handles real-time notifications and task management.

---

## Features

- **Role-Based Access**: Different functionalities for managers, workers, and main administrators.
- **10 Work Areas**: Tailored interfaces for different hotel departments like Kitchen Staff, Housekeeping, Security, Reception, etc.
- **Real-Time Notifications**: Admins can send notifications to specific worker areas in real time.
- **Room Management**: View and manage room details, bookings, and availability.
- **Supplies and Inventory**: Manage stock levels and ensure proper communication with suppliers.
- **Subscription Model**: Administrators can subscribe to manage their hotel organization and invite other users.

---

## Roles

- **ROLE_MANAGER**: Manage hotel-wide operations, including rooms, workers, supplies, and notifications.
- **ROLE_WORKER**: Perform specific tasks based on the assigned work area and receive real-time notifications.
- **ROLE_MAIN_ADMIN**: [Upcoming] Full administrative control, including subscription management and organization setup.

---

## Tech Stack

- **Frontend**: React (with Vite for bundling)
- **Backend**: .NET Web API
- **Database**: MySQL (with JWT Authentication for secure access)
- **Containerization**: Docker (for easy deployment with both API and MySQL containers)
- **Architecture**: CQRS, Domain Driven Design, SCRUM for development process
