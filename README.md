# BlinkIt-Clone Frontend (React)

This repository contains the **frontend** for a Blinkit-style e-commerce platform, built with React and Vite and nodejs as well.  
You can use this frontend with any backend of your choice by updating the API endpoints.

## Features

- Modern UI inspired by Blinkit
- Product browsing and search
- Cart and checkout flow
- User authentication (login/register/forgot password)
- Admin panel for product/category management
- Responsive design for mobile and desktop

## Getting Started

### 1. Install Dependencies

```bash
cd client
npm install
```

### 2. Configure API Endpoints

Update the API base URL to point to your backend in [`client/src/common/SummaryApi.js`](client/src/common/SummaryApi.js):

```js
export const baseURL = import.meta.env.VITE_API_URL
```

Set `VITE_API_URL` in a `.env` file inside the `client` folder:

```
VITE_API_URL=https://your-backend-url.com
```

### 3. Run the Frontend

```bash
npm run dev
```

Open the app in your browser:

```bash
"$BROWSER" http://localhost:5173


---
**Note:**  
This project is frontend-only. To use all features, connect it to a compatible backend (REST API).


