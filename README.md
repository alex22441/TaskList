# 📝 Task List React App

A simple yet powerful **Task List App** built with **React + Vite + TypeScript**.  
This project was created **from scratch as a learning exercise** to understand React fundamentals — including components, props, state, hooks, and localStorage persistence.

---

## 🎯 Project Goal

Build a task management application that allows users to:
- Add, edit, delete, and mark tasks as completed.
- Filter tasks by status (`All`, `Active`, `Completed`).
- Search tasks by title or description.
- Persist data locally using `localStorage`.
- Maintain a clean and accessible user experience.

---

## 🚀 Features

| Feature | Description |
|----------|--------------|
| ➕ **Add Tasks** | Add a new task with title (required) and optional description. |
| ✏️ **Edit Tasks** | Edit the title or description of an existing task. |
| ✅ **Complete Tasks** | Toggle tasks between “completed” and “active.” |
| ❌ **Delete Tasks** | Remove tasks permanently. |
| 🔍 **Search & Filter** | Filter by completion status and search by text. |
| 💾 **Persistent Storage** | Tasks and filter preferences are stored in localStorage. |
| ♿ **Accessible UI** | Keyboard-friendly, with focus styles and labels. |
| 📱 **Responsive Layout** | Works across desktop and mobile devices. |

---

## 🧩 Tech Stack

- **React 18**
- **Vite** for fast development and hot module replacement.
- **TypeScript** for type safety.
- **CSS Modules** (or plain CSS) for styling.
- **uuid** (optional) for unique task IDs.

---

## 📂 Project Structure

```bash
task-list/
├─ src/
│  ├─ components/
│  │  ├─ AddTaskForm.tsx          # Form for creating new tasks
│  │  ├─ TaskItem.tsx             # Individual task with edit/toggle/delete
│  │  ├─ TaskList.tsx             # Renders list of tasks
│  │  ├─ Filters.tsx              # Buttons for All / Active / Completed
│  │  └─ SearchBox.tsx            # Search input for task filtering
│  ├─ hooks/
│  │  └─ useLocalStorage.ts       # Custom hook for persistence
│  ├─ types/
│  │  └─ task.ts                  # TypeScript type definition for Task
│  ├─ App.tsx                     # Main app component
│  ├─ main.tsx                    # Entry point
│  ├─ app.css                     # Global app styles
│  └─ index.css                   # Reset/base CSS
├─ public/
├─ package.json
└─ README.md

