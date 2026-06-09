# ⚔️ The Boss Project Catalog

> Knowledge fades. A shipped repo is forever. **Every level ends with a project** designed to be *shown*, not just done — this is how you build a GitHub resume that gets interviews without you saying a word.

For each project you get: 🎯 **Goal** · 🧰 **Stack** · 🚀 **Stretch goals** · 💼 **What it proves to recruiters**.

> **The one rule:** every project = a **public repo** with a real README (screenshot/GIF + "what it does" + "how to run"). A finished project nobody can see doesn't count. 📸

---

## 🤖 The "Can I Use AI?" Rule

You'll see an **🤖 AI** verdict on every project. Here's the philosophy behind it:

> **Early on, AI is a tutor — not a ghostwriter. Later, using AI *is the job.***

If you let AI write your first Python script, you'll *feel* productive and *learn nothing*. The fundamentals (Levels 1–4) must go through your own fingers, or the whole tower wobbles later. But once you reach the LLM/RAG/agent levels, refusing to use AI tools would be like a carpenter refusing power tools — **vibe coding well (see [VIBE-CODING.md](VIBE-CODING.md)) is a core skill of the modern AI engineer.**

The legend:
- ⛔ **Hands-off** — write it yourself. AI *only* to explain concepts/errors, never to produce the answer.
- 🟡 **Assist allowed** — write the core logic yourself; let AI handle boilerplate, UI, and glue.
- ✅ **Go for it** — full vibe coding encouraged. *But you must still understand every line you ship* (the Golden Rule).

> 💡 Whatever you use, **be honest in your README** — a "Built with: Cursor + Claude" line is a flex, not a confession. Recruiters care that it *works* and that *you understand it*.

---

## Level 0 — The Awakening 🌅

🎯 **Goal:** Land your first commits and make a profile that doesn't look empty.
🧰 **Stack:** Git, GitHub, Markdown.
🤖 **AI:** ✅ **Go for it** — let AI help you set up and write your profile README. Setup isn't the skill being tested here.
**Build:**
1. A `hello-ai` repo with a script that calls an LLM API and prints a response.
2. A **GitHub profile README** (create a repo named exactly your username) — intro, what you're learning, a "currently leveling up" section linking to this roadmap.

🚀 **Stretch:** Add a fun ASCII banner; embed your GitHub stats card.
💼 **Proves:** You can use Git and present yourself. Table stakes — but an empty profile screams "beginner," and this fixes it on day one.

---

## Level 1 — Speak Python 🐍

🎯 **Goal:** Write a small but *complete* program with real logic.
🧰 **Stack:** Python standard library.
🤖 **AI:** ⛔ **Hands-off.** Write every line yourself. Use AI *only* to explain an error or a concept — never to generate the solution. This is where your fingers learn to code.
**Build:** A **CLI tool** that solves a tiny real problem — a tip/loan calculator, password generator, unit converter, or a to-do list that saves to a file.

🚀 **Stretch:** Add `argparse` for flags; handle bad input gracefully; write one test.
💼 **Proves:** You can turn an idea into working code, handle edge cases, and structure a project. (Coders: make it call an LLM API to skip the toy phase.)

---

## Level 2 — Data & Math-Lite 📊

🎯 **Goal:** Wrangle real data and tell a story with charts.
🧰 **Stack:** pandas, NumPy, Matplotlib/Seaborn, Jupyter.
🤖 **AI:** ⛔ **Hands-off.** Type the pandas/NumPy yourself — fluency here pays off forever. AI is allowed to explain *what* a function does, but you write the analysis.
**Build:** An **Exploratory Data Analysis (EDA)** notebook on a dataset you actually care about — your Spotify export, a Kaggle dataset, sports stats, movie ratings. Produce **3 charts that reveal something surprising.**

🚀 **Stretch:** Write a short "findings" markdown summary; clean messy real-world data.
💼 **Proves:** Data fluency — the daily bread of AI work. Recruiters love a clean, narrated notebook.

---

## Level 3 — Classic ML 🤖

