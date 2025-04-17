# Book Review

Brief description of your project.

## Setup Instructions

Follow these steps to set up the project locally.

### Prerequisites
- Node.js (version X.X or higher)
- npm (usually comes with Node.js)
- MongoDB (or MongoDB Atlas for cloud database)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Install dependencies:
  npm install

3. Create a .env.local and .env.dev file in the root directory with the following variables:
  MONGO_URL=your_mongodb_connection_string
  PORT=your_preferred_port (e.g., 3000)
  SALT_ROUNDS=your_salt_rounds_number (e.g., 10)
  JWT_SECRET=your_jwt_secret_key
  DB_NAME=your_db_name

Running the Application
Start the development server:

npm run local 
npm run dev

//depednign on environment
