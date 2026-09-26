<div align="center">
  <a href="#gabriel-felipe-guarnieri" title="Read in English">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f310.png" alt="English" height="40" style="vertical-align:middle;" />
  </a>

  <a href="#gabriel-felipe-guarnieri-1" title="Ler em Português">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f1e7-1f1f7.png" alt="Português" height="40" style="vertical-align:middle;" />
  </a>
</div>

<div align="center">

# Gabriel Felipe Guarnieri

#### Software Engineer · QA Automation & Python Backend

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Terraform</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/Capstone-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
  </a>

  <a href="https://oguarni.github.io">
    <img src="https://img.shields.io/badge/Portfolio-Visit_Site-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/oguarni/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="mailto:gfguarnieri@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Location-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Languages-PT_(Native)_%7C_EN_(Full_Professional)-blueviolet?style=flat-square"/>
</p>

</div>

---

Software Engineer (B.S., UTFPR, July 2026). I've done QA professionally (functional and regression testing on a production ERP), and I build Python backends with security wired in before release. Heading toward DevSecOps and cloud security.

**Agentic Engineer** — I keep the coding agent under the same controls as the code: per-directory `CLAUDE.md` context, [repo-scoped commands](https://github.com/oguarni/crescebr-b2b-marketplace/tree/main/.claude/commands) committed alongside it, and a [workflow](https://github.com/oguarni/terravault/blob/main/.github/workflows/claude.yml) that runs `claude-code-action` pinned to a commit SHA and only for the repository owner, so a public `@claude` comment cannot spend the token.

The agent's memory gets the same care. engram-sync, a private tool I wrote in Bash and PowerShell, syncs it between my Linux and Windows machines through Git. It blocks any export that matches known sensitive patterns, and an age-encrypted backup is only accepted with a recent restore drill. The tests run in CI on Ubuntu and on Windows PowerShell 5.1, each behind a pinned linter.

**Open to:** QA / Test Automation · Python / Backend · Full Stack — Remote / Hybrid / On-site.

---

## TerraVault — Capstone

> **The problem:** a rule-based scanner only catches what it has a rule for. Misconfiguration is one of the leading causes of cloud breaches, and the average breach cost **$4.99M** in IBM's [*Cost of a Data Breach 2026*](https://www.ibm.com/reports/data-breach).

Hybrid security scanner for Terraform: **11 deterministic rules** + an Isolation Forest trained on **35,594 real feature vectors** mined from the Terraform Registry and public GitHub.

**Quality** — 200+ pytest cases · 82%+ line coverage · Pylint 10.00/10 · 0 Bandit/Safety/Flake8/Mypy · CI gate with a non-regression ratchet that fails the build on a drop · SARIF v2.1.0 for GitHub Code Scanning. These are floors, and the ratchet only ever raises them. Run `make quality-gate` for the exact figures; it writes them to `gate-metrics.json`.

**Results** — **83% recall** on third-party KICS fixtures inside the declared rule scope; Checkov's broader catalogue still wins the aggregate (F1 73.5 vs 64.4), and the ablation shows the rules, not the ML, doing the separating. All three numbers are [in the repository](https://github.com/oguarni/terravault/tree/main/evaluation/results).

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

---

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | Scores a 568-item NVD/CVE dataset down to 185 items needing review, a 67.4% reduction, at 83.27% accuracy on the held-out split — Naive Bayes + fine-tuned BERT behind a validated Flask API. 435 pytest cases, all passing. | `Python` `Flask` `PyTorch` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | B2B procurement platform published as a live static demo at [crescebr.com.br](https://crescebr.com.br) — strict CSP and a CI job that re-measures the deployed site daily and fails below an A security grade. ~68k LOC TypeScript, 103 test files carrying 2,200+ tests. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Cypress E2E Suite](https://github.com/oguarni/kurzgesagt-cypress-tests)** | 5 E2E specs with custom resilient commands, retry strategy and HTML reporting. | `Cypress` `JavaScript` |
| **[crash-loop](https://github.com/oguarni/crash-loop)** | Browser-playable SRE puzzle — deterministic sim engine, 165 Vitest cases with enforced coverage thresholds. [Play it live.](https://oguarni.github.io/crash-loop/) | `TypeScript` `Vite` `Vitest` |
| **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** | Isolated attack-and-defense lab built and destroyed by 4 Bash scripts — five Cyber Kill Chain techniques, each answered with cloud-native detection. | `GCP` `Bash` `Nmap` `Wireshark` |

---

## Experience

**ERP Software Tester (QA)** — PRECISA Software · May – Aug 2026
Functional, regression and performance testing on a production ERP (financial, fiscal, sales orders, purchasing, billing). Validated developer fixes against customer-reported defects through a ticket workflow, checked report data with SQL, documented each case with reproducible evidence — including stopwatch timings recorded on the tickets raised for slowness. Fiscal areas covered in testing: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, the IBS/CBS transition. Method: test the whole screen beyond the reported item, with every flag set and unset, and check both print layouts, because a fix made in one often misses the other.

**AWS Cloud Data Engineer, Intern** — Compass UOL · May – Oct 2025 · Remote
Python/Boto3 automations across EC2, S3, RDS, IAM and Lambda. Migrated batch pipelines to PySpark, validated data integrity with SQL.

**Full Stack Developer, Intern** — Procfy · Nov 2023 – Nov 2024
Collaborated on features in Ruby on Rails/PostgreSQL. REST API testing with Postman, root cause analysis, SQL validation.

**IT Assistant** — Property Registry Office · Apr 2021 – Nov 2023
Integration testing across court and registry systems (SAEC/ONR, e-Notariado, PJe, Projudi) under judicial oversight, LGPD access controls, Windows Server. 99%+ availability, zero findings in inspections.

---

## Skills

|     |     |
| --- | --- |
| **Testing & QA** | Pytest · Cypress · Playwright · Jest + Supertest · Vitest · React Testing Library · Postman · SQL validation · coverage gates in CI · Pylint, Mypy & ESLint · functional, regression, integration & API testing · defect lifecycle and fix validation (homologation/UAT) |
| **Backend** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC · PostgreSQL · Redis |
| **Cloud & DevSecOps** | AWS (EC2, S3, RDS, IAM, Lambda, Boto3, PySpark) · GCP (Compute Engine, VPC, BigQuery) · Terraform · Docker · GitHub Actions · Bandit · Trivy · GitLeaks · SARIF |
| **ML** | Scikit-learn · Isolation Forest · feature engineering |

---

## Education

**B.S. Software Engineering** — UTFPR, Dois Vizinhos · 2022 – Jul 2026 · graduated
Capstone: TerraVault — approved by the examining board.

**Containers & Kubernetes Essentials** — Coursera, IBM-authored course · Jul 2026 · [verify](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)

---

<div align="center">

# Gabriel Felipe Guarnieri

#### Engenheiro de Software · QA & Automação de Testes · Back-end Python

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Terraform</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/TCC-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
  </a>

  <a href="https://oguarni.github.io">
    <img src="https://img.shields.io/badge/Portfólio-Visitar-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/oguarni/">
    <img src="https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="mailto:gfguarnieri@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Localização-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Idiomas-PT_(Nativo)_%7C_EN_(Profissional_Completo)-blueviolet?style=flat-square"/>
</p>

</div>

---

Engenheiro de Software (Bacharel, UTFPR, julho de 2026). Já trabalhei como QA, com testes funcionais e de regressão em um ERP em produção, e construo back-ends em Python com a segurança integrada antes do release. Caminhando para DevSecOps e segurança em cloud.

**Agentic Engineer** — mantenho o agente de código sob os mesmos controles do código: contexto `CLAUDE.md` por diretório, [comandos de repositório](https://github.com/oguarni/crescebr-b2b-marketplace/tree/main/.claude/commands) versionados junto dele e um [workflow](https://github.com/oguarni/terravault/blob/main/.github/workflows/claude.yml) que roda a `claude-code-action` fixada por SHA e só para o dono do repositório, de modo que um `@claude` de qualquer visitante não gasta o token.

A memória do agente recebe o mesmo cuidado. O engram-sync, ferramenta privada que escrevi em Bash e PowerShell, sincroniza essa memória entre meus computadores Linux e Windows via Git. Ele barra qualquer exportação que bata com padrões sensíveis conhecidos, e um backup criptografado com age só é aceito com um teste de restauração recente. Os testes rodam no CI em Ubuntu e no Windows PowerShell 5.1, cada um atrás de um linter com versão fixada.

**Aberto a:** QA / Automação de Testes · Python / Back-end · Full Stack — Remoto / Híbrido / Presencial.

---

## TerraVault — TCC

> **O problema:** um scanner baseado em regras só pega o que tem regra. Configuração incorreta está entre as principais causas de violações em nuvem, e a violação média custou **US$ 4,99 milhões** no [*Cost of a Data Breach 2026*](https://www.ibm.com/reports/data-breach) da IBM.

Scanner híbrido de segurança para Terraform: **11 regras determinísticas** + Isolation Forest treinado sobre **35.594 vetores reais** extraídos do Terraform Registry e do GitHub público.

**Qualidade** — 200+ casos pytest · 82%+ de cobertura de linhas · Pylint 10,00/10 · 0 Bandit/Safety/Flake8/Mypy · quality gate com catraca de não regressão que reprova o build a qualquer queda · SARIF v2.1.0 para o GitHub Code Scanning. São pisos, e a catraca só os eleva. Rode `make quality-gate` para ver os números exatos; ele grava tudo no `gate-metrics.json`.

**Resultados** — **83% de recall** em fixtures de terceiros do KICS, dentro do escopo declarado das regras; o catálogo mais amplo do Checkov ainda vence no agregado (F1 73,5 contra 64,4), e a ablação mostra que quem separa são as regras, não o ML. Os três números estão [no repositório](https://github.com/oguarni/terravault/tree/main/evaluation/results).

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

---

## Projetos

| Projeto | O que é | Stack |
| --- | --- | --- |
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | Reduz um conjunto NVD/CVE de 568 itens a 185 que exigem revisão, queda de 67,4%, com 83,27% de acurácia no conjunto de teste separado — Naive Bayes + BERT fine-tuned atrás de uma API Flask validada. 435 casos pytest, todos passando. | `Python` `Flask` `PyTorch` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | Plataforma de compras B2B publicada como demo estática em [crescebr.com.br](https://crescebr.com.br) — CSP estrita e job de CI que remede o site publicado todo dia e reprova abaixo do grau A de segurança. ~68 mil LOC TypeScript, 103 arquivos de teste com mais de 2.200 testes. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Suíte E2E Cypress](https://github.com/oguarni/kurzgesagt-cypress-tests)** | 5 specs E2E com comandos resilientes customizados, retry e relatório HTML. | `Cypress` `JavaScript` |
| **[crash-loop](https://github.com/oguarni/crash-loop)** | Puzzle SRE jogável no navegador — motor de simulação determinístico, 165 casos Vitest com thresholds de cobertura. [Jogue online.](https://oguarni.github.io/crash-loop/) | `TypeScript` `Vite` `Vitest` |
| **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** | Laboratório isolado de ataque e defesa criado e destruído por 4 scripts Bash — cinco técnicas da Cyber Kill Chain, cada uma respondida com detecção cloud-native. | `GCP` `Bash` `Nmap` `Wireshark` |

---

## Experiência

**Testador de Software ERP (QA)** — PRECISA Software · Mai – Ago 2026
Testes funcionais, de regressão e de performance em um ERP em produção (financeiro, fiscal, pedidos de venda, compras, faturamento). Validei correções dos desenvolvedores frente a defeitos reportados por clientes dentro de um fluxo de tickets, conferi dados de relatórios com SQL e documentei cada caso com evidências reprodutíveis — incluindo a cronometragem registrada nos chamados abertos por lentidão. Áreas fiscais cobertas nos testes: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, transição IBS/CBS. Método: testar a tela inteira além do item reportado, com cada flag marcada e desmarcada, e conferir os dois layouts de impressão, porque a correção feita em um costuma não chegar ao outro.

**Engenharia de Dados Cloud AWS, Estágio** — Compass UOL · Mai – Out 2025 · Remoto
Automações Python/Boto3 em EC2, S3, RDS, IAM e Lambda. Migrei pipelines batch para PySpark e validei integridade de dados com SQL.

**Desenvolvimento Full Stack, Estágio** — Procfy · Nov 2023 – Nov 2024
Colaborei no desenvolvimento de funcionalidades em Ruby on Rails/PostgreSQL. Testes de API REST com Postman, análise de causa raiz e validação via SQL.

**Assistente de TI** — Serviço de Registro de Imóveis · Abr 2021 – Nov 2023
Testes de integração com sistemas judiciais e registrais (SAEC/ONR, e-Notariado, PJe, Projudi) sob fiscalização judicial, controles de acesso para a LGPD, Windows Server. 99%+ de disponibilidade, zero achados em inspeções.

---

## Competências

|     |     |
| --- | --- |
| **Testes & QA** | Pytest · Cypress · Playwright · Jest + Supertest · Vitest · React Testing Library · Postman · validação via SQL · gates de cobertura no CI · Pylint, Mypy e ESLint · testes funcionais, de regressão, integração e API · ciclo de vida de defeitos e validação de correções (homologação/UAT) |
| **Back-end** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC · PostgreSQL · Redis |
| **Cloud & DevSecOps** | AWS (EC2, S3, RDS, IAM, Lambda, Boto3, PySpark) · GCP (Compute Engine, VPC, BigQuery) · Terraform · Docker · GitHub Actions · Bandit · Trivy · GitLeaks · SARIF |
| **ML** | Scikit-learn · Isolation Forest · feature engineering |

---

## Formação

**Bacharelado em Engenharia de Software** — UTFPR, Dois Vizinhos · 2022 – Jul 2026 · graduado
TCC: TerraVault — aprovado pela banca examinadora.

**Containers & Kubernetes Essentials** — Coursera, curso da IBM · Jul 2026 · [verificar](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)
