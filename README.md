<div align="center">
  <a href="#-english" title="Read in English">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f310.png" alt="English" height="40" style="vertical-align:middle;" />
  </a>
  &nbsp;&nbsp;
  <a href="#-português" title="Ler em Português">
    <img src="https://flagcdn.com/h40/br.png" alt="Português" height="40" />
  </a>
</div>

<div id="-english"></div>

<div align="center">

# Gabriel Felipe Guarnieri

#### ERP Software Tester (QA) · Test Automation · Python / Backend

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Postman</code> · <code>SQL</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code> · <code>CI/CD</code>

**I test the fiscal modules of an ERP through Brazil's IBS/CBS tax reform — and I measure my own work honestly enough to publish the unflattering results.**

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/Capstone-TerraVault_9.7%2F10-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
  </a>
  &nbsp;
  <a href="https://oguarni.github.io">
    <img src="https://img.shields.io/badge/Portfolio-Visit_Site-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/oguarni/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:gfguarnieri@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Open_to_Work-Remote_%7C_Hybrid_%7C_On--site-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Location-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Languages-PT_(Native)_%7C_EN_(Full_Professional)-blueviolet?style=flat-square"/>
</p>

</div>

---

## About Me

Software Engineer (B.S., UTFPR, graduated July 2026). I work as an **ERP Software Tester (QA)** at PRECISA Software, testing the financial, fiscal, sales-order, purchasing and billing modules of the Solution ERP — through the live transition of Brazil's tax reform.

**What I do differently:** I exercise the whole screen, not only the item a ticket reported. Every flag marked and unmarked, across companies, date ranges and filters. And I validate both print outputs, standard and matrix — that is where fixes that reached one path but not the other show up. When I find a defect, it goes back with one objective sentence and a reproducible case: exact labels, figures, the divergence.

Fiscal domain: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, the IBS/CBS transition, alphanumeric CNPJ, TEF, accrual vs cash regimes.

Before this: AWS data engineering at Compass UOL, full-stack development at Procfy, and nearly three years keeping mission-critical integrations running under judicial oversight — 99%+ availability, zero findings across inspections.

**Long-term objective:** DevSecOps & Cloud Security Engineering.
**Open to:** QA / Test Automation · Python / Backend Developer · Full Stack Jr · DevSecOps Jr · Cloud / Data Jr — Remote / Hybrid / On-site.

---

## 🔬 Capstone: TerraVault

> **The problem:** rule-based SAST catches *known* bad patterns but misses novel anomalies. With **66%** of breaches traced to IaC misconfigurations, that gap costs organizations an average of **$4.5M** per incident.

**TerraVault** is a hybrid dual-engine scanner for Terraform:

| Engine | Method | Detects |
|--------|--------|---------|
| **Deterministic** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 11 misconfiguration classes |
| **Probabilistic** | Isolation Forest (8-feature structural vector) | Out-of-catalog configuration anomalies |

Risk score: `S = 0.6 · rules + 0.4 · ML`, operator-configurable.

### Benchmark

On a labeled 22-module Terraform corpus (16 vulnerable + 6 hardened, 11 categories):

| Scanner | Precision | Recall | F1 |
|---------|:---------:|:------:|:--:|
| **TerraVault** | **100%** | **100%** | **100%** |
| Checkov | 100% | 95.7% | 97.8% |
| tfsec | 100% | 87.0% | 93.0% |
| Terrascan | 100% | 47.8% | 64.7% |

The only scanner in the set to detect hardcoded secrets.

### ML training on Google Cloud

After the defense I retrained the detector over **35,594 real feature vectors** — mined from **10,639 Terraform Registry modules** and **30,303 public GitHub files**, deduplicated by content hash — on self-terminating GCE instances that stage artifacts to Cloud Storage and power themselves off when finished. This retired the "trained only on synthetic data" limitation the manuscript disclosed.

### The ablation — the honest result

Then I measured what the ML actually contributes:

| Configuration | Safe / vulnerable separation |
|---------------|:----------------------------:|
| Deterministic rules alone | **33.3 points** |
| Hybrid (rules + ML) | 21.4 points |
| ML alone | 3.2 points |

The model **compresses** the rules' separation rather than improving it. It contributes an orthogonal, out-of-catalog signal — nothing more. I published that as it came out rather than reframing it, and closing that gap is my current work: using the model to **classify findings and suppress false positives** instead of restating what the rules already say.

### Engineering

