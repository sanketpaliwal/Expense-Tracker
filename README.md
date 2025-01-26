# Expense Tracker (CRUD MERN App)

An **Expense Tracker** application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). This app allows users to efficiently track their expenses with Create, Read, Update, and Delete (CRUD) functionality.

---

## 🛠️ Features
- Add, edit, and delete expenses.
- View a summary of all expenses.
- Categorize expenses (e.g., food, travel, utilities).
- Responsive and user-friendly interface.
- RESTful APIs for CRUD operations.
- Data persistence using MongoDB.
- State management with React Context API or Redux (optional).
- Deployed on [Insert Deployment Platform Here] (e.g., Render, Netlify, Vercel).

---

## 🚀 Tech Stack
### Frontend:
- **React.js** (UI Development)
- **Axios** (API calls)
- **Bootstrap** or **Tailwind CSS** (Styling)
- **React Router** (Navigation)

### Backend:
- **Node.js** (Runtime environment)
- **Express.js** (Server framework)
- **MongoDB** (Database for storing expenses)
- **Mongoose** (ODM for MongoDB)

---

## 📦 Installation

### Prerequisites:
- **Node.js** and **npm/yarn**
- **MongoDB** installed locally or a cloud MongoDB connection (e.g., MongoDB Atlas)

### Steps to Run Locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/expense-tracker.git
    cd expense-tracker
    ```

2. **Install dependencies** for both the client and server:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the `server` directory with the following variables:
    ```env
    MONGO_URI=your-mongodb-connection-string
    PORT=5000
    ```

4. **Start the application**:
    Open two terminals:
    - Start the backend:
      ```bash
      cd server
      npm start
      ```
    - Start the frontend:
      ```bash
      cd client
      npm start
      ```

5. Open your browser and navigate to `http://localhost:3000`.

---

## 📂 Project Structure
