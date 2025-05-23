
MINI PROJECT REPORT
Course Code: ENSI152
Group Code: Y1-2024-25-[G286]
Project Title: Food Donation Platform – FoodDoor

Post Graduation in
Master of Computer Applications

Submitted by:
[Hitesh Singh], [Kaushal Dixit], [Sandeep Rajmania],[Himanshu Yadav]

Under the Supervision of:
Dr. [Harsh Vardhan]

School of Engineering & Technology
K. R. Mangalam University, Sohna

   
# FoodDoor – Feed a Homeless Person

**FoodDoor** is a full-stack web application that connects food donors (individuals or restaurants) with volunteers to redistribute surplus food to underprivileged communities. The platform aims to reduce food waste and hunger by making it simple to donate or volunteer.

## 🧩 Features
- 🌐 User-friendly interface for food/money donation
- 🍛 Separate donation flows for individuals and restaurants
- 🙋 Volunteer registration with form submission and ID upload
- 📦 MongoDB-based storage of donor and volunteer data
- 📸 Informational sections: Gallery, Programs, About, Contact
- 🔒 Secure data handling and form validation

## 🔧 Tech Stack
| Technology       | Purpose                          |
|------------------|----------------------------------|
| HTML, CSS, JS    | Frontend UI/UX                  |
| Bootstrap        | Responsive design (optional)     |
| Node.js, Express | Backend (optional)               |
| MongoDB          | Database                         |

## 🚀 How It Works
1. User visits homepage
2. Personal donors submit food/money via form
3. Restaurant donors enter multiple items and contact info
4. Volunteers register with ID proof
5. Data stored in MongoDB for processing

## 📁 Project Structure
FoodDoor/
├── public/
│   ├── index.html
│   ├── personal-donate.html
│   ├── restaurant-donate.html
│   └── volunteer-register.html
├── backend/ (optional)
├── database/ (MongoDB config)
├── css/
├── images/
└── README.md

## 📈 Future Enhancements
- Mobile App (React Native)
- Admin Dashboard
- Real-time tracking
- Notifications (Email/SMS)
- Feedback System

## 📜 License
Open-source under MIT License

## 📬 Contact
Email: [jadaunhitesh9@gmail.com]
"""

presentation_points = """\
PowerPoint Presentation – FoodDoor Project (10 Slides)

1. Title Slide
- Project: FoodDoor – Feed a Homeless Person
- Tagline, submitted by, course name, and university

2. Overview of FoodDoor
- Social impact project
- Connects donors and volunteers
- Reduces food waste

3. User Roles
- Personal Donor
- Restaurant Donor
- Volunteer
- Admin (optional)
- Public Viewer

4. Overall Workflow
- Homepage → Action selection → Form Submission
- Data → MongoDB → Admin/Volunteer Coordination

5. Home Page Navigation
- Includes links to all key pages
- CTA buttons like "Donate" and "Login"

6. Personal Donation Flow
- Fill name, age, contact
- Choose donation type and submit

7. Restaurant Donation Flow
- Business info, food items, optional money donation

8. Volunteer Registration
- Name, gender, DOB, upload ID, submit

9. Backend & Data Storage
- Node.js server (if used), MongoDB database
- Secure form handling

10. Conclusion & Future Scope
- FoodDoor is scalable and impactful
- Future: tracking, mobile app, feedback, SMS alerts
"""



