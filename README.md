# Mini-link-management
## 📌 Overview
This platform can be used to shorten any url by hashing the url and can be used to access these websites.Mini Link Management Platform that allows users to **shorten, manage, and analyze** URLs efficiently. Users can create short URLs, track clicks, and manage their accounts seamlessly.


## 🏗 Tech Stack
### Frontend:
- **React** (with Vanilla CSS)
### Backend:
- **Node.js** with **Express**
- **MongoDB** (for database storage)
### Hosting:
- **Frontend**: Vercel/Netlify
- **Backend**: Render/Heroku

## 🚀 Live Demo
🔗 [Live Demo](https://bramha-kl-mini-link-management-app.vercel.app/signup)

## 🛠 Setup Instructions
### Prerequisites:
- **Node.js** installed
- **MongoDB** (Local or Atlas connection)

### Clone the Repository
```sh
 git clone (https://bramha-kl-mini-link-management-app.vercel.app/signup)
 cd frontend
```

### Backend Setup
```sh
 cd backend
 npm install
 npm start
```
Create a **.env** file in the `backend` folder with:
```env
PORT=5000
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
```

### Frontend Setup
```sh
 cd frontend
 npm install
 npm start
```

## 🌟 Features

- **URL Shortening:** Shortens a given URL using hashing, allowing users to use the generated link to navigate to the desired location.
- ⏳ **Expiration Dates**: Set expiration dates for links.
- 🔑 **User Authentication**: Secure **registration and login** with email and password.authentication is implemented using HTTPS cookies.
- 🛠 **User Management**:
  - Update profile (name & email).
  - Secure password hashing.
  - Delete account (removes all associated links and data).
- 📊 **Dashboard**:
  - View **original and shortened URLs**.
  - **Click analytics** (timestamps, IP, browser, OS details).
  - **Edit and delete** links.
- 📈 **Analytics**:
  - Device type (mobile, desktop, tablet).
  - Browser details.
- **React Toast Notifications:** Success and error messages are handled using React Toast.
- **State Management:** Uses React Context API for efficient state handling across the application.
- **Mobile Responsive:** Fully responsive design for seamless use on different devices.
- **REST API Practices:** Follows RESTful API principles for efficient client-server communication.
- 📱 **Responsive Design**: Works on both desktop and mobile devices.
-  📃  **Pagination and Aggregation Pipelines:** Implemented efficient data pagination and aggregation pipelines to handle large sets of data and provide seamless user experience with fast, organized responses.

