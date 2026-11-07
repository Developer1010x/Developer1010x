# S. Prajwall Narayana

**AI Engineer · AI Systems · Backend & Infrastructure** · Bengaluru, India

I build AI systems and run what I ship.

My work spans multi-agent LLM systems, MCP orchestration, backend engineering and production infrastructure, from CI/CD and infrastructure as code to observability and incident response. I'm currently an AI Engineer at Colligence Research, working across product engineering and platform reliability.

[Portfolio](https://sprajwallnarayana.vercel.app) · [Research](https://sprajwallnarayana.vercel.app/#research) · [Email](mailto:prajwallspambox@gmail.com)

## Start here

| If you want to see | Look at |
| --- | --- |
| Systems and protocol work | **[openplay](https://github.com/Developer1010x/openplay)**: screen casting written from scratch in Rust. Discovery, Linux screen capture and TLS pinning work today; the WebRTC and Miracast casting paths are wired end to end with in-process tests but not yet confirmed between two real machines |
| Applied research with code | **[deepfake-detector](https://github.com/Developer1010x/deepfake-detector)**: label-free multimodal detection on hand-written NumPy DSP (Haar DWT, DCT-II, STFT, LBP, Benford), with calibrated outputs and explanation maps |
| Software you can install today | **[Audier](https://github.com/Developer1010x/audiobook-reader/releases/tag/v1.0.0)**: a private, local-first reader and audiobook player for Linux, v1.0.0 as AppImage, .deb and tarball |
| AI integrations | **[pybridge.ai](https://github.com/Developer1010x/pybridge.ai)**: routes WhatsApp, Telegram, email and iMessage to Claude, OpenAI or Ollama |
| Developer tooling | **[universal-converter](https://github.com/Developer1010x/universal-converter)** (multi-hop file conversion) · **[cyclomatic-complexity-plugin](https://github.com/Developer1010x/cyclomatic-complexity-plugin)** (Clang plugin, per-function complexity) |

## How I work

- **AI and evaluation:** at work I build multi-agent LLM workflows over MCP. In research I care about calibrated, explainable outputs rather than bare scores, as in [deepfake-detector](https://github.com/Developer1010x/deepfake-detector), which documents its own limitations.
- **Backend and systems:** protocol work in Rust ([openplay](https://github.com/Developer1010x/openplay)), compiler tooling on the Clang AST ([cyclomatic-complexity-plugin](https://github.com/Developer1010x/cyclomatic-complexity-plugin)), and a single routing core behind many channels ([pybridge.ai](https://github.com/Developer1010x/pybridge.ai)).
- **Delivery and reliability:** CI runs on openplay, deepfake-detector, Audier, pybridge.ai and universal-converter, and Audier ships through a GitHub Actions release workflow. At work I own CI/CD, infrastructure as code with OpenTofu and Ansible, monitoring, alerting and incident response.

## Merged upstream contributions

All seven pull requests below are merged upstream (checked through the GitHub API on 7 November 2026).


- **Apache DataFusion**: [#25261](https://github.com/apache/datafusion/pull/25261) return an error for an invalid CSV `null_regex` instead of panicking · [#25254](https://github.com/apache/datafusion/pull/25254) apply CSV `null_regex` when reading, not only when inferring the schema
- **Nushell**: [#19017](https://github.com/nushell/nushell/pull/19017) `mkdir --verbose` no longer reports an existing directory as created · [#19023](https://github.com/nushell/nushell/pull/19023) fix the `--verbose` docs example · [#19024](https://github.com/nushell/nushell/pull/19024) `view source` spacing on rest parameters
- **Ansible community.general**: [#12570](https://github.com/ansible-collections/community.general/pull/12570) the snap module reports missing snaps instead of raising `IndexError`
- **World Monitor**: [#5459](https://github.com/koala73/worldmonitor/pull/5459) an expandable terminal price chart, plus an OpenSky proxy-path fix

## Publications

- *An Empirical Study of Label-Free Deepfake and AI-Content Detection*, IEEE CSITSS 2026 (accepted, first author)
- *Web-Server Controlled Rover with Robotic Arm and Object Detection*, IEEE CSITSS 2024, [IEEE Xplore](https://ieeexplore.ieee.org/document/10816816) (first author) · [code](https://github.com/Developer1010x/Robotic_rover)
- *An Empirical Study of ResNet50 Hyperparameter Tuning for Plant Disease Classification*, IEEE CSITSS 2024, [IEEE Xplore](https://ieeexplore.ieee.org/document/10816835) · [code](https://github.com/Developer1010x/Plant-Disease-Detection)
- *EduConnect: A Smart Solution for Streamlined School Administrations*, Springer ICTIS 2025, LNNS Vol. 1507, [DOI](https://doi.org/10.1007/978-981-96-8750-3_36)

## Additional engineering work

- **Arogya-Sathi**, my final-year project (third place, college showcase): an offline, multilingual healthcare assistant on quantised local models, with a deterministic safety layer beneath the LLM that the model cannot override. Source private pending journal publication.
- **agentic-devops**: AI-assisted CI/CD pipeline generation and monitoring for GitHub Actions and GitLab CI. The repository is currently private.

---

B.E. Computer Science and Engineering, R V College of Engineering (VTU), 2021–2025