- **137 pytest cases** · **76.8% line coverage** · **Pylint 10.00/10** · 0 Flake8 · 0 Bandit · 0 Safety · 0 Mypy
- CI quality gate with a **non-regression ratchet** — coverage floor, file-size cap, duplication guard
- Sub-second per-file scans · SARIF v2.1.0 for GitHub Code Scanning
- Clean Architecture · SOLID · Dependency Injection · static typing

**Stack:** Python 3.10+ · FastAPI · PostgreSQL 15 · SQLAlchemy (async) · Redis 7 · Docker · GitHub Actions · Prometheus · Grafana · Scikit-learn · NumPy · Joblib

<a href="https://github.com/oguarni/terravault">
  <img src="https://img.shields.io/badge/View_Repository-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>ML · Python · Security</b></p>
      <p>ML-powered security alert prioritization using Naive Bayes + fine-tuned BERT. <b>67.4% alert reduction</b> (568 → 185 critical) at <b>83.27% accuracy</b>. Production-grade Flask REST API with Redis caching and Pydantic validation. <b>435 pytest cases collected</b>.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Backend at scale · TypeScript</b></p>
      <p>B2B industrial procurement platform with real-time CNPJ validation, tier pricing, NF-e Módulo 11 and order lifecycle tracking. <b>~57k LOC</b> TypeScript, <b>87 test files</b> (Vitest + Jest + Supertest), GitHub Actions CI/CD.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA · E2E Automation</b></p>
      <p>E2E suite covering <b>5 functional flows</b> — homepage content, video playback, search, navigation and shop browsing — with custom resilient commands (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), retry strategy, video recording, failure screenshots and HTML report generation.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Agiliza — Task Management</h3>
      <p align="center"><b>Full-Stack · Clean Architecture</b></p>
      <p>Kanban platform with RBAC (Admin/Manager/Collaborator), drag-and-drop boards and i18n (PT-BR/EN). Strict 4-layer Clean Architecture, dependency injection via Inversify, JWT + Bcrypt auth, 7 Jest test suites, Docker Compose orchestration.</p>
      <p><code>React 18</code> <code>Express</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Docker</code> <code>Jest</code></p>
      <p align="center"><a href="https://github.com/oguarni/agiliza"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
</table>

---

## 💼 Experience

### ERP Software Tester (QA) — PRECISA Software
**May 2026 – Present** · Dois Vizinhos, PR

- Test the **Solution ERP** (financial, fiscal, sales-order, purchasing, billing) against customer-reported defects: restore each client base into an isolated **homologation** environment, compare pre-fix and fixed builds, and exercise the entire screen — every flag marked and unmarked, across companies, date ranges and filters
- Catch regressions developers miss by validating **both output layouts** — a fix applied to standard printing is frequently absent from the matrix layout
- Return each defect with a one-line statement plus a reproducible case (exact labels, figures, the divergence); document every ticket in versioned reports with step-by-step evidence
- Validate report data with **SQL**, confirm routine performance under load, and work the Brazilian fiscal domain — **NF-e/NFC-e/CT-e**, **PIS/COFINS**, and the **IBS/CBS** tax-reform transition

---

### AWS Cloud Data Engineer Intern — Compass UOL
**May – Oct 2025** · Remote

- Built **Python/Boto3** automations to provision AWS infrastructure (EC2, S3, RDS, IAM, Lambda)
- Migrated batch pipelines from Pandas to **PySpark**, improving throughput on larger datasets
- Validated data integrity with **SQL** at every pipeline boundary and containerized environments with Docker
- Applied **IAM least-privilege** and RBAC controls, working through Git pull requests and review with senior engineers

---

### Full Stack Developer Intern — Procfy
**Nov 2023 – Nov 2024** · Dois Vizinhos, PR

- Shipped production features in **Ruby on Rails / PostgreSQL**: granular search filters, multi-search, date-range selectors, dynamic transaction updates
- Ran REST API testing with **Postman**, root cause analysis on production incidents and SQL-based data validation
- Collaborated on code reviews and written documentation

---

### IT Assistant — Technical Focal Point — Serviço de Registro de Imóveis
**Apr 2021 – Nov 2023** (2 years 8 months) · Dois Vizinhos, PR

- Kept the **IMOB ERP** integrated with external mission-critical systems (**SAEC/ONR**, **e-Notariado**, **PJe**, **Projudi**) under TJPR oversight (**Provimento 74/CNJ**)
- Reached **99%+ availability** and **zero findings** across judicial inspections
- First contact for every technical incident: reproduced and documented problems, ran root cause analysis, trained users on the integrated systems

