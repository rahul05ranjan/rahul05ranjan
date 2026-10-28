<div align="center">

# Rahul Kumar

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=Applied+AI+Systems+%26+Full-Stack+Engineer;Creator+of+Hydra+Nano+%26+VIC-2B+Models;Local-First+Inference+%7C+Agentic+Orchestration;7%2B+Open-Weights+Models+on+Hugging+Face&font=Fira+Code&size=20&center=true&width=620&height=45&color=38BDF8&vCenter=true" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <b>Architecting small local AI models, deterministic agent systems, and resilient production web applications.</b><br>
  Based in Chandigarh, India · Open-weights creator on Hugging Face · Building developer tools that respect context and privacy.
</p>

<!-- Quick Contact & Social Hub -->
<p align="center">
  <a href="mailto:rahul05ranjan@gmail.com">
    <img src="https://img.shields.io/badge/Email-Direct_Inbox-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/rahulswt7/">
    <img src="https://img.shields.io/badge/LinkedIn-Rahul_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://wa.me/917004541481?text=Hi%20Rahul,%20saw%20your%20GitHub%20profile%20and%20wanted%20to%20connect!">
    <img src="https://img.shields.io/badge/WhatsApp-+91_7004541481-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="https://aratt.ai/message/91-7004541481">
    <img src="https://img.shields.io/badge/Arattai-+91_7004541481-2A62D7?style=for-the-badge&logo=rocketchat&logoColor=white" alt="Arattai" />
  </a>
  <a href="https://huggingface.co/rahul05ranjan">
    <img src="https://img.shields.io/badge/Hugging_Face-3k+_Downloads-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  </a>
  <a href="https://x.com/rahul05ranjan">
    <img src="https://img.shields.io/badge/Twitter/X-@rahul05ranjan-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter/X" />
  </a>
</p>

</div>

---

## ⚡ Executive Summary

I specialize in **Applied AI Engineering** and **Full-Stack Systems**. My recent focus is solving the context window crisis for AI coding agents and building deterministic AI engines powered by compact, open-weights language models that run 100% locally on user hardware.

- 🧠 **Model Creator:** Published **7 specialized open-weights models** on Hugging Face (Hydra Nano family & VIC-2B) with **3,000+ downloads**.
- 🛠️ **Agent Context Optimization:** Creator of **Hydra**, shaving **76% of noise tokens** out of coding agent context windows using local GGUF models.
- 📊 **Deterministic Query Planning:** Developed **VIC-2B** and the **vasuki** engine, achieving **83.0% accuracy on Spider** and matching 120B parameter models at 1.55 GB footprint.
- 💻 **Production Full-Stack:** Scalable, reliable architectures across TypeScript, React, Next.js, Node.js, Python, PHP, and Docker.

---

