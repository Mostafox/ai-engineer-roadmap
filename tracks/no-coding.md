# 🌱 Track B — The Newcomer (No Coding Background)

> "I've never written code in my life." Perfect. You're not behind — you're *unburdened*. Some of the best AI engineers started exactly where you are. Let's go. 🚀

This track takes the [10-level campaign](../README.md#-the-campaign-map) and adds **more hand-holding, more reassurance, and a slower ramp** through the early levels. We spend extra time on Levels 0–2 so the foundation is rock-solid. By Level 5 you'll be neck-and-neck with the coders.

📚 All resources referenced here live in **[RESOURCES.md](../RESOURCES.md)**.
⚔️ All project briefs live in **[PROJECTS.md](../PROJECTS.md)**.

> **Golden rule for you specifically:** Type out every example by hand. Don't copy-paste. Your fingers learn what your eyes skim past.

---

## Level 0 — The Awakening 🌅

**Goal:** Get set up and lose the fear.

**Learn:**
- What an "AI Engineer" actually does in 2026 (builds apps *on top of* AI models — you don't need to invent the math).
- Install the basics: [Python](https://www.python.org/downloads/), [VS Code](https://code.visualstudio.com/), and make a [GitHub account](https://github.com/signup).
- Learn what Git is (saving your work like checkpoints in a game) and the *3 commands* you need: `add`, `commit`, `push`.
- **Meet your study buddy:** ChatGPT / Claude. Whenever you're stuck, ask "explain this like I'm 12." This is your superpower — use it shamelessly.

**Resources:** → [RESOURCES.md → Setup & Git](../RESOURCES.md#-setup--git)

**⚔️ Boss Project:** Create your `hello-ai` repo and a [GitHub profile README](../PROJECTS.md#level-0--the-awakening-) that introduces you. *First green square. It begins.*

> 🌟 **Pep talk:** Setup is the hardest emotional hurdle, not the hardest technical one. Once your first commit lands, the momentum carries you.

---

## Level 1 — Speak Python 🐍

**Goal:** Become conversational in Python. This is your longest level — take your time.

**Learn:**
- Variables, types, `if`/`else`, `for`/`while` loops.
- Functions, lists, dictionaries.
- Reading errors *calmly* (errors are clues, not judgments).
- How to run code in a [Jupyter notebook](https://jupyter.org/) — your AI sketchpad.

**Resources:** → [RESOURCES.md → Python](../RESOURCES.md#-python-the-language-of-ai)
Recommended primary: **freeCodeCamp's Python course** + **"Automate the Boring Stuff"** (free online, gentle, fun).

**⚔️ Boss Project:** A [small CLI tool](../PROJECTS.md#level-1--speak-python-) — a tip calculator, a password generator, a to-do list. Tiny, but *yours*.

> Don't rush past this. Everything in AI sits on top of Python. Solid here = smooth everywhere.

---

## Level 2 — Data & Math-Lite 📊

**Goal:** Handle data and absorb *just enough* math to not be scared of it.

**Learn:**
- [NumPy](https://numpy.org/) (arrays/numbers) and [pandas](https://pandas.pydata.org/) (spreadsheets in code).
- Making charts with [Matplotlib](https://matplotlib.org/).
- **Math intuition only** — watch, don't grind: what a vector is, what "average/spread" means, the *idea* of a derivative (slope). **3Blue1Brown** makes this beautiful.

**Resources:** → [RESOURCES.md → Math-Lite](../RESOURCES.md#-math-lite-just-enough-no-phd)

**⚔️ Boss Project:** An [Exploratory Data Analysis notebook](../PROJECTS.md#level-2--data--math-lite-) on a dataset you genuinely care about (movies, sports, your Spotify history). Make 3 charts that tell a story.

> 🧘 **Math anxiety?** You need *intuition*, not proofs. You'll never hand-calculate a gradient — the computer does that. Promise.

---

## Level 3 — Classic ML 🤖

**Goal:** Train your first model that *predicts* things. Pure magic moment. ✨

**Learn:** scikit-learn, train/test split, what "accuracy" really means, overfitting (memorizing vs. learning).

**Resources:** → [RESOURCES.md → ML & Deep Learning](../RESOURCES.md#-machine-learning--deep-learning)
Recommended: **Andrew Ng's Machine Learning Specialization** (the legendary on-ramp).

**⚔️ Boss Project:** [Predict something + a Streamlit demo](../PROJECTS.md#level-3--classic-ml-) — house prices, who survived the Titanic, spam vs. not. Deploy the demo so people can click it.

---

## Level 4 — Deep Learning 🧠

**Goal:** Neural networks — the engine under all the cool stuff.

**Learn:** What a neural net is, [PyTorch](https://pytorch.org/) basics, training loops, CNNs for images, **transfer learning** (standing on giants' shoulders).

**Resources:** → [RESOURCES.md → ML & Deep Learning](../RESOURCES.md#-machine-learning--deep-learning)
Recommended: **fast.ai "Practical Deep Learning for Coders"** — top-down and beginner-friendly *despite* the name.

**⚔️ Boss Project:** A [custom image classifier](../PROJECTS.md#level-4--deep-learning-) — your dog vs. your cat, healthy vs. diseased leaves, anything. Fine-tune a pretrained model.

> 🎉 **You made it to the convergence point.** From here, you and the coders walk the same road.

---

## Level 5 — Transformers & LLMs ✨

**Goal:** Understand and command the models behind ChatGPT/Claude.

**Learn:** The *intuition* of attention & transformers (not the matrix algebra), tokens, embeddings, [Hugging Face](https://huggingface.co/), and **prompt engineering** as a real skill.

**Resources:** → [RESOURCES.md → LLMs & Prompting](../RESOURCES.md#-llms--prompt-engineering)

**⚔️ Boss Project:** A [prompt-powered app](../PROJECTS.md#level-5--transformers--llms-) (study-buddy, recipe-from-fridge-contents, email rewriter) + a small **evals** notebook proving it works.

---

## Level 6 — RAG 📚

**Goal:** Make an AI answer questions about *your* documents — accurately, with sources.

**Learn:** Embeddings, vector databases ([Chroma](https://www.trychroma.com/), FAISS, pgvector), chunking, retrieval, and orchestration with [LangChain](https://www.langchain.com/) or [LlamaIndex](https://www.llamaindex.ai/). Why RAG beats "just fine-tune it" for facts.

**Resources:** → [RESOURCES.md → RAG](../RESOURCES.md#-rag-retrieval-augmented-generation)

**⚔️ Boss Project:** [**Chat with your docs**](../PROJECTS.md#level-6--rag-) — upload PDFs and ask questions, with citations. *This single project gets people interviews.*

---

## Level 7 — Image & Video Generation 🎨

**Goal:** Generate and control images (and dabble in video).

**Learn:** How diffusion models work (denoising, intuitively), [Stable Diffusion](https://stability.ai/)/[Flux](https://blackforestlabs.ai/), [ComfyUI](https://github.com/comfyanonymous/ComfyUI), ControlNet & **LoRA** (teaching a model a new style/face), and generation APIs.

**Resources:** → [RESOURCES.md → Image & Video Gen](../RESOURCES.md#-image--video-generation)

**⚔️ Boss Project:** An [image-gen web app or a custom LoRA](../PROJECTS.md#level-7--image--video-generation-) trained on a theme you love. Wildly portfolio-friendly — it's *visual*.

---

## Level 8 — Agents & Automation 🦾

**Goal:** Build AI that *acts*, not just chats — uses tools, takes steps, gets things done.

**Learn:** Tool/function calling, multi-step agent loops, [MCP](https://modelcontextprotocol.io/), and automation glue like [n8n](https://n8n.io/). When agents are magic vs. when they're overkill.

**Resources:** → [RESOURCES.md → Agents & Automation](../RESOURCES.md#-agents--automation)

**⚔️ Boss Project:** An [agent that does a real task](../PROJECTS.md#level-8--agents--automation-) — researches a topic and emails you a digest, triages your inbox, or auto-files expenses.

---

## Level 9 — Ship It (LLMOps) 🚢

**Goal:** Turn a notebook toy into a real, deployed thing people can use.

**Learn:** [FastAPI](https://fastapi.tiangolo.com/) (turn code into an API), [Docker](https://www.docker.com/) (package it), cost & latency, monitoring, guardrails, and deploying to the cloud (free tiers).

**Resources:** → [RESOURCES.md → Deployment & LLMOps](../RESOURCES.md#-deployment--llmops)

**⚔️ Boss Project:** [Take an earlier project and deploy it for real](../PROJECTS.md#level-9--ship-it-llmops-) — public URL, uptime, a `Dockerfile`. This is the leap from "student" to "engineer."

---

## Level 10 — Unstoppable 👑

**Goal:** Final form. Fine-tune models, evaluate rigorously, contribute to open source, and build a system to stay current forever.

**Learn:** Fine-tuning & PEFT/[LoRA](https://huggingface.co/docs/peft), serious evaluation, reading papers in 5 minutes, and a sustainable "stay current" routine.

**Resources:** → [RESOURCES.md → Staying Current](../RESOURCES.md#-staying-current-dont-drown)

**⚔️ Boss Project:** A [capstone](../PROJECTS.md#level-10--unstoppable-) combining RAG + agents + generative media, **plus** your first open-source contribution to an AI repo.

---

## 🏁 You did it.

You started never having coded. You're ending as someone who **ships production AI systems**. Update your GitHub bio. Pin your best 6 projects. Apply for the job. You're not "trying to break into AI" anymore — **you're in.** 👑

> Next stop: **[PROJECTS.md → Turn Projects into a Resume](../PROJECTS.md#-turn-projects-into-a-resume)**
