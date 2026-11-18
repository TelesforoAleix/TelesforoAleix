# Aleix Moreno Telesforo

**I design and build AI systems, and I use AI agents to build them.**

My background spans business operations, product development and enterprise software. Today, I
focus on applied AI: I try to understand real problems, design practical systems and explore how AI
agents can make software development more effective.

[Website](https://aleixmorenotelesforo.com) · [LinkedIn](https://linkedin.com/in/aleix-moreno-telesforo) · [Email](mailto:hello@aleixmorenotelesforo.com)

---

## Projects

- **[Home Lab](https://github.com/TelesforoAleix/homelab-v2):** my self-hosted applied-AI
  platform. It integrates hosted and local models through purpose-based routing, shared APIs and
  secure execution environments. Factory is built on top of it. It is an AI-assisted software
  development system that separates planning and orchestration from sandboxed agent execution,
  automated review and deployment. Factory is private for now.
- **[med-ask](https://github.com/TelesforoAleix/med-ask):** search over a medical student's 13
  textbooks (about 12,500 pages). Four are indexed so far. It returns the original passages with
  book and page, and keeps the generated answer apart from the sources.
- **[Practical Quantum Advantage in Finance](https://github.com/TelesforoAleix/quantum-finance):**
  my MSc thesis. I did an AI-supported review of 777 papers with several LLMs. None of the 13 best
  candidates gives a practical advantage once the cost of loading data is counted.
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

| Principle | How I apply it |
|---|---|
| **Design before implementation** | An AI planner questions me one point at a time until we agree on the design. I write no code before that. |
| **Context and separation of responsibilities** | I give each AI session one role: research, ideation, planning, orchestration or execution. My private planning repository stays apart from the project repositories, and only a self-contained brief crosses between them. |
| **Small, verifiable changes** | Each change is one agent session, one branch, one pull request and one done-criterion. It ends with something that runs and is tested. |
| **Risk-based autonomy** | Agents merge and deploy on their own, with automatic rollback. Only changes that cannot be undone, or that touch secrets, money or public exposure, wait for me. |
| **Evaluation and cost discipline** | I measure before I add machinery, and I test models on my own past work. Each task uses the cheapest model that does it reliably, and I prefer mature libraries to custom machinery. |

The platform that runs this process: [homelab-v2](https://github.com/TelesforoAleix/homelab-v2).
