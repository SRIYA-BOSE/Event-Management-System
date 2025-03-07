# Event Management System

This is a full-stack **Event Management System** built with a **Node.js/Express backend** and a **React.js frontend**. It allows users to create, view, and delete events. The system now includes **user authentication** (login/signup) to ensure that only authenticated users can manage events.

## Features
- **User Authentication**:
  - Signup: Users can create an account.
  - Login: Users can log in to their account.
- **Event Management**:
  - Create Event: Add a new event with a title, description, and date.
  - View Events: Display a list of all events.
  - Delete Event: Remove an event from the list.
- **Protected Routes**:
  - Only authenticated users can create, view, or delete events.

## Technologies Used
- **Backend**: Node.js, Express, MongoDB, Mongoose, JWT (JSON Web Tokens)
- **Frontend**: React.js, Axios

## Setup Instructions

### Prerequisites
1. **Node.js**: Install Node.js from [https://nodejs.org](https://nodejs.org).
2. **MongoDB**: Install MongoDB locally or use a cloud service like MongoDB Atlas.

### Backend Setup
1. Navigate to the `backend` folder:
   ```bash
   cd backend