# Ryder 🚖

Ryder is a ride-booking web application developed as a collaborative group project inspired by modern cab-booking platforms. The application provides separate interfaces for users and captains, secure authentication, and a complete ride-booking workflow with a mobile-first design approach.
This project was developed collaboratively by [AVC](https://github.com/the-avc) and me as a team project.


## Features

* User signup and login authentication
* Captain signup and login
* Protected routes and secure access
* Ride booking workflow
* Captain ride management interface
* Password validation
* Mobile-first UI design
* Context API for state management

## Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication

## Installation

Clone the repository:

```bash
git clone https://github.com/anjalirawat05/Ryder.git
```

Move into the project directory:

```bash
cd Ryder
```

Frontend setup:

```bash
cd Frontend
npm install
npm run dev
```

Backend setup:

```bash
cd Backend
npm install
npm start
```

## Environment Variables

Create a `.env` file inside the Backend folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Future Enhancements

* Desktop responsiveness
* Real-time ride tracking
* Payment integration
* Notifications system
* Maps and live location support

## Note

The application follows a mobile-first design approach and is optimized primarily for smartphone screens.
