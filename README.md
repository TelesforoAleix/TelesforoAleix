# Aleix Moreno Telesforo

**I design and build AI systems, and I use AI agents to build them.**

My background spans business operations, product development and enterprise software. Today, I
focus on applied AI: understanding real problems, designing practical systems and exploring how
AI agents can make software development more effective.

[Website](https://aleixmorenotelesforo.com/?utm_source=github&utm_medium=referral) · [LinkedIn](https://linkedin.com/in/aleix-moreno-telesforo) · [Email](mailto:hello@aleixmorenotelesforo.com)

---

## Projects

- **[Home Lab](https://github.com/TelesforoAleix/homelab-v2):** HomeLab provides the infrastructure
  for model routing, APIs and secure execution. Built on top of it,
  [Factory](https://github.com/TelesforoAleix/factory) orchestrates AI-assisted software
  development, separating planning and orchestration from sandboxed agent execution, automated
  review and deployment.
- **[med-ask](https://github.com/TelesforoAleix/med-ask):** search over a medical student's 13
  textbooks (about 12,500 pages). It returns the original passages with
  book and page, and keeps the generated answer apart from the sources.
- **[Practical Quantum Advantage in Finance](https://github.com/TelesforoAleix/quantum-finance):**
  my MSc thesis, co-authored with [Vincent Wallerich](https://github.com/vallahrich). We ran an
  AI-supported review of 777 papers with several LLMs. None of the 13 strongest template circuits
  passed all five advantage criteria once the cost of loading data was counted.
- **[Business Central Manufacturing Videos](https://www.youtube.com/playlist?list=PLEyIZHETM3k4)
  and [ClickReplay](https://github.com/TelesforoAleix/ClickReplay):** six tutorial videos that I
  made at Microsoft with a GenAI toolchain (Copilot agents, the Microsoft Learn MCP server).
  ClickReplay is the small public tool that I built to record and replay the demo input.

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

I own the system architecture, the technical decisions, the execution boundaries and the acceptance
criteria. AI coding agents implement the changes. I validate them through reviews, tests and
operational feedback.

| Practice | What it means |
|---|---|
| **One role per chat** | I keep research, ideation, planning, orchestration and execution in separate AI sessions. Each has one job and only the context it needs. |
| **Strategy apart from code** | My private planning repository holds direction, decisions and designs. Each project repository holds only what exists and works. Only a self-contained brief crosses from one to the other. |
| **Design before building** | I research, design and stress-test each change with AI sparring before any code: its fit with the current architecture, its conflicts and its failure modes. Building starts when the design holds. |
| **Small slices** | Each piece of work is one agent session, one branch, one pull request and one done-criterion. It ends with something that runs. |
| **Safeguards sized to risk** | Agents merge and deploy on their own, with automatic rollback. Only changes that cannot be undone, or that touch secrets, money or public exposure, wait for me. |
| **Evidence before abstraction** | I measure before I add machinery. I test models on my own past work, and each task uses the cheapest model that does it reliably. |
| **Mature tools, honest claims** | Libraries own the machinery; I write code only for the seams and rules between them. Built, running and planned are different words. |

The platform that runs this process: [homelab-v2](https://github.com/TelesforoAleix/homelab-v2).
