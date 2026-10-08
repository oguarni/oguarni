<div align="center">
  <a href="#user-content-gabriel-felipe-guarnieri" title="Read in English">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f310.png" alt="English" height="40" style="vertical-align:middle;" />
  </a>

  <a href="#user-content-gabriel-felipe-guarnieri-1" title="Ler em Português">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f1e7-1f1f7.png" alt="Português" height="40" style="vertical-align:middle;" />
  </a>
</div>

<div align="center">

# Gabriel Felipe Guarnieri

Software Engineer · QA & Test Automation

[Portfolio](https://oguarni.github.io) · [CV (PDF)](https://oguarni.github.io/assets/gabriel-guarnieri-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Email](mailto:gfguarnieri@gmail.com)

</div>

---

I'm a Software Engineer (B.S., UTFPR, 2026) looking for a role in QA and test automation. I live in Dois Vizinhos, Brazil, and I'm open to remote, hybrid or on-site work. Portuguese is my first language, and my English is at full professional proficiency.

My professional QA work was on a tax and billing ERP at PRECISA Software (May–Aug 2026): functional, regression and performance testing of developer fixes, with reproducible evidence for each case. In academic and personal projects I automate tests with Pytest, Playwright and Cypress and build Python backends with the tests running in CI. Longer term I want to grow into DevSecOps and cloud security, which is where TerraVault comes from.

## TerraVault — Capstone

> **The problem:** a rule-based scanner only catches what it already knows. Misconfiguration is one of the leading causes of cloud breaches, and the average breach cost **$4.99M** in IBM's [*Cost of a Data Breach 2026*](https://www.ibm.com/reports/data-breach).

Hybrid security scanner for Terraform: **11 deterministic rules** + an Isolation Forest trained on **35,594 real feature vectors** mined from the Terraform Registry and public GitHub.

**Quality** — 200+ pytest cases · 82%+ line coverage · Pylint 10.00/10 · 0 Bandit/Flake8/Mypy · SARIF v2.1.0 for GitHub Code Scanning. The CI gate fails the build if coverage falls below its recorded floor, which only moves up, if Pylint drops under 10.00, or if Bandit, Flake8 or Mypy report anything. Run `make quality-gate` for the exact figures; it writes them to `gate-metrics.json`.

**Results** — **83% recall** on third-party KICS fixtures inside the declared rule scope; Checkov's broader catalogue still wins the aggregate (F1 73.5 vs 64.4), and the ablation shows the rules, not the ML, doing the separating. All three numbers are [in the repository](https://github.com/oguarni/terravault/tree/main/evaluation/results).

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

## Other projects

- **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** (personal) — B2B procurement platform in TypeScript (React 19, Express 5, PostgreSQL), published as a live static demo at [crescebr.com.br](https://crescebr.com.br). A CI job re-measures the deployed site daily and fails below an A security grade; 100+ test files carry 2,200+ tests.
- **[crash-loop](https://github.com/oguarni/crash-loop)** (course project, team of three) — Browser-playable SRE puzzle in TypeScript with a deterministic simulation engine and 165 Vitest cases under enforced coverage thresholds. [Play it.](https://oguarni.github.io/crash-loop/)
- **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** (academic) — Scores a 568-item NVD/CVE dataset down to 185 items needing review, a 67.4% reduction, at 83.27% accuracy on the held-out split. Naive Bayes + fine-tuned BERT behind a Flask API with authentication, rate limiting and Redis caching; 435 pytest cases, all passing.
- **[Cypress E2E suite](https://github.com/oguarni/kurzgesagt-cypress-tests)** (coursework) — 5 end-to-end specs for kurzgesagt.org with custom commands, retries and an HTML report.
- **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** (academic) — Isolated attack-and-defense lab created and destroyed by 4 Bash scripts: five Cyber Kill Chain techniques, each paired with cloud-native detection.

## Coding agents

**Agentic Engineer** — I keep coding agents under the same controls as the code: per-directory `CLAUDE.md` context, [repo-scoped commands](https://github.com/oguarni/crescebr-b2b-marketplace/tree/main/.claude/commands) committed alongside it, and a [workflow](https://github.com/oguarni/terravault/blob/main/.github/workflows/claude.yml) that runs `claude-code-action` pinned to a commit SHA and only for the repository owner, so a public `@claude` comment cannot spend the token.

## Background

- **ERP Software Tester (QA)** — PRECISA Software · May–Aug 2026
- **AWS Cloud Data Engineer, intern** — Compass UOL · May–Oct 2025 · Python/Boto3 automation, Pandas-to-PySpark pipelines
- **Full Stack Developer, intern** — Procfy · Nov 2023–Nov 2024 · collaborated on Rails/PostgreSQL features, REST API testing with Postman
- **IT Assistant** — property registry office · Apr 2021–Nov 2023 · integration testing across court and registry systems under judicial oversight; 99%+ availability, zero findings in inspections
- **B.S. Software Engineering** — UTFPR · 2022–Jul 2026 · capstone approved by the examining board
- **Containers & Kubernetes Essentials** — Coursera, IBM-authored course · Jul 2026 · [verify](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)

---

<div align="center">

# Gabriel Felipe Guarnieri

Engenheiro de Software · QA e Automação de Testes

[Portfólio](https://oguarni.github.io) · [CV (PDF)](https://oguarni.github.io/assets/gabriel-guarnieri-cv-pt.pdf) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [E-mail](mailto:gfguarnieri@gmail.com)

</div>

---

Sou engenheiro de software (Bacharel, UTFPR, 2026) e procuro vaga em QA e automação de testes. Moro em Dois Vizinhos (PR) e posso trabalhar remoto, híbrido ou presencial. Tenho inglês em nível de proficiência profissional completa.

Meu trabalho profissional em QA foi num ERP fiscal, na PRECISA Software (mai–ago 2026): testes funcionais, de regressão e de desempenho das correções dos desenvolvedores, com evidências reprodutíveis de cada caso. Em projetos acadêmicos e pessoais, automatizo testes com Pytest, Playwright e Cypress e construo back-ends em Python com os testes rodando no CI. No longo prazo, quero crescer em DevSecOps e segurança em cloud, e é daí que vem o TerraVault.

## TerraVault — TCC

> **O problema:** um scanner baseado em regras só pega o que já tem regra. Configuração incorreta está entre as principais causas de violações em nuvem, e a violação média custou **US$ 4,99 milhões** no [*Cost of a Data Breach 2026*](https://www.ibm.com/reports/data-breach) da IBM.

Scanner híbrido de segurança para Terraform: **11 regras determinísticas** + Isolation Forest treinado sobre **35.594 vetores reais** extraídos do Terraform Registry e do GitHub público.

**Qualidade** — 200+ casos pytest · 82%+ de cobertura de linhas · Pylint 10,00/10 · 0 Bandit/Flake8/Mypy · SARIF v2.1.0 para o GitHub Code Scanning. O gate de CI reprova o build se a cobertura cair abaixo do piso registrado, que só sobe, se o Pylint ficar abaixo de 10,00 ou se Bandit, Flake8 ou Mypy acusarem qualquer achado. Rode `make quality-gate` para ver os números exatos; ele grava tudo no `gate-metrics.json`.

**Resultados** — **83% de recall** em fixtures de terceiros do KICS, dentro do escopo declarado das regras; o catálogo mais amplo do Checkov ainda vence no agregado (F1 73,5 contra 64,4), e a ablação mostra que quem separa são as regras, não o ML. Os três números estão [no repositório](https://github.com/oguarni/terravault/tree/main/evaluation/results).

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

## Outros projetos

- **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** (pessoal) — Plataforma de compras B2B em TypeScript (React 19, Express 5, PostgreSQL), publicada como demo estática em [crescebr.com.br](https://crescebr.com.br). Um job de CI remede o site publicado todo dia e reprova abaixo do grau A de segurança; são 100+ arquivos de teste com mais de 2.200 testes.
- **[crash-loop](https://github.com/oguarni/crash-loop)** (projeto de disciplina, em equipe de três) — Puzzle SRE jogável no navegador, em TypeScript, com motor de simulação determinístico e 165 casos Vitest sob thresholds de cobertura. [Jogue online.](https://oguarni.github.io/crash-loop/)
- **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** (acadêmico) — Reduz um conjunto NVD/CVE de 568 itens a 185 que exigem revisão, queda de 67,4%, com 83,27% de acurácia no conjunto de teste separado. Naive Bayes + BERT fine-tuned atrás de uma API Flask com autenticação, rate limiting e cache Redis; 435 casos pytest, todos passando.
- **[Suíte E2E Cypress](https://github.com/oguarni/kurzgesagt-cypress-tests)** (trabalho de disciplina) — 5 specs E2E para kurzgesagt.org com comandos customizados, retry e relatório HTML.
- **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** (acadêmico) — Laboratório isolado de ataque e defesa criado e destruído por 4 scripts Bash: cinco técnicas da Cyber Kill Chain, cada uma com detecção cloud-native.

## Agentes de código

**Agentic Engineer** — mantenho os agentes de código sob os mesmos controles do código: contexto `CLAUDE.md` por diretório, [comandos de repositório](https://github.com/oguarni/crescebr-b2b-marketplace/tree/main/.claude/commands) versionados junto dele e um [workflow](https://github.com/oguarni/terravault/blob/main/.github/workflows/claude.yml) que roda a `claude-code-action` fixada por SHA e só para o dono do repositório, de modo que um `@claude` de qualquer visitante não gasta o token.

## Trajetória

- **Testador de Software ERP (QA)** — PRECISA Software · mai–ago 2026
- **Estágio em Engenharia de Dados Cloud (AWS)** — Compass UOL · mai–out 2025 · automações Python/Boto3, pipelines de Pandas para PySpark
- **Estágio em Desenvolvimento Full Stack** — Procfy · nov 2023–nov 2024 · colaborei no desenvolvimento de funcionalidades em Rails/PostgreSQL, testes de API REST com Postman
- **Assistente de TI** — Serviço de Registro de Imóveis · abr 2021–nov 2023 · testes de integração com sistemas judiciais e registrais sob fiscalização judicial; 99%+ de disponibilidade, zero achados em inspeções
- **Bacharelado em Engenharia de Software** — UTFPR · 2022–jul 2026 · TCC aprovado pela banca examinadora
- **Containers & Kubernetes Essentials** — Coursera, curso da IBM · jul 2026 · [verificar](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)
