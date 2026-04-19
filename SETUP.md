# SETUP.md

## Development Environment Setup

### Prerequisites
1. **Node.js**: Download and install the latest version from [Node.js official website](https://nodejs.org/).
2. **MongoDB**: Download and install MongoDB from [MongoDB official website](https://www.mongodb.com/try/download/community).
3. **Git**: Install Git from [Git official website](https://git-scm.com/downloads).

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/MakaBettah/CarPart-E-ccommerce.git
   cd CarPart-E-ccommerce
   ```
2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the `backend` directory based on the example `.env.example` file, and fill in the required values.
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install frontend dependencies:
   ```bash
   npm install
   ```
3. Start the frontend application:
   ```bash
   npm start
   ```

### Database Setup
1. Start the MongoDB server:
   ```bash
   mongod
   ```
2. Open another terminal and connect to the MongoDB shell:
   ```bash
   mongo
   ```
3. Create a database for your application:
   ```bash
   use carpart_db
   ```
   - Modify the database name as necessary in the backend `.env` file.

### Running the Application Locally
1. Ensure both backend and frontend servers are running.
2. Access the application in your browser at `http://localhost:3000`.

**Note**: Make sure to resolve any dependency issues and consult documentation for any additional setup that may be required based on your system configuration.