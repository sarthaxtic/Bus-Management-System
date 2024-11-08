# **Bus Management System**

![Bus Management System Banner](https://tinyurl.com/24m3c2fp)

## **Project Overview**

The **Bus Management System** is a web-based platform designed for **Graphic Era Hill University, Bhimtal**, to streamline bus services for hostel and day scholar students. The system enables online ticket booking, seat management, real-time bus tracking, attendance marking, and maintenance alerts. It aims to enhance the convenience of university transportation for students, parents, and administrators.

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)

---

## **Features**

- **Online Bus Ticket Booking**: Allows students to reserve seats on specific buses with real-time seat availability.
- **Seat Management**: Students can mark seats as vacant if not needed, updating availability in real-time.
- **Route and Number Tracking**: Provides bus route and number information, along with notifications for route changes.
- **Real-Time Bus Tracking**: GPS tracking for buses, accessible by students, parents, and administrators.
- **Student ID Verification**: Ensures only students with valid IDs can board the bus.
- **Attendance Tracking for Day Scholars**: Options for automated or manual attendance tracking.
- **Bus Maintenance and Fuel Monitoring**: Alerts for bus servicing schedules, fuel monitoring, and maintenance needs.
- **Admin Dashboard**: Centralized management of buses, routes, schedules, and student attendance.
- **Parent Portal**: Allows parents to monitor buses and receive updates on their child’s arrival and departure times.

---

## **Tech Stack**

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Hosting**: To be determined
- **Version Control**: GitHub

---

## **Setup and Installation**

### **Prerequisites**
- Node.js and npm installed
- MongoDB or MySQL setup locally or hosted
- Git for version control

### **Installation Steps**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sarthaxtic/Bus-Management-System.git
   cd Bus-Management-System
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Setup Environment Variables**
   - Create a `.env` file in the project root.
   - Add required environment variables, such as:
     ```
     DATABASE_URL=mongodb://localhost:27017/bus_management
     PORT=3000
     ```

4. **Run the Application**
   ```bash
   npm start
   ```

   Access the application in your browser at `http://localhost:3000`.

---

## **Usage**

### **Admin Dashboard**
The admin dashboard allows university administrators to:
- Manage buses, routes, schedules, and student attendance.
- View seat occupancy, maintenance alerts, and bus tracking.

### **Student Portal**
Students can:
- Book bus tickets, view available seats, and track buses.
- Access route information, check bus availability, and mark seats as vacant.

### **Parent Portal**
Parents can:
- Monitor bus location in real-time and view notifications about bus arrival/departure times.

---

## **Project Structure**

```plaintext
Bus-Management-System/
├── public/            # Static assets
├── src/
│   ├── components/    # React components
│   ├── pages/         # Application pages (e.g., home, dashboard, admin, etc.)
│   ├── services/      # API and backend services
│   ├── styles/        # Tailwind CSS styles
│   ├── utils/         # Utility functions
│   └── index.js       # Application entry point
├── .env               # Environment variables
├── .gitignore         # Git ignore file
├── package.json       # Project dependencies and scripts
└── README.md          # Project documentation
```

---

## **Future Enhancements**

- **Mobile App Integration**: A mobile app version for easy access and notifications.
- **Payment Gateway**: Integration for online payment options to book tickets.
- **AI-Powered Seat and Route Suggestions**: Predictive analytics for seat allocation and route planning.
- **Automated ID Verification**: Use of facial recognition or ID scanning for attendance marking.

---