---

## 🛠️ Technical Arsenal

| Category | Tools & Technologies |
|----------|---------------------|
| **Testing & QA** | Functional, regression, integration, performance & API testing · Pytest · Cypress · Playwright · Jest · Vitest · Postman · SQL data validation · ERP & client-server testing · defect lifecycle & fix validation |
| **Backend** | Python (FastAPI, async I/O, Pydantic, SQLAlchemy) · Node.js 20+ (Express 4 & 5) · Ruby on Rails · REST / OpenAPI 3.0 · JWT/Bcrypt · RBAC middleware · rate limiting |
| **Machine Learning** | Scikit-learn (Isolation Forest, unsupervised anomaly detection) · NumPy · Joblib · feature engineering · corpus collection at 30k+ file scale · model versioning & rollback · drift detection · ablation studies |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS) via Boto3 · PySpark · Google Cloud (Compute Engine, Cloud Storage, BigQuery, gcloud CLI) |
| **Security** | Bandit · GitLeaks · Trivy · Safety · SonarQube · Nmap · Wireshark · SBOM (CycloneDX) · SARIF |
| **Databases** | PostgreSQL 15 · Redis 7 |
| **Infrastructure & CI/CD** | Docker & Compose · Linux · Windows Server · Terraform · GitHub Actions (5-stage pipelines) · Prometheus · Grafana |
| **Domain** | NF-e/NFC-e/CT-e · SPED · PIS/COFINS · IBS/CBS tax reform · Provimento 74/CNJ · LGPD · Bacen 4658 |

---

## 🎓 Education

**B.S. Software Engineering** — UTFPR-DV (Dois Vizinhos, PR) · Apr 2022 – Jul 2026

- Capstone **TerraVault** (grade **9.7/10**), approved by the examining board
- Built end-to-end **Cypress** suites in coursework; CI/CD and Terraform through independent study

---

## 📈 Metrics Snapshot

<div align="center">

| Metric | Value | Context |
|:------:|:-----:|:--------|
| **Capstone Grade** | 9.7 / 10 | TerraVault, approved by the examining board |
| **Detection Benchmark** | 100% / 100% / 100% | Precision / recall / F1 on 22 labeled Terraform modules |
| **ML Training Corpus** | 35,594 vectors | Real Terraform from Registry + public GitHub, on GCP |
| **Code Quality** | Pylint 10.00 / 10 | 0 Flake8 · 0 Bandit · 0 Safety · 0 Mypy |
| **Test Discipline** | 137 cases · 76.8% | With a CI ratchet that blocks coverage regression |
| **Compliance Record** | 0 findings | 2y8m under TJPR judicial oversight |
| **System Availability** | 99%+ | Registry office operations |
| **Alert Triage (AI project)** | 67.4% reduction | 568 → 185 critical alerts |

</div>

---

## 🧭 What Sets Me Apart

```
Regulated ops (2y8m)  →  ERP fiscal QA (current)  →  Security engineering & ML
        ↓                         ↓                            ↓
 Zero tolerance for        Whole-screen coverage,      Measured my own design,
 downtime; failures had    both print paths — where    found it didn't help,
 legal consequences        the real defects hide       and published that
```

Two things are rare in a junior profile. First, I test fiscal software during a tax reform — fiscal-domain knowledge and software QA almost never live in the same person. Second, when I measured whether my own ML component earned its place, it did not, and I reported that instead of reframing it. Both are on this page with the numbers attached.

---

<div align="center">

**📫 Let's connect:** [gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfolio](https://oguarni.github.io)

</div>

---

<div id="-português"></div>

<div align="center">

# Gabriel Felipe Guarnieri

#### Testador de Software ERP (QA) · Automação de Testes · Python / Back-end

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Postman</code> · <code>SQL</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code> · <code>CI/CD</code>

**Testo os módulos fiscais de um ERP durante a Reforma Tributária — e meço meu próprio trabalho com honestidade suficiente para publicar os resultados desfavoráveis.**

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/TCC-TerraVault_9.7%2F10-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
  </a>
  &nbsp;
  <a href="https://oguarni.github.io">
    <img src="https://img.shields.io/badge/Portfólio-Visitar-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/oguarni/">
    <img src="https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:gfguarnieri@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Aberto_a_Oportunidades-Remoto_%7C_Híbrido_%7C_Presencial-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Localização-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Idiomas-PT_(Nativo)_%7C_EN_(Profissional_Completo)-blueviolet?style=flat-square"/>
