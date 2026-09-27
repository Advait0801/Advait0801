<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=180&section=header&text=Advait%20Naik&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20·%20Building%20AI%20into%20real%20systems&descAlignY=58&descSize=16" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=26D0CE&center=true&vCenter=true&width=580&lines=Software+Engineer;I+build+systems%2C+then+integrate+AI+into+them;SWE+Intern+%40+PlusAI;Research+Assistant+%40+USC+CESR;MSCS+%40+USC%2C+May+2027" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/advait-naik-344689245/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ad.naik2003@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://leetcode.com/u/advait_lc/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="https://codeforces.com/profile/advait_cf"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" /></a>
</p>

<br>

## What I Build

> I build software systems and integrate AI into them. Backend services, data pipelines, deployment
> infrastructure, and the models that have to hold up once they're in production. The interesting
> problems are rarely in the model itself. They're in everything around it.

<table>
<tr>
<td width="50%" valign="top">

### PlusAI
**Software Engineer Intern** · current

Shipped semantic video search end to end across 4 production repos: ingestion wheel, NVIDIA Cosmos indexer, GPU embedder, and an Argo workflow on Kubernetes.

`47 GPU-seconds per driving-hour`

</td>
<td width="50%" valign="top">

### USC CESR
**Research Assistant** · current

Retrieval-augmented QA over 29,716 ageing-survey documents across 10 HRS/ELSA waves. Hybrid BM25 and dense retrieval, grounded generation, FastAPI/Next.js app on Postgres and pgvector.

`identifier lookups 81.7% → 97.5%` · `355/373 eval cases`

</td>
</tr>
</table>

<p align="center">
  <sub><i>Most of my professional work lives in private repos at PlusAI and USC CESR.<br>
  What's public here is side projects and research.</i></sub>
</p>

<br>

## Selected Work

<details open>
<summary><b>InterviewForge</b> · Next.js, Express, FastAPI, PostgreSQL, ChromaDB, Docker</summary>

<br>

AI mock interview platform running a full loop (behavioral, coding, system design, core CS) across
10 companies, with RAG-grounded questions and a 150-problem coding engine in sandboxed containers.

- Raised retrieval quality from **nDCG 0.7712 → 0.9009** on a 42-query labelled benchmark by
  building the evaluation harness first, then testing five techniques and reverting the two that lost.
- Cut retrieval **p50 latency 6.6×** (1762 ms → 268 ms) at equal quality by routing per interview
  stage instead of stacking techniques.
- Hardened the code sandboxes and proved each control adversarially: a fork bomb stops at
  **exactly 127 children**, and `/etc/passwd` writes succeeded before the change and are blocked after.

<a href="https://github.com/Advait0801/InterviewForge"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white" /></a>

</details>

<details>
<summary><b>AgriTech</b> · PyTorch, Vision Transformer, Flask, ThingSpeak</summary>

<br>

Vision Transformer fine-tuned for crop-disease detection at 94% accuracy across 6 categories,
with KNN and Random Forest models for yield prediction at 97.53% and 96.42%. Survey paper
published at IEEE GC4T 2025.

<a href="https://github.com/Advait0801/AgriTech"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white" /></a>

</details>

<details>
<summary><b>SemEval 2024: Semantic Textual Relatedness</b> · Sentence Transformers, PyTorch</summary>

<br>

Supervised, unsupervised, and cross-lingual approaches to Semantic Textual Relatedness across
English, Hindi, Marathi, and Spanish. Built a translation-based pipeline to transfer labeled
data into low-resource languages with no directly labeled corpora.

**Ranked 1st in the unsupervised Hindi track.**

<a href="https://github.com/RA-01-CAILMD-23/SemEval-24-01"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white" /></a>

</details>

<br>

## Tech

