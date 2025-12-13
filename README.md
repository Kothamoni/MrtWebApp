🚇 MRT Booking & Management System
<div align="center">
  <img src="Image/mrt_logo.png" alt="MRT App Logo" width="300">
</div>
<br/>

MRT Booking & Management System is a modern urban transit platform designed to enhance the commuting experience in Bangladesh. The system provides passengers with real-time train tracking, fare calculation, ticket booking, balance management, and notifications, all through an intuitive web interface built like a native mobile app.

📑 Table of Contents
- 🚀 Tools & Technologies
- 📋 Project Management
- 🏗️ Project Status
- 🌐 Live Demo
- 👥 Team Members
- 📘 Documentation
- 💻 Tech Stack
- 📜 Project Description
- 🛠️ Getting Started
- 🗺️ System Architecture
- 📊 Database Models

---

🚀 **Tools & Technologies**
<p align="center">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> 
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/> 
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/> <br/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express"/> 
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/> 
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens"/> 
<img src="https://img.shields.io/badge/jsPDF-000000?style=for-the-badge&logo=adobe"/>
</p>

---

📋 **Project Management**

Version Control: Git & GitHub

📁 **MRTApp Folder Structure**

<details>
  <summary>📂 frontend/ (Client-side app)</summary>

📄 index.html # Splash / Landing page  
📄 login.html  
📄 register.html  
📄 dashboard.html  
📄 profile.html  
📄 checkfare.html  
📄 history.html  
📄 recharge.html  
📄 mrt_tracker.html  
📄 ticket.html  
📄 verify-otp.html  

📂 css/
├── 📄 tailwind.css
└── 📄 custom.css

📂 js/
├── 📄 auth.js
├── 📄 dashboard.js
├── 📄 profile.js
├── 📄 fare.js
├── 📄 history.js
├── 📄 recharge.js
├── 📄 ticket.js
├── 📄 tracker.js
└── 📄 utils.js

📂 assets/
├── 📂 images/
└── 📂 icons/

</details>

<details>
  <summary>📂 backend/ (Server-side app)</summary>

📄 server.js  
📂 config/  
📂 routes/  
📂 controllers/  
📂 models/  
📂 middlewares/  
📂 utils/  
📄 package.json  

</details>

<details>
  <summary>📂 database/ (DB dump)</summary>

📄 mrtapp.mongodb # Optional

</details>

<details>
  <summary>📂 documentation/ (SRS, diagrams)</summary>

📄 SRS.pdf  
📄 UseCaseDiagram.png  
📄 ERDiagram.png  
📄 SequenceDiagram.png  
📄 ArchitectureDiagram.png

</details>

📄 .env.example  
📄 README.md  
📄 LICENSE

---

🌐 **Live Demo**

🚧 Coming Soon  
(Local backend required for execution)

---

👥 **Team Members**
| Name                    | Role                                |
| ----------------------- | ----------------------------------- |
| Umme Nafisa Anzum Kotha | Project Lead / Full-Stack Developer |

---

💻 **Tech Stack**
| Category                      | Technology         | Purpose                                |
| ----------------------------- | ------------------ | -------------------------------------- |
| **Frontend**                  | HTML5              | Structuring web pages                  |
|                               | Tailwind CSS       | Responsive and modern UI design        |
|                               | JavaScript (ES6+)  | Client-side logic and interactivity    |
| **Backend**                   | Node.js            | Server-side JavaScript runtime         |
|                               | Express.js         | REST API development                   |
|                               | MongoDB            | NoSQL database                         |
|                               | Mongoose           | MongoDB object modeling (ODM)          |
| **Authentication & Security** | JWT Authentication | Secure user login and session handling |
|                               | OTP Verification   | Two-step authentication                |
| **Payments & Utilities**      | SSLCommerz / MFS   | Mobile payment integration             |
|                               | jsPDF              | PDF receipt & ticket generation        |

---

📜 **Project Description**

MRT Booking & Management System is a full-stack web application designed to enhance public transit experiences by offering:

- **Passenger Features:** Secure login, profile management, live train schedule, fare calculator, ticket booking, balance recharge, ticket history, notifications.
- **Driver Features:** Optional driver interface for tracking and fare collection (future feature).
- **Admin Features:** Manage schedules, monitor ticketing, and generate analytics (future feature).

| 🚀 Objective                           |
| -------------------------------------- |
| Simplify urban commuting                |
| Provide transparent fare calculation    |
| Enable digital ticketing & balance mgmt |
| Improve passenger safety & notifications|

---

🛠️ **Getting Started**
| Requirement         | Version    |
| ------------------- | ---------- |
| **Node.js**         | v18+       |
| **MongoDB**         | v6+        |
| **Package Manager** | npm / yarn |

⚙️ **Installation (Development)**
```bash
git clone https://github.com/yourusername/mrt-booking-system.git
cd mrt-booking-system
npm install
npm run dev
➡ Backend Server: http://localhost:3000

🗺️ System Architecture

Client (Web Browser)
↓
REST API (Express.js)
↓
MongoDB Database

Layer	Responsibility
Frontend	UI rendering & user interaction
Backend	Business logic, security & payments
Database	Persistent data storage

📊 Database Models

Collection
Users (Passenger / Admin / Driver)
Tickets
Transactions
Notifications
TrainSchedules

Relationships
One user → multiple tickets
One ticket → one passenger & train
Transactions ↔ tickets

🔮 Future Work

Real-time WebSocket train tracking

Map integration with live train positions

Enhanced admin dashboard & analytics

Multi-tier notifications and alerts

Mobile PWA version for offline usage

📄 License

MIT License

<div align="center"> <p><strong>MRT Booking & Management System</strong></p> <p>Smart • Fast • Reliable Public Transport</p> <p>Built with ❤️ for Bangladesh</p> <p><em>Bangladesh University of Professionals</em></p> <p><em>Department of ICT</em></p> </div> ```
