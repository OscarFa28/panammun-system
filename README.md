# Panammun System

## Description
Panammun System is a web-based platform designed for the Universidad Panamericana in Aguascalientes, Mexico to manage their Model United Nations event, Panammun. This system is tailored to streamline the event organization, allowing participants to select committees and delegations in real-time, while offering administrative tools for managing registrations and event editions.

## Main Features

### User Panel:
- Participants can select their preferred committee and delegation at the time of opening.
- The system ensures only one committee per participant, and selections are confirmed on a first-come, first-served basis.

### Admin Panel 1:
- Displays a list of registered users, along with their payment proof for authorization.
- Additionally, if participants have chosen their committees and delegations, the distribution is shown in real-time.

### Admin Panel 2:
- A Django default admin panel where administrators can manage and modify users, committees, delegations, and event editions.
- Supports creating new event editions with specific information, ensuring the system is reusable for future years or editions.

## Technologies Used

### Backend:
- **Django** (Python)
- **MySQL**

### Frontend:
- **HTML**, **JS**, **CSS**

### Server:
- **Ubuntu VPS**

### Other Tools:
- **Gunicorn**
- **Nginx** (with SSL certificate)
- **Supervisor** (for process management)