🎯 **Goal:** Train a model that predicts, and let people try it.
🧰 **Stack:** scikit-learn, pandas, **Streamlit**.
🤖 **AI:** 🟡 **Assist allowed.** Write the ML core (the split, training, metrics) yourself so you *get* it — let AI handle Streamlit boilerplate and plotting glue.
**Build:** An **end-to-end predictor** — house prices, Titanic survival, customer churn, or spam detection. Train, evaluate honestly (precision/recall, not just accuracy), then wrap it in a **Streamlit app** with input widgets.

🚀 **Stretch:** Deploy the Streamlit app publicly (free Community Cloud); compare 2–3 models.
💼 **Proves:** You understand the full ML lifecycle — data → model → evaluation → usable demo. A *clickable* model beats a notebook every time.

---

## Level 4 — Deep Learning 🧠

🎯 **Goal:** Fine-tune a neural network on *your own* data.
🧰 **Stack:** PyTorch (or fastai), transfer learning, Hugging Face Hub.
🤖 **AI:** 🟡 **Assist allowed.** Write the training loop *by hand at least once* so you understand what's happening — then let AI scaffold data loading, the demo, and the boilerplate.
**Build:** A **custom image classifier** — your pets, plant diseases, food types, recyclable vs. trash. Fine-tune a pretrained CNN/ViT; report accuracy with a confusion matrix.

🚀 **Stretch:** Push the model to the HF Hub; build a Gradio demo where people upload an image.
💼 **Proves:** You can do deep learning with modern transfer learning — not just `model.fit()` on a tutorial dataset. *Your own dataset* is the flex.

---

## Level 5 — Transformers & LLMs ✨

🎯 **Goal:** Build a useful LLM app **and** prove it works.
🧰 **Stack:** Anthropic/OpenAI API (or HF), Python, a simple UI (Streamlit/Gradio).
🤖 **AI:** ✅ **Go for it** — vibe coding officially unlocked. From here, *using AI tools well is the skill.* Just understand every line you ship, especially the prompts and evals.
**Build:** A **prompt-powered app** — a study-buddy that quizzes you, "what can I cook with these fridge items," a tone-adjusting email rewriter, or a meeting-notes summarizer. **Plus a small evals notebook**: 10–20 test cases scoring quality, so you can prove it's not vibes.

🚀 **Stretch:** Add structured output (JSON), few-shot examples, and prompt versions you A/B tested.
💼 **Proves:** You can engineer with LLMs *and* evaluate them — the evals are what separate engineers from prompt-tinkerers. **Huge signal.**

---

## Level 6 — RAG 📚

🎯 **Goal:** Make an AI answer questions about specific documents, **with citations.**
🧰 **Stack:** LangChain *or* LlamaIndex, an embedding model, Chroma/FAISS/pgvector, Streamlit/FastAPI.
🤖 **AI:** ✅ **Go for it.** Full vibe coding — but you must be able to explain *how retrieval works*, or you can't debug it. Understand the pipeline, not just the prompt.
**Build:** **"Chat with your docs"** — upload PDFs (a textbook, company handbook, research papers) and ask questions; answers cite the source chunks.

🚀 **Stretch:** Add retrieval **evaluation** (faithfulness, relevance), hybrid search + reranking, and conversation memory.
💼 **Proves:** The single most in-demand AI-engineering skill right now. **This project alone gets people interviews** — make it your portfolio centerpiece.

---

## Level 7 — Image & Video Generation 🎨

🎯 **Goal:** Generate and *control* visual content.
🧰 **Stack:** diffusers / Stable Diffusion / Flux, ComfyUI, LoRA/PEFT, Gradio or Next.js.
🤖 **AI:** ✅ **Go for it** — and use *generative* AI as the product itself. Vibe-code the app, generate the media, the whole point is creating with AI.
**Build:** Pick one —
- An **image-gen web app** (prompt → image, with style presets and a gallery), **or**
- A **custom LoRA** trained on a theme/character/style you love, with before/after samples.

🚀 **Stretch:** Add ControlNet (pose/edge guidance); dabble in image-to-video; deploy on HF Spaces.
💼 **Proves:** Generative-media chops + a *visual* portfolio piece that literally catches the eye in a scroll. Visual = clicks = callbacks.

---

## Level 8 — Agents & Automation 🦾

