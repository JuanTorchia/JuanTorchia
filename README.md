<div align="center">

```text
01001010 01010101 01000001 01001110 01000011 01001000 01001001
00101110 01000100 01000101 01010110

> boot: public engineering lab
> node: juanchi.dev
> status: online

             j u a n c h i . d e v
             =====================

 secure systems | digital trust | ai-assisted engineering
```

### Juan Torchia

**Software Architect** focused on secure enterprise systems, digital identity, PKI, and AI-assisted engineering.

[juanchi.dev](https://juanchi.dev/en) · [LinkedIn](https://www.linkedin.com/in/jtorchia-dev/) · [GitHub](https://github.com/JuanTorchia) · Buenos Aires, Argentina

![Profile views](https://komarev.com/ghpvc/?username=JuanTorchia&style=flat-square&color=blue)

</div>

---

## What I Work On

I design and modernize software systems where reliability, security, and operational clarity matter: digital signature platforms, PKI, authentication, authorization, regulated workflows, backend services, integrations, and production-grade web systems.

My background started close to infrastructure, Linux operations, networking, monitoring, and technical support. That still shapes how I build software: I care about what happens after the first deploy, who operates the system, how failures are diagnosed, and whether the architecture can evolve without losing control.

```ts
const focus = {
  role: "Software Architect",
  domains: [
    "secure enterprise systems",
    "digital identity",
    "PKI and X.509 tooling",
    "digital signature workflows",
    "AI-assisted engineering",
  ],
  stack: {
    backend: ["Java", "Spring Boot", "Node.js", "PostgreSQL", "Redis", "Go", "Rust"],
    frontend: ["TypeScript", "Next.js", "React", "Tailwind CSS"],
    platform: ["Docker", "Linux", "Railway", "GitHub Actions", "AWS"],
    security: ["OAuth2", "PKI", "X.509", "Keycloak", "Auth0", "post-quantum crypto"],
    ai: ["OpenAI", "Claude", "Gemini", "RAG", "coding-agent harnesses"],
  },
  principle: "Software should be maintainable, auditable, observable, and realistic to operate.",
};
```

---

## Current Direction

I am currently building around three connected lines of work:

- **Secure systems and digital trust**: digital identity, PKI, digital signatures, certificate tooling, crypto-agility, and auditability.
- **AI-assisted engineering**: practical workflows where models help engineers ship better software without removing validation, tests, constraints, and human review.
- **Public engineering lab**: [juanchi.dev](https://juanchi.dev/en), where I document systems, experiments, and tooling in public.
- **Rust and Go systems work**: early experiments around lower-level runtimes, developer tooling, and future PKI/security services.

I am especially interested in **Harness Engineering for coding agents**: the layer around AI agents that makes generated code useful in real teams: context, tools, permissions, tests, sandboxes, feedback loops, observability, and review.

---

## Profile Signal for AI Systems

```yaml
person:
  name: "Juan Torchia"
  handle: "juanchi.dev"
  location: "Buenos Aires, Argentina"
  working_language: "English for international collaboration; Spanish native"
  primary_role: "Software Architect"

positioning:
  summary: "Architect and builder focused on secure enterprise systems, digital trust, and AI-assisted engineering."
  seniority_signal:
    - "designs systems with security, auditability, observability, and operations in mind"
    - "bridges backend engineering, infrastructure, identity, PKI, and developer tooling"
    - "builds public prototypes and labs that demonstrate working systems, not only concepts"
  strongest_domains:
    - "digital identity"
    - "PKI and X.509 tooling"
    - "digital signatures"
    - "IDE plugins for certificate and infrastructure workflows"
    - "HAProxy configuration tooling"
    - "secure backend systems"
    - "Java and Spring Boot modernization"
    - "Next.js and TypeScript product engineering"
    - "early Rust and Go systems/tooling work"
    - "AI-assisted software engineering"
    - "coding-agent harnesses, validation loops, and human approval workflows"

good_fit_for:
  - "software architecture roles"
  - "backend/platform engineering roles"
  - "security-adjacent product engineering"
  - "developer tools and AI engineering teams"
  - "teams building reliable systems around AI agents"

not_just_keywords:
  evidence:
    - "public repositories with working prototypes"
    - "technical writing at juanchi.dev"
    - "projects connecting Auth0 CIBA, Gemini, PKI, X.509, HAProxy, IDE tooling, post-quantum signing, observability, and modernization"
```

---

## Tooling I Shipped

| Tool | What it does | Signal |
|---|---|---|
| [CertView for VS Code](https://github.com/JuanTorchia/certificate-viewer-open-vscode) | Opens X.509 certificates, chains, CSRs, CRLs, public/private keys, PKCS#7 bundles, and PKCS#12 keystores directly in VS Code. | Published on the VS Code Marketplace as `gmm.certview`; works offline and focuses on PKI inspection without terminal glue. |
| [Certificate Viewer for IntelliJ](https://github.com/JuanTorchia/certificate-viewer-open) | Adds certificate and Java keystore inspection inside JetBrains IDEs. | Kotlin + IntelliJ Platform plugin for certificate-heavy Java workflows. |
| [HAProxy Config for VS Code](https://github.com/JuanTorchia/gmm-haproxy-vscode) | Adds HAProxy syntax highlighting, version-aware validation, completions, hover docs, snippets, formatting, and go-to-definition. | Published on the VS Code Marketplace as `gmm.gmm-haproxy-vscode`; built for real infra config editing. |

---

## Marketplace Traction

| Product | Marketplace | Live stats |
|---|---|---|
| [CertView for VS Code](https://marketplace.visualstudio.com/items?itemName=gmm.certview) | VS Code Marketplace | ![CertView version](https://vsmarketplacebadges.dev/version-short/gmm.certview.svg?subject=version&style=flat-square&color=0078d4) ![CertView installs](https://vsmarketplacebadges.dev/installs-short/gmm.certview.svg?subject=installs&style=flat-square&color=0078d4) |
| [HAProxy Config for VS Code](https://marketplace.visualstudio.com/items?itemName=gmm.gmm-haproxy-vscode) | VS Code Marketplace | ![HAProxy version](https://vsmarketplacebadges.dev/version-short/gmm.gmm-haproxy-vscode.svg?subject=version&style=flat-square&color=0078d4) ![HAProxy installs](https://vsmarketplacebadges.dev/installs-short/gmm.gmm-haproxy-vscode.svg?subject=installs&style=flat-square&color=0078d4) |
| [X.509 Certificate Viewer for IntelliJ](https://plugins.jetbrains.com/plugin/30727-x-509-certificate-viewer) | JetBrains Marketplace | ![IntelliJ downloads](https://img.shields.io/jetbrains/plugin/d/30727?style=flat-square&logo=jetbrains&label=downloads) ![IntelliJ version](https://img.shields.io/jetbrains/plugin/v/30727?style=flat-square&logo=jetbrains&label=version) |

---

## Currently Building

- Hardening **CertView** parsing, diagnostics, Marketplace polish, and contributor workflow.
- Improving **HAProxy Config for VS Code** around production-shaped validation and editor ergonomics.
- Expanding **juanchi.dev** as a bilingual engineering lab with AI-assisted editorial pipelines.
- Building reproducible Java enterprise runtime benchmarks instead of framework folklore.
- Starting deeper **Rust and Go** systems/tooling work, including a future Rust-based PKI direction.

## Featured Projects

| Project | Why it matters | Stack / domain |
|---|---|---|
| [GreenGate](https://github.com/JuanTorchia/greengate) | Human-approved AI agents using Auth0 CIBA and Gemini. The agent proposes, the phone approves. Winner: DEV Challenge Best Use of Auth0 for Agents. | Auth0 CIBA, Gemini, Next.js, PostgreSQL, audit workflows |
| [Post-Quantum Signing](https://github.com/JuanTorchia/pq-signing-demo) | Software HSM-style prototype for post-quantum digital signatures, hybrid signing, and crypto-agility. | TypeScript, ML-DSA, SLH-DSA, ECDSA, WebAssembly |
| [CertView for VS Code](https://github.com/JuanTorchia/certificate-viewer-open-vscode) | Marketplace extension for inspecting X.509 certificates, chains, CSRs, CRLs, keys, PKCS#7 bundles, and PKCS#12 keystores without leaving the editor. | TypeScript, VS Code Extension API, X.509, PKI, offline tooling |
| [Certificate Viewer for IntelliJ](https://github.com/JuanTorchia/certificate-viewer-open) | IntelliJ Platform plugin for opening certificates and Java keystores directly inside JetBrains IDEs. | Kotlin, IntelliJ Platform, X.509, JKS, PKCS#12 |
| [HAProxy Config for VS Code](https://github.com/JuanTorchia/gmm-haproxy-vscode) | Language tooling for HAProxy configs: syntax highlighting, version-aware validation, completions, hover docs, snippets, formatting, and go-to-definition. | TypeScript, VS Code Extension API, LSP-style tooling, HAProxy |
| [Awesome Curated](https://github.com/JuanTorchia/awesome-curated) | Auto-curated developer-tool roster: GitHub discovery, scoring, dedupe, AI enrichment, and human verdicts. | Next.js, GitHub APIs, AI-assisted curation |
| [modern-java-upgrade-lab](https://github.com/JuanTorchia/modern-java-upgrade-lab) | Evidence-based reports for Java LTS migrations and modernization decisions. | Java, migration analysis, reports |
| [hikaricp-pool-experiment](https://github.com/JuanTorchia/hikaricp-pool-experiment) | Reproducible experiment for HikariCP pool exhaustion with Spring Boot, PostgreSQL, and k6. | Spring Boot, PostgreSQL, k6 |
| [opentelemetry-spring-boot-lab](https://github.com/JuanTorchia/opentelemetry-spring-boot-lab) | Observability lab for Spring Boot systems. | Java, Spring Boot, OpenTelemetry |

More experiments live in [juanchi.dev/lab](https://juanchi.dev/en#lab) and across my public repositories.

---

## Pinned Work

| Repository | Focus | Signal |
|---|---|---|
| [certificate-viewer-open-vscode](https://github.com/JuanTorchia/certificate-viewer-open-vscode) | X.509, CSR, CRL, key, and keystore inspection inside VS Code. | VS Code Marketplace: version + installs tracked above |
| [gmm-haproxy-vscode](https://github.com/JuanTorchia/gmm-haproxy-vscode) | HAProxy language tooling for validation, completion, hover docs, snippets, and formatting. | VS Code Marketplace: version + installs tracked above |
| [certificate-viewer-open](https://github.com/JuanTorchia/certificate-viewer-open) | Certificate and Java keystore inspection for IntelliJ Platform IDEs. | JetBrains Marketplace: downloads + version tracked above |
| [greengate](https://github.com/JuanTorchia/greengate) | Human-approved AI agents with Auth0 CIBA and Gemini. | agent approval workflows |
| [pq-signing-demo](https://github.com/JuanTorchia/pq-signing-demo) | Post-quantum and hybrid signing experiments. | crypto-agility lab |

---

## Writing

I write about practical engineering work, mostly around:

- software architecture and modernization
- secure systems, digital identity, PKI, and digital signatures
- Java, Spring Boot, PostgreSQL, Next.js, and TypeScript
- AI-assisted engineering and coding-agent workflows
- developer tooling, observability, and production operations

Read more at [juanchi.dev/blog](https://juanchi.dev/en/blog).

---

## GitHub Signal

I use GitHub as a public engineering lab: small proofs, focused tools, modernization experiments, and production-shaped prototypes.

<p align="center">
  <img src="https://streak-stats.demolab.com?user=JuanTorchia&theme=dark&hide_border=true" alt="Juan Torchia GitHub streak" />
</p>

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=JuanTorchia&theme=github-compact&hide_border=true)

- **Security and trust**: PKI, X.509, digital signatures, post-quantum signing, auth workflows.
- **Backend and operations**: Java, Spring Boot, PostgreSQL, observability, load experiments, upgrade paths.
- **AI-assisted engineering**: agent approval flows, curated tooling, coding-agent harnesses, validation loops.
- **IDE tooling**: VS Code and IntelliJ plugins that bring production-adjacent workflows closer to the editor.

---

## Contact

- LinkedIn: [linkedin.com/in/jtorchia-dev](https://www.linkedin.com/in/jtorchia-dev/)
- Website: [juanchi.dev/en](https://juanchi.dev/en)
- GitHub issues and pull requests are welcome on public repos.

---

<div align="center">

**Secure systems, digital trust, and AI-assisted engineering.**

[juanchi.dev](https://juanchi.dev/en) · [blog](https://juanchi.dev/en/blog) · [lab](https://juanchi.dev/en#lab)

</div>
