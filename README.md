<a href="https://nyanlh.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg" />
    <img src="assets/header-light.svg" width="100%" alt="Nyan Lin Htet, Student @ MIT, Cambridge, MA" />
  </picture>
</a>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3200&pause=900&color=C5A463&vCenter=true&width=640&height=30&lines=%3E+low-latency+C%2B%2B+and+systems;%3E+LLM+research+and+evals;%3E+retrieval+that+answers+from+evidence;%3E+production+AI+voice+agents" alt="Typing animation" />

[![Website](https://img.shields.io/badge/nyanlh.com-0a0a0a?style=flat-square&logo=googlechrome&logoColor=C5A463)](https://nyanlh.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-0a0a0a?style=flat-square&logo=linkedin&logoColor=C5A463)](https://linkedin.com/in/alexnyan)
[![Email](https://img.shields.io/badge/nyanlh@mit.edu-0a0a0a?style=flat-square&logo=gmail&logoColor=C5A463)](mailto:nyanlh@mit.edu)

Computer Science and Engineering at MIT, class of 2028. I'm interested in low-latency systems and LLM research. On the systems side that means C++ hot paths, cache behavior, and measuring p99 instead of guessing at it. On the LLM side it means retrieval, evals, and getting models to answer from evidence.

## `01` Working on now

**BusyBeaver.** The course website for 6.1210 (MIT's Introduction to Algorithms). Students submit problem-set work and get LLM feedback graded against human-reviewed rubrics, and there's an office-hours tutor mode. A separate eval pipeline with an LLM judge runs against the real production grading code, so prompt changes get measured before students see them. Next.js, Postgres, MIT's Parley model.

**Algorithmic trading bot.** An automated trading system, in progress.

**Fog of War challenge.** Fog of War is the chess variant where you only see the squares your own pieces can move to or attack. The hard part is choosing moves on a board you can't fully see.

**MIT CSAIL.** I deployed Compass Search, a retrieval-augmented generation system on MIT's in-house Parley model that answers natural-language questions over course notes and syllabi for 300+ students. I'm now building a voice-agent moderator that listens to live student group discussions and manages turn-taking in real time.

## `02` Past work

**AutoAce (Y Combinator F25)** · Software Engineering Intern · Jun–Aug 2026<br />
AI voice agents that take calls for car dealerships. I wrote the warm-transfer telephony flow (LiveKit, Telnyx) that hands a caller to a human and lets the agent listen back in if the line drops. I also built the document-retrieval layer on Hono, Supabase, and pgvector, and a Google Places fast path that cut location-query latency from roughly 4 seconds to under one second by skipping an LLM round-trip.

## `03` Projects

**Low-Latency Feed Handler & Order Book**<br />
A NASDAQ ITCH 5.0 binary protocol parser and in-memory order book in C++20 with a zero-allocation hot path. A flat price-level array plus a hash map give O(1) add, cancel, and execute. I traced tail latency to cache misses and branch mispredicts with Linux perf and measured per-message p50/p99/p99.9 on a calibrated nanosecond timing harness.<br />
`C++20` `Linux` `perf` `HdrHistogram`

**PinnyaPrep**<br />
An exam-prep platform for Myanmar's Grade 12 national curriculum. It generates bilingual practice questions (Burmese and English) grounded in real textbook content through retrieval, with a validation pass that scores and filters every generated question before a student sees it.<br />
`Next.js` `Supabase` `pgvector` `Cohere` `Gemini`

**[Acceleration-Aware DeepSORT](https://github.com/alex-nyan/deepsort-cv)**<br />
A multi-object tracker for broadcast soccer, co-authored with a labmate. I designed a 12-dimensional constant-acceleration Kalman filter for players who accelerate and cut sharply. On SoccerNet it cut acceleration-driven ID-switch errors by 47% (14,054 down to 7,479), measured through a four-way ablation across 87 video sequences.<br />
`Python` `OpenCV` `Kalman Filter` `DeepSORT`

**[UROP Search Engine](https://miturop.org)**<br />
A search tool for MIT research listings, built with AppDev@MIT and used by about 500 students. Sub-second filtering over the listings, fed by a daily cron job that scrapes MIT's ELx API and deduplicates into MongoDB.<br />
`React` `TypeScript` `Express` `MongoDB`

## `04` Tools I reach for

**Languages** &nbsp; `C++` `Python` `TypeScript` `C` `Java` `SQL`<br />
**Frameworks** &nbsp; `PyTorch` `LiveKit` `React` `Next.js` `Node.js` `Hono` `NumPy` `OpenCV`<br />
**Infrastructure** &nbsp; `Linux` `perf` `PostgreSQL` `pgvector` `MongoDB` `Docker` `AWS`