## 🚀 Featured Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🐉 <a href="https://github.com/rahul05ranjan/hydra">Hydra</a></h3>
      <p align="center">
        <b>Small Local Models That Take the Noisy Work Off Coding Agents</b><br>
        <a href="https://www.npmjs.com/package/hydra-nano"><img src="https://img.shields.io/npm/v/hydra-nano?color=7c5cff&label=npm" alt="npm"></a>
        <a href="https://huggingface.co/rahul05ranjan/hydra-nano-git"><img src="https://img.shields.io/badge/HF-Hydra%20Nano%20v2-22d3ee?logo=huggingface&logoColor=black" alt="HF Model"></a>
        <img src="https://img.shields.io/badge/100%25-Local_Inference-5eead4" alt="Local">
      </p>
      <ul>
        <li><b>Context Savior:</b> Intercepts verbose tool outputs (test suites, build logs, git diffs, process lists) using fine-tuned 0.8B/0.9B local models running on <code>llama.cpp</code>.</li>
        <li><b>Proven Efficiency:</b> Filters out <b>76% of token waste</b> (e.g. compressing a ~13,800 token test run into 57 critical failure tokens).</li>
        <li><b>Harness Integrations:</b> Seamlessly hooks into <b>Claude Code, Cursor, Codex, OpenCode, Gemini CLI</b>, and MCP-compatible clients.</li>
        <li><b>Zero Data Leaks:</b> 100% local, read-only telemetry in local ledger, zero cloud dependency.</li>
      </ul>
      <p align="center">
        <code>npx hydra-nano</code> · <a href="https://github.com/rahul05ranjan/hydra"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚡ <a href="https://github.com/rahul05ranjan/vasuki-vic">Vasuki & VIC-2B</a></h3>
      <p align="center">
        <b>Deterministic Tabular Query Engine & 1.55 GB Planner Model</b><br>
        <a href="https://huggingface.co/rahul05ranjan/VIC-2B"><img src="https://img.shields.io/badge/HF-VIC--2B-ffcc4d?logo=huggingface&logoColor=black" alt="VIC-2B"></a>
        <a href="https://ollama.com/rahuul/vic-2b"><img src="https://img.shields.io/badge/Ollama-rahuul%2Fvic--2b-000000?logo=ollama&logoColor=white" alt="Ollama"></a>
        <img src="https://img.shields.io/badge/License-Apache_2.0-blue" alt="License">
      </p>
      <ul>
        <li><b>Auditable Planning:</b> Translates plain English and Hinglish queries into typed, 12-operation JSON execution plans without hallucinated code or unsafe <code>eval</code>.</li>
        <li><b>Frontier-Level Benchmarks:</b> Fine-tuned on Qwen3.5-2B, achieving <b>83.0% on Spider</b> and <b>66.7% on BIRD</b>, matching a 120B model at a fraction of compute.</li>
        <li><b>Multi-Format Runner:</b> Operates on <code>.csv</code>, <code>.tsv</code>, <code>.json</code>, and <code>.jsonl</code> with zero third-party dependencies outside Python stdlib.</li>
        <li><b>MCP & Agent Skill:</b> Native CLI, Python API, Ollama support, and MCP server for agentic integration.</li>
      </ul>
      <p align="center">
        <code>uvx --from git+https://github.com/rahul05ranjan/vasuki-vic vasuki ask</code> · <a href="https://github.com/rahul05ranjan/vasuki-vic"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🤗 <a href="https://huggingface.co/rahul05ranjan">Open-Weights Models Ecosystem</a></h3>
      <p align="center">
        <b>Specialized Compact Models Fine-Tuned for Autonomous Workflows</b><br>
        <a href="https://huggingface.co/rahul05ranjan"><img src="https://img.shields.io/badge/HuggingFace-7_Models_Published-FFD21E?logo=huggingface&logoColor=black" alt="HF"></a>
      </p>
      <ul>
        <li><a href="https://huggingface.co/rahul05ranjan/hydra-nano-git"><b>hydra-nano-git</b></a> (0.8B Q8_0 GGUF): Specializes in git diffs, commit history, and blame extraction (1.4k+ downloads).</li>
        <li><a href="https://huggingface.co/rahul05ranjan/hydra-nano-test"><b>hydra-nano-test</b></a> (0.9B): Test runner log digesting across 8 frameworks with 97.5% task solve rate.</li>
        <li><a href="https://huggingface.co/rahul05ranjan/hydra-nano-os"><b>hydra-nano-os</b></a>, <b>read</b> & <b>files</b>: System inspection, symbol extraction, and AST-aware file localization.</li>
        <li><a href="https://huggingface.co/rahul05ranjan/VIC-2B"><b>VIC-2B</b></a> & <a href="https://huggingface.co/rahul05ranjan/VIC-2B-GGUF"><b>VIC-2B-GGUF</b></a>: Deterministic data planner with Ollama ready-to-run package.</li>
      </ul>
      <p align="center">
        <a href="https://huggingface.co/rahul05ranjan"><b>View Models on Hugging Face →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ <a href="https://github.com/rahul05ranjan/dhruv-cli">Dhruv CLI</a></h3>
      <p align="center">
        <b>Local-First AI Command Center for Terminal Developers</b><br>
        <a href="https://www.npmjs.com/package/@rahul05ranjan/dhruv-cli"><img src="https://img.shields.io/npm/v/@rahul05ranjan/dhruv-cli?color=cb3837&label=npm" alt="npm"></a>
        <a href="https://rahul05ranjan.github.io/dhruv-cli/"><img src="https://img.shields.io/badge/Docs-Live-00bcd4" alt="Documentation"></a>
      </p>
      <ul>
        <li><b>Offline AI Terminal:</b> Powers terminal workflows with local LLMs via Ollama, keeping sensitive proprietary code off external servers.</li>
        <li><b>Intelligent Tooling:</b> Automated security scans, code reviews, unit test generation, and natural-language command translation.</li>
        <li><b>Modular Architecture:</b> Built with TypeScript and Node.js featuring an extensible third-party plugin ecosystem.</li>
      </ul>
      <p align="center">
        <code>npm install -g @rahul05ranjan/dhruv-cli</code> · <a href="https://github.com/rahul05ranjan/dhruv-cli"><b>Explore Repository →</b></a>
      </p>
    </td>
  </tr>
</table>

---

## 🌐 Open Source Contributions

I contribute fixes, reviews, and QA upstream to the projects I build on — not just my own.

<!-- proof-links-start -->
**Live proof — every figure links to the always-current full list:**

