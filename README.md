# Blinkit Full Stack Clone

This project is a full-stack clone of Blinkit, featuring a React frontend and a Node.js/Express backend. It includes user authentication, product management, cart functionality, and more.

## Project Structure

- `client/` — Frontend (React, Vite, Tailwind CSS)
- `server/` — Backend (Node.js, Express, MongoDB)

---

## Prerequisites

- **Node.js** (v18+ recommended)
- **npm** (comes with Node.js)
- **MongoDB** (local or Atlas)

---

## 1. Clone the Repository
```

---

## 2. Backend Setup (`server/`)

### Install Dependencies
```bash
cd server
npm install
```

### Configure Environment Variables
Create a `.env` file in the `server/` directory. Example:
```env
MONGODB_URL=mongodb://localhost:27017/blinkit_clone
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
STRIPE_SECRET_KEY=your_stripe_secret
```

### Start MongoDB (if running locally)
```bash
mongod
```

### Start Backend Server
```bash
npm start
```
The backend will run on `http://localhost:8080` (or as configured).

---

## 3. Frontend Setup (`client/`)

### Install Dependencies
```bash
cd ../client
npm install
```

### Configure API Endpoint
If needed, update API endpoints in `client/src/common/SummaryApi.js` to point to your backend (`http://localhost:8080`).

### Start Frontend
```bash
npm run dev
```
The frontend will run on `http://localhost:5173` (default Vite port).

---

## 4. Access the Application

- **Frontend:** [http://localhost:5173](http://localhost:5173)
- **Backend API:** [http://localhost:8080](http://localhost:8080)

---

## 5. Notes
- Ensure both servers are running for full functionality.
- MongoDB must be running and accessible.
- For email and Stripe features, provide valid credentials in `.env`.

---

## 6. Troubleshooting
- Check console logs for errors.
- Verify `.env` configuration and MongoDB connection.
- Ensure ports `8080` (backend) and `5173` (frontend) are not blocked.



## 7. License
This project is for educational purposes only.


#8. important step to run this application

download dependencies and then run following things one by one


cd server
npm install
npm start
cd ../client
npm install 
npm run dev
