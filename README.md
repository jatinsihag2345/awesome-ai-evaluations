# Awesome AI Evaluations & Agent Benchmarks

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated list of frontier AI evaluation benchmarks, long-horizon agent test suites, terminal sandboxes, RLVR math verifiers, and red-teaming datasets.

## 📑 Table of Contents
- [🏛️ Code & Software Engineering Benchmarks](#-code--software-engineering-benchmarks)
- [🖥️ Terminal & Operating System Sandboxes](#-terminal--operating-system-sandboxes)
- [🔧 Tool Use & Function Calling Benchmarks](#-tool-use--function-calling-benchmarks)
- [🌐 Web & Multi-Modal Assistant Benchmarks](#-web--multi-modal-assistant-benchmarks)
- [🧭 Long-Horizon Multi-Step Agent Trajectories](#-long-horizon-multi-step-agent-trajectories)
- [🧠 Chain-of-Thought & Reasoning Trace Benchmarks](#-chain-of-thought--reasoning-trace-benchmarks)
- [📐 Mathematical Reasoning & RLVR](#-mathematical-reasoning--rlvr)
- [🛡️ Model Red-Teaming, Alignment & Jailbreak](#-model-red-teaming-alignment--jailbreak)
- [🧪 Synthetic Data & Distillation Quality Evaluations](#-synthetic-data--distillation-quality-evaluations)
- [🛠️ Evaluation Frameworks & Toolkits](#-evaluation-frameworks--toolkits)

---

## 🏛️ Code & Software Engineering Benchmarks
- **[SWE-bench](https://www.swebench.com/)** - Resolving real-world GitHub issues using repository-level context and pytest oracle suites.
- **[SWE-bench-Task-Forge](https://github.com/jatinsihag2345/swe-bench-task-forge)** - Toolchain and verification pipeline for authoring and verifying SWE-bench instances.
- **[LiveCodeBench](https://livecodebench.github.io/)** - Contamination-free coding benchmark featuring periodic competitive programming problems.

## 🖥️ Terminal & Operating System Sandboxes
- **[TerminalBench](https://github.com/jatinsihag2345/terminal-bench-eval)** - Sandboxed CLI and OS benchmark harness evaluating autonomous sysadmin and coding agents.
- **[InterCode](https://intercode-benchmark.github.io/)** - Interactive coding environment for evaluating agents in Bash and SQL execution environments.
- **[OSWorld](https://os-world.github.io/)** - Real-world operating system environment benchmark for multimodal desktop agents across Ubuntu/Linux.

## 🔧 Tool Use & Function Calling Benchmarks
- **[Agentic-Tool-Use-Eval](https://github.com/jatinsihag2345/agentic-tool-use-eval)** - Comprehensive benchmark evaluating function calling, nested JSON schema compliance, and multi-tool orchestration in LLM agents.
- **[Berkeley Function Calling Leaderboard (BFCL)](https://gorilla.cs.berkeley.edu/leaderboard.html)** - Gorilla LLM's live evaluation for tool call generation across AST, execution, and multi-turn dialogues.

## 🌐 Web & Multi-Modal Assistant Benchmarks
- **[GAIA](https://huggingface.co/gaia-benchmark)** - General AI Assistants benchmark testing multi-modal file parsing, web navigation, and tool execution.
- **[Gaia-Agent-Eval-Harness](https://github.com/jatinsihag2345/gaia-agent-eval-harness)** - Deterministic evaluation harness and task suite for GAIA.
- **[WebArena](https://webarena.dev/)** - Realistic web environment for evaluating autonomous web agents across e-commerce, forums, and code collaboration sites.

## 🧭 Long-Horizon Multi-Step Agent Trajectories
- **[Long-Horizon-Agent-Stress-Bench](https://github.com/jatinsihag2345/long-horizon-agent-stress-bench)** - Cognitive audit suite evaluating frontier LLM agent degradation, context compaction loss, and state hallucination across 15-30+ step trajectories.
- **[TravelPlanner](https://github.com/OSU-NLP-Group/TravelPlanner)** - Multi-step planning benchmark testing constraint satisfaction and environment search.

## 🧠 Chain-of-Thought & Reasoning Trace Benchmarks
- **[AIME 2024/2025](https://artofproblemsolving.com/wiki/index.php/AIME_Problems_and_Solutions)** - American Invitational Mathematics Examination benchmark.
- **[GPQA Diamond](https://github.com/idavidrein/gpqa)** - Google-proof Q&A benchmark vetted by domain experts in biology, physics, and chemistry.
- **[CoT-Reasoning-Auditor](https://github.com/jatinsihag2345/cot-reasoning-auditor)** - Reasoning trace audit toolkit for evaluating logical coherence and fallacy detection.

## 📐 Mathematical Reasoning & RLVR
- **[MATH-500](https://github.com/openai/prm800k)** - 500 challenging high-school and Olympiad mathematics problems with symbolic answers.
- **[GSM8K](https://github.com/openai/grade-school-math)** - Grade school math word problems evaluating multi-step arithmetic reasoning.
- **[RLVR-Math-Verifiers](https://github.com/jatinsihag2345/rlvr-math-verifiers)** - Deterministic mathematical and symbolic verification environments for Reinforcement Learning with Verifiable Rewards.

## 🛡️ Model Red-Teaming, Alignment & Jailbreak
- **[HarmBench](https://www.harmbench.org/)** - Standardized evaluation framework for automated red-teaming.
- **[JailbreakBench](https://jailbreakbench.github.io/)** - Open-source benchmark for robust adversarial attack and defense tracking.
- **[Model-Redteam-Atlas](https://github.com/jatinsihag2345/model-redteam-atlas)** - 250+ adversarial vectors testing prompt injections, canary leaks, sycophancy, and autonomous breakout attempts.

## 🧪 Synthetic Data & Distillation Quality Evaluations
- **[UltraFeedback](https://github.com/OpenBMB/UltraFeedback)** - Large-scale multi-turn preference dataset and evaluation framework for RLHF alignment.
- **[LMSYS Chatbot Arena](https://chat.lmsys.org/)** - Crowdsourced open platform for LLM evaluations using Elo rating system.
- **[AlpacaEval](https://github.com/tatsu-lab/alpaca_eval)** - Fast, affordable, and reliable automated evaluation using GPT-4 and frontier judge models.

## 🛠️ Evaluation Frameworks & Toolkits
- **[Inspect AI](https://inspect.ai-safety-institute.org.uk/)** - UK AI Safety Institute's framework for large language model evaluations.
- **[OpenAI Evals](https://github.com/openai/evals)** - Framework for evaluating LLMs and LLM-powered systems.
- **[DeepEval](https://github.com/confident-ai/deepeval)** - Production-grade unit testing framework for LLM applications.
- **[Promptfoo](https://www.promptfoo.dev/)** - Fast, lightweight CLI evaluation tool for prompt engineering and red-teaming.
- **[LLM-Eval-Toolkit](https://github.com/jatinsihag2345/llm-eval-toolkit)** - Modular Python SDK for deterministic grading, AST semantic diffing, and fuzzy scoring.
