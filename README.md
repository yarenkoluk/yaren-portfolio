# Yaren | Software Engineering Portfolio 🚀
A personal portfolio website built with **Django**, **Python**, and **Bootstrap** to showcase my projects, technical blog posts, and software engineering skills.
This project reflects my learning journey as a Software Engineering student at Near East University.

## 🛠 Tech Stack
- **Backend:** Python & Django Framework
- **Frontend:** Bootstrap 5, HTML5, CSS3
- **Database:** SQLite
- **Management:** Django Admin Panel

## 🌟 Key Features
- **Dynamic Project Gallery:** A dedicated space for my software projects (e.g., Python Snake Game) with detailed descriptions.
- **Technical Blog:** An area where I post about my coding journey, school projects (Computer Architecture, Physics experiments, etc.), and technical tutorials.
- **Categorization:** Fully functional category system for both blog posts and projects.
- **Responsive Design:** Optimized for a seamless experience across all devices (mobile, tablet, and desktop).

## 📁 Project Structure
- `personal_portfolio/`: Core Django project settings.
- `blog/`: Application managing the blog posts and comments.
- `projects/`: Application managing the project portfolio gallery.
- `media/`: Storage for project screenshots and profile images.

## 🚀 Local Setup
```bash
git clone https://github.com/yarenkoluk/yaren-portfolio.git
cd yaren-portfolio

python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.