<p align="center"><b>LANGUAGES</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=py" width="48" height="48" alt="Python" /><br><sub><b>Python</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=cpp" width="48" height="48" alt="C++" /><br><sub><b>C++</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" /><br><sub><b>Java</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" /><br><sub><b>TypeScript</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" /><br><sub><b>JavaScript</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=dart" width="48" height="48" alt="Dart" /><br><sub><b>Dart</b></sub></td>
</tr>
</table>
<sub>SQL</sub>
</div>

<p align="center"><b>AI &amp; RETRIEVAL</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=pytorch" width="48" height="48" alt="PyTorch" /><br><sub><b>PyTorch</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/huggingface/FFD21E" width="44" height="44" alt="Transformers" /><br><sub><b>Transformers</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/langchain/26D0CE" width="44" height="44" alt="LangChain" /><br><sub><b>LangChain</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/nvidia/76B900" width="44" height="44" alt="NVIDIA Cosmos" /><br><sub><b>NVIDIA Cosmos</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=opencv" width="48" height="48" alt="OpenCV" /><br><sub><b>OpenCV</b></sub></td>
</tr>
</table>
<sub>RAG · BM25 · Cross-encoders</sub>
</div>

<p align="center"><b>BACKEND &amp; FRONTEND</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" alt="FastAPI" /><br><sub><b>FastAPI</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=flask" width="48" height="48" alt="Flask" /><br><sub><b>Flask</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" /><br><sub><b>Node.js</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="Express" /><br><sub><b>Express</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="Next.js" /><br><sub><b>Next.js</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" /><br><sub><b>React</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=flutter" width="48" height="48" alt="Flutter" /><br><sub><b>Flutter</b></sub></td>
</tr>
</table>
<sub>Apache Thrift · REST</sub>
</div>

<p align="center"><b>CLOUD &amp; DEVOPS</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=aws" width="48" height="48" alt="AWS" /><br><sub><b>AWS</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=gcp" width="48" height="48" alt="GCP" /><br><sub><b>GCP</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" /><br><sub><b>Docker</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=kubernetes" width="48" height="48" alt="Kubernetes" /><br><sub><b>Kubernetes</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/argo/EF7B4D" width="44" height="44" alt="Argo Workflows" /><br><sub><b>Argo Workflows</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=jenkins" width="48" height="48" alt="Jenkins" /><br><sub><b>Jenkins</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=vercel" width="48" height="48" alt="Vercel" /><br><sub><b>Vercel</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/render/46E3B7" width="44" height="44" alt="Render" /><br><sub><b>Render</b></sub></td>
</tr>
</table>
</div>

<p align="center"><b>DATA STORES</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" /><br><sub><b>PostgreSQL</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="MySQL" /><br><sub><b>MySQL</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB" /><br><sub><b>MongoDB</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" /><br><sub><b>Redis</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/clickhouse/FFCC01" width="44" height="44" alt="ClickHouse" /><br><sub><b>ClickHouse</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=firebase" width="48" height="48" alt="Firebase" /><br><sub><b>Firebase</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/milvus/00A1EA" width="44" height="44" alt="Milvus" /><br><sub><b>Milvus</b></sub></td>
</tr>
</table>
<sub>FAISS · ChromaDB</sub>
</div>

<p align="center"><b>DEVELOPER TOOLS</b></p>
<div align="center">
<table>
<tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" /><br><sub><b>Git</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub" /><br><sub><b>GitHub</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" /><br><sub><b>Linux</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=postman" width="48" height="48" alt="Postman" /><br><sub><b>Postman</b></sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=vscode" width="48" height="48" alt="VS Code" /><br><sub><b>VS Code</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/cursor/8B949E" width="44" height="44" alt="Cursor" /><br><sub><b>Cursor</b></sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/claude/D97757" width="44" height="44" alt="Claude Code" /><br><sub><b>Claude Code</b></sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@latest/icons/codex-color.svg" width="44" height="44" alt="Codex" /><br><sub><b>Codex</b></sub></td>
</tr>
</table>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:26d0ce,100:1a2980&height=120&section=footer" />
