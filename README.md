# Merry Berry Web Application
## Live Website: [https://merry-berry.finneh.xyz/](https://merry-berry.finneh.xyz/)

Merry Berry is a full-stack web application structured across **three distinct repositories**: `client`, `server`, and `docs`. This modular approach facilitates independent development, deployment, and documentation for each core component.

The application leverages **Express.js** and **MongoDB Atlas** for a robust backend, **React.js** for a dynamic frontend, and incorporates **Firebase** for client-side authentication and **Stripe** for payment processing.

---

### ✨ Overall Application Features

* 🔐 **User Authentication (via Firebase Frontend):** Secure signup and login processes managed entirely by Firebase Authentication on the client-side, providing robust user identity management.
* 💳 **Comprehensive Account Management:** Users can effortlessly create, view, update, and delete their accounts, maintaining full control over their financial profiles.
* 🚀 **RESTful API with CRUD Operations:** The backend provides a well-structured RESTful API supporting Create, Read, Update, and Delete (CRUD) operations for managing user accounts, transactions, and other data.
* 📊 **Streamlined Transaction & Operation Processing:** Facilitates various financial transactions (e.g., deposits, withdrawals, transfers) and operations with real-time updates.
* 💸 **Secure Payment Integration (Stripe):** Enables secure processing of payments and financial transactions directly within the application using Stripe's robust API.
* 📱 **Intuitive & Responsive User Interface:** Built with a modern React.js frontend, ensuring a smooth and engaging user experience across all devices, from desktops to mobile phones.

---

### 📦 Repositories Overview

This project is comprised of the following independent repositories:

* **🌐 `merry-berry-client`** (Frontend Application)
    * **Description:** The user-facing web application built with React.js, responsible for the interactive user interface, consuming the backend API, and handling client-side authentication via Firebase.
    * **Key Technologies:** ⚛️ React.js, 🛣️ React Router DOM, 📡 Axios, 🔥 Firebase (Client SDK), 💳 Stripe.js.
    * **Deployment:** Deployed on Netlify.

* **🖥️ `merry-berry-server`** (Backend API)
    * **Description:** The RESTful API that handles business logic, database interactions, and payment processing. It provides endpoints for CRUD operations and integrates with MongoDB Atlas and Stripe.
    * **Key Technologies:** ⚡ Express.js, 💾 MongoDB Atlas, 🔗 Mongoose, 💵 Stripe API.

* **📚 `merry-berry-docs`** (Documentation)
    * **Description:** This repository contains all project documentation, including architectural diagrams, API specifications, setup guides, and any other relevant project information.

---

### 🛠️ Technologies Used

* **Frontend:** ⚛️ React.js, 🛣️ React Router DOM, 📡 Axios, 🔥 Firebase (Client SDK), 💳 Stripe.js, 🎨 CSS Modules / Styled Components.
* **Backend:** ⚡ Express.js, 💾 MongoDB Atlas, 🔗 Mongoose, 💳 Stripe API.
* **Deployment:** 🚀 Netlify (for client), Render (for server).
* **Database:** ☁️ MongoDB Atlas.
* **Authentication:** 🔐 Firebase Authentication (frontend-only).

---

### 🌐 Deployment

* **Frontend (`merry-berry-client`):** The client-side (React.js) is deployed using **Netlify**, leveraging its continuous deployment features for easy updates.
    * **Netlify Deployment Link:** [https://merry-berry.finneh.xyz/](https://merry-berry.finneh.xyz/)

* **Backend (`merry-berry-server`):** The server-side (Express.js) is deployed on Render.com, a unified cloud platform for all your apps and websites. It connects to MongoDB Atlas for data persistence, handles user authentication purely via Firebase Authentication on the frontend, and securely manages payment processing with Stripe.
