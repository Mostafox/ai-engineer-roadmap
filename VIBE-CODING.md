# 🎸 Vibe Coding: 0 → Production in Any Language

> 📍 **This is the playbook for [Level 5](README.md#-the-campaign-map) of the roadmap** — the skill that turns you from "someone who learned to code" into "someone who ships." Both tracks converge here.

> **Vibe coding** = you describe what you want in plain language, and AI writes the code while you steer, review, and ship. You're the director; the AI is the crew. 🎬
>
> Done lazily, it produces broken apps you don't understand. Done *well*, it's a superpower that lets one person build what used to take a team. This guide teaches the *well* version.

---

## 🧠 The Golden Rule

> **Never ship code you don't understand.**

AI can write 500 lines in 5 seconds. If you paste it in blindly and it breaks, you're stuck with no idea why. The skill isn't *generating* code — it's **directing, reading, and verifying** it. Treat the AI like a brilliant, fast, slightly overconfident junior dev: amazing output, but *you* are responsible for what ships.

---

## 🛠️ Your Vibe-Coding Setup

Pick the tool that matches your level (full list in **[TOOLBOX.md](TOOLBOX.md#-vibe-coding--ai-dev-tools)**):

| You want to… | Use |
|---|---|
| Build a web app fast, beginner-friendly | **Bolt.new**, **Lovable**, **v0** |
| Code seriously in a real editor | **Cursor** or **Windsurf** |
| Drive an agent over your whole repo | **Claude Code** |
| Code in the cloud, instant hosting | **Replit + Agent** |

Language-agnostic: the *same workflow* works for Python, JavaScript/TypeScript, Go, Rust, Swift — anything. The AI adapts to the language; you keep the process.

---

## 🔄 The Workflow — 8 Steps from Idea to Production

### 1. 🎯 Define the thing (1 paragraph)
Before any code, write what you're building, for whom, and the *one* core feature. Vague prompts → vague apps. Example:
> "A web app where users paste a YouTube URL and get an AI-generated summary with timestamps. Just that, working, deployable."

### 2. 🗺️ Ask AI to plan, not code (yet)
Prompt: *"Before writing code, propose a tech stack and a step-by-step build plan for [idea]. Keep it minimal."* This gives you a map and catches bad decisions early. **Review the plan like a manager** — push back, simplify.

### 3. 🧱 Scaffold the project
Let the AI generate the skeleton: folder structure, dependencies, a "hello world" that *runs*. **Get something running on screen before adding features.** A running ugly app beats a beautiful broken one.

### 4. 🧩 Build one feature at a time
Work in **small loops**: one feature → run it → see it work → commit → next. Don't ask for the whole app at once; you can't review a wall of code. Small diffs = you stay in control and bugs are easy to locate.

### 5. 👀 Read everything (this is the level-up)
For each chunk the AI writes, ask yourself: *What does this do? Why this approach?* If you don't know, **ask the AI to explain it line by line.** This is how vibe coding makes you a *better* engineer instead of a dependent one.

### 6. 🧪 Test & debug with the AI
When it breaks (it will): **paste the full error message** back to the AI. Errors are the AI's best fuel. Ask for tests too: *"Write tests for this function and show me they pass."* Verify behavior yourself — don't take "it works" on faith.

### 7. 🔐 Lock it down before shipping
Vibe-coded apps leak secrets and skip security. Before production, explicitly check:
- ✅ **No API keys in code** — use environment variables / `.env` (and `.gitignore` it!).
- ✅ **Input validation** — never trust user input.
- ✅ **Auth** if there's user data.
- ✅ **Rate limits & cost caps** on any AI API calls (a loose loop can cost real money 💸).
- ✅ Ask: *"Review this code for security issues and secrets before I deploy."*

### 8. 🚀 Deploy
Push to a host (most have free tiers): **Vercel/Netlify** (web front ends), **Railway/Render/Fly.io** (backends), **Hugging Face Spaces** (ML demos), **Streamlit Community Cloud** (data apps). Then put the **live URL in your README**. A deployed thing > a localhost thing, every time.

---

## ✍️ How to Prompt Like a Pro

- **Give context:** language, framework, file you're editing, what you've tried.
- **Be specific:** "add input validation and a loading spinner" beats "make it better."
- **One job per prompt:** don't pile five asks into one message.
- **Bring the error:** paste the *exact* stack trace, not "it doesn't work."
- **Ask for explanations:** "explain this like I'm new to Rust."
- **Iterate:** treat the first answer as a draft. "Good, now make it handle empty input."
- **Use version control as a safety net:** commit working states so you can always roll back when the AI "improves" your app into oblivion.

---

## 🚧 Vibe-Coding Traps (and how to dodge them)

| Trap | Fix |
|---|---|
| Pasting code you don't understand | Ask for a line-by-line explanation first |
| One giant "build my whole app" prompt | Break into small, runnable steps |
| Ignoring security/secrets | Run a security-review prompt before deploy; never hardcode keys |
| Endless "fix it" loops on a bad foundation | Stop, re-plan from step 2 — sometimes restart clean |
| No version control | `git commit` every working state |
| Believing "it works" without checking | Run it yourself, write a test |

---

## 🎬 A Tiny Worked Example (any language)

> **Goal:** "URL → AI summary" web app.

1. **Define:** one feature — paste URL, get summary.
2. **Plan:** ask AI → it suggests e.g. Next.js + an LLM API (or Python + FastAPI + Streamlit). Pick one.
3. **Scaffold:** AI builds a running page with an input box. You open it — it loads. ✅ commit.
4. **Feature 1:** fetch the page/transcript. Run it. ✅ commit.
5. **Feature 2:** send text to an LLM, show the summary. Run it. ✅ commit.
6. **Debug:** error about an env var → paste it → AI fixes the `.env` loading.
7. **Secure:** move the API key to env, add a rate limit, run a security-review prompt.
8. **Deploy:** push to Vercel/Render → live URL → into the README.

Congrats — that's a portfolio project, vibe-coded *responsibly*. 🎉

---

## 🤖 But wait — am I allowed to use AI on my roadmap projects?

Great question, and it has a deliberate answer that changes by level. **See the rule in [PROJECTS.md → The "Can I Use AI?" Rule](PROJECTS.md#-the-can-i-use-ai-rule).** Short version: **write the early-level code yourself** (so you actually learn the fundamentals), then **go full vibe-coding from the LLM levels onward** (because using AI tools well *is the job*).

> Back to **[the roadmap](README.md)** · Tools in **[TOOLBOX.md](TOOLBOX.md)**
