## Hey, I'm Hamed 👋

I started as a developer, drifted into product and engineering leadership – and still keep coming back to the code. I'm a bit obsessive by nature, dealing with ADHD since childhood, and it still fucking bothers me that the dash in the previous sentence might make this look AI-generated. So, I've spent the last 10 minutes revising this over and over to prove otherwise. Anyway.

These days, most of that obsession goes into **running open-weight LLMs locally on Apple Silicon**. Unlike conventional GPUs with limited VRAM, Apple's unified memory lets us keep much larger models accessible to the GPU; but RAM is expensive and models keep getting bigger.

**One question I can't get out of my head:** how far can we push SSD streaming to keep only the active experts of a large MoE model in memory and load the rest on demand? If we can make that efficient enough, ordinary MacBooks could run frontier-scale models. Between GPU export controls, artificially constrained consumer hardware, and frontier models locked behind increasingly restrictive APIs, I'd rather see powerful AI running on the hardware we actually own, without someone else deciding what we're allowed to do with it!


## Open-source contributions

- **Local LLM inference:** [oMLX](https://github.com/jundot/omlx/pulls?q=author%3AHamedShams) · [SwiftLM](https://github.com/SharpAI/SwiftLM/pulls?q=author%3AHamedShams) · [inferSSD](https://github.com/wici-ai/inferssd/pulls?q=author%3AHamedShams)  
  Running and serving LLMs on Apple Silicon, including SSD-backed inference.
<!-- 
- **ML frameworks:** [mlx-swift](https://github.com/ml-explore/mlx-swift/pulls?q=author%3AHamedShams)  
  Tensor operations and ML framework correctness. -->

- **Model freedom:** [Heretic](https://github.com/p-e-w/heretic/pulls?q=author%3AHamedShams)  
  Modifying model behaviour without retraining - including removing built-in refusals / censorship.

- **Proof-checked GPU computing:** [Bend](https://github.com/bendlang/bend/pulls?q=author%3AHamedShams)  
  A proof-based programming language that compiles to massively parallel GPU code.

---
My DFlash streaming and cancellation fix in SwiftLM was selected for the XERJ Corpus Hub: 

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/HamedShams/badge.svg)](https://hub.xerj.org/contributors/HamedShams)


<!--
**HamedShams/HamedShams** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- ⚡ Fun fact: ...
-->
