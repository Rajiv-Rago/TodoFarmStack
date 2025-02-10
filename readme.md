# 📋 Simple To-do App

A straightforward, web-based to-do list application designed to help you manage your tasks effortlessly.

## 🚀 Key Features

- **Add & Remove Todo Lists:** Organize tasks into separate lists for better clarity.
- **Add & Remove Todo Tasks:** Easily manage tasks within each list.

## 🛠️ Technologies Used

- **Backend:** FastAPI
- **Frontend:** React.js
- **Database:** MongoDB

## ⚙️ Installation & Setup

### Prerequisites

- **Python** (Ensure it's installed and added to your PATH)
- **Node.js** (Required for the frontend)
- **MongoDB** (External MongoDB server setup)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/simple-todo-app.git
   cd simple-todo-app
   ```
2. **Run the application using Docker Compose:**
   ```bash
   docker-compose -f compose.yaml up
   ```

## 💻 How to Run the Project

### Development Mode

To run the project in development mode:
```bash
   docker-compose up
```

This will start both the FastAPI backend and the React frontend.

## 📦 Usage Examples

### Basic Usage

- **Create a Todo List:** Add lists to categorize your tasks.
- **Manage Tasks:** Add and remove tasks within each list to stay organized.

### API Endpoints

- **Base URL:** `http://localhost:8000`
- Example request to get all todos:

## 🤝 Contributing Guidelines

We welcome contributions! Follow these steps to get started:

### How to Contribute

- **Fork the repository** and create your branch:
  ```bash
  git checkout -b feature/YourFeature
  ```
- **Commit your changes:**
  ```bash
  git commit -m "Add new feature"
  ```
- **Push to the branch:**
  ```bash
  git push origin feature/YourFeature
  ```
- **Open a Pull Request** with a clear description of your changes.

### Code Style Guidelines

- Follow **PEP 8** for Python code.
- Use **ESLint** standards for React code.
- Write clear, concise commit messages.

## 🙌 Acknowledgments

This project is inspired by the Todo List project from FreeCodeCamp's **FARM Stack Course**. A big thank you to the creators for their valuable content!

