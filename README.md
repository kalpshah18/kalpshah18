<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg?v=2">
  <img alt="Kalp Shah. ML infrastructure and computer vision." src="assets/hero-light.svg?v=2" width="100%">
</picture>

```console
$ whoami
Kalp Shah. B.Tech Electrical Engineering, Minor in CSE (2024-28), IIT Gandhinagar

$ cat focus.txt
ml infra  GPU cluster scheduling, streaming data pipelines, RAG systems
ai/ml     computer vision, single-view metrology, deep learning
systems   C++, matching engines, emulators

$ cat next.txt
Quantitative Developer Intern @ Graviton Research Capital (2027)
```

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[Trade Matching Engine](https://github.com/kalpshah18/TradeMatchingEngine)**<br>
`systems`

Order matching engine in C++26 with price-time priority and FIFO execution. Matching, cancellation and execution run in O(1) using stable `std::hive` iterators. Benchmarked with RDTSC timers over 200K+ orders: 12.5M+ orders/sec, 60 ns median latency.

`C++26` `RDTSC` `CMake`

</td>
<td width="50%" valign="top">

**[CHIP-8 Emulator](https://github.com/kalpshah18/CHIP8-Emulator)**<br>
`systems`

CHIP-8 interpreter with SDL2: all 34 opcodes, 4 KB memory, 16-level stack, 64×32 XOR display, keypad and square-wave audio. 60 Hz timers decoupled from a configurable CPU rate via a time accumulator, plus 4 runtime quirk flags for COSMAC VIP and SCHIP compatibility.

`C++17` `SDL2`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Fairness and Efficiency in Shared GPU Allocation](https://drive.google.com/file/d/1uprvcMUWQ_vRBFq5DtTMwSuMrfqwRffF/view?usp=sharing)** · report<br>
`ml infra`

Simulator for shared GPU clusters that tests scheduling mechanisms on efficiency, long-run fairness and resistance to strategic misreporting. A history-penalised scoring rule reaches >95% of theoretical welfare and Jain's Index ~0.991 while neutralising priority inflation.

`Python` `Mechanism Design` `Simulation`

Advisor: Prof. Manisha Padala

</td>
<td width="50%" valign="top">

**[Realtime Carbon Credit Market Platform](https://github.com/kalpshah18/InterIITTech_)**<br>
`ml infra` `ai/ml`

Full-stack analytics platform serving live carbon credit pricing, trend signals and risk analysis, built by an 8-person team at Inter IIT Tech Meet 14.0. Kafka + Debezium change-data-capture cut data freshness from 60 minutes to under 3 seconds; a multi-agent RAG system generates recommendations from scraped data.

`Python` `LangChain` `Kafka` `PostgreSQL` `Next.js`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[Identifying Landing Locations on Mars with Classical CV](https://drive.google.com/file/d/12Waq8WWIeSgllUhhJSCgVeoda9_2_jpi/view)** · poster<br>
`ai/ml`

Compute-constrained pipeline, with ISRO, for finding safe landing zones on Mars. Sobel derivatives for slope, FFT for texture, and the maximal-rectangle algorithm for zone extraction. Runs in 1.5 s on consumer hardware.

`Python` `OpenCV` `NumPy`

Advisor: Prof. Shanmuganathan Raman

</td>
</tr>
</table>

## Experience

```console
2027  Graviton Research Capital   Quantitative Developer Intern (incoming)
2026  AIResQ ClimSols             ML/CV Intern: flood depth from CCTV networks, ±3 cm via single-view metrology
2025  ABSix Robotics              SDE Intern: Python/Qt robot-student desktop app, 100+ students, RAG assistant
2026  IIT Gandhinagar             Co-instructor, SC 428: Introduction to C++ and the STL
```

## Achievements

- Codeforces Expert, max rating 1746 ([KaPraSh](https://codeforces.com/profile/KaPraSh))
- AMS Derive finalist, rank 26 / 2500+ (Jane Street, QRT)
- Integral Cup S1, AIR 47 / 2500+ (Optiver, Da Vinci Trading)
- Barclays BIIC Mentorship, top 5

## Stack

```console
languages   Python, C++, C, SQL, JavaScript
ml / cv     PyTorch, OpenCV, scikit-learn, NumPy, Pandas, LangChain
infra       FastAPI, PostgreSQL, Kafka, Debezium
tools       Linux, Git, Docker, CMake, SDL2, Jupyter
```

## Contact

[Portfolio](https://www.kalpshah.in) · [kalpshah1808@gmail.com](mailto:kalpshah1808@gmail.com) · [LinkedIn](https://linkedin.com/in/kalpshah18) · [Codeforces](https://codeforces.com/profile/KaPraSh)
