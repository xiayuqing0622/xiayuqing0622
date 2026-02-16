### Hey, I'm Yuqing Xia 👋

I'm obsessed with one thing: **making LLMs ridiculously fast.**

Every wasted microsecond on GPU is a personal offense to me. I work at the intersection of **LLM inference systems**, **GPU kernel wizardry**, and **AI compilers** — turning "that's theoretically possible" into shipped code.

---

#### 🔥 TileRT — LLM Inference, Absurdly Fast

[![TileRT](https://img.shields.io/github/stars/tile-ai/TileRT?style=for-the-badge&logo=github&label=tile-ai/TileRT)](https://github.com/tile-ai/TileRT)
[![PyPI](https://img.shields.io/pypi/v/tilert?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/tilert/)

Most inference engines optimize for throughput. We chose the harder problem: **per-request latency**.

TileRT is a tile-based runtime built for scenarios where every millisecond counts — AI-assisted coding, real-time conversation, high-frequency decision making. No batching tricks, no latency hiding. Just raw speed.

- ⚡ **600 tok/s** on DeepSeek-V3.2 | **500 tok/s** on GLM-5-FP8
- 🧠 **Multi-Token Prediction** — why generate one token when you can do three?
- 🧩 **Compiler-driven tile-level scheduling** with dynamic rescheduling across devices
- 🚀 `pip install tilert` | Try it live at [tilert.ai](https://tilert.ai)

---

#### 🧱 The tile-ai Ecosystem

TileRT doesn't exist in a vacuum. It's part of [**tile-ai**](https://github.com/tile-ai) — a full stack we're building from scratch around one simple idea: **tiles are the right abstraction for AI compute.**

| | Project | What it does |
|---|---|---|
| 🗣️ | [**tilelang**](https://github.com/tile-ai/tilelang) [![](https://img.shields.io/github/stars/tile-ai/tilelang?style=flat-square)](https://github.com/tile-ai/tilelang) | **The language.** Write tile programs, get optimized GPU kernels. Simple as that. |
| 🌐 | [**TileScale**](https://github.com/tile-ai/tilescale) [![](https://img.shields.io/github/stars/tile-ai/tilescale?style=flat-square)](https://github.com/tile-ai/tilescale) | **The scale-out.** Multi-GPU, multi-node — one mega-device, zero headaches. |
| ⚙️ | [**TileOPs**](https://github.com/tile-ai/TileOPs) [![](https://img.shields.io/github/stars/tile-ai/TileOPs?style=flat-square)](https://github.com/tile-ai/TileOPs) | **The operators.** FlashAttention, MLA, DSA — battle-tested, auto-tuned. |

---

#### 🏛️ Previously

- [**NNFusion**](https://github.com/microsoft/nnfusion) — A DNN compiler that turns model descriptions into framework-free, high-performance executables. Built at Microsoft Research. We were doing AI compilers before it was cool. ⭐ 1000+

---

#### 🛠️ Tech Stack

`CUDA` `C++` `Python` `PyTorch` `CUTLASS`

---

#### 📫 Get in Touch

Building something latency-critical? Want to push LLM inference to the edge? Let's talk.

- **Email**: xiayuqing0622@outlook.com | xiayq001@gmail.com
- **GitHub**: [@xiayuqing0622](https://github.com/xiayuqing0622)
