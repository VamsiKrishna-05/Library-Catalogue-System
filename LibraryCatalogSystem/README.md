# 📚 Library Catalogue System

A simple yet powerful Java application that allows users to manage a collection of books using both a Command-Line Interface (CLI) and a Graphical User Interface (GUI) built with Swing.

## ✨ Features

- ✅ Add new books to the catalog
- 🔍 Search books by **Title** or **Author**
- 📋 List all books
- ✏️ Update book details by ISBN
- ❌ Delete books from the catalog
- 🖥️ GUI support for a more user-friendly experience
- 💾 Uses `HashMap` for fast lookup based on ISBN

---

## 🧱 Project Structure

```bash
LibraryCatalogSystem/
│
├── Book.java             # Book model class
├── Library.java          # Core logic (add, search, update, delete)
├── LibraryApp.java       # CLI interface
├── LibraryGUIApp.java    # GUI using Java Swing
└── background.png        # (Optional) background image for GUI


## How to Run

1. Compile all Java files:
   ```bash
   javac *.java
