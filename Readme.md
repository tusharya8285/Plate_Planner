'''# 🍽️ PlatePlanner

**Dining, Reimagined.** A social dining platform where users capture food memories, discover authentic reviews, and book tables instantly.

## 🚀 Key Features

* **Capture & Share:** Post visual food diaries and reviews of your dining experiences.
* **Discover:** Browse a real-time feed of meals from the community—no anonymous ratings, just real food.
* **Instant Booking:** See a dish you like? Click **"Reserve Table"** on the post to book immediately.

## 🛠️ Tech Stack

* **MERN Stack:** MongoDB, Express.js, React, Node.js
* **Auth:** JSON Web Tokens (JWT)

## 💻 Setup Guide

### 1. Installation
Clone the repo and install dependencies for both server and client:

```bash
# Clone
git clone [https://github.com/yourusername/plateplanner.git](https://github.com/yourusername/plateplanner.git)
cd plateplanner

# Install Backend Deps
npm install

# Install Frontend Deps
cd client
npm install
npm install framer-motion@4.1.17 --legacy-peer-deps
cd ..
```

### 2. Configuration
Create a .env file in the root folder:

```bash
NODE_ENV=development
PORT=3000
JWT_SECRET=YOUR_SECRET_KEY
MONGO_URI=YOUR_MONGODB_CONNECTION_STRING
```

### 3. Run
Start both backend and frontend with one command:

```bash
npm run development
```
Access the app at http://localhost:3000.


📝 License
Open source under the MIT License.



