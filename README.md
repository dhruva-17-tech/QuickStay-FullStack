# 🏨 QuickStay-FullStack

[![React Version](https://img.shields.io/badge/React-v18.x-61dafb?logo=react&logoColor=black)](https://react.dev/)
[![Node Version](https://img.shields.io/badge/Node.js-v18.x-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![Project Status](https://img.shields.io/badge/Status-In_Development-yellow?style=flat-square)](https://github.com/dhruva-17-tech/QuickStay-FullStack)

QuickStay is a modern, full-stack hotel management and accommodation booking web application. Designed with a component-driven architecture, it aims to provide users with a seamless interface to browse real estate, check room availabilities, and book stays.

---

## ⚡ Project Overview & Status

> 🚧 **Current Deployment Note:**  
> The **Frontend (Client)** is fully implemented, fully responsive, and completely functional with mock data flows. The **Backend (Server)** and database integrations are currently in active development (Phase 2). 

### Key Technical Achievements (Frontend)
* **Dynamic Client-Side Routing:** Built with React Router for seamless, zero-refresh navigation.
* **Stateful UI Components:** Form validations, dynamic cards, and live filter systems managed locally.
* **Responsive Styling:** Clean, modern CSS layout optimized for both desktop and mobile viewports.

---

## 🛠️ Tech Stack

| Layer | Technologies Used | Status |
| :--- | :--- | :--- |
| **Frontend** | React.js, JavaScript (ES6+), HTML5, CSS3 | 🟢 Fully Functional |
| **Backend** | Node.js, Express.js | 🟡 In Development |
| **Database** | MongoDB, Mongoose ODM | 🟡 In Development |

---

## 📂 Architecture & Project Structure

The project is split cleanly into a decoupled repository structure to separate concerns between the presentation layer and the data layer:

```text
QuickStay-FullStack/
├── client/                 # Frontend React Application
│   ├── public/             # Static assets
│   └── src/
│       ├── components/     # Reusable UI elements (Navbar, Cards, Footer)
│       ├── pages/          # View components (Home, Search, Booking)
│       └── App.js          # Core routing and layout
└── server/                 # Backend REST API (Under Active Construction)
    ├── config/             # Database connection setups
    ├── models/             # MongoDB Schemas
    └── routes/             # Express API endpoints
```

Local Installation & Setup
Follow these steps to clone the repository and run the working frontend interface on your local machine.

Prerequisites
Ensure you have Node.js (v18+) installed.

1. Clone the Repository
git clone [https://github.com/dhruva-17-tech/QuickStay-FullStack.git](https://github.com/dhruva-17-tech/QuickStay-FullStack.git)
cd QuickStay-FullStack

2. Launch the Frontend (Client)
To explore the user interface and components:
cd client
npm install
npm start

The client app will boot up automatically at http://localhost:3000.

3. Launch the Backend (Server - Experimental)
Note: Server architecture is currently being stabilized.
cd ../server
npm install
npm start

Development Roadmap
This project is actively maintained. Below is the development pipeline toward the stable v1.0.0 release:

[x] Phase 1: UI/UX Design & Core React Component Architecture.

[x] Phase 2: Responsive CSS optimization and mock data integration.

[ ] Phase 3: Stabilize Express router endpoints for /api/hotels and /api/bookings.

[ ] Phase 4: Establish secure Atlas MongoDB cloud database connection.

[ ] Phase 5: Implement JSON Web Token (JWT) user authentication sessions.

[ ] Phase 6: Refactor frontend fetch hooks to replace mock data with live database API calls.

License
This project is open-source and available under the MIT License.
