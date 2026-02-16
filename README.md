### Hey, I'm Yuqing Xia 👋

I'm obsessed with one thing: **making LLMs ridiculously fast.**

Every wasted microsecond on GPU is a personal offense to me. I work at the intersection of **LLM inference systems**, **GPU kernel wizardry**, and **AI compilers** — turning "that's theoretically possible" into shipped code.

---

#### 🔥 TileRT — LLM Inference, Absurdly Fast

<a href="https://github.com/tile-ai/TileRT">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=tile-ai&repo=TileRT&theme=default" />
</a>

Most inference engines optimize for throughput. We chose the harder problem: **per-request latency**.

TileRT is a tile-based runtime built for scenarios where every millisecond counts — AI-assisted coding, real-time conversation, high-frequency decision making. No batching tricks, no latency hiding. Just raw speed.

- ⚡ **600 tok/s** on DeepSeek-V3.2 | **500 tok/s** on GLM-5-FP8
- 🧠 **Multi-Token Prediction** — why generate one token when you can do three?
- 🧩 **Compiler-driven tile-level scheduling** with dynamic rescheduling across devices
- 🚀 `pip install tilert` | Try it live at [tilert.ai](https://tilert.ai)

---

#### 🧱 The tile-ai Ecosystem

TileRT doesn't exist in a vacuum. It's part of [**tile-ai**](https://github.com/tile-ai) — a full stack we're building from scratch around one simple idea: **tiles are the right abstraction for AI compute.**

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://github.com/tile-ai/tilelang">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=tile-ai&repo=tilelang&theme=default" />
      </a>
      <br/>
      <sub><b>The language.</b> Write tile programs, get optimized GPU kernels. Simple as that.</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/tile-ai/TileOPs">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=tile-ai&repo=TileOPs&theme=default" />
      </a>
      <br/>
      <sub><b>The operators.</b> FlashAttention, MLA, DSA — battle-tested, auto-tuned.</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/tile-ai/tilescale">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=tile-ai&repo=tilescale&theme=default" />
      </a>
      <br/>
      <sub><b>The scale-out.</b> Multi-GPU, multi-node — one mega-device, zero headaches.</sub>
    </td>
  </tr>
</table>

---

#### 🏛️ Previously

- [**NNFusion**](https://github.com/microsoft/nnfusion) — A DNN compiler that turns model descriptions into framework-free, high-performance executables. Built at Microsoft Research. We were doing AI compilers before it was cool. ⭐ 1000+

---

#### 🛠️ Tech Stack

`CUDA` `C++` `Python` `PyTorch` `TensorRT` `CUTLASS`

---

#### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=xiayuqing0622&show_icons=true&count_private=true&theme=default" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=xiayuqing0622&layout=compact&theme=default" height="165" />
</p>

---

#### 📫 Get in Touch

Building something latency-critical? Want to push LLM inference to the edge? Let's talk.

- **Email**: xiayuqing0622@outlook.com
- **GitHub**: [@xiayuqing0622](https://github.com/xiayuqing0622)
