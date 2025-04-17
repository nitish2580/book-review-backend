# 📚 Book Review

A simple full-stack web application that allows users to review books. This app includes user authentication, review management, and a seamless user interface for book lovers to share their thoughts.

---

## 🚀 Setup Instructions

Follow these steps to set up the project locally.

### ✅ Prerequisites

Make sure the following are installed on your system:

- [Node.js](https://nodejs.org/) (version X.X or higher)
- npm (comes with Node.js)
- [MongoDB](https://www.mongodb.com/) (or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for a cloud database)

---

### ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Install dependencies
   npm install
3. Create Environment Files
   In the root directory, create .env.local and .env.dev files with the following variables:
<pre> 
MONGO_URL=your_mongodb_connection_string 
PORT=3000
SALT_ROUNDS=10
JWT_SECRET=your_jwt_secret_key
DB_NAME=your_db_name
</pre>

🏃‍♂️ Running the Application
To start the application, use the following commands based on your environment

For local environment:
<pre>
npm run local
</pre>

For development mode:
<pre>
npm run dev
</pre>

