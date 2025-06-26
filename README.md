🚀 How to Run This Project

This repository is structured into multiple folders containing both frontend and backend code. Here's an overview:

📁 backend_api_integration
   ├── 📁 backend     → Node.js/Express API
   └── 📁 frontend    → React frontend (User & Admin modules)

📁 frontend             → Main frontend interface (React)

📦 Prerequisites

Before you begin, make sure you have the following installed on your system:

* [Node.js](https://nodejs.org/) (v14 or higher)
* [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
* Git (to clone the project)

🧩 Step 1: Clone the Repository-----    
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
⚙️ Step 2: Start the Backend (API Integration)----------
cd backend_api_integration/backend
npm install
npm start

This will start the backend server (API) on: http://localhost:5000

🖥️ Step 3: Start the API Frontend (User & Admin Modules)

cd ../frontend
npm install
npm start

This will run the React frontend that interacts with the backend.

Modules included:

* ✅ **User Module**
* 🛠️ **Admin Module**

Access via: http://localhost:3000

🌐 Step 4: Start the Main Frontend (Optional)

If your project includes a separate main frontend:

cd ../../frontend
npm install
npm start

It will also run on: http://localhost:3000 (or another port if already in use)

