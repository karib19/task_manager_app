# 📝 Task Manager App

A modern and responsive Task Manager application built with React that helps users organize their daily activities efficiently. Users can add, complete, reopen, and delete tasks while keeping their data persistent through Local Storage.

## 🔗 Live Demo

🌐 https://karib19.github.io/task_manager_app/

## 📂 GitHub Repository

💻 https://github.com/karib19/task_manager_app

## ✨ Features

* ➕ Add new tasks
* ✅ Mark tasks as completed
* 🔄 Reopen completed tasks by marking them as pending
* 🗑️ Delete tasks
* 📅 Automatically records the creation date and time of each task
* 🏷️ Displays task status badges (Pending / Completed)
* 📊 Real-time dashboard showing:

  * Total Tasks
  * Completed Tasks
  * Pending Tasks
* 📌 Displays the latest task added
* 🔃 Automatically sorts tasks so pending tasks appear before completed ones
* 💾 Saves all tasks using Local Storage
* 📱 Fully responsive design for desktop and mobile devices
* 🎨 Modern UI built with Tailwind CSS

## 🛠️ Technologies Used

* React.js
* JavaScript (ES6+)
* Tailwind CSS
* HTML5
* Local Storage API
* Git
* GitHub
* GitHub Pages

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/karib19/task_manager_app.git
```

Move into the project directory:

```bash
cd task_manager_app
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

## 📂 Project Structure

```text
task manager app using react/
├── screenshots/
├── Task/
│  ├── public/
│  ├── src/
│    ├── components/
│    │    └── Task.jsx
│    ├── App.jsx
│    ├── App.css
│    └── main.jsx
└── README.md

## 💡 How It Works

* Users can create tasks using the input field.
* Each task receives a unique ID generated using `Date.now()`.
* The creation timestamp is stored and displayed in a user-friendly format.
* Tasks can be marked as done or switched back to pending.
* All changes are instantly saved to Local Storage.
* When the application reloads, previously saved tasks are restored automatically.


## 👨‍💻 Author

**Sharfuddin Karib**

GitHub: https://github.com/karib19