</p>

</div>

---

## Sobre Mim

Engenheiro de Software (Bacharel, UTFPR, julho de 2026). Atuo como **Testador de Software ERP (QA)** na PRECISA Software, testando os módulos financeiro, fiscal, de pedidos de venda, compras e faturamento do ERP Solution — em pleno período de transição da Reforma Tributária.

**O que faço de diferente:** exercito a tela inteira, não apenas o item que o chamado pediu. Cada flag marcada e desmarcada, por empresa, período e filtro. E valido as duas saídas de impressão, padrão e matricial — é ali que aparecem as correções que chegaram a um caminho e não ao outro. Quando encontro um defeito, devolvo com uma frase objetiva e um caso reprodutível: rótulos exatos, números, a divergência.

Domínio fiscal: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, transição IBS/CBS, CNPJ alfanumérico, TEF, DRE vs DFC.

Antes disso: engenharia de dados na AWS na Compass UOL, desenvolvimento full stack na Procfy e quase três anos mantendo integrações de missão crítica sob fiscalização judicial — 99%+ de disponibilidade, zero achados em inspeções.

**Objetivo de longo prazo:** DevSecOps & Segurança em Cloud.
**Aberto a:** QA / Automação de Testes · Desenvolvedor Python / Back-end · Full Stack Jr · DevSecOps Jr · Cloud / Dados Jr — Remoto / Híbrido / Presencial.

---

## 🔬 TCC: TerraVault

> **O problema:** ferramentas SAST baseadas em regras detectam padrões *conhecidos*, mas falham em anomalias inéditas. Com **66%** das violações rastreadas a configurações incorretas de IaC, essa lacuna custa em média **US$ 4,5 milhões** por incidente.

**TerraVault** é um scanner híbrido de motor duplo para Terraform:

| Motor | Método | Detecta |
|-------|--------|---------|
| **Determinístico** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 11 classes de configuração incorreta |
| **Probabilístico** | Isolation Forest (vetor estrutural de 8 características) | Anomalias fora do catálogo de regras |

Score de risco: `S = 0,6 · regras + 0,4 · ML`, configurável pelo operador.

### Benchmark

Em um corpus rotulado de 22 módulos Terraform (16 vulneráveis + 6 endurecidos, 11 categorias):

| Scanner | Precisão | Recall | F1 |
|---------|:--------:|:------:|:--:|
| **TerraVault** | **100%** | **100%** | **100%** |
| Checkov | 100% | 95,7% | 97,8% |
| tfsec | 100% | 87,0% | 93,0% |
| Terrascan | 100% | 47,8% | 64,7% |

Única ferramenta do conjunto a detectar segredos hardcoded.

### Treinamento de ML no Google Cloud

Depois da defesa, re-treinei o detector sobre **35.594 vetores reais** — extraídos de **10.639 módulos do Terraform Registry** e **30.303 arquivos públicos do GitHub**, deduplicados por hash de conteúdo — em instâncias GCE que enviam os artefatos ao Cloud Storage e se desligam sozinhas ao terminar. Isso aposentou a limitação de "treinado apenas com dados sintéticos" declarada no manuscrito.

### A ablação — o resultado honesto

Depois medi o que o ML de fato contribui:

| Configuração | Separação seguro / vulnerável |
|--------------|:-----------------------------:|
| Apenas regras determinísticas | **33,3 pontos** |
| Híbrido (regras + ML) | 21,4 pontos |
| Apenas ML | 3,2 pontos |

O modelo **comprime** a separação das regras em vez de melhorá-la. Ele entrega um sinal ortogonal, fora do catálogo — nada além disso. Publiquei assim mesmo, sem reenquadrar, e fechar essa lacuna é o trabalho que faço agora: usar o modelo para **classificar achados e suprimir falsos positivos** em vez de repetir o que as regras já dizem.

### Engenharia

- **137 casos pytest** · **76,8% de cobertura de linhas** · **Pylint 10,00/10** · 0 Flake8 · 0 Bandit · 0 Safety · 0 Mypy
- Quality gate em CI com **catraca de não regressão** — piso de cobertura, limite de tamanho de arquivo, guarda de duplicação
- Scans sub-segundo por arquivo · SARIF v2.1.0 para GitHub Code Scanning
- Clean Architecture · SOLID · Injeção de Dependência · tipagem estática

