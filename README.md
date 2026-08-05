<div align="center">

# 🗓️ Conference Event Planner

Efficiently plan, organize, and manage conferences and events with ease. A comprehensive web application designed to streamline event scheduling, attendee management, and speaker coordination.

[![React](https://img.shields.io/badge/React-Frontend_UI-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Redux](https://img.shields.io/badge/Redux-State_Management-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux.js.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)

</div>

---

## 📌 Project Overview

**conference_event_planner** is a comprehensive web application designed to streamline the organization of conferences, workshops, and events. It offers powerful, easy-to-use tools for scheduling, attendee management, speaker coordination, and real-time updates to ensure a smooth, professional event experience.

*Make your event planning effortless and successful!*

---

## ✨ Key Features

* **📅 Event & Session Scheduling:** Create, manage, and adjust timeblocks for your events effortlessly.
* **📝 Registration & Cost Tracking:** Seamlessly calculate total costs with dedicated pricing modules.
* **🎛️ Venue & AV Management:** Configure venue selections, meals, and audio/visual (AV) equipment requirements.
* **📊 Dynamic State Management:** Real-time updates and accurate calculations powered by Redux Toolkit.
* **📱 Responsive Design:** A flawless, accessible experience optimized for both mobile and desktop screens.

---

## 🛠️ Core Tech Stack

| Category | Technologies Used | Purpose |
| :--- | :--- | :--- |
| **Frontend Framework**| React.js | Building a fast, interactive, and component-based UI (`.jsx` structure) |
| **State Management** | Redux Toolkit | Centralized state architecture utilizing `store.js` and modular slices (`*Slice.js`) |
| **Styling & Layout** | CSS3 | Component-level styling for structured, responsive layouts (`.css`) |
| **Version Control** | Git, GitHub | Codebase management and feature versioning |

---

## 📁 Project Structure

Based on the repository architecture, the application modularizes its features into specific React components and Redux slices:

```text
conference_event_planner/
├── assets/                    # Static images and visual assets
├── store.js                   # Redux Toolkit centralized store configuration
├── avSlice.js                 # Redux slice for Audio/Visual equipment state
├── mealsSlice.js              # Redux slice for catering and meal selections
├── venueSlice.js              # Redux slice for venue and room scheduling
├── App.jsx / App.css          # Root application component and styles
├── main.jsx / index.css       # Application entry point and global styles
├── AboutUs.jsx                # Informational landing component
├── ConferenceEvent.jsx        # Core event management component
├── TotalCost.jsx              # Cost calculation and summary component
└── README.md                  # Project documentation
```

⚙️ Local Setup & Execution
To run this event planner application locally on your machine:

1. Clone the Repository
```text
git clone [https://github.com/HAMED-PAYANDA/conference_event_planner.git](https://github.com/HAMED-PAYANDA/conference_event_planner.git)
cd conference_event_planner
```

2. Install Dependencies
Ensure you have Node.js installed, then install the required packages (including React and Redux):
```text
npm install
```

3. Run the Development Server
Launch the application:
```text
npm start
```

The application will now be accessible in your web browser at http://localhost:3000/ or http://localhost:5173/.

👤 Author
Hamed Payanda
•	GitHub: @HAMED-PAYANDA
Completed as part of the IBM Full-Stack Software Developer Professional.
