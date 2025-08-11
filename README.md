# clubXplore

## Overview

Many colleges face challenges in promoting club events, managing participation, and reaching the right audience—especially across different institutions. There is a lack of a unified digital platform that allows seamless visibility and management of club events while controlling access based on institution-specific criteria.

**clubXplore** is a centralized platform where college clubs can create, manage, and promote events with customizable visibility settings (college-exclusive or open to all). Students can register on the platform, browse events within their own college, and search for events from other colleges. College-exclusive events are visible only to students of that specific institution.

Clubs have access to dashboards displaying registered participants in a tabular format, enabling effective attendee management. This platform streamlines communication between clubs and students, encourages inter-college participation where applicable, and enhances overall event management efficiency.

---

## Features

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

## Technologies Used

- **Frontend:** EJS, CSS, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** Passport.js  
- **Language:** JavaScript  

---

## Installation & Setup

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

## Usage

- **Landing Page:** `/interface` - Login page for colleges and students  
- **Authentication:**  
  - Colleges log in using their **college name**  
  - Students log in using their **registered number**  
- **Admin Role:** Can create and edit events and clubs  
- **Student Role:** Can browse clubs and colleges and register for events  

---

## Project Structure

- `/routes` - Express route handlers for colleges, clubs, events, and authentication  
- `/views` - EJS templates for frontend UI  
- `/public` - Static assets (CSS, images, Bootstrap files)  
- `/models` - Mongoose schemas for College, Club, Event, Student  

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Contact

For any questions or feedback, please contact:

**Santhosh Charanthu**  
Email: santhoshcharanthu455@gmail.com 

---
