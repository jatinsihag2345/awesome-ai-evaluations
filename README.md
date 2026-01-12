# Awesome AI Evaluations & Agent Benchmarks

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated list of frontier AI evaluation benchmarks, long-horizon agent test suites, terminal sandboxes, RLVR math verifiers, and red-teaming datasets.

## 🧠 Chain-of-Thought & Reasoning Trace Benchmarks
- **[AIME 2024/2025](https://artofproblemsolving.com/wiki/index.php/AIME_Problems_and_Solutions)** - American Invitational Mathematics Examination benchmark for high-compute reasoning models.
- **[GPQA Diamond](https://github.com/idavidrein/gpqa)** - Google-proof Q&A benchmark vetted by domain experts in biology, physics, and chemistry.
- **[CoT-Reasoning-Auditor](https://github.com/jatinsihag2345/cot-reasoning-auditor)** - Reasoning trace audit toolkit for evaluating logical coherence, circular reasoning, and overthinking token penalties.

## 🏛️ Code & Software Engineering Benchmarks
- **[SWE-bench](https://www.swebench.com/)** - Resolving real-world GitHub issues using repository-level context and pytest oracle suites.
- **[SWE-bench Lite](https://www.swebench.com/lite.html)** - 300 selected self-contained SWE-bench instances for faster iteration and model evaluation.
- **[LiveCodeBench](https://livecodebench.github.io/)** - Contamination-free coding benchmark featuring periodic problems from LeetCode, AtCoder, and Codeforces.

## 🖥️ Terminal & Operating System Sandboxes
- **[TerminalBench](https://github.com/jatinsihag2345/terminal-bench-eval)** - Sandboxed CLI and OS benchmark harness evaluating autonomous sysadmin and coding agents with deterministic verification.
- **[InterCode](https://intercode-benchmark.github.io/)** - Interactive coding environment for evaluating agents in Bash and SQL execution environments.
- **[OSWorld](https://os-world.github.io/)** - Real-world operating system environment benchmark for multimodal desktop agents across Ubuntu/Linux.

## 🌐 Web & Multi-Modal Assistant Benchmarks
- **[GAIA](https://huggingface.co/gaia-benchmark)** - General AI Assistants benchmark testing multi-modal file parsing, web navigation, and tool execution.
- **[WebArena](https://webarena.dev/)** - Realistic web environment for evaluating autonomous web agents across e-commerce, forums, and code collaboration sites.

## 📐 Mathematical Reasoning & RLVR
- **[MATH-500](https://github.com/openai/prm800k)** - 500 challenging high-school and Olympiad mathematics problems with symbolic answers.
- **[GSM8K](https://github.com/openai/grade-school-math)** - Grade school math word problems evaluating multi-step arithmetic reasoning.
- **[RLVR-Math-Verifiers](https://github.com/jatinsihag2345/rlvr-math-verifiers)** - Deterministic mathematical and symbolic verification environments for Reinforcement Learning with Verifiable Rewards.

## 🛡️ Model Red-Teaming, Alignment & Jailbreak
- **[HarmBench](https://www.harmbench.org/)** - Standardized evaluation framework for automated red-teaming and safety jailbreak defenses.
- **[JailbreakBench](https://jailbreakbench.github.io/)** - Open-source benchmark for robust adversarial attack and defense tracking.
- **[Model-Redteam-Atlas](https://github.com/jatinsihag2345/model-redteam-atlas)** - 250+ adversarial vectors testing prompt injections, canary leaks, sycophancy, and autonomous breakout attempts.