**Stack:** Python 3.10+ · FastAPI · PostgreSQL 15 · SQLAlchemy (async) · Redis 7 · Docker · GitHub Actions · Prometheus · Grafana · Scikit-learn · NumPy · Joblib

<a href="https://github.com/oguarni/terravault">
  <img src="https://img.shields.io/badge/Ver_Repositório-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Projetos em Destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>ML · Python · Segurança</b></p>
      <p>Priorização de alertas de segurança com ML usando Naive Bayes + BERT fine-tuned. <b>67,4% de redução de alertas</b> (568 → 185 críticos) com <b>83,27% de acurácia</b>. API REST Flask com cache Redis e validação Pydantic. <b>435 casos pytest coletados</b>.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Back-end em escala · TypeScript</b></p>
      <p>Plataforma de compras B2B com validação CNPJ em tempo real, precificação por faixa, NF-e Módulo 11 e rastreamento do ciclo do pedido. <b>~57 mil LOC</b> TypeScript, <b>87 arquivos de teste</b> (Vitest + Jest + Supertest), CI/CD com GitHub Actions.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA · Automação E2E</b></p>
      <p>Suíte E2E cobrindo <b>5 fluxos funcionais</b> — conteúdo da homepage, reprodução de vídeo, busca, navegação e loja — com comandos resilientes customizados (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), estratégia de retry, gravação de vídeo, captura de tela em falhas e relatório HTML.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Agiliza — Gestão de Tarefas</h3>
      <p align="center"><b>Full-Stack · Clean Architecture</b></p>
      <p>Plataforma Kanban com RBAC (Admin/Gerente/Colaborador), drag-and-drop e i18n (PT-BR/EN). Clean Architecture estrita em 4 camadas, injeção de dependência via Inversify, autenticação JWT + Bcrypt, 7 suítes Jest, orquestração com Docker Compose.</p>
      <p><code>React 18</code> <code>Express</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Docker</code> <code>Jest</code></p>
      <p align="center"><a href="https://github.com/oguarni/agiliza"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
</table>

---

## 💼 Experiência

### Testador de Software ERP (QA) — PRECISA Software
**Mai 2026 – Atual** · Dois Vizinhos, PR

- Testo o **ERP Solution** (financeiro, fiscal, pedidos de venda, compras, faturamento) frente a defeitos reportados por clientes: restauro a base de cada cliente em ambiente de **homologação** isolado, comparo a versão anterior com a corrigida e exercito a tela inteira — cada flag marcada e desmarcada, por empresa, período e filtro
- Encontro regressões que passam despercebidas ao validar **as duas saídas de impressão** — uma correção aplicada à impressão padrão frequentemente não chega à matricial
- Devolvo cada defeito com uma frase objetiva e um caso reprodutível (rótulos exatos, números, a divergência); documento cada chamado em relatórios versionados com evidências passo a passo
- Valido dados de relatórios com **SQL**, confirmo desempenho de rotinas sob carga e atuo no domínio fiscal brasileiro — **NF-e/NFC-e/CT-e**, **PIS/COFINS** e a transição **IBS/CBS**

---

### AWS Cloud Data Engineer (Estágio) — Compass UOL
**Mai – Out 2025** · Remoto

- Desenvolvi automações **Python/Boto3** para provisionar infraestrutura AWS (EC2, S3, RDS, IAM, Lambda)
- Migrei pipelines batch de Pandas para **PySpark**, melhorando a vazão em conjuntos de dados maiores
- Validei integridade de dados com **SQL** em cada fronteira do pipeline e containerizei ambientes com Docker
- Apliquei controles de **least-privilege de IAM** e RBAC, trabalhando via pull requests e revisão com engenheiros sênior

---

### Desenvolvedor Full Stack (Estágio) — Procfy
**Nov 2023 – Nov 2024** · Dois Vizinhos, PR

- Entreguei funcionalidades em produção em **Ruby on Rails / PostgreSQL**: filtros de busca granulares, multibusca, seletores de período, atualizações dinâmicas de transações
- Realizei testes de API REST com **Postman**, análise de causa raiz em incidentes de produção e validação de dados via SQL
- Colaborei em revisões de código e documentação escrita

---

### Assistente de TI — Ponto Focal Técnico — Serviço de Registro de Imóveis
**Abr 2021 – Nov 2023** (2 anos e 8 meses) · Dois Vizinhos, PR

