# College Event Management System

A web application built using Django for managing events and handling registrations. This system allows users to view, register for events, and manage their registrations. Admin users can manage events and user registrations.

## Author

Aabhas Katyal

<img width="1876" height="957" alt="eventx" src="https://github.com/user-attachments/assets/3f049081-a690-4df0-b1be-81a694b02c02" />


<img width="1887" height="949" alt="Screenshot 2026-02-03 111327" src="https://github.com/user-attachments/assets/934d25ae-62a2-4b9c-9a32-29fa97238812" />

<img width="1879" height="951" alt="Screenshot 2026-02-03 111342" src="https://github.com/user-attachments/assets/7a37633f-e0c1-4657-af1f-4f36123187f7" />


## Features

- **User Registration**: Users can create an account, log in, and register for events.
- **Event Management**: Admins can create, update, and delete events.
- **Registration Management**: Users can view and manage their event registrations.
- **Admin Dashboard**: Admins can view all event registrations and manage them.

## Technologies Used

- **Django**: A Python web framework for building web applications.
- **HTML/CSS**: For designing the user interface.
- **SQLite**: Default database for storing user registrations and event details.

## Getting Started

### Prerequisites

- Python 3.x
- Django 4.x or higher
- Virtual Environment (recommended)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aaryanbudakoti/EVENTX.git
   cd EVENTX
2. **Create and activate a virtual environment (recommended):**
   - On Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
4. **Set up the database:**
   Run the following commands to apply migrations and set up the SQLite database:
   ```bash
   python manage.py migrate
5. **Create a superuser (for admin access):**
   To manage the system as an admin, create a superuser account:
   ```bash
   python manage.py createsuperuser
6. **Run the development server:**
   Start the development server with the following command:
   ```bash
   python manage.py runserver
7. **Access the application:**
   - Open your browser and go to `http://127.0.0.1:8000/` to access the user-facing pages.
   - To access the admin dashboard, go to `http://127.0.0.1:8000/admin/` and log in using the superuser credentials.

### Usage
- **User Registration & Login:** Users can register, log in, and manage event registrations.
- **Admin Dashboard:** Admins can create, update, delete events, and view all user registrations.
