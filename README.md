
📘 College CRM (Student & Teacher Portal)

This is a College CRM (Customer Relationship Management)system built using Django for backend and customized HTML/CSS for frontend. The platform supports role-based navigation for both students and teachers, making it easier to manage academic interactions, data, and user-specific pages.

🚀 Features

- 🔐 Role-based navigation for students and teachers
- 🧑‍🏫 Separate apps for each role (`students/` and `teachers/`)
- 📄 Frontend template adapted and enhanced from [this CodePen template](https://codepen.io/Mashibe/pen/GRmvdvv)
- 🛠️ Modular Django app structure
- 🗂 Template-based rendering with `navbar.html`, `student.html`, and `index.html`
- 🗃 SQLite database (`db.sqlite3`) for simple local development
- 🖼️ Media and static file support

🛠 Tech Stack

- Backend: Django
- Frontend: HTML/CSS (customized from CodePen)
- Database: SQLite
- Environment: Python Virtual Environment (`clgenv/`)

 📁 Folder Structure

```
College_CRM/
├── clgenv/                  # Python virtual environment
├── school/
│   ├── manage.py
│   ├── db.sqlite3
│   ├── media/
│   ├── static/
│   ├── templates/
│   │   ├── index.html
│   │   ├── navbar.html
│   │   └── student.html
│   ├── students/            # Student module
│   └── teachers/            # Teacher module
```

 ⚙️ Setup Instructions

1. Clone the repo  
   ```bash
   git clone https://github.com/marennagarikurumurthy2005/College-CRM.git
   cd College_CRM/school
   ```

2. Create a virtual environment (optional if already present)  
   ```bash
   python -m venv clgenv
   source clgenv/Scripts/activate  # On Windows
   ```

3. Install dependencies  
   ```bash
   pip install django
   ```

4. Run migrations and start the server  
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

📝 Credits

Frontend template inspired by [Mashibe's CodePen](https://codepen.io/Mashibe/pen/GRmvdvv).
