# 🧠 Awesome LLM Security Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of open-source tools, benchmarks, datasets, and papers focused on the **security of Large Language Models (LLMs)** — covering prompt injection, jailbreaks, red-teaming, evaluations, and defenses.  
>  
> **🛡️ Stay secure. Test everything. Contribute often.**

---



---

## 📚 Table of Contents

- [🛡️ Red Teaming & Attack Frameworks](#-red-teaming--attack-frameworks)
- [🧠 Jailbreak & Prompt Injection](#-jailbreak--prompt-injection)
- [🔍 Detection & Defense Tools](#-detection--defense-tools)
- [📈 Benchmarks & Datasets](#-benchmarks--datasets)
- [📜 Papers & Research](#-papers--research)
- [🧩 Related Projects & Standards](#-related-projects--standards)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🛡️ Red Teaming & Attack Frameworks

- [**DeepTeam**](https://github.com/confident-ai/deepteam) – Modular LLM red teaming framework (prompt injection, hallucination, data leaks, jailbreaks).
- [**garak**](https://github.com/NVIDIA/garak) – LLM vulnerability scanner covering toxicity, bias, sensitive data leaks, etc.
- [**LLMFuzzer**](https://github.com/corca-ai/LLMFuzzer) – Adversarial fuzzing toolkit for generating harmful prompts automatically.

---

## 🧠 Jailbreak & Prompt Injection

- [**Awesome-Jailbreak-on-LLMs**](https://github.com/yueliu1999/Awesome-Jailbreak-on-LLMs) – Collection of jailbreak techniques, datasets, and defenses.
- [**JailbreakingLLMs (PAIR)**](https://github.com/patrickrchao/JailbreakingLLMs) – Black-box jailbreak generation via automatic prompt refinement.
- [**jailbreak_llms**](https://github.com/verazuo/jailbreak_llms) – Real-world prompt jailbreak dataset (15k+ examples).

---

## 🔍 Detection & Defense Tools

- [**llm-warden**](https://github.com/jackhhao/llm-warden) – Hugging Face-based jailbreak detection model.
- [**vigil-llm**](https://github.com/deadbits/vigil-llm) – REST API for LLM security risk scoring.
- [**last_layer**](https://github.com/arekusandr/last_layer) – Low-latency pre-filter for prompt injection prevention.
- [**Omega Walls**](https://github.com/synqratech/omega-walls) – Deterministic Ω trust boundary for RAG/agents: wall-pressure projection + memory (scar-mass) + Off predicate for prompt injection, exfiltration, and tool-abuse defense.

---

## 📈 Benchmarks & Datasets

- [**JailbreakBench**](https://github.com/JailbreakBench/jailbreakbench) – Benchmark suite for evaluating jailbreak resilience and defense effectiveness.
- [**LLM Red Teaming Dataset**](https://github.com/google/llmredteam) – Google’s multi-domain adversarial testing prompts and tasks.
- [**AdvBench**](https://github.com/LLM-adversarial/advbench) – Benchmark focused on adversarial robustness and safety of LLMs.

---

## 📜 Papers & Research

- [**UDora**](https://github.com/AI-secure/UDora) – Unified red teaming for LLM agents via reasoning hijacks ([arXiv](https://arxiv.org/abs/2503.01908))
- [**PrivAgent**](https://github.com/rucnyz/RedAgent) – Privacy attack simulation through agentic LLMs ([arXiv](https://arxiv.org/abs/2412.05734))
- [**AutoDefense**](https://github.com/XHMY/AutoDefense) – Multi-agent automated jailbreak defense ([arXiv](https://arxiv.org/abs/2403.04783))

---

## 🧩 Related Projects & Standards

- [**GuardrailsAI**](https://github.com/guardrails-ai/guardrails) – Add structured validation and policy enforcement for LLMs.
- [**Rebuff**](https://github.com/CalebGrove/rebuff) – Defense wrapper for LLMs, stops adversarial instructions.
- [**OWASP Top 10 for LLMs (2024)**](https://owasp.org/www-project-top-10-for-llms/) – Official list of key LLM risks including prompt injection.

---

## 🤝 Contributing

Want to add a tool, dataset, or paper? 💡

- Fork this repo
- Add your entry under the right category in `README.md`
- Submit a pull request!

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Show Your Support

If you find this list helpful:

- Give us a ⭐️ on GitHub
- Share it with fellow researchers and builders
- Submit issues/PRs to keep it fresh!

---

> Maintained by the community. Inspired by [awesome-mlops](https://github.com/visenger/awesome-mlops), [awesome-appsec](https://github.com/paragonie/awesome-appsec), and [awesome-ai-security](https://github.com/0xmachos/awesome-ai-security).
