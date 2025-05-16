Technology Stack
Language: JavaScript | Node.js | Express | MongoDB | React | Stripe | HTML | CSS | REST API

🚀 Getting Started
To run the Tomato Delivery application successfully, ensure you have the following prerequisites in place:

🛠 MongoDB Atlas
Create a free MongoDB Atlas cluster to host your database.


💳 Stripe Account
Create a Stripe account to obtain your SECRET STRIPE KEY for payment processing.


🧩 Installation
Follow the steps below to install and run each part of the application:

1️⃣ Frontend Setup
Navigate to the frontend directory and run the following commands:

bash
npm install
npm run dev
⚠️ Make sure to start the frontend first at: http://localhost:5173

2️⃣ Admin Panel Setup
Navigate to the admin directory and run:

bash
npm install
npm run dev
⚠️ Open the admin panel only after the frontend at: http://localhost:5174

3️⃣ Backend Setup
Navigate to the backend directory and start the server with:

bash
npm start server
⚠️ Important Configuration Notes:

Update your MongoDB URI in db.js

Add your Stripe Secret Key in the .env file
