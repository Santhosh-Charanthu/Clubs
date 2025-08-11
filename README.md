# 🚀 clubXplore

## 🎯 Overview

clubXplore is a unified platform for college clubs to create, manage, and promote events with customizable visibility. Students can browse and register for events within their college or others, while clubs can efficiently manage participation through dashboards. It simplifies event promotion and boosts student engagement across colleges.

---

## Features ✨

- College registration and management (CRUD operations)
- Club registration and management (CRUD operations)
- Event creation with customizable registration forms
- Events displayed as cards on club profiles
- Clubs displayed as cards on college profiles
- Student registration links accessible via college dashboard, ensuring only students from that college can register through the link
- Students can browse and register for events
- Role-based access:  
  - **Admin:** Create and edit events and clubs  
  - **Student:** Explore clubs and colleges, register for events

---

## Technologies Used 🛠️

- **Frontend:** EJS, CSS, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** Passport.js  
- **Language:** JavaScript  

---

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd clubXplore
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file and add the following (example):

   ```
   MONGODB_URI=your_mongodb_connection_string
   SESSION_SECRET=your_session_secret
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Open your browser and navigate to:

   ```
   http://localhost:8080/interface
   ```

---

## Usage 📋

- **Landing Page:** `/interface` - Login page for colleges and students  
- **Authentication:**  
  - Colleges log in using their **college name**  
  - Students log in using their **registered number**  
- **Admin Role:** Can create and edit events and clubs  
- **Student Role:** Can browse clubs and colleges and register for events  

---

## Project Structure 📁

- `/routes` - Express route handlers for colleges, clubs, events, and authentication  
- `/views` - EJS templates for frontend UI  
- `/public` - Static assets (CSS, images, Bootstrap files)  
- `/models` - Mongoose schemas for College, Club, Event, Student  

---

## Contributing 🤝

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License 📄

This project is licensed under the MIT License.

---

## Contact ✉️

For any questions or feedback, please contact:

**Santhosh Charanthu**  
Email: santhoshcharanthu455@gmail.com 

---
