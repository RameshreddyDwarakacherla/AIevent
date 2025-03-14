# AI-Powered Event Planner

A modern event planning platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and enhanced with AI capabilities.

## Features

### User & Vendor Authentication
- JWT-based authentication for secure login and registration
- User and vendor profiles with role-based access control
- Identity verification for vendors

### Event Booking System
- Search, filter, and book vendors (caterers, decorators, photographers, venues, etc.)
- AI-driven vendor recommendations based on user preferences
- Real-time booking status with availability updates

### Vendor Dashboard
- Business profile and service management
- AI-powered pricing suggestions based on market trends
- Review and rating system for user feedback

### Smart Budgeting & Planning
- AI-driven event budget calculator
- Cost breakdowns and alternative suggestions to stay within budget

### Real-time Collaboration & Notifications
- Chat system for user-vendor communication
- Real-time notifications for booking updates and reminders

### Secure Payments & Contracts
- Integrated payment gateway (Stripe) for secure transactions
- Smart contracts for vendor agreements

### Additional Features
- AI-powered social media post generation for event announcements
- Admin dashboard to monitor users, vendors, and transactions

## Tech Stack

### Frontend
- React.js
- TailwindCSS
- React Router
- Formik & Yup for form validation
- Chart.js for analytics
- Socket.io for real-time features

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- OpenAI API for AI features
- Stripe for payment processing

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- OpenAI API key
- Stripe API keys

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/ai-event-planner.git
cd ai-event-planner
```

2. Install backend dependencies
```
cd backend
npm install
```

3. Install frontend dependencies
```
cd ../frontend
npm install
```

4. Set up environment variables
   - Create a `.env` file in the backend directory based on the `.env.example` file
   - Add your MongoDB URI, JWT secret, OpenAI API key, and Stripe keys

5. Start the development servers
   - Backend: `npm run dev` (from the backend directory)
   - Frontend: `npm start` (from the frontend directory)

6. Access the application at `http://localhost:3000`

## Project Structure

```
.
├── backend/                 # Backend code
│   ├── config/              # Configuration files
│   ├── controllers/         # Route controllers
│   ├── middleware/          # Custom middleware
│   ├── models/              # Mongoose models
│   ├── routes/              # API routes
│   ├── utils/               # Utility functions
│   └── server.js            # Entry point
│
└── frontend/                # Frontend code
    ├── public/              # Static files
    └── src/                 # React source code
        ├── components/      # Reusable components
        ├── context/         # React context
        ├── pages/           # Page components
        └── utils/           # Utility functions
```

## API Documentation

The API documentation is available at `/api-docs` when running the server.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenAI for providing the AI capabilities
- Stripe for the payment processing infrastructure
- TailwindCSS for the UI components #   A I e v e n t  
 #   A I e v e n t  
 #   E v e n t - F i n a l  
 