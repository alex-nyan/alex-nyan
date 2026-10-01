<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A8B8C,100:A31F34&height=200&section=header&text=Nyan%20(Alex)%20Lin%20Htet&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=MIT%20CS%20%2B%20Math%20%E2%80%A2%20Class%20of%202028&descAlignY=58&descSize=18" alt="Header" />

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=A31F34&center=true&vCenter=true&width=600&lines=CS+%2B+Math+%40+MIT+'28;Building+production+AI+voice+agents;ML+closure+models+for+ocean+flows;Computer+vision+for+broadcast+soccer" alt="Typing SVG" /></a>
</p>

<p align="center">
  <a href="https://nyanlh.com"><img src="https://img.shields.io/badge/Website-nyanlh.com-A31F34?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://linkedin.com/in/alexnyan"><img src="https://img.shields.io/badge/LinkedIn-alexnyan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nyanlh@mit.edu"><img src="https://img.shields.io/badge/Email-nyanlh%40mit.edu-8A8B8C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" alt="wave" /> Hi! Computer Science and Engineering at MIT, class of 2028. I build production AI systems and run quantitative experiments on physical models. Lately that means voice agents for car dealerships and Gaussian-process closure models for ocean flows.

## 🔭 Working on now

**AutoAce.** AI voice agents that take calls for car dealerships. I wrote the warm-transfer telephony flow (LiveKit, Telnyx) that hands a caller to a human and lets the agent listen back in if the line drops. I also built the document-retrieval layer on Hono, Supabase, and pgvector, and a Google Places fast path that cut location-query latency from roughly 4 seconds to under one second by skipping an LLM round-trip.

**MIT MSEAS Lab.** Closure modeling for coarse ocean and fluid simulations. I built a PyTorch pipeline that mines informative 5×5 stencil patches from simulation snapshots and feeds a CNN encoder plus a sparse variational Gaussian process head, then wired the trained model into a finite-volume CFD solver for online correction.

## 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| **PinnyaPrep** | Exam prep for Myanmar's Grade 12 national curriculum. Generates bilingual (Burmese/English) practice questions grounded in real textbook content via retrieval, with a validation pass that scores and filters every question before a student sees it. | Next.js, Supabase, pgvector, Cohere, Gemini |
| **[Acceleration-Aware DeepSORT](https://github.com/alex-nyan/deepsort-cv)** | Multi-object tracker for broadcast soccer, co-authored with a labmate. I designed a 12-D constant-acceleration Kalman filter for players who cut sharply. On SoccerNet it cut acceleration-driven ID switches by **47%** (14,054 → 7,479) across a four-way ablation on 87 sequences. | Python, OpenCV |
| **UROP Search Engine** | Search for MIT research listings, built with AppDev@MIT and used by **~500 students**. Sub-second filtering, fed by a daily cron job that scrapes MIT's ELx API and dedupes into MongoDB. | React, TypeScript, Express |

## 🧰 Tools I reach for

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,ts,java,c,cpp,react,nextjs,nodejs,pytorch,opencv,postgres,mongodb,supabase,docker,aws&perline=15" alt="Tech stack" />
</p>

NumPy, pandas, LiveKit, Hono, pgvector, and whatever the problem needs.

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=alex-nyan&show_icons=true&hide_border=true&theme=transparent&title_color=A31F34&icon_color=A31F34" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alex-nyan&layout=compact&hide_border=true&theme=transparent&title_color=A31F34" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=alex-nyan&hide_border=true&theme=transparent&ring=A31F34&fire=A31F34&currStreakLabel=A31F34" alt="GitHub streak" />
</p>

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alex-nyan/alex-nyan/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/alex-nyan/alex-nyan/output/github-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/alex-nyan/alex-nyan/output/github-snake.svg" />
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A31F34,100:8A8B8C&height=120&section=footer" alt="Footer" />
