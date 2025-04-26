# StudyNotion Ed-Tech Platform

StudyNotion is a powerful and user-friendly educational technology platform designed to empower learners and instructors alike. Built on the MERN stack (MongoDB, Express.js, React.js, Node.js), it allows users to create, explore, and review educational content seamlessly. Whether you’re a student eager to learn or an instructor ready to share your expertise, StudyNotion offers an engaging and interactive learning environment accessible worldwide.

[![Live Demo](https://raw.githubusercontent.com/NikhilFullstack/StudyNotion/refs/heads/main/frontend/src/assets/Images/flowchart-studynotion.png) of Contents

- [Architecture Overview](#architecture-overview)
- [Front-end Features](#front-end-features)
- [Back-end Functionality](#back-end-functionality)
- [API Endpoints](#api-endpoints)
- [Deployment Details](#deployment-details)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## Architecture Overview

StudyNotion follows a classic client-server model with three core components:

- **Front-end:** Developed using ReactJS, delivering a dynamic and responsive user interface that communicates with the server through RESTful APIs.
- **Back-end:** Powered by Node.js and Express.js, responsible for handling authentication, course operations, payment processing, and more.
- **Database:** MongoDB serves as the NoSQL database that stores all user profiles, course data, ratings, and other essential information.

![System Architecture Diagram] Features

The front-end application built with ReactJS offers a smooth and intuitive experience for both learners and educators.

### For Students:

- **Homepage:** Overview and introduction to the platform.
- **Course Catalog:** Browse courses with detailed descriptions and user ratings.
- **Wishlist:** Save courses for future enrollment.
- **Checkout:** Secure payment integration with Razorpay.
- **Course Access:** View course materials, including video lectures.
- **Enrolled Courses:** Track progress and revisit purchased courses.
- **Profile Management:** View and update personal account details.

### For Instructors:

- **Dashboard:** Monitor courses and student feedback.
- **Analytics:** Gain insights into course engagement metrics like views and clicks.
- **Course Management:** Create, edit, or remove courses effortlessly.
- **Profile Settings:** Manage instructor profile information.

Technologies used include ReactJS, Tailwind CSS for styling, Redux for state management, and VSCode as the development environment.

---

## Back-end Functionality

The server-side is built with Node.js and Express.js, integrating MongoDB for data persistence. Key backend capabilities include:

- **Authentication:** Secure user login, OTP verification, and password recovery.
- **Course Operations:** Full CRUD (Create, Read, Update, Delete) support for courses.
- **Payment Gateway:** Razorpay integration for handling course purchases.
- **Media Management:** Cloudinary integration for storing and serving media files.
- **Content Formatting:** Course materials stored in Markdown for flexible rendering.

The backend leverages JWT for secure authentication, bcrypt for password encryption, and Mongoose for database modeling.

---

## API Endpoints

StudyNotion exposes a RESTful API with JSON payloads for seamless communication between client and server. Some key endpoints include:

- `POST /api/auth/signup` – Register a new user.
- `POST /api/auth/login` – Authenticate and obtain a JWT token.
- `POST /api/auth/verify-otp` – Confirm OTP sent via email.
- `POST /api/auth/forgot-password` – Initiate password reset.
- `GET /api/courses` – Retrieve all available courses.
- `GET /api/courses/:id` – Fetch details of a specific course.
- `POST /api/courses` – Add a new course (instructor only).
- `PUT /api/courses/:id` – Update an existing course.
- `DELETE /api/courses/:id` – Remove a course.
- `POST /api/courses/:id/rate` – Submit a course rating (1-5 stars).

---

## Deployment Details

The platform is hosted on modern cloud infrastructure to ensure scalability and reliability:

- **Front-end:** Deployed on Vercel for fast and secure static hosting.
- **Back-end:** Hosted on Render or Railway platforms for Node.js and MongoDB services.
- **Media Storage:** Cloudinary manages all media assets.
- **Database:** MongoDB Atlas provides a fully managed cloud database.

---

## Getting Started

To run StudyNotion locally:

```bash
git clone (https://github.com/nikhilfullstack/StudyNotion.git)
cd StudyNotion
# Follow instructions to install dependencies and configure environment variables for front-end and back-end
```

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for exploring StudyNotion - your gateway to interactive and collaborative learning! 🚀

---

If you want, I can also help you generate the installation instructions or contributing guidelines in detail. Would you like me to do that?

---
