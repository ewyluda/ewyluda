# Eric Wyluda

**I build the systems that run hyperscale data center delivery, and I build them by directing AI coding agents.**

I'm a Sr. Power Platform & AI Developer at Microsoft (Cloud Operations + Innovation), building the cost-reporting, controls, and automation layer for the global data center capital program. Behind the tooling are 11+ years of delivering physical infrastructure:

- Led a 15-person equipment supply chain team on a 1+ GW hyperscale data center portfolio (Turner & Townsend, embedded with Google Data Centers)
- Did Primavera P6 schedule forensics for construction disputes at Ankura
- Delivered a $200M NYC transit hub on schedule and $17M under forecast

M.S. Construction Management, Columbia · B.S. Mechanical Engineering, UVM

## Selected builds

| Project | What it is |
|---|---|
| **[GPU Price Index](https://github.com/ewyluda/gpu-rental-rate)** · [live dashboard](https://ewyluda.github.io/gpu-rental-rate/) | An open, daily index of GPU rental prices across hyperscalers, neoclouds, and marketplaces. It is built from primary sources, versioned in git, and collected in CI, with a cluster cost calculator and an MCP server so agents can query it. |
| **[MacroGauge](https://github.com/ewyluda/macrogauge)** · [data center page](https://macrogauge-cloudten.vercel.app/datacenter) | Daily data center cost indexes for build, operations, and hardware (switchgear, transformers, generators, HVAC, labor), plus state cost parity and real data center construction spending. Every published artifact is schema-validated and QA-gated, with an append-only revision history. |
| **[Sector Research](https://github.com/ewyluda/sector-research)** | An agentic research analyst. It turns SEC filings, fundamentals, and earnings calls into cited theses with falsifiable kill criteria, then monitors them. The math is deterministic code; the model handles judgment, and its output is checked by an eval harness, 1,100+ tests, and CI gates. |
| **[Multi-Agent Market Research](https://github.com/ewyluda/multi-agent-market-research)** + **[Equity DD Agent Playbook](https://github.com/ewyluda/equity-dd-agent-playbook)** | Fifteen parallel data and synthesis agents with deterministic guardrails behind a 42-tool MCP server, plus the due-diligence methodology written as executable agent skills. |

## How I build

- **Agent-directed and terminal-first.** I write the spec, agents write the code, and I review, test, and evaluate it. I use Claude Code and Codex for independent work and GitHub Copilot CLI at work.
- **Deterministic where it has to be right.** Math, routing, and validation live in code, and the model handles judgment. Evals and CI gates check the model's work.
- **Data products that keep running.** They publish on a schedule, keep history, and fail loudly.

**Stack:** Python · SQL · FastAPI · Next.js · Postgres · GitHub Actions · MCP · Anthropic / OpenAI / xAI APIs · Power Platform (Power Apps, Power Automate, Power BI, Dataverse) · Azure · Primavera P6

## What I'm interested in

I'm interested in roles where data center and AI-infrastructure delivery meets software and AI:

- **Data center delivery TPM or controls lead** roles that build the tracking, reporting, and tooling layer, not just coordinate it
- **Applied AI and internal-tools** roles inside data center, capacity, and infrastructure organizations
- **Deployment lead or strategist** roles taking AI systems from contract to production

I'm based in Florida and remote-first, and open to relocating for the right role. You can reach me on [LinkedIn](https://www.linkedin.com/in/ericwyluda/).
