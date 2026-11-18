# Aleix Moreno Telesforo

**I design and build AI systems, and I use AI agents to build them.**
I started in operations, moved to product, and now I work in technology.

[aleixmorenotelesforo.com](https://aleixmorenotelesforo.com) ·
[LinkedIn](https://linkedin.com/in/aleix-moreno-telesforo) ·
[Email](mailto:hello@aleixmorenotelesforo.com)

---

## What I am exploring

> How far can AI agents take software development on their own (safely, cheaply and in a way I
> can measure), and where do I still add the most value?

1. **Capability where it pays.** Which work needs a frontier model, and which can a small or local
   model do just as well? *I measure models on my own past work, not on public benchmarks.*
2. **Autonomy that is safe by design.** How much can agents plan, merge and deploy without me?
   *I size my approval to what a mistake would cost. I do not approve every step.*
3. **Context, not prompts.** How does a system prepare what an agent needs to know, so that each
   agent starts small and focused? *I keep strategy apart from execution, and I hand over each
   piece of work as a self-contained brief.*
4. **The human's new role.** When agents write the code, what is my job? *I work as architect,
   decision maker and reviewer, and I watch where my time actually goes.*

## How I work

| Practice | What it means |
|---|---|
| **One role per chat** | I keep research, ideation, planning, orchestration and execution in separate AI sessions. Each has one job and only the context it needs. |
| **Strategy apart from code** | My private planning repository holds direction, decisions and designs. Each project repository holds only what exists and works. Only a self-contained brief crosses from one to the other. |
| **Design before building** | An AI planner questions me one point at a time until we agree on the design. No code is written before that. |
| **Small slices** | Each piece of work is one agent session, one branch, one pull request and one done-criterion. It ends with something that runs. |
| **Safeguards sized to risk** | Agents merge and deploy on their own, with automatic rollback. Only changes that cannot be undone, or that touch secrets, money or public exposure, wait for me. |
| **Evidence before abstraction** | I measure before I add machinery, and I test models on my own past work. |
| **The cheapest model that does the job** | Each task uses the least capable model that does it reliably. It moves up a model when it fails. |
| **Mature tools over custom machinery** | Libraries own the machinery. I write code only for the seams and the rules between them. |
| **Say what is true** | Built, running, in progress and planned are different words. |

The platform that runs this process: [homelab-v2](https://github.com/TelesforoAleix/homelab-v2).

## Projects

- **[Home Lab](https://github.com/TelesforoAleix/homelab-v2):** my self-hosted applied-AI
  platform. It routes each request by purpose across hosted and local models, and runs coding
  agents in sandboxes. Its development system, Factory, plans, builds, reviews and deploys the
  platform with AI agents (Factory is private for now). I have delivered about 360 slices of work
  this way since September 2026.
- **[med-ask](https://github.com/TelesforoAleix/med-ask):** search over 13 medical textbooks (about
  12,500 pages) that I built for a medical student. It returns the original passages with book and
  page, and keeps the generated answer apart from the sources.
- **[Practical Quantum Advantage in Finance](https://github.com/TelesforoAleix/quantum-finance):**
  my MSc thesis. I did an AI-supported review of 777 papers with several LLMs. None of the 13 best
  candidates gives a practical advantage once the cost of loading data is counted.
- **[Business Central Manufacturing Videos](https://www.youtube.com/playlist?list=PLEyIZHETM3k4)
  and [ClickReplay](https://github.com/TelesforoAleix/ClickReplay):** six tutorial videos that I
  made at Microsoft with a GenAI toolchain (Copilot agents, the Microsoft Learn MCP server).
  ClickReplay is the small public tool that I built to record and replay the demo input.
