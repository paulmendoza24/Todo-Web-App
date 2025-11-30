# 📝 Vanilla JS Todo App  
A beautiful, responsive **Todo App** built entirely with **Vanilla JavaScript** — no frameworks, no build tools. Tasks persist using **localStorage**, support **drag & drop reordering**, and can be **imported/exported as JSON**.

<p align="center">
  <img src="https://img.shields.io/badge/Vanilla%20JS-Project-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/LocalStorage-Persistent%20Data-4ade80?logo=googlechrome" />
  <img src="https://img.shields.io/badge/License-MIT-6366f1" />
</p>

---

## 📸 Screenshots


<p align="center">
  <img src="/todo-ss.png" width="75%" />
</p>

---

## 🚀 Features

### ✔ Core
- Add, edit, delete tasks  
- Toggle completion  
- Drag & drop to reorder  
- Fast searching  
- Filters: All / Active / Completed  
- Sort by Newest / Oldest  

### 💾 Data
- Stored in `localStorage`
- Export tasks as `.json`
- Import tasks from `.json` (validated + repaired)

### 🎨 UI
- Beautiful dark UI  
- Responsive layout  
- Smooth animations  
- Empty state messages  

---

## 📂 File Structure

    📦 todo-app
          │
          ├── index.html
          └── README.md

---

## ▶️ Running

    Just open:
      index.html

    No dependencies.  
    No build step.  
    Works entirely offline.

---

## ❗ Data Model

    {
      "id": "unique-id",
      "title": "My Task",
      "note": "",
      "done": false,
      "created": 1710000000000
    }

## LocalStorage key:
    vd_todos_v1

## 🌐 Browser Support
- Chrome
- Firefox
- Edge
- Safari

---

## 📜 License: 
MIT License.

---