- Mantive o **ERP IMOB** integrado a sistemas externos de missão crítica (**SAEC/ONR**, **e-Notariado**, **PJe**, **Projudi**) sob fiscalização do TJPR (**Provimento 74/CNJ**)
- Alcancei **99%+ de disponibilidade** e **zero achados** em inspeções judiciais
- Primeiro contato para todo incidente técnico: reproduzi e documentei problemas, conduzi análise de causa raiz e treinei usuários nos sistemas integrados

---

## 🛠️ Arsenal Técnico

| Categoria | Ferramentas & Tecnologias |
|-----------|--------------------------|
| **Testes & QA** | Testes funcionais, de regressão, integração, desempenho e API · Pytest · Cypress · Playwright · Jest · Vitest · Postman · validação de dados via SQL · testes em ERP e cliente-servidor · ciclo de vida de defeitos e validação de correções |
| **Back-end** | Python (FastAPI, I/O assíncrono, Pydantic, SQLAlchemy) · Node.js 20+ (Express 4 e 5) · Ruby on Rails · REST / OpenAPI 3.0 · JWT/Bcrypt · middleware RBAC · rate limiting |
| **Machine Learning** | Scikit-learn (Isolation Forest, detecção de anomalias não supervisionada) · NumPy · Joblib · engenharia de características · coleta de corpus em escala de 30 mil+ arquivos · versionamento de modelos com rollback · detecção de drift · estudos de ablação |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS) via Boto3 · PySpark · Google Cloud (Compute Engine, Cloud Storage, BigQuery, gcloud CLI) |
| **Segurança** | Bandit · GitLeaks · Trivy · Safety · SonarQube · Nmap · Wireshark · SBOM (CycloneDX) · SARIF |
| **Bancos de Dados** | PostgreSQL 15 · Redis 7 |
| **Infraestrutura & CI/CD** | Docker & Compose · Linux · Windows Server · Terraform · GitHub Actions (pipelines de 5 estágios) · Prometheus · Grafana |
| **Domínio** | NF-e/NFC-e/CT-e · SPED · PIS/COFINS · Reforma Tributária IBS/CBS · Provimento 74/CNJ · LGPD · Bacen 4658 |

---

## 🎓 Formação

**Bacharelado em Engenharia de Software** — UTFPR-DV (Dois Vizinhos, PR) · Abr 2022 – Jul 2026

- TCC **TerraVault** (nota **9,7/10**), aprovado pela banca examinadora
- Desenvolvi suítes **Cypress** ponta a ponta em projetos acadêmicos; CI/CD e Terraform por estudo independente

---

## 📈 Resumo de Métricas

<div align="center">

| Métrica | Valor | Contexto |
|:-------:|:-----:|:---------|
| **Nota do TCC** | 9,7 / 10 | TerraVault, aprovado pela banca |
| **Benchmark de Detecção** | 100% / 100% / 100% | Precisão / recall / F1 em 22 módulos Terraform rotulados |
| **Corpus de Treino do ML** | 35.594 vetores | Terraform real do Registry + GitHub público, no GCP |
| **Qualidade de Código** | Pylint 10,00 / 10 | 0 Flake8 · 0 Bandit · 0 Safety · 0 Mypy |
| **Disciplina de Testes** | 137 casos · 76,8% | Com catraca em CI que bloqueia regressão de cobertura |
| **Histórico de Compliance** | 0 achados | 2a8m sob fiscalização judicial (TJPR) |
| **Disponibilidade de Sistema** | 99%+ | Operações do cartório |
| **Triagem de Alertas (projeto IA)** | 67,4% de redução | 568 → 185 alertas críticos |

</div>

---

## 🧭 O Que Me Diferencia

```
Operação regulada (2a8m)  →  QA fiscal de ERP (atual)  →  Segurança e ML
          ↓                            ↓                         ↓
 Tolerância zero a parada     Cobertura da tela inteira,   Medi meu próprio design,
 falhas tinham consequência   as duas impressões — onde    vi que não ajudava,
 legal                        os defeitos reais se escondem e publiquei assim
```

Duas coisas são raras em um perfil júnior. Primeiro: testo software fiscal durante uma reforma tributária — conhecimento do domínio fiscal e QA de software quase nunca coexistem na mesma pessoa. Segundo: quando medi se o componente de ML do meu próprio projeto se justificava, ele não se justificou, e eu reportei isso em vez de reenquadrar. Ambos estão nesta página com os números anexados.

---

<div align="center">

**📫 Vamos conversar:** [gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfólio](https://oguarni.github.io)

</div>
