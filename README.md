# mode-rental-MS
A full-stack application connecting rental managers and tenants. Features include apartment listings, tenant registration, booking management, notifications, and real-time updates. Built collaboratively as a capstone project to showcase development skills.


## Backend Workflow and Technologies
Overview
The backend of this Rental Management System is built using Python and Flask, providing a robust and scalable foundation for API development. PostgreSQL is used as the database to manage and store rental information efficiently. Additional features include email notifications and integration with M-Pesa Daraja API for payment processing.

## Key Technologies
Python: Core programming language for backend development.
Flask: Lightweight framework for building RESTful APIs.
PostgreSQL: Relational database management system for data persistence.
Email Notification: Used for sending updates such as booking confirmations and reminders.
M-Pesa Daraja API: Enables mobile money transactions for rental payments (to be implemented later).

## Workflow
1. API Development:

RESTful API endpoints will be created to handle core functionalities, such as:
User authentication and authorization.
Apartment listing management.
Booking system for tenants.

2. Database Design:

PostgreSQL will store structured data like:
Apartment details (name, availability, price).
User information (name, role, booking history).
Notifications and payment records.

3. Email Notifications:

Utilize Python libraries like smtplib or Flask-Mail for sending automated emails during key events, such as booking confirmations or maintenance alerts.

3. Payment Integration

The M-Pesa Daraja API will be incorporated to handle rental payments securely.
Borrowing from the Money Transfer App, we’ll ensure seamless mobile payment functionality.
4. Future Enhancements
Refine the email system to handle bulk notifications.
Explore additional third-party APIs for payment methods beyond M-Pesa.
## Setup Instructions
To set up the backend locally:

Clone the repository:
bash
git clone <repository-url>
cd <repository-folder>

Install dependencies:

bash
pip install -r requirements.txt

Set up the PostgreSQL database and configure the connection in .env.
Run the Flask development server:
bash
flask run
