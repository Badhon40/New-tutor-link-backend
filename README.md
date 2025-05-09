# TutorLink

TutorLink is a web-based platform for connecting students with experienced tutors. It enables seamless tutor-student interactions, easy booking, and role-based dashboards for effective learning experiences.

Live Link : (https://new-tutor-link-frontend.vercel.app)

Server Link : (https://tutor-link-backend-pi.vercel.app)

## Features

* 👨‍🏫 **Tutor Registration:** Register as a tutor with details like subjects, grades, availability, and bio.
* 🎓 **Student Dashboard:** Browse available tutors and schedule sessions.
* 📅 **Booking System:** Real-time calendar integration for easy booking.
* 🔐 **Role-Based Access:** Different views and permissions for students and tutors.
* 💳 **Checkout System:** Secure payment gateway for booking confirmation.
* 🔎 **Search & Filter:** Find tutors by subject, grade, or availability.
* 📝 **User Authentication:** Register, log in, and manage your account securely.

## Technologies Used

* **Frontend:** Next.js, TailwindCSS, TypeScript
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **Authentication:** JWT (JSON Web Token)
* **Payment Integration:** Stripe
* **State Management:** Redux Toolkit
* **Calendar Integration:** FullCalendar

## Getting Started

### Prerequisites

* Node.js
* MongoDB
* Git

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/tutorlink.git

# Navigate to the project directory
cd tutorlink

# Install dependencies
npm install

# Start the development server
npm run dev
```

The application will be running at `http://localhost:3000`.

### Environment Variables

Create a `.env` file in the root directory and add the following:

```
MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret
STRIPE_SECRET_KEY=your-stripe-secret-key
```

## Usage

* Register as a tutor or student.
* Students can browse tutors and book sessions.
* Tutors can manage availability and respond to bookings.

---

# Backend Documentation

This section covers the backend structure, API documentation, and server configurations.

## Backend Setup

```bash
# Navigate to the backend directory
cd backend

# Install dependencies
npm install

# Start the backend server
npm run dev
```

The backend server runs on `http://localhost:5000` by default.

### Environment Variables

Create a `.env` file inside the `backend` directory:

```
PORT=5000
MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret
STRIPE_SECRET_KEY=your-stripe-secret-key
```

## API Endpoints

| Method | Endpoint             | Description                         |
| ------ | -------------------- | ----------------------------------- |
| GET    | `/api/tutors`        | Fetch all tutors                    |
| GET    | `/api/tutors/:id`    | Get details of a specific tutor     |
| POST   | `/api/auth/register` | Register a new user (Student/Tutor) |
| POST   | `/api/auth/login`    | User login                          |
| POST   | `/api/bookings`      | Book a session with a tutor         |
| GET    | `/api/bookings`      | Fetch all bookings for a user       |

## Deployment

To deploy the backend:

1. Make sure all environment variables are set up correctly.
2. Deploy to platforms like **Heroku, DigitalOcean, or Vercel**.
3. Set up your MongoDB database on **MongoDB Atlas**.

```bash
# For Heroku deployment
heroku create
git push heroku main
heroku config:set MONGODB_URI=your-mongodb-uri
heroku config:set JWT_SECRET=your-jwt-secret
heroku config:set STRIPE_SECRET_KEY=your-stripe-secret-key
```

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or feedback, feel free to reach out:

* **Email:** [your-email@example.com](badhonraniroy@gmail.com)
* **GitHub:** [your-username](https://github.com/Badhon40)


Happy Learning! 📘✨
