
# 📝 ToDo List

A simple and intuitive ToDo List web application built with **HTML, CSS and JavaScript**, powered by [Vite](https://vite.dev/).

The application allows users to manage their daily tasks, track their progress and keep their personal to-do list saved directly in the browser.

## ✨ Features

- **Add tasks:** Create new tasks by entering a description.
- **Complete tasks:** Click on a task to mark it as completed or restore it to pending.
- **Delete tasks:** Remove individual tasks from the list.
- **Clear completed tasks:** Delete all completed tasks at once.
- **Progress tracking:** View the total number of tasks, completed tasks and remaining tasks.
- **Personalized welcome:** Enter your name to receive a personalized welcome message.
- **Automatic data persistence:** Tasks and your name are saved using the browser's `localStorage`.
- **Task organization:** Completed tasks are automatically displayed after pending tasks.

## 🛠️ Technologies

- **HTML5** – Application structure.
- **CSS3** – Styling and layout.
- **JavaScript (ES Modules)** – Application logic and task management.
- **Vite** – Development server and build tool.
- **LocalStorage** – Client-side data persistence.

## 📁 Project Structure

```text
ToDo-List/
│
├── src/
│   ├── main.js       # Application logic
│   └── style.css     # Application styles
│
├── index.html        # Main HTML page
├── package.json      # Project configuration and scripts
├── package-lock.json # Dependency lock file
└── .gitignore        # Git ignored files
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js).
- [Git](https://git-scm.com/).

### Installation

1. Clone the repository:

```bash
git clone https://github.com/TommasoSaleri/ToDo-List.git
```

2. Navigate to the project directory:

```bash
cd ToDo-List
```

3. Install dependencies:

```bash
npm install
```

### Run the Development Server

Start the Vite development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal (usually `http://localhost:5173/`) in your browser.

## 📦 Production Build

To generate an optimized production build, run:

```bash
npm run build
```

The generated files will be available in the `dist/` directory.

To preview the production build locally:

```bash
npm run preview
```

## 💾 Data Persistence

The application uses the browser's `localStorage` to store information:

- `todo-tasks`: Stores the task list, including task IDs, titles and completion status.
- `todo-nome`: Stores the user's name for the personalized welcome message.

Data remains available after refreshing or reopening the browser, as long as the browser's local storage is not cleared.

**Note:** Data is stored locally in the browser and is not synchronized between different devices or browsers.

## 📸 Usage

1. Open the application in your browser.
2. Enter your name when prompted.
3. Type a task in the input field.
4. Click **Aggiungi** to add it to your list.
5. Click on a task to mark it as completed.
6. Use the **×** button to delete an individual task.
7. Use **Elimina completati** to remove all completed tasks.

## 👨‍💻 Author

**Tommaso Saleri**

GitHub: [@TommasoSaleri](https://github.com/TommasoSaleri)

## 📄 License

No license has currently been specified for this repository. Please contact the author before redistributing or reusing the code.
