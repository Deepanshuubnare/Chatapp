# 💬 Real-Time Chat Application

A full-stack, real-time chat application built with the MERN stack (MongoDB, Express, React, Node.js) and Socket.io. This project allows users to sign up, log in, and communicate with each other instantly in a beautifully designed interface.

The application demonstrates a solid understanding of modern web technologies, including real-time communication, user authentication with JWT, and state management in a single-page application (SPA).

---

###  Live Demo

* **Live Demo:** [https://chatappdev-pkjz.onrender.com/](https://chatappdev-pkjz.onrender.com/)

---

## 🚀 Key Features

* **Real-Time Messaging:** Instant message delivery and reception using **Socket.io**.
* **User Authentication:** Secure user registration and login system using **JSON Web Tokens (JWT)**.
* **Online User Status:** View a list of currently online users and engage in one-on-one conversations.
* **Modern UI with Tailwind CSS:** A responsive and intuitive user interface built with the utility-first **Tailwind CSS** framework.
* **State Management:** Efficient state management on the frontend using **Zustand**.
* **Error Handling:** Robust error handling on both the client and server to ensure a smooth user experience.
* **Secure Backend:** Backend APIs are protected, and passwords are encrypted using **bcrypt.js**.

---

## 🛠️ Technical Skills Demonstrated

This project showcases proficiency in:

* **Full-Stack Development:** Building both the client and server from scratch using the **MERN** stack.
* **Real-Time Communication:** Implementing bidirectional communication with **WebSockets** via **Socket.io**.
* **Authentication & Security:** Creating secure authentication flows with **JWT**, password hashing, and protecting routes.
* **Modern Frontend:** Developing a responsive Single Page Application (SPA) with **React.js** and managing complex state with **Zustand**.
* **API Development:** Designing and building a RESTful API with **Node.js** and **Express.js**.
* **Database Management:** Modeling application data and interacting with a **MongoDB** database using **Mongoose**.
* **Version Control:** Managing the codebase with **Git** and **GitHub**.

---

## 💻 Tech Stack

| Category      | Technology                                    |
| ------------- | --------------------------------------------- |
| **Frontend** | React.js,Tailwind CSS, Zustand                  |
| **Backend** | Node.js, Express.js                           |
| **Database** | MongoDB, Mongoose                             |
| **Real-Time** | Socket.io                                     |
| **Auth** | JSON Web Tokens (JWT), bcrypt.js              |

---

## ⚙️ Getting Started

Follow these instructions to get a local copy up and running for development.

### Prerequisites

* [Node.js](https://nodejs.org/en/) (v16 or newer)
* [MongoDB](https://www.mongodb.com/try/download/community) (a local instance or a MongoDB Atlas account)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/Deepanshuubnare/Chatapp.git](https://github.com/Deepanshuubnare/Chatapp.git)
    cd Chatapp
    ```

2.  **Install backend dependencies:**
    ```sh
    cd server
    npm install
    ```

3.  **Install frontend dependencies:**
    ```sh
    cd ../client
    npm install
    ```

4.  **Set up Environment Variables:**
    Create a `.env` file in the `server` directory and add the following variables:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    NODE_ENV=development
    ```
    *Replace the placeholder values with your actual MongoDB URI and a secret key for JWT.*

### Running the Application

1.  **Start the backend server:**
    From the `server` directory, run:
    ```sh
    npm start
    ```
    The server will start on `http://localhost:5000` (or the port you defined).

2.  **Start the frontend client:**
    In a new terminal, from the `client` directory, run:
    ```sh
d   npm run dev
    ```
    The application will be available at `http://localhost:3000`.

---

## 🧑‍💻 Author

* **Deepanshu Ubnare**
    * **GitHub:** [@Deepanshuubnare](https://github.com/Deepanshuubnare)
