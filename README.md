<!--
  VIDEO: GitHub only plays video that it hosts. Drag an .mp4 into this file in the
  web editor, wait for the github.com/user-attachments/... link to appear, and keep
  that link on its own line. Put it under "work" if you want a demo reel.
-->

<div align="center">

<img src="./assets/hero.svg" alt="Valyrian-Code: folded, tested, reforged." width="100%"/>

<br/>

[![work](https://img.shields.io/badge/work-161C27?style=flat-square)](#work)
[![now](https://img.shields.io/badge/now-161C27?style=flat-square)](#now)
[![stack](https://img.shields.io/badge/stack-161C27?style=flat-square)](#stack)
[![activity](https://img.shields.io/badge/activity-161C27?style=flat-square)](#activity)
[![contact](https://img.shields.io/badge/contact-161C27?style=flat-square)](#contact)

</div>

<br/>

I fine-tune small language models, build backend systems, and send patches upstream to open source projects.
This is the lab account, where experiments live. The polished versions ship from [RAJVEER42](https://github.com/RAJVEER42).

<img src="./assets/divider.svg" width="100%" alt=""/>

## work

| project | what it does |
|:--|:--|
| [phi3-pr-reviewer](https://github.com/Valyrian-Code/phi3-pr-reviewer) | A fine-tuned phi-3 that reviews pull requests. It once flagged a bug I had merged two weeks earlier. |
| [generative-ai-essentials](https://github.com/Valyrian-Code/RAJVEER42-Generative-AI-Essentials-) | The full fine-tuning workflow, documented so the next person skips my mistakes. |
| [notes.](https://github.com/Valyrian-Code/notes.) | Everything I learn, written down in one place. |
| fossology, nrnb, lfevents | Upstream contributions to open source projects. The fossology patch was accepted. |

<img src="./assets/divider.svg" width="100%" alt=""/>

## now

<div align="center">
<img src="./assets/now.svg" alt="Currently training phi-3-mini with QLoRA, shipping phi3-pr-reviewer, studying fine-tuning versus RAG." width="100%"/>
</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,java,spring,go,ts,react,nextjs,docker,kubernetes,aws,postgres&perline=12&theme=dark" alt="Python, PyTorch, Java, Spring, Go, TypeScript, React, Next.js, Docker, Kubernetes, AWS, PostgreSQL"/>
</div>

<br/>

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#121926','primaryTextColor':'#E4ECF6','primaryBorderColor':'#6F7F96','lineColor':'#FFB454','fontFamily':'ui-monospace, monospace'}}}%%
graph LR
  A(["idea"]) --> B["write it in the lab"]
  B --> C{"phi3-pr-reviewer<br/>approves?"}
  C -->|"no"| B
  C -->|"yes"| D(["ship from RAJVEER42"])
  style C stroke:#FFB454
```

<img src="./assets/divider.svg" width="100%" alt=""/>

## activity

<div align="center">

<!-- The snake appears after you run the workflow once (see .github/workflows/snake.yml).
     Until then this points at a demo so nothing renders broken. After the first run, swap BOTH urls to:
       https://raw.githubusercontent.com/Valyrian-Code/Valyrian-Code/output/github-contribution-grid-snake-dark.svg
       https://raw.githubusercontent.com/Valyrian-Code/Valyrian-Code/output/github-contribution-grid-snake.svg -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="100%"/>
</picture>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Valyrian-Code&hide_border=true&hide_title=true&bg_color=00000000&color=9FB0C8&line=6F7F96&point=FFB454&area=true&area_color=1A2230" alt="Contribution activity graph" width="100%"/>

</div>

<br/>

<details>
<summary><b>lab log</b></summary>
<br/>

```diff
+ adapter merged. loss went down and stayed down
+ pr bot deployed. it immediately requested changes on my own code
! vram at 97%
- colab free tier killed the session at epoch 3 of 4
+ fossology patch accepted upstream
```

</details>

<details>
<summary><b>why valyrian</b></summary>
<br/>

Valyrian steel is folded and reforged until nothing weak remains. A training loop is the same idea: run it, test it, throw out what fails, run it again.

If `phi3-pr-reviewer` ever approves its own pull request, I will stop and look at what I built.

</details>

<img src="./assets/divider.svg" width="100%" alt=""/>

## contact

<div align="center">

[![GitHub](https://img.shields.io/badge/RAJVEER42-161C27?style=flat-square&logo=github&logoColor=FFB454)](https://github.com/RAJVEER42)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-161C27?style=flat-square&logo=linkedin&logoColor=FFB454)](https://www.linkedin.com/in/rajveer-bishnoi-576b62356)
[![Email](https://img.shields.io/badge/Email-161C27?style=flat-square&logo=gmail&logoColor=FFB454)](mailto:irajveer.bishnoi2310@email.com)

<sub>Open to open source collaboration, ML experiments, and arguments about fine-tuning versus RAG. Open an issue and I will answer it faster than a text.</sub>

</div>
