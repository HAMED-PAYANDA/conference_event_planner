<div align="center">

# 🗓️ Conference Event Planner

Efficiently plan, organize, and manage conferences and events with ease. A comprehensive web application designed to streamline event scheduling, attendee management, and speaker coordination.

[![React](https://img.shields.io/badge/React-Frontend_UI-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Redux](https://img.shields.io/badge/Redux-State_Management-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux.js.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Node.js](https://img.shields.io/badge/Node.js-Environment-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](#)
<br>
[![IBM Certification](https://img.shields.io/badge/IBM-Full%20Stack%20Software%20Developer%20Professional-blue?style=for-the-badge&logo=ibm)](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](#)

</div>

---

## 📌 Project Overview

**conference_event_planner** is a comprehensive web application designed to streamline the organization of conferences, workshops, and events. It offers powerful, easy-to-use tools for scheduling, attendee management, speaker coordination, and real-time updates to ensure a smooth, professional event experience.

*Make your event planning effortless and successful!*

---

## 🏗️ State Management Architecture

```mermaid
graph LR
    UI(["🖥️ UI Components<br>(ConferenceEvent.jsx)"])
    Store[("📦 Redux Store<br>(store.js)")]
    Cost(["💲 Total Cost Calculation<br>(TotalCost.jsx)"])

    subgraph Slices ["🧩 Redux Toolkit Slices"]
        direction TB
        Venue["🏠 venueSlice"]
        AV["🎛️ avSlice"]
        Meals["🍽️ mealsSlice"]
    end

    UI -->|"Dispatches Actions"| Slices
    Slices -->|"Updates Global State"| Store
    Store -->|"Selects State Data"| Cost
    Store -->|"Triggers Re-renders"| UI

    style UI fill:#e1f5fe,stroke:#0288d1,stroke-width:2px,color:#000
    style Cost fill:#e8f5e9,stroke:#388e3c,stroke-width:2px,color:#000
    style Store fill:#fff3e0,stroke:#f57c00,stroke-width:2px,color:#000
    style Venue fill:#f3e5f5,stroke:#8e24aa,stroke-width:2px,color:#000
    style AV fill:#f3e5f5,stroke:#8e24aa,stroke-width:2px,color:#000
    style Meals fill:#f3e5f5,stroke:#8e24aa,stroke-width:2px,color:#000
```
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

## 📸 Visual Proof



---

## 📁 Project Structure

Based on the repository architecture, the application modularizes its features into specific React components and Redux slices:

```text
conference_event_planner/
├── public/                    # Static public assets
├── src/                       # Application source code (React components, Redux store, slices)
├── .eslintrc.cjs              # ESLint configuration and rules for code quality
├── .gitignore                 # Specifies intentionally untracked files for Git
├── index.html                 # Main HTML template and application entry point
├── LICENSE                    # Project license file
├── package-lock.json          # Deterministic dependency tree
├── package.json               # Project metadata, dependencies, and script commands
├── README.md                  # Project documentation
├── screenshot2.png            # Visual proof: Event planner landing page
├── screenshot3.png            # Visual proof: Contact Us interaction form
└── vite.config.js             # Vite build and plugin configuration
```

---

## ⚙️ Local Setup & Execution
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

---

## 📜 License 

This project is licensed under the [Apache 2.0 License](LICENSE).

---

## 👤 Author

**Hamed Payanda**
* **GitHub:** [@HAMED-PAYANDA](https://github.com/HAMED-PAYANDA)
* Completed as part of the **IBM Full-Stack Software Developer Professional**.

