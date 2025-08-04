# 📝 Task List – Tailwind CSS Practice
This is a simple project to practice building a task list interface using **HTML** and **Tailwind CLI**. It’s meant for experimenting with utility classes, responsive layout, and modern project structure.

---
## 📁 Project Structure
- `index.html` – Main HTML file  
- `src/`
  - `css/`
    - `input.css` – Source CSS with Tailwind directives (`@tailwind base;`, etc.)
  - `dist/`
    - `output.css` – Compiled Tailwind CSS
- `package.json` – Project dependencies and scripts
- `package-lock.json` – Auto-generated version lock
- `.gitignore` – Ignored files and folders (like `node_modules`, `dist/`, etc.)
---
## 🚀 How to Run
1. **Install dependencies**
  Make sure Node.js is installed, then run:
```bash
npm install
```
  2. Compile Tailwind in watch mode
```bash
npm run tailwindDev
```
This will compile `src/css/input.css` into `src/dist/output.css` and watch for changes automatically.
## 🛠 Scripts
Defined inside `package.json`:
```json
"scripts": {
  "tailwindDev": "tailwindcss -i ./src/css/input.css -o ./src/dist/output.css --watch"
}
```
## 🧾 .gitignore
```bash
node_modules/
dist/
.env
.DS_Store
.vscode/
*.log
```
