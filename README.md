<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=26&pause=1200&color=7AA2F7&center=true&vCenter=true&width=560&lines=Amit+Jirobe;Full-Stack+(MERN)+Developer;Building+with+AI+%2B+Automation" alt="Typing SVG" />

<p>
<a href="https://amitjirobe.onrender.com/"><img src="https://img.shields.io/badge/Portfolio-24292F?style=flat-square&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/amit-jirobe-a48484295/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:amitjirobe07@gmail.com"><img src="https://img.shields.io/badge/Email-24292F?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

</div>

&nbsp;

## About

B.Tech Computer Science student (PCCOE, Pune — expected 2027) building full-stack web applications on the MERN stack. Currently extending into AI systems — Retrieval-Augmented Generation, agentic workflows, and automation with n8n — alongside cloud fundamentals on OCI and AWS.

OCI Generative AI Professional certified &nbsp;·&nbsp; 70+ problems solved on LeetCode

&nbsp;

## Stack

<p align="left">
<img src="https://skillicons.dev/icons?i=cpp,java,js,ts,py,html,css,react,nodejs,express,mongodb,mysql,tailwind,bootstrap,docker,git,github,postman,aws,oracle&perline=10" />
</p>

**Currently exploring:** LangChain · RAG pipelines · n8n · Agentic AI patterns

&nbsp;

## Experience

**Software Development Intern (Freelance)** — Dhritsthal &nbsp;`Mar 2026 – Apr 2026`
Configured SMTP/email systems, implemented form validation, improved SEO and site reliability, integrated analytics.

**Software Development Intern** — Robota Solution &nbsp;`Jun 2023 – Jul 2023`
Built Arduino-based embedded systems in C/C++; hands-on PCB design and hardware integration.

&nbsp;

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[MJGPT — AI Chat Application](https://github.com/amit2227-github)**

Full-stack ChatGPT-style app with OpenAI API integration, JWT/bcrypt authentication, and Stripe subscriptions.

`MongoDB` `Express` `React` `Node.js` `OpenAI API` `Stripe`

</td>
<td width="50%" valign="top">

**[Wanderlust — Property Listing Platform](https://github.com/amit2227-github)**

MVC web app with full CRUD for listings and reviews, Passport.js auth with ownership-based access control, Joi validation.

`Node.js` `Express` `MongoDB` `EJS` `Bootstrap`

</td>
</tr>
</table>

&nbsp;

## GitHub Activity

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=amit2227-github&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=amit2227-github&hide_border=true&theme=tokyonight" height="165"/>
</div>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amit2227-github&layout=compact&hide_border=true&theme=tokyonight" height="165"/>
<img src="https://github-profile-trophy.vercel.app/?username=amit2227-github&theme=tokyonight&no-frame=true&row=2&column=3&margin-w=8&margin-h=8" height="165"/>
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=amit2227-github&theme=tokyo-night&hide_border=true&hide_title=true" width="100%" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/amit2227-github/amit2227-github/output/github-contribution-grid-snake-dark.svg" width="100%" />
</div>

<sub>Snake animation needs a one-time GitHub Action — see setup below.</sub>

&nbsp;

## Contact

Email: amitjirobe07@gmail.com &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/amit-jirobe-a48484295/) &nbsp;·&nbsp; [Portfolio](https://amitjirobe.onrender.com/)

---

<details>
<summary><b>⚙ Setup: activate the snake animation (one-time, ~2 min)</b></summary>
<br>

1. In your `amit2227-github` repo, create `.github/workflows/snake.yml`
2. Paste:

```yaml
name: Generate Snake Animation
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: amit2227-github
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Commit → go to the **Actions** tab → run the workflow manually once.
4. It creates an `output` branch with the animated SVG, which the image above already points to.
5. Refreshes daily on its own after that.

</details>
