# 📚 Bookstore Management System  

A lightweight bookstore management system built with **Flask**, **SQLite**, **Bootstrap**, and **JavaScript**.  

---

## 🚀 Features
- Manage books (CRUD operations).
- Record and view sales transactions.
- Real-time book stock updates upon sales.
- Responsive UI using **Bootstrap**.
- Supports light and dark themes with **lightstyle.css** and **darkstyle.css**.

---

## 🛠️ Tech Stack
- **Back-end**: Flask
- **Database**: SQLite
- **Front-end**: HTML, CSS, JavaScript, Bootstrap 5
- **Styling**: Custom and Bootstrap styles

---

## 📂 Project Structure  
```
📂 Project Directory
├── 📁 templates
│   └── index.html    # Main HTML file
├── 📁 static
│   ├── script.js     # JavaScript for dynamic functionality
│   ├── lightstyle.css # Light theme styling file
│   ├── darkstyle.css  # Dark theme styling file
│   └── favicon.png   # Favicon
├── app.py            # Flask application
├── bookstore.db      # SQLite database (generated at runtime)
└── README.md         # Project documentation
```
## 🚀 Getting Started
### 1. Prerequisites
Ensure you have Python 3.x installed.

### 2. Installation
#### 1. Install dependencies:
```
pip install flask flask-cors
```

#### 2. Run the Flask application:
```
python app.py
```
#### 3. Open your browser and navigate to:
```
http://127.0.0.1:5000
```
| Feature          | Description                     | Status    |
|-------------------|---------------------------------|-----------|
| Add Books         | Add new books to the system    | ✅ Done   |
| Update Books      | Edit book details              | ✅ Done   |
| Delete Books      | Remove books from the system   | ✅ Done   |
| Dark Theme        | Switch to dark mode styling    | 🟡 In Progress |
| Sales Reporting   | Generate sales reports         | ❌ Pending |
