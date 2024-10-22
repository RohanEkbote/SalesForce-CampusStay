🌟 CampusStay: Simplifying Hostel Booking in Salesforce 🌟
Welcome to CampusStay, a custom Salesforce CRM application designed to streamline the hostel booking experience for students. This project empowers colleges to manage on-campus accommodations efficiently and ensures a smooth booking process for students.

🚀 Project Overview
CampusStay is a robust CRM solution built on the Salesforce platform. It enables students to seamlessly book cots in on-campus hostels, while hostel managers can efficiently track bookings and manage hostel capacity. The goal is to improve the user experience for students and simplify hostel management for administrators.

🎯 Key Features:
📋 College & Hostel Management: Supports multiple colleges, each with their own Boys and Girls hostels.
🛏️ Cot-Based Booking System: Book single or multiple cots based on availability.
💰 Automated Payment Records: Automatically generates payment records after booking confirmation.
🔄 Dynamic Flow for Students: Guides students through the booking process, with automated validation for cot availability.
🏢 Hostel Manager Control: Real-time updates on cot availability and booking status.

💡 Technologies Used

This project leverages Salesforce's powerful suite of tools and technologies:

Apex for backend business logic and validations.
Flow Builder for a smooth and interactive booking experience.
Salesforce Objects (College, Hostel/PG, Booking, Payment) to model the data.
Trigger for handling booking and overbooking validations.
Profiles & Roles to manage permissions for students and hostel managers.

🌐 Project Flow
Booking Process Flow:
The flow is designed to provide a user-friendly and intuitive booking experience for students. Here's a quick overview of the flow steps:

Select College & Hostel Type: Students start by choosing their college and selecting either Boys or Girls hostel.
Booking Details: Enter the number of cots to book and any room preferences.
Check Availability: The system automatically checks for cot availability based on selected hostel and displays error messages if overbooked.
Booking Confirmation: Students receive a confirmation with the details of their booking.
Payment Record Creation: A payment record is auto-generated, streamlining the transaction process.
Success Screen: Students are shown a "Booking Successful" message.

📸 Screenshots
🛠️ Flow Overview:
🏢 Booking Screen:
🛏️ Hostel Manager Dashboard:

🎯 Project Objectives
The CampusStay project was built to achieve the following key objectives:

Simplify Hostel Booking: Provide a quick and easy way for students to book accommodation.
Enhance Hostel Management: Help hostel managers track and manage cots, bookings, and payments more efficiently.
Automate Payment Creation: Automatically generate payment records upon booking, reducing manual errors.
Real-Time Validation: Prevent overbooking by checking cot availability dynamically.

🧩 How to Use This Project
To use this project, follow these steps:

Clone the Repository: git clone https://github.com/RohanEkbote/CampusStay-Project.git
Deploy to Salesforce: Use Salesforce's deployment tools to deploy this project to your Developer Edition.
Import Data: Set up sample data for colleges, hostels, and students.
Run the Flow: Test the booking process by running the flow from the Salesforce App.

🔍 Testing & Validation
Unit Testing: Apex classes and triggers have been thoroughly tested to ensure proper functionality.
Flow Testing: Each screen in the flow has been tested to handle cot availability, errors, and booking confirmation.

🔐 Roles and Profiles
CampusStay implements strict access control through roles and profiles:

Student Role: Can view available hostels, book cots, and make payments.
Hostel Manager Role: Can manage bookings, track cot availability, and view all student bookings for their respective hostel.
Hierarchy:
Admin > Hostel Manager > Student

👨‍💻 Contributing
We welcome contributions to make CampusStay even better! Here's how you can contribute:

Fork the repository.
Create a new feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.

🎉 Conclusion
CampusStay brings innovation to hostel management by making the cot-booking process hassle-free. Students can now secure their accommodation with just a few clicks, while hostel managers can easily monitor bookings and availability.

Thank you for checking out CampusStay! 🚀
