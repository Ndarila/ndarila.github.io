---
layout: home
title: "James Ndarila"
author_profile: true
---

## 🚀 Welcome!

Hi, I’m **James Ndarila** — an ICT Specialist and Data & AI Enthusiast focused on Machine Learning, NLP, and real-world data systems.

I am currently advancing my skills through the **Cyber Shujaa Data & AI Program**, building production-style ML and AI projects.

📄 [Download My Resume (PDF)](/assets/files/assets/James-Ndarila-CV.pdf)

---

## 🎯 What I Do

I design and build end-to-end AI and data systems:

- Machine Learning models for prediction and classification  
- NLP systems using transformer architectures (BERT, HuggingFace)  
- Data analysis, visualization, and storytelling  
- MLOps workflows for automation and deployment  

💡 Focus: Turning raw data into intelligent, production-ready solutions.

---

## 🛠 Technical Skills

- **Programming:** Python, SQL  
- **Machine Learning:** Scikit-learn, XGBoost  
- **Deep Learning:** TensorFlow, Keras, PyTorch  
- **NLP:** BERT, Transformers, HuggingFace  
- **Data Tools:** Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Git, GitHub  

---

## 🔧 Featured Projects (Live GitHub Portfolio)

## 🔧 Featured Projects (Auto-Updating)

<div id="projects">Loading projects...</div>

<script>
const username = "Ndarila";

fetch(`https://api.github.com/users/${username}/repos?sort=updated`)
  .then(res => res.json())
  .then(repos => {

    const container = document.getElementById("projects");

    // remove forks + limit to top 8 most relevant repos
    const filtered = repos
      .filter(r => !r.fork)
      .sort((a, b) => b.stargazers_count - a.stargazers_count)
      .slice(0, 8);

    container.innerHTML = filtered.map(repo => `
      <div style="
        border:1px solid #ddd;
        padding:15px;
        margin-bottom:12px;
        border-radius:10px;
        transition:0.2s;
      ">

        <h3>🚀 <a href="${repo.html_url}" target="_blank">
          ${repo.name}
        </a></h3>

        <p>${repo.description || "AI/ML project - no description yet"}</p>

        <small>
          ⭐ ${repo.stargazers_count} | 🍴 ${repo.forks_count} | 🧠 ${repo.language || "Mixed"}
        </small>

      </div>
    `).join("");
  });
</script>---

## 📝 Latest Posts

{% if site.posts.size > 0 %}
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) – {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
{% else %}
_No blog posts yet. Check back soon!_
{% endif %}

---

## 📫 Contact

- GitHub: https://github.com/Ndarila  
- Portfolio: https://ndarila.github.io  
- LinkedIn: https://www.linkedin.com/in/james-ndarila-2185971a4  

---

⭐ Built with passion for AI, Data Science, and real-world problem solving.