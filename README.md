<a href="https://nyanlh.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
    <img src="assets/header-light.svg" width="100%" alt="Nyan Lin Htet, Student @ MIT, Cambridge, MA" />
  </picture>
</a>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3200&pause=900&color=C5A463&vCenter=true&width=640&height=30&lines=%3E+building+production+AI+voice+agents;%3E+ML+closure+models+for+ocean+flows;%3E+low-latency+C%2B%2B+and+backend+systems;%3E+computer+vision+for+broadcast+soccer" alt="Typing animation" />

[![Website](https://img.shields.io/badge/nyanlh.com-0a0a0a?style=flat-square&logo=googlechrome&logoColor=C5A463)](https://nyanlh.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-0a0a0a?style=flat-square&logo=linkedin&logoColor=C5A463)](https://linkedin.com/in/alexnyan)
[![Email](https://img.shields.io/badge/nyanlh@mit.edu-0a0a0a?style=flat-square&logo=gmail&logoColor=C5A463)](mailto:nyanlh@mit.edu)

Computer Science and Engineering at MIT, class of 2028. I build production AI systems and run quantitative experiments on physical models. Lately that means voice agents for car dealerships and Gaussian-process closure models for ocean flows.

## `01` Working on now

**AutoAce.** AI voice agents that take calls for car dealerships. I wrote the warm-transfer telephony flow (LiveKit, Telnyx) that hands a caller to a human and lets the agent listen back in if the line drops. I also built the document-retrieval layer on Hono, Supabase, and pgvector, and a Google Places fast path that cut location-query latency from roughly 4 seconds to under one second by skipping an LLM round-trip.

**MIT MSEAS Lab.** Closure modeling for coarse ocean and fluid simulations. I built a PyTorch pipeline that mines informative 5×5 stencil patches from simulation snapshots and feeds a CNN encoder plus a sparse variational Gaussian process head, then wired the trained model into a finite-volume CFD solver for online correction.

## `02` Projects

**PinnyaPrep**<br />
An exam-prep platform for Myanmar's Grade 12 national curriculum. It generates bilingual practice questions (Burmese and English) grounded in real textbook content through retrieval, with a validation pass that scores and filters every generated question before a student sees it.<br />
`Next.js` `Supabase` `pgvector` `Cohere` `Gemini`

**[Acceleration-Aware DeepSORT](https://github.com/alex-nyan/deepsort-cv)**<br />
A multi-object tracker for broadcast soccer, co-authored with a labmate. I designed a 12-dimensional constant-acceleration Kalman filter for players who accelerate and cut sharply. On SoccerNet it cut acceleration-driven ID-switch errors by 47% (14,054 down to 7,479), measured through a four-way ablation across 87 video sequences.<br />
`Python` `OpenCV` `Kalman Filter` `DeepSORT`

**[UROP Search Engine](https://miturop.org)**<br />
A search tool for MIT research listings, built with AppDev@MIT and used by about 500 students. Sub-second filtering over the listings, fed by a daily cron job that scrapes MIT's ELx API and deduplicates into MongoDB.<br />
`React` `TypeScript` `Express` `MongoDB`

## `03` Tools I reach for

**Languages** &nbsp; `Python` `TypeScript` `Java` `C` `C++`<br />
**Frameworks** &nbsp; `React` `Next.js` `Node.js` `PyTorch` `NumPy` `pandas` `OpenCV`<br />
**Infrastructure** &nbsp; `PostgreSQL` `MongoDB` `Docker` `AWS`
