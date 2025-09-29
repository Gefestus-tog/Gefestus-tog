<div align="center">

# 🔥 Gefest

**Backend with a little of Frontend | Python & Django Developer**

Building robust backend systems with Python and Django, while crafting clean frontend interfaces when needed.

[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139)](https://yourportfolio.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@domain.com)

</div>

---

## 🛠️ Tech Stack

Here are the technologies I work with:

<div align="center">

| Technology | Logo | Use Case |
|------------|------|----------|
| **Python** | <img src="img/python_40x40.png" alt="Python" width="40" height="40"> | Backend Development & Scripting |
| **Django** | <img src="img/django_40x40.png" alt="Django" width="40" height="40"> | Web Framework & APIs |
| **PostgreSQL** | <img src="img/postgres_40x40.png" alt="PostgreSQL" width="40" height="40"> | Database Management |
| **HTML** | <img src="img/html_40x40.png" alt="HTML" width="40" height="40"> | Frontend Structure |
| **CSS** | <img src="img/css_40x40.png" alt="CSS" width="40" height="40"> | Styling & Layout |
| **JavaScript** | <img src="img/js_40x40.png" alt="JavaScript" width="40" height="40"> | Frontend Interactivity |
| **Git** | <img src="img/git_40x40.png" alt="Git" width="40" height="40"> | Version Control |

</div>

---

## 💼 My Projects

### 🔧 Backend Focused
- **Django REST API** - Robust backend system with authentication and CRUD operations
- **E-commerce Platform** - Full-featured online store with payment integration
- **Task Management System** - API for project and task tracking

### 🎨 Full Stack
- **Portfolio Website** - Django backend with custom frontend
- **Blog Application** - Content management with admin interface
- **Data Dashboard** - Visualizing data with Django and JavaScript charts

---

## 👥 My Team

<div align="center">

![Team Photo](img/team.png)

### Working Together to Build Amazing Things! 🚀

This is my incredible team! We collaborate on building robust backend systems and user-friendly interfaces. Our diverse skills in both backend and frontend technologies allow us to deliver complete solutions.

**Our Strengths:** Python Development • Database Design • API Creation • Clean Frontends

</div>

---

## 📊 GitHub Stats

<div align="center">

![Gefest's GitHub Stats](https://github-readme-stats.vercel.app/api?username=gefest&show_icons=true&theme=radical&hide_title=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=gefest&layout=compact&theme=radical&hide=html,css)

</div>

---

## 🐍 Python & Django Expertise

```python
# Example of my typical Django view
from django.shortcuts import render
from django.http import JsonResponse
from .models import Project

def project_api_view(request):
    """REST API endpoint for project data"""
    projects = Project.objects.all().values('name', 'description', 'tech_stack')
    return JsonResponse(list(projects), safe=False)