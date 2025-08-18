# Create a downloadable README.md file with the animated, professional profile template
content = """<!--
INSTRUCTIONS: Replace ALL occurrences of `your-username`, `your-email`, and links with your details.
Commit this file as README.md in a repo named exactly your GitHub username: your-username/your-username
-->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=28&pause=1000&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Prince+Kumar;I+build+clean%2C+practical+software;Web+Dev+%7C+AI%2FML+%7C+Data+Science" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/your-username?tab=followers"><img src="https://img.shields.io/github/followers/your-username?label=Followers&logo=github" alt="followers" /></a>
  <a href="https://github.com/your-username"><img src="https://img.shields.io/github/stars/your-username?affiliations=OWNER%2CCOLLABORATOR&label=Stars" alt="stars" /></a>
  <img src="https://komarev.com/ghpvc/?username=your-username&style=flat-square" alt="profile views"/>
  <a href="mailto:your-email"><img src="https://img.shields.io/badge/Email-Contact-informational" alt="email"/></a>
  <a href="https://www.linkedin.com/in/your-link/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue" alt="LinkedIn"/></a>
</p>

---

## About me
- CSE student focusing on **Web Development**, **AI/ML**, and **Data Science**.
- Currently building **EduGenius AI** and an **Image Restoration App**.
- I like shipping small, well-documented projects and learning in public.

## Skills
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
</p>

## Featured projects
> Pin these on your profile for quick access.

- **EduGenius AI** – AI-powered learning assistant.
  - Repo: https://github.com/your-username/edugenius-ai
  - Demo: https://your-demo-link
- **Image Restoration App** – Restore old or damaged photos with deep learning.
  - Repo: https://github.com/your-username/image-restoration
  - Demo: https://your-demo-link
- **DSA Notebook** – Clean, well-tested solutions with explanations.
  - Repo: https://github.com/your-username/dsa-notebook

## Stats
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&hide_title=true&rank_icon=github" alt="stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=your-username" alt="streak" />
</p>

<p align="center">
  <img height="195" src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-username&layout=compact" alt="top langs"/>
</p>

<!-- Contribution Snake (enable the action in a public repo, then update the URL below) -->
<p align="center">
  <img src="https://raw.githubusercontent.com/your-username/your-username/output/snake.svg" alt="snake animation"/>
</p>

## Get in touch
- Portfolio: https://your-portfolio.site
- LinkedIn: https://www.linkedin.com/in/your-link/
- Email: your-email

---

### Setup notes
- Keep READMEs short, with screenshots and setup steps.
- Use clear commit messages. Add a license and a `.gitignore`.
- Pin your best 5–6 repos.

<!--
Optional extras to explore later:
- Activity graph: https://github-readme-activity-graph.vercel.app/graph?username=your-username
- Profile summary cards: https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=your-username
- Shields directory: https://shields.io/
-->
"""
path = "/mnt/data/README.md"
with open(path, "w", encoding="utf-8") as f:
    f.write(content)
path
