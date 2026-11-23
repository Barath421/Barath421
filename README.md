from pathlib import Path

content = """# Hi 👋, I'm Barath

### 🚀 Aspiring DevOps Engineer | Cloud Computing Enthusiast | Software Developer

I'm a Computer Science and Engineering student passionate about **Cloud Computing, DevOps, Automation, and Software Development**. I enjoy learning new technologies, building practical projects, and exploring ways to automate and optimize software development and deployment workflows.

- 🔭 Currently exploring **DevOps and Cloud Engineering**
- ☁️ Learning AWS Cloud Services and Cloud Infrastructure
- 🐳 Interested in Docker, Kubernetes, and CI/CD Pipelines
- 💻 Skilled in Python, Java, C, C++, HTML, CSS, and JavaScript
- 🌱 Improving my knowledge of Linux, Git, GitHub, and Cloud Technologies
- 🎯 Goal: To become a skilled DevOps and Cloud Engineer

---

### 🛠️ Technical Skills

**☁️ Cloud Computing**
- Amazon Web Services (AWS)
- EC2, S3, VPC, IAM

**⚙️ DevOps & Tools**
- Git & GitHub
- Linux
- Docker
- Kubernetes
- Jenkins
- CI/CD

**💻 Programming Languages**
- Python
- Java
- C
- C++
- JavaScript

**🌐 Web Technologies**
- HTML
- CSS
- JavaScript

**🗄️ Database**
- MySQL
- DBMS
- SQL

---

### ☁️ Cloud & DevOps Learning Journey

- Exploring AWS cloud infrastructure and services.
- Practicing EC2 instance creation and management.
- Learning S3 storage and bucket management.
- Understanding VPC networking and cloud security.
- Practicing Git and GitHub version control.
- Exploring containerization and CI/CD automation.

---

### 📂 Projects & Hands-on Practice

- **AWS Cloud Labs:** Hands-on practice with EC2, S3, VPC, and AWS networking.
- **Healthcare Chatbot:** AI-powered chatbot developed using Python and Google Gemini API.
- **College Suggestion System:** Data-driven college recommendation system for TNEA counselling.
- **Wildlife Sanctuary Management System:** Web-based management application using PHP and MySQL.

---

### 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight)

---

### 🤝 Connect With Me

- GitHub:https://github.com/Barath421
- LinkedIn: in/barath-p-a56956257
- Email: barathvaj421@gmail.com

---

### 💡 My Motto

**"Learn continuously, automate everything possible, and build solutions that scale."**

⭐ Thanks for visiting my profile! Let's connect, collaborate, and grow together.
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
