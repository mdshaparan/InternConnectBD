# InternConnectBD- Student Internship Management System (SIMS)

InternConnectBD is a full-stack web platform designed to connect students with companies across Bangladesh through geolocation, skill matching, and a structured internship application pipeline.

## 1. Project Overview

The Student Internship Management System (SIMS) aims to streamline the internship ecosystem in Bangladesh. The platform enables companies to post detailed internship opportunities while allowing students to discover, apply, and track internships that match their skills and location.

## Key goals of the system:

* Reduce the gap between students and companies
* Improve internship discovery using location-based search
* Provide transparent skill matching for fair selection
* Enable companies to manage applicants efficiently
* Ensure platform authenticity through admin verification

## 2. Core Features

Student Features

* Profile creation with skills and personal details
* Discover nearby internships within a **5 km radius**
* Apply to internships with a **calculated skill match percentage**
* Track application status in real time
* Receive and respond to full-time job offers
* Save internships for later application

Company (HR) Features

* Company verification by admin
* Post internships with:

  * Required skills
  * Internship timeline (start month to end month)
  * Location and application deadline
* View applicants with skill match percentage
* Shortlist candidates using an application pipeline
* Offer full-time jobs with salary details to high-performing interns

Admin Features

* Verify or reject company registrations
* Moderate internship postings
* Monitor system activity
* View reports and statistics for students, companies, internships, and applications

## 3. Tech Stack & Rationale

### Frontend

1.HTML, CSS, JavaScript**

  Chosen for its component-based architecture and dynamic user interface capabilities.
Database

2. MySQL (configurable)
  Used for storing users, internships, applications, and system data.

Mapping & Geolocation

Google Maps API / Leaflet.js
  Used to implement location-based internship search within a 5 km radius.

Authentication

  Ensures secure authentication and role-based access for Admin, Company, and Student users.


4. Installation & Setup

Prerequisites

* Git
* Node.js (v18 or higher)
* npm

Steps

Clone the Repository

```bash
git clone https://github.com/your-username/student-internship-management-system.git
cd student-internship-management-system
```

#### Install Backend Dependencies

```bash
cd backend
npm install
```
Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

5. How to Use

Authentication & Registration

* Navigate to the homepage
* Students and companies can register using their email addresses
* Admin accounts are pre-configured

Test Credentials

Student:[shahaparanmd474@gmail.com] / passwoed: 12345678
Company: [itltd@gmail.com] / password: aaaaaaaa
Admin:[admin@internconnectbd.com] / password: admin@123


6. User Workflows

Student Workflow

1. Register and log in
2. Complete profile and add skills
3. View nearby internships on the map
4. Apply and view skill match percentage
5. Track application status
6. Accept or reject job offers

## Company Workflow

1. Register and get verified by admin
2. Post internship details
3. Review applicants with skill match scores
4. Shortlist candidates
5. Send job offers and track responses

## Admin Workflow

1. Verify companies
2. Moderate internship posts
3. Monitor system statistics

7. Project Credits

## Developed By

#### Md Shaparan Ahammed
ID: 23-51096-1
Primary Responsibilities:

Company module
* Backend logic
* System integration

#### Risa, Sumiya Haider
ID: 23-50860-1
Primary Responsibilities:

Student module
Frontend design
Admin panel

Course: Web Technology (Fall 2025–26)
Section: T


8. Challenges Faced

* Implementing accurate geolocation filtering within a 5 km radius
* Designing a fair and transparent skill match algorithm
* Managing application flow for multiple user roles

9. Future Enhancements

Planned improvements include:

* In-app messaging between students and companies
* Review and rating system after internships
* Automated resume parsing
* Bulk application processing
* Email notifications
* Company analytics dashboard


## 10. Testing

To run backend tests:

```bash
cd backend
npm test
```

Frontend and integration tests are under development.