- 🔀 [**150+ Open Pull Requests**](https://github.com/search?q=is%3Apr+is%3Aopen+author%3Arahul05ranjan+-user%3Arahul05ranjan+archived%3Afalse&type=pullrequests) — fixes awaiting or in maintainer review across open-source repos
- ✅ [**130+ Merged Pull Requests**](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Arahul05ranjan+-user%3Arahul05ranjan+archived%3Afalse&type=pullrequests) — accepted by upstream maintainers
- 🔍 [**580+ Code Reviews**](https://github.com/search?q=is%3Apr+reviewed-by%3Arahul05ranjan+-user%3Arahul05ranjan+archived%3Afalse&type=pullrequests) — verified reviews on other maintainers' pull requests
- 🎫 [**170+ Open Issue Tickets**](https://github.com/search?q=is%3Aissue+is%3Aopen+author%3Arahul05ranjan+-user%3Arahul05ranjan&type=issues) — reproducible bug reports filed upstream
<!-- proof-links-end -->

- **Merged PRs — 130+ across 30+ public repos**, including [openai/openai-cookbook](https://github.com/openai/openai-cookbook), [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate), [spatie/twitter-labs](https://github.com/spatie/twitter-labs), [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp), and [guillaumemeyer/watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover) (3).
<!-- active-review-start -->
- **PRs in active maintainer review:** [facelessuser/soupsieve#337](https://github.com/facelessuser/soupsieve/pull/337) · [pypa/wheel#714](https://github.com/pypa/wheel/pull/714) · [py-pdf/pypdf#4286](https://github.com/py-pdf/pypdf/pull/4286) · [py-pdf/pypdf#4284](https://github.com/py-pdf/pypdf/pull/4284) · [PyCQA/isort#2764](https://github.com/PyCQA/isort/pull/2764)
<!-- active-review-end -->
- **Code review at depth:** 100+ verified code reviews on open-source pull requests. Recent catches: a 366-day duplicate-month calendar bug, a regex regression that silently broke no-space time formats, and a hot-path O(n) rewrite flagged before merge.
- **QA that ships:** 170+ reproducible bug reports filed; fixes already merged by maintainers in [caronc/apprise](https://github.com/caronc/apprise), [shaongitbd/doory](https://github.com/shaongitbd/doory), [KKKKhazix/AIHOT](https://github.com/KKKKhazix/AIHOT) and others.

---

## 🛠️ Technical Capabilities & Stack

<div align="center">

| Domain | Core Competencies & Tools |
| :--- | :--- |
| **Applied AI & Local LLMs** | Fine-tuning compact SLMs (0.8B–2B), Qwen3.5, Llama, Ollama, llama.cpp, MLX, GGUF quantization, OpenCV |
| **Agentic Frameworks & Context** | Model Context Protocol (MCP), tool output sandboxing, context token compression, deterministic planning |
| **Frontend & Interfaces** | Next.js, React, TypeScript, JavaScript, Tailwind CSS, Bootstrap, Responsive UI/UX |
| **Backend & APIs** | Node.js, Express, Python, PHP, Laravel, RESTful APIs, WebSockets, CLI development |
| **Databases & DevOps** | MySQL, MongoDB, Docker, Git/GitHub Actions, Linux/macOS runtime environments |

</div>

<br>

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,nodejs,express,php,laravel,mysql,mongodb,docker,git,github,bash,vscode&perline=8" alt="Tech Stack Icons" />
</div>

---

## 📊 Engineering Activity & Impact

<div align="center">
  <img height="185em" src="https://raw.githubusercontent.com/rahul05ranjan/rahul05ranjan/output/github-stats.svg" alt="GitHub Stats" />
  <img height="185em" src="https://raw.githubusercontent.com/rahul05ranjan/rahul05ranjan/output/github-top-langs.svg" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/rahul05ranjan/rahul05ranjan/output/github-streak.svg" alt="GitHub Streak" />
</div>

### 🐍 Contribution Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/rahul05ranjan/rahul05ranjan/output/github-contribution-snake.svg" alt="Contribution Snake" width="95%" />
</div>

---

## 🤝 Let's Connect & Collaborate

Whether you're exploring **compact AI model deployments**, building **agentic workflows that don't burn tokens**, or need a **dependable full-stack application built from zero to production**, let's talk.

<div align="center">

[![Email](https://img.shields.io/badge/Email-rahul05ranjan@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahul05ranjan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahulswt7/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+91_7004541481-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/917004541481?text=Hi%20Rahul,%20saw%20your%20GitHub%20profile%20and%20wanted%20to%20connect!)
[![Arattai](https://img.shields.io/badge/Arattai-+91_7004541481-2A62D7?style=for-the-badge&logo=rocketchat&logoColor=white)](https://aratt.ai/message/91-7004541481)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-rahul05ranjan-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/rahul05ranjan)
[![Twitter/X](https://img.shields.io/badge/Twitter/X-@rahul05ranjan-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/rahul05ranjan)

<p>
  <sub>Direct Mobile / WhatsApp / Arattai: <a href="tel:+917004541481"><strong>+91 7004541481</strong></a> · Email: <a href="mailto:rahul05ranjan@gmail.com">rahul05ranjan@gmail.com</a></sub>
</p>

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=rahul05ranjan&color=38bdf8&style=flat-square&label=Profile+Views" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/rahul05ranjan?style=flat-square&color=22c55e" alt="Followers" />
  <img src="https://img.shields.io/github/stars/rahul05ranjan?style=flat-square&color=eab308" alt="Stars" />
</div>

<div align="center">
  <sub>Designed with precision · Open-source enthusiast · Built by Rahul Kumar</sub>
</div>
