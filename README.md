# 📝 TODO List Application

A modern, full-stack Todo List application built with React and Node.js, featuring a clean UI with theme switching capabilities.

## 📖 Project Description

This is a feature-rich Todo List application that allows users to manage their daily tasks efficiently. The application provides a seamless user experience with real-time updates, persistent storage, and a beautiful interface that supports both light and dark themes.

## ✨ Project Details

- **Frontend**: Built with React and Vite for fast development and optimal performance
- **Backend**: RESTful API powered by Node.js and Express
- **Database**: MongoDB for reliable data persistence
- **Styling**: Custom CSS with responsive design
- **Theme Support**: Light and dark mode toggle

## 🛠️ Tech Stack

### Frontend
- **React** - UI library for building interactive interfaces
- **Vite** - Next-generation frontend tooling
- **Axios** - HTTP client for API requests
- **Context API** - State management for theme

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### Development Tools
- **ESLint** - Code linting
- **npm** - Package management

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas account)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abinesh2418/todo-list.git
   cd TODO-LIST
   ```

2. **Install frontend dependencies**
   ```bash
   npm install
   ```

3. **Install backend dependencies**
   ```bash
   cd api
   npm install
   cd ..
   ```

4. **Configure the database**
   - Create a MongoDB database or use MongoDB Atlas
   - Update the database configuration in `api/config/db.js`

5. **Start the backend server**
   ```bash
   cd api
   node server.js
   ```

6. **Start the frontend development server**
   ```bash
   npm run dev
   ```

7. **Open your browser**
   - Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📁 Project Structure

```
TODO-LIST/
├── api/                      # Backend application
│   ├── config/              # Configuration files
│   │   └── db.js           # Database configuration
│   ├── controllers/        # Request handlers
│   │   └── todoController.js
│   ├── models/             # Database models
│   │   └── todoModels.js
│   ├── views/              # Routes
│   │   └── todoRoutes.js
│   ├── package.json        # Backend dependencies
│   └── server.js           # Express server setup
├── src/                    # Frontend application
│   ├── components/         # React components
│   │   ├── TaskForm.jsx   # Form for adding tasks
│   │   ├── TaskItem.jsx   # Individual task component
│   │   ├── TaskList.jsx   # List of tasks
│   │   └── ThemeContext.jsx # Theme management
│   ├── App.css            # Main styles
│   ├── App.jsx            # Root component
│   ├── axios.js           # Axios configuration
│   ├── index.css          # Global styles
│   └── main.jsx           # Application entry point
├── eslint.config.js       # ESLint configuration
├── index.html             # HTML template
├── package.json           # Frontend dependencies
├── vite.config.js         # Vite configuration
└── README.md              # Project documentation
```

## 📬 Contact

For any queries or suggestions, feel free to reach out:

- 📧 **Email:** abineshbalasubramaniyam@gmail.com
- 💼 **LinkedIn:** [linkedin.com/in/abinesh-b-1b14a1290/](https://linkedin.com/in/abinesh-b-1b14a1290/)
- 🐙 **GitHub:** [github.com/Abinesh2418](https://github.com/Abinesh2418)
- 💻 **LeetCode:** [leetcode.com/u/abinesh_06/](https://leetcode.com/u/abinesh_06/)