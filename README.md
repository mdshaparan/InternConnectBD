# InternConnectBD

A full-stack web platform connecting students with companies in Bangladesh through geolocation, skill-matching, and a structured application pipeline.
**Student Internship Management System (SIMS)**

A full-stack web platform connecting students with companies in Bangladesh through geolocation, skill-matching, and a structured application pipeline.

1. Project Description
This system is designed to streamline the internship ecosystem in Bangladesh. It allows companies to post detailed opportunities, enables students to discover and apply to nearby internships with a calculated skill match, and provides tools for companies to shortlist candidates and convert high-performing interns to full-time employees. An admin panel ensures authenticity by verifying all entities and content.

2. Tech Stack & Why
Frontend:** HTML, CSS, JavaScript, React.js. *Chosen for component-based architecture and rich user interactivity.*
Backend:** Node.js with Express.js. *Provides a fast, scalable server environment ideal for handling concurrent requests.*
Mapping/Geolocation:** Google Maps API / Leaflet.js. *Essential for implementing the 5km radius search feature.*
Authentication:** JWT (JSON Web Tokens). *Secures user sessions across the three distinct user roles (Admin, Company, Student).*

## **Installation & Setup**

Prerequisites
Git


Steps
**Clone the repository:**
```bash
git clone https://github.com/your-username/student-internship-management-system.git
cd student-internship-management-system

**Install backend dependencies:**
```bash
cd backend
npm install


**Install frontend dependencies:**
```bash
cd ../frontend
npm install

How to Use
1. Authentication & Registration**
Navigate to the homepage.
Students & Companies can register using their institutional/company emails.
Admins are pre-configured.

Test Credentials:
Student: `shahaparanmd474@gmail.com` / `12345678’
Company:`company@test.com` / `password123`
Admin:`admin@system.com` / `adminpass`


2. User-Specific Workflows**
Student:
Complete your profile and add skills.
Use the "Nearby Internships" map to find opportunities within 5km.
Apply to an internship; the system will show your **Skill Match Percentage**.
Track applications and respond to job offers from the dashboard.

Company (HR):
Get verified by Admin.
Post an internship by specifying skills, timeline (start/end month), and location.
View applicants with their skill match score in the application pipeline.
Shortlist candidates and send full-time job offers with salary details.

Admin:
Verify new company registrations from the admin panel.
Moderate all internship postings.
View system-wide reports and statistics.

Credits
Developed By:
Md Shaparan Ahammed (ID: 23-51096-1) - [GitHub Profile](https://github.com/yourprofile)
Primary Responsibilities: Company Features, Backend Logic, System Integration
Risa, Sumiya Haider (ID: 23-50860-1) - [GitHub Profile](https://github.com/yourprofile)
Primary Responsibilities: Student Features, Frontend Design, Admin Panel

Course: Web Technology (Fall 25-26), Section T.
Acknowledgements:
Thanks to our course instructor for guidance.
Inspired by modern platforms like LinkedIn, Glassdoor, and local job boards.

## License
This project is licensed under the **GPL-3.0 License**. See the `LICENSE` file for details. This allows others to make modifications and use it commercially, provided they disclose their source.

## Future Features & Challenges
Challenges Faced:
Implementing accurate real-time geolocation filtering for the 5km radius.
Designing a fair and transparent algorithm for calculating the skill match percentage.
Managing state for the complex, multi-role application flow.

Planned Future Implementations:
In-app messaging system for direct student-company communication.
Review and rating system** for companies and interns post-internship.
Automated resume parsing** to auto-fill student skills.
Bulk application processing** and email notifications for companies.
Analytics dashboard** for companies to track internship post performance.

Contribute
We welcome contributions! Please follow these steps:
Open a Pull Request. Please ensure your code adheres to the existing style.

Tests
To run the backend test suite (using Jest):
```bash
cd backend
npm test

More test suites for frontend components and integration are under development.*
