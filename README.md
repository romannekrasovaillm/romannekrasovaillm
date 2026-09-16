<div align="center">

<a href="https://github.com/romannekrasovaillm">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=2F80ED&center=true&vCenter=true&width=820&lines=Agentic+mid-training+%C2%B7+RLVR+%C2%B7+agent+environments+at+scale;Rust+agent+harnesses+%E2%80%94+tools%2C+skills%2C+governance;CPT+%E2%86%92+SFT+%E2%86%92+GRPO+on+small+models%2C+at+home;Architecture+for+an+AI-native+bank" alt="Typing SVG" />
</a>

# Roman Nekrasov

**IT Architect — corporate banking architecture · independent LLM/RL researcher-practitioner**
**ИТ-архитектор (корпоративная архитектура банка) · независимый исследователь-практик LLM/RL**

![Profile views](https://komarev.com/ghpvc/?username=romannekrasovaillm&label=Profile%20views&color=2f80ed&style=flat)
[![Followers](https://img.shields.io/github/followers/romannekrasovaillm?label=Followers&style=flat&color=2f80ed)](https://github.com/romannekrasovaillm?tab=followers)
[![Stars](https://img.shields.io/github/stars/romannekrasovaillm?affiliations=OWNER&label=Total%20stars&style=flat&color=2f80ed)](https://github.com/romannekrasovaillm?tab=repositories)

</div>

---

### 🧭 The thesis · Тезис

**A domain-tuned agent harness beats a universal one on its own tasks.**
**Доменно-заточенный агентный харнесс бьёт универсальный — на задачах самого универсала.**

Everything below is a working proof — built, measured and dogfooded daily.
Всё ниже — рабочие доказательства: построено, измерено и используется каждый день.

### 🏛️ Agent harnesses (Rust)

| Repo | What it is · Что это |
|---|---|
| [**theseus**](https://github.com/romannekrasovaillm/theseus) | Industrial-grade agentic TUI harness for the ML/RL domain — built after a code review of three industry leaders, then deliberately bent where leaders don't go. **~57K LOC · 74 modules · 31 agent tools · 1,367 green tests · 981 skills (1,093 SKILL.md) · 0 clippy warnings.** Runs a local GRPO-tuned Qwen3.5-4B as its «Ariadne's thread». |
| [**spine**](https://github.com/romannekrasovaillm/spine) | Domain harness for solution architects: spine-invariants, ADR workflow, LLM-judge rubrics, skills/plugins, subagents, governance. |
| [**spine-bank**](https://github.com/romannekrasovaillm/spine-bank) | Spine Banking Edition (arch-be) — harness for banking solution architects; public MIT snapshot of the core. |
| [**spine-aiml**](https://github.com/romannekrasovaillm/spine-aiml) | Spine AI/ML Edition (arch-ml) — meta-harness for AI/ML researchers riding on top of coding harnesses: invariants, fitness gates, handoff contracts. |
| [**spine-be-distrib**](https://github.com/romannekrasovaillm/spine-be-distrib) | arch-be distribution — binary releases and install guides. |

### 🧪 Post-training line (CPT → SFT → GRPO / RLVR)

| Repo | What it is · Что это |
|---|---|
| [**ariadna-training**](https://github.com/romannekrasovaillm/ariadna-training) | Qwen3.5-4B CPT + SFT + GRPO pipeline for ML-concept curation, fed by a private 18.6K-paper arXiv library distilled into concept cards. |
| [**qwen35-4b-ariadna-grpo**](https://github.com/romannekrasovaillm/qwen35-4b-ariadna-grpo) | GRPO post-training: 5 iterations (v6–v10), 3-level reward + GRM judge. Weights: [GGUF on Hugging Face](https://huggingface.co/Rob1234567/qwen3.5-4b-ariadna-grpo-v1-gguf). |
| [**alfworld-grpo-siri-reskill**](https://github.com/romannekrasovaillm/alfworld-grpo-siri-reskill) | Multi-turn GRPO on ALFWorld — SIRI+Replay skill internalization (Qwen2.5-1.5B). |

### 🛠️ Skills, evals & benchmarks

| Repo | What it is · Что это |
|---|---|
| [**agent-eval-skills**](https://github.com/romannekrasovaillm/agent-eval-skills) | Agent Skills for evaluating LLM agents and LLM apps: classification, rubrics, gates. |
| [**tui-trace-control**](https://github.com/romannekrasovaillm/tui-trace-control) | Controlling TUI agents' reasoning and actions via local traces — a full 8-skill lifecycle (setup → watch → audit → contain → resume). |
| [**ai-detector-evasion-skills**](https://github.com/romannekrasovaillm/ai-detector-evasion-skills) | How AI-content detectors work, where they fail, and the ethics boundaries — Agent Skills. |
| [**ai-native-sdlc-architect-artifacts**](https://github.com/romannekrasovaillm/ai-native-sdlc-architect-artifacts) | AI-native SDLC: architectural artifacts for corporate & solution architects. |
| [**spine-contour-bench**](https://github.com/romannekrasovaillm/spine-contour-bench) | Benchmark of the contour around an agent: gates, traceability, handoff packages. |
| [**platformv-arch-bench**](https://github.com/romannekrasovaillm/platformv-arch-bench) | Benchmark of architecture tasks: harness role & Spine format vs the universal approach. |

### 📊 GitHub stats

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=romannekrasovaillm&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight" />
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=romannekrasovaillm&show_icons=true&hide_border=true&rank_icon=github" alt="GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=romannekrasovaillm&hide_border=true&theme=tokyonight" />
  <img height="165" src="https://streak-stats.demolab.com?user=romannekrasovaillm&hide_border=true" alt="GitHub streak" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=romannekrasovaillm&layout=compact&hide_border=true&langs_count=8&theme=tokyonight" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=romannekrasovaillm&layout=compact&hide_border=true&langs_count=8" alt="Top languages" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=romannekrasovaillm&hide_border=true&theme=tokyo-night" />
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=romannekrasovaillm&hide_border=true&theme=minimal" alt="Activity graph" />
</picture>
</div>

### 🧰 Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=rust,python,pytorch,docker,linux,git,githubactions,bash,postgres,vscode&perline=10" alt="Stack icons" />
</div>

### 🐍

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/romannekrasovaillm/romannekrasovaillm/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/romannekrasovaillm/romannekrasovaillm/output/github-contribution-grid-snake.svg" alt="Contribution snake" />
</picture>
</div>

---

<div align="center">
<sub>Research projects — not for production · Исследовательские проекты, не для прода</sub>
</div>
