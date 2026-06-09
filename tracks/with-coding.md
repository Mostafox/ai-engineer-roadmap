# 🧑‍💻 Track A — The Coder (Programming Background)

> You already ship code. You don't need a 6-month "intro to variables." You need the **fast lane** to AI engineering — and a no-nonsense map of what's actually worth your time. Let's sprint. 🏃‍♂️💨

This track maps onto the same [12-level campaign](../README.md#-the-campaign-map) but **compresses Levels 1–2 into a skim checklist**, drops you into the real work at Level 3, and **leans harder on production** (Levels 9–11) where most self-taught folks are weak and where you'll stand out.

📚 Resources → **[RESOURCES.md](../RESOURCES.md)** ⚔️ Project briefs → **[PROJECTS.md](../PROJECTS.md)**

> **Your unfair advantage:** you already understand abstraction, debugging, and shipping. Most "AI" work is *software engineering with a probabilistic dependency.* You're closer than you think.

---

## Level 0 — The Awakening (15 min) 🌅

You have Git, an editor, and a GitHub account. Just:
- Set up a clean Python env with **[uv](https://github.com/astral-sh/uv)** (fast, modern — ditch the old venv/pip dance).
- Get API keys: [Anthropic](https://console.anthropic.com/) and/or [OpenAI](https://platform.openai.com/).
- Skim what "AI Engineer" means in 2026 vs. "ML Researcher" (you want the former: building *on* models).

**⚔️ Boss Project:** A polished [profile README](../PROJECTS.md#level-0--the-awakening-) if you don't have one. First impressions matter to recruiters.

---

## Level 1 — Speak Python (Skim Checklist) 🐍

If you came from JS/Java/C#/Go, Python is a weekend. **Skip the courses.** Just verify you can do all of these without Googling:

- [ ] f-strings, list/dict **comprehensions**, slicing
- [ ] `*args`/`**kwargs`, decorators, context managers (`with`)
- [ ] type hints, `dataclasses`, `pathlib`
- [ ] virtual envs, `pip`/`uv`, reading a `pyproject.toml`
- [ ] async basics (`async`/`await`) — you'll need it for API calls

✅ All checked? **Jump to Level 3.** ❌ Gaps? → [RESOURCES.md → Python](../RESOURCES.md#-python-the-language-of-ai) (skim only the gaps).

**⚔️ Optional flex project:** A [CLI tool](../PROJECTS.md#level-1--speak-python-) that already calls an LLM API. Skip the toy phase.

---

## Level 2 — Data & Math-Lite (Targeted) 📊

You don't need to *like* math, just not fear it. Speed-run:
- **pandas + NumPy** — learn enough to slice/merge/groupby fluently (you'll use this constantly).
- **Math intuition** — watch [3Blue1Brown's Neural Networks + Linear Algebra](https://www.3blue1brown.com/) series at 1.5x. Vectors, dot products, gradients (slopes). That's the whole job.

**Resources:** → [RESOURCES.md → Math-Lite](../RESOURCES.md#-math-lite-just-enough-no-phd)

**⚔️ Boss Project:** A quick [EDA notebook](../PROJECTS.md#level-2--data--math-lite-) — prove pandas fluency, then move on.

---

## Level 3 — Classic ML 🤖

Don't skip this thinking "LLMs are all that matters." Understanding train/test, overfitting, and metrics makes you *dangerous* at evaluating LLM systems later.

**Learn:** scikit-learn pipelines, cross-validation, precision/recall/F1, when a simple model beats a fancy one.

**Resources:** → [RESOURCES.md → ML & Deep Learning](../RESOURCES.md#-machine-learning--deep-learning)

**⚔️ Boss Project:** [End-to-end ML predictor + Streamlit demo](../PROJECTS.md#level-3--classic-ml-). Make it deployable, not just a notebook.

---

## Level 4 — Deep Learning 🧠

**Learn:** [PyTorch](https://pytorch.org/) (the industry default), the training loop *by hand* once, CNNs, and **transfer learning** (you'll rarely train from scratch). Recommended: **fast.ai** — fastest path to competence for someone who can already code.

**Resources:** → [RESOURCES.md → ML & Deep Learning](../RESOURCES.md#-machine-learning--deep-learning)

**⚔️ Boss Project:** [Fine-tuned image classifier](../PROJECTS.md#level-4--deep-learning-) on a custom dataset. Bonus: push the model to the Hugging Face Hub.

> 🎯 **Convergence point.** Both tracks merge here. Levels 5+ are identical — but as a coder you should push the *production* depth in each.

---

## Level 5 — Vibe Coding 🎸

You already write code — so this isn't about *whether* to use AI, it's about using it like a **tech lead**, not a copy-paste gremlin. Master this and you'll out-ship engineers twice your experience.

**Learn:**
- Agentic coding workflows: drive **Claude Code** / **Cursor** agent mode over a whole repo — plan, edit, run, iterate.
- Treat the AI as a fast junior: make it propose a plan, review it critically, keep diffs small, and **read every line** (you can — you're a coder).
- Prompting as spec-writing: precise context, one job per prompt, paste full stack traces, demand tests.
- Guardrails that matter at speed: version-control every working state, run a **security-review pass** before deploy, never hardcode secrets.
- Know when *not* to vibe: subtle algorithms and security-critical code still want your hands on the keyboard.

**Resources:** → **[VIBE-CODING.md](../VIBE-CODING.md)** (the full playbook) + **[TOOLBOX.md → Vibe-Coding Tools](../TOOLBOX.md#-vibe-coding--ai-dev-tools)**

**⚔️ Boss Project:** [Take a non-trivial app and build it end-to-end, AI-assisted, then deploy it](../PROJECTS.md#level-5--vibe-coding-) — and write a short "how I vibe-coded this" section in the README documenting your prompts and where you had to step in. *That meta-awareness is a senior signal.*

---

## Level 6 — Transformers & LLMs ✨

**Learn:** Attention (read ["The Illustrated Transformer"](https://jalammar.github.io/illustrated-transformer/)), tokenization, embeddings, the [Hugging Face](https://huggingface.co/) ecosystem, and **prompt engineering** as engineering — structured outputs, system prompts, few-shot.

**Resources:** → [RESOURCES.md → LLMs & Prompting](../RESOURCES.md#-llms--prompt-engineering)

**⚔️ Boss Project:** A [prompt-powered app with a real evals harness](../PROJECTS.md#level-6--transformers--llms-). The evals are what separate engineers from prompt-tinkerers — lean in here.

---

## Level 7 — RAG 📚

**Learn:** Embeddings, vector DBs ([Chroma](https://www.trychroma.com/)/FAISS/[pgvector](https://github.com/pgvector/pgvector)), chunking strategies, hybrid search, reranking, and **RAG evaluation** (retrieval quality, faithfulness). [LangChain](https://www.langchain.com/) / [LlamaIndex](https://www.llamaindex.ai/) — but understand the primitives so you can drop the framework when it bloats.

**Resources:** → [RESOURCES.md → RAG](../RESOURCES.md#-rag-retrieval-augmented-generation)

**⚔️ Boss Project:** [Production-grade "chat with your docs"](../PROJECTS.md#level-7--rag-) — citations, eval metrics, and a clean API. Push hard: this is *the* most in-demand skill right now.

---

## Level 8 — Image & Video Generation 🎨

**Learn:** Diffusion intuition, [Stable Diffusion](https://stability.ai/)/[Flux](https://blackforestlabs.ai/), [ComfyUI](https://github.com/comfyanonymous/ComfyUI) graphs, ControlNet, and training a **LoRA**. Plus calling hosted gen APIs for product work.

**Resources:** → [RESOURCES.md → Image & Video Gen](../RESOURCES.md#-image--video-generation)

**⚔️ Boss Project:** [Image-gen web app **or** a trained LoRA](../PROJECTS.md#level-8--image--video-generation-) with a Gradio/Next.js front end. Visual projects get clicks — and clicks get callbacks.

---

## Level 9 — Agents & Automation 🦾

This is where coders pull ahead. Real agentic systems are *systems engineering*.

**Learn:** Function/tool calling, agent loops & planning, [MCP](https://modelcontextprotocol.io/) (build your own MCP server), multi-agent orchestration, and automation with [n8n](https://n8n.io/). Critically: **failure handling, retries, and cost control** — where toy agents die.

**Resources:** → [RESOURCES.md → Agents & Automation](../RESOURCES.md#-agents--automation)

**⚔️ Boss Project:** A [robust autonomous agent](../PROJECTS.md#level-9--agents--automation-) doing a genuinely useful task, with logging and guardrails. Build it as a reusable MCP server for extra credit.

---

## Level 10 — Ship It (LLMOps) 🚢

Your home turf — make it your differentiator.

**Learn:** [FastAPI](https://fastapi.tiangolo.com/) services, [Docker](https://www.docker.com/), streaming responses, caching, rate limiting, observability ([LangSmith](https://www.langchain.com/langsmith)/[Langfuse](https://langfuse.com/)), evals in CI, prompt versioning, and cloud deploy.

**Resources:** → [RESOURCES.md → Deployment & LLMOps](../RESOURCES.md#-deployment--llmops)

**⚔️ Boss Project:** [Deploy a prior project as a real service](../PROJECTS.md#level-10--ship-it-llmops-) — Dockerized, monitored, with a CI pipeline and a status page. *This is what gets you hired as a senior.*

---

## Level 11 — Unstoppable 👑

**Learn:** Fine-tuning & PEFT/[LoRA](https://huggingface.co/docs/peft) for LLMs, quantization, rigorous evals, reading papers fast, and a personal "stay current" system. Then **contribute to open source** — a merged PR to a known AI repo is worth more than any certificate.

**Resources:** → [RESOURCES.md → Staying Current](../RESOURCES.md#-staying-current-dont-drown)

**⚔️ Boss Project:** A [full-stack capstone](../PROJECTS.md#level-11--unstoppable-) (RAG + agents + gen media, deployed) **and** a merged OSS contribution.

---

## 🏁 Final Form

You went from "software engineer" to "**AI engineer who ships systems that think.**" Your GitHub tells the whole story — train, retrieve, generate, deploy. Pin the best 6, polish the READMEs, and walk into interviews with receipts. 👑

> Next: **[PROJECTS.md → Turn Projects into a Resume](../PROJECTS.md#-turn-projects-into-a-resume)**