🎯 **Goal:** Build AI that *acts* — uses tools, takes multiple steps, finishes a real task.
🧰 **Stack:** Function/tool calling, LangGraph or a custom loop, MCP, n8n (optional).
🤖 **AI:** ✅ **Go for it.** Building agents *with* AI assistance is expected. Focus your understanding on the failure handling, retries, and cost control — that's where it counts.
**Build:** An **autonomous agent** that does something genuinely useful for *you*: researches a topic and emails a daily digest, triages/labels your inbox, monitors prices and alerts you, or auto-files expenses from receipts.

🚀 **Stretch:** Package it as a reusable **MCP server**; add logging, retries, and a hard cost cap.
💼 **Proves:** You can build agentic systems with proper error handling — the gap between a viral demo and something that survives contact with reality. *Coders: this is where you pull ahead.*

---

## Level 9 — Ship It (LLMOps) 🚢

🎯 **Goal:** Turn a notebook toy into a real, deployed service people can hit.
🧰 **Stack:** FastAPI, Docker, a cloud host (Railway/Render/Fly/HF Spaces), Langfuse/LangSmith.
🤖 **AI:** ✅ **Go for it** — but run a **security-review prompt** before you deploy (no leaked keys, validated input, rate limits). Understand your deploy setup; "the AI did it" won't save a downed service.
**Build:** Take your **Level 6 RAG app or Level 8 agent** and ship it properly: FastAPI backend, `Dockerfile`, streaming responses, caching, rate limiting, basic monitoring, and a public URL.

🚀 **Stretch:** Add a CI pipeline that runs your evals on every push; a status page; prompt versioning.
💼 **Proves:** You're an **engineer**, not a tutorial-follower. "I deployed it, here's the live URL and the Dockerfile" is the sentence that gets you hired as a senior.

---

## Level 10 — Unstoppable 👑

🎯 **Goal:** Final form — fine-tune, evaluate rigorously, and give back.
🧰 **Stack:** PEFT/LoRA for LLMs, an eval framework, + everything above.
🤖 **AI:** ✅ **Go for it** — use every tool you've got. One caveat: your **open-source PR must be code you fully understand**, because maintainers *will* ask. By now, that's second nature.
**Build (two parts):**
1. A **full-stack capstone** that combines **RAG + agents + generative media**, deployed. Example: an agent that researches a topic (RAG over sources), writes a report, *and* generates illustrative images — all behind a real UI.
2. Your **first open-source contribution** to an AI repo — fix a bug, improve docs, add an example. A merged PR > any certificate.

🚀 **Stretch:** Fine-tune a small open model on a domain task and benchmark it vs. the base; write a blog post about what you learned.
💼 **Proves:** You can architect, build, deploy, *and* collaborate in the open. This is the portfolio of someone who gets hired. **You're unstoppable.** 👑

---

## 🧱 Turn Projects into a Resume

You've built ~11 projects. Now make them *work for you*:

### 📌 Pin your best 6
GitHub lets you pin 6 repos to your profile. Choose the ones that show range: **RAG, an agent, a deployed service, a gen-media app, a deep-learning model, the capstone.**

### 📝 Every pinned repo needs:
- ✅ A **one-line description** + topics/tags
- ✅ A README with a **screenshot or GIF at the top** (people decide in 3 seconds)
- ✅ **"What it does"** in plain English, then **"How to run it"**
- ✅ A **live demo link** if at all possible (Streamlit/Gradio/HF Spaces/Vercel — all free)
- ✅ The **tech stack** as badges

### 🪪 Your profile README
- Who you are + what you build, in two sentences
- "Featured Projects" with links + one-liners
- Your stack (Python, PyTorch, LangChain, FastAPI, Docker…)
- How to reach you (LinkedIn, email)

### 🗣️ Write about it
A short blog post or LinkedIn thread per big project ("How I built a RAG system that cites its sources") doubles the value — it shows communication, which seniors are hired for.

### 🎯 The mindset
> Don't apply as "someone trying to break into AI." Apply as **"someone who has built and deployed AI systems — here are 6 of them."** The repos are the receipts. Go get the job. 🚀

---

> Back to **[the roadmap](README.md)** · Resources in **[RESOURCES.md](RESOURCES.md)**
