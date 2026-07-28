<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=180&section=header&text=amit2227%40github:~%24&fontColor=00FF41&fontSize=38&fontAlignY=38&animation=fadeIn&desc=Software%20Engineer%20%7C%20MERN%20%7C%20Agentic%20AI&descAlignY=58&descSize=16&descColor=00FF41" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=700&color=00FF41&background=0D1117&center=true&vCenter=true&width=650&lines=%24+whoami;%3E+amit_jirobe+%E2%80%94+full-stack+%2B+AI+systems;%24+cat+status.txt;%3E+building+%7C+learning+%7C+shipping;%24+./connect.sh" alt="Typing SVG" />

</div>

<br>

```bash
┌──(amit㉿github)-[~]
└─$ cat about.md
```

```yaml
role:        Software Engineering Student — B.Tech CSE, PCCOE (2027)
stack:       MERN — React / Node.js / Express / MongoDB
focus:       Agentic AI · RAG Pipelines · Cloud (OCI/AWS) · n8n Automation
cert:        OCI 2025 Generative AI Professional
location:    Pune, India
links:       portfolio.sh · linkedin.sh · mail.sh
status:      [ONLINE] currently building
```

<br>

```bash
┌──(amit㉿github)-[~]
└─$ ./skills.sh --animate
```

<div align="center">
  <img src="./skills-animated.svg" alt="animated skill bars" width="100%"/>
</div>

<sub>⚠ This is a custom animated SVG — upload <code>skills-animated.svg</code> to the root of your <code>amit2227-github</code> repo for it to render (file provided alongside this README).</sub>

<br>

```bash
┌──(amit㉿github)-[~]
└─$ ls -la ./tech-stack/
```

<p align="left">
<img src="https://skillicons.dev/icons?i=cpp,java,js,ts,py,html,css,react,nodejs,express,mongodb,mysql,tailwind,docker,git,aws,oracle&perline=9&theme=dark" />
</p>

<br>

```bash
┌──(amit㉿github)-[~]
└─$ ./run_projects.sh --list
```

| `PROCESS` | `DESCRIPTION` | `STACK` |
|---|---|---|
| `[MJGPT]` → running | AI chat app · OpenAI API · JWT auth · Stripe subscriptions | MERN, OpenAI, Stripe |
| `[Wanderlust]` → running | Full-stack property listing platform · Passport.js auth | Node, Express, MongoDB, EJS |

<br>

```bash
┌──(amit㉿github)-[~]
└─$ ./contribution_snake.sh
```

<div align="center">
  <img src="https://raw.githubusercontent.com/amit2227-github/amit2227-github/output/github-contribution-grid-snake-dark.svg" alt="snake animation" width="100%"/>
</div>

<br>

```bash
┌──(amit㉿github)-[~]
└─$ ./stats --verbose
```

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=amit2227-github&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00FF41&icon_color=00FF41&text_color=00FF41&ring_color=00FF41" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=amit2227-github&hide_border=true&background=0D1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&currStreakNum=FFFFFF&sideLabels=00FF41&sideNums=FFFFFF&dates=00FF41" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amit2227-github&layout=compact&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=00FF41" />
  <img src="https://github-profile-trophy.vercel.app/?username=amit2227-github&theme=matrix&no-frame=true&row=2&column=3&margin-w=6&margin-h=6" height="150"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=amit2227-github&bg_color=0D1117&color=00FF41&line=00FF41&point=FFFFFF&area=true&hide_border=true" width="100%" />
</div>

<br>

```bash
┌──(amit㉿github)-[~]
└─$ echo $CONNECT
```

<p align="center">
  <a href="https://amitjirobe.onrender.com/"><img src="https://img.shields.io/badge/-PORTFOLIO-000000?style=for-the-badge&logoColor=00FF41&labelColor=000000" /></a>
  <a href="https://www.linkedin.com/in/amit-jirobe-a48484295/"><img src="https://img.shields.io/badge/-LINKEDIN-000000?style=for-the-badge&logo=linkedin&logoColor=00FF41&labelColor=000000" /></a>
  <a href="mailto:amitjirobe07@gmail.com"><img src="https://img.shields.io/badge/-EMAIL-000000?style=for-the-badge&logo=gmail&logoColor=00FF41&labelColor=000000" /></a>
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF41,100:0D1117&height=100&section=footer" width="100%"/>
</div>

---

### ⚙️ SETUP.md

**1. Animated skill bars**
Upload `skills-animated.svg` (provided) to the root of your `amit2227-github` repo. The image tag above already points to it via a relative path.

**2. Contribution snake** (one-time, ~2 min)

Create `.github/workflows/snake.yml` in the same repo:

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

Commit → go to **Actions** tab → run the workflow manually once. It creates an `output` branch with the animated SVG that the snake image above already points to. Refreshes daily on its own after that.
