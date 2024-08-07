# TodoHub

TodoHub is a MERN stack project where users can store their future tasks by creating an account. Users can add tasks with due dates, filter tasks by their status, search tasks by name, and manage their tasks efficiently.

## Features

1. **User Authentication**: Users can create an account, log in, and log out securely.
2. **Add Task**: Users can add tasks with a due date.
3. **Filter Tasks**: Users can filter tasks by status: Pending, Completed, and Due Today.
4. **Search Tasks**: Users can search for tasks by their name.
5. **Task Management**: Users can delete tasks and mark them as completed.
6. **Email Verification**: Users receive a verification email upon registration.

## Tech Stack

### Frontend

[![React Js](https://img.shields.io/badge/React%20Js-00a8ff?style=flat&link=https://react.dev/)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-00cec9?style=flat&link=https://tailwindcss.com/)](https://tailwindcss.com/)
[![Axios](https://img.shields.io/badge/Axios-6c5ce7?style=flat&link=https://axios-http.com/)](https://axios-http.com/)
[![Formik](https://img.shields.io/badge/Formik-0984e3?style=flat&link=https://formik.org/)](https://formik.org/)

### Backend

[![Node Js](https://img.shields.io/badge/Node%20Js-4cd137?style=flat&logoWidth=30&link=https://nodejs.org/en)](https://nodejs.org/en)
[![Express Js](https://img.shields.io/badge/Express%20Js-ffffff?style=flat&logoWidth=30&link=https://expressjs.com/)](https://expressjs.com/)
[![JWT](https://img.shields.io/badge/JWT-ff4757?style=flat&logoWidth=30&link=https://jwt.io/)](https://jwt.io/)
[![Nodemailer](https://img.shields.io/badge/Nodemailer-00a8ff?style=flat&logoWidth=30&link=https://nodemailer.com/)](https://nodemailer.com/)

### Database
[![MongoDB](https://img.shields.io/badge/MongoDB-27ae60?style=flat&logoWidth=30&link=https://www.mongodb.com/)](https://www.mongodb.com/)

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. **Clone the repository**

```
   git clone https://github.com/sobhandev2003/TodoHub.git
   cd todohub
```
 2. Install dependencies
```
#Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```
3. Set up environment variables
```
#Server
PORT=
CONECTION_STRING=
PASSWORD_SALT=
ACCESS_TOKE_SECRET=
SALT_ROUNDS=
JWT_SECRET_KEY=
GMAIL_ID=
GMAIL_PASS=

#Client
REACT_APP_BASEURL=
```
4. Start the development server
```
# Start the backend server
cd server
npm run dev

# Start the frontend server
cd ../client
npm start
```
