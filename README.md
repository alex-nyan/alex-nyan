# Nyan (Alex) Lin Htet

Computer Science and Engineering at MIT, class of 2028. I build production AI systems and run quantitative experiments on physical models. Lately that means voice agents for car dealerships and Gaussian-process closure models for ocean flows.

[LinkedIn](https://linkedin.com/in/alexnyan) · [Email](mailto:nyanlh@mit.edu)

## Working on now

**AutoAce.** AI voice agents that take calls for car dealerships. I wrote the warm-transfer telephony flow (LiveKit, Telnyx) that hands a caller to a human and lets the agent listen back in if the line drops. I also built the document-retrieval layer on Hono, Supabase, and pgvector, and a Google Places fast path that cut location-query latency from roughly 4 seconds to under one second by skipping an LLM round-trip.

**MIT MSEAS Lab.** Closure modeling for coarse ocean and fluid simulations. I built a PyTorch pipeline that mines informative 5×5 stencil patches from simulation snapshots and feeds a CNN encoder plus a sparse variational Gaussian process head, then wired the trained model into a finite-volume CFD solver for online correction.

## Projects

**[PinnyaPrep](#)** — An exam-prep platform for Myanmar's Grade 12 national curriculum. It generates bilingual practice questions (Burmese and English) grounded in real textbook content through retrieval, with a validation pass that scores and filters every generated question before a student sees it. Next.js, Supabase, pgvector, Cohere embeddings, Gemini.

**[Acceleration-Aware DeepSORT](#)** — A multi-object tracker for broadcast soccer, co-authored with a labmate. I designed a 12-dimensional constant-acceleration Kalman filter for players who accelerate and cut sharply. On SoccerNet it cut acceleration-driven ID-switch errors by 47% (14,054 down to 7,479), measured through a four-way ablation across 87 video sequences. Python, OpenCV.

**[UROP Search Engine](#)** — A search tool for MIT research listings, built with AppDev@MIT and used by about 500 students. Sub-second filtering over the listings, fed by a daily cron job that scrapes MIT's ELx API and deduplicates into MongoDB. React, TypeScript, Express.

**[uv](https://github.com/astral-sh/uv/issues/6264)** — A fix to the docs site of Astral's Python package manager, reserving image dimensions to stop the page from shifting as content loads.

## Tools I reach for

Python, TypeScript, Java, C, C++. React, Next.js, Node.js, PyTorch, NumPy, pandas, OpenCV. Postgres, MongoDB, Docker, AWS.
