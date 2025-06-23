# To-Do-List-App

# ✅ To-Do List App (Python CLI + Streamlit)

This project is a simple and effective **To-Do List App** implemented in two ways:
- 🖥️ A command-line interface (CLI) version, runnable in **Google Colab**
- 🌐 A web app version using **Streamlit**

---

## 🧩 Features

- 📋 View your tasks
- ➕ Add new tasks
- 🗑️ Delete existing tasks
- 💾 Tasks are stored in a `tasks.txt` file for persistence

---

## 🚀 Versions

### 1️⃣ CLI Version (Google Colab)
- File: `todo_colab.ipynb`
- Works directly in [Google Colab]
- Menu-driven interface using `input()` and `print()`

#### 🔽 To download your task list:
Run this cell in a new code cell at the end of your Colab session:

```python
from google.colab import files
files.download("tasks.txt")
