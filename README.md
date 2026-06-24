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

#### QA & Test Analyst · Security Analyst · Python Developer · System Implementation

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Docker</code> · <code>AWS</code> · <code>CI/CD</code> · <code>Linux</code> · <code>PostgreSQL</code>

**Quality is disciplined — Pylint 10.00/10 · 0 SAST findings · 0 audit findings in 2y8m under judicial oversight.**

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

Software Engineering student at UTFPR (8th and final semester, graduating July 2026) with a **testing-first mindset** forged in environments where failure carries legal consequences. Built **TerraVault** (grade **9.7/10**) — a hybrid IaC security scanner with a deliberately focused test suite (**72 high-signal pytest cases, 74% line coverage, Pylint 10.00/10, zero SAST findings**). Practiced manual testing with structured documentation at Procfy and developed Cypress E2E suites in academic projects.

Nearly **3 years as Technical Focal Point** in a judicially regulated registry office: Key User for SAEC/ONR and ERP IMOB (Brainsoft), responsible for integration testing between 5+ external systems, user training, post-deployment support, and compliance documentation under TJPR oversight — **99%+ availability, zero audit findings**. Python is my primary language: TerraVault (FastAPI, SQLAlchemy, Scikit-learn), AWS automation (Boto3, Lambda, PySpark), and scripting across every role.

Security analysis experience through TerraVault's 7 deterministic detection rules, SAST toolchain (Bandit, GitLeaks, Trivy, SonarQube), and hands-on network analysis with Nmap and Wireshark. Compliance background (Provimento 74/CNJ, LGPD, ICP-Brasil, Bacen 4658) provides the regulatory awareness that separates effective security analysts from tool operators.

**Long-term objective:** DevSecOps & Cloud Security Engineering.
**Seeking:** QA/Test Analyst · Security Analyst · DevOps / DevSecOps Jr · Infrastructure Analyst · Python Developer — Remote / Hybrid / On-site.

---

## 🔬 Capstone: TerraVault

> **The Problem:** Traditional SAST tools rely on predefined rules — they catch *known* bad patterns but miss novel anomalies. With **66%** of breaches traced to IaC misconfigurations, this detection gap costs organizations an average of **$4.5M** per incident.

**TerraVault** solves this with a **hybrid dual-engine** approach:

| Engine | Method | Detects |
|--------|--------|---------|
| **Deterministic** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 7 known misconfiguration patterns |
| **Probabilistic** | Isolation Forest ML (7D feature vector) | Novel configuration anomalies |

**Key Results:**
- 📊 Grade **9.7/10** — Technical Report (Methodology & Research Phase)
- ✅ **72 focused pytest cases** (refactored from a verbose suite to a high-signal set) · **74% line coverage** across 1,518 SLOC
- 🧹 **Pylint 10.00/10** · **0 Flake8 issues** · **0 Bandit findings** · **0 Safety advisories**
- ⚡ Sub-second per-file scans — suitable for CI gating
- 🏗️ Clean Architecture · SOLID · Dependency Injection · Static type checking (Mypy)
- 🔐 bcrypt auth · Redis caching/rate limiting · Prometheus metrics · SARIF v2.1.0 output for GitHub Code Scanning
- 📏 **1,518 SLOC** application (terravault package) · **1,360 SLOC** test code — healthy signal-to-noise ratio

**Stack:** Python 3.10+ · FastAPI · PostgreSQL 15 · SQLAlchemy (async) · Redis 7 · Docker · GitHub Actions (5-stage CI/CD) · Prometheus · Grafana · Scikit-learn · NumPy · Joblib

<a href="https://github.com/oguarni/terravault">
  <img src="https://img.shields.io/badge/View_Repository-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>Security Analyst · Python Developer</b></p>
      <p>ML-powered security alert prioritization using Naive Bayes + fine-tuned BERT. Achieved <b>67.4% alert reduction</b> (568 → 185 critical) and <b>83.27% accuracy</b>. Production-grade Flask REST API with Redis caching and Pydantic validation. <b>435 pytest cases collected</b>.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code> <code>pytest</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Test Analyst · Python/JS Developer</b></p>
      <p>B2B industrial procurement platform with CNPJ validation, tier pricing, NF-e Módulo 11, and supplier ratings. <b>106 tests</b> (Vitest + React Testing Library), full CI/CD pipeline with GitHub Actions. ~19,733 LOC.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA Analyst · Test Analyst</b></p>
      <p>E2E test automation suite covering 4 functional flows with custom Cypress commands (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), retry strategy, video recording, screenshot capture, and HTML report generation. <b>100% pass rate</b>.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Agiliza — Task Management</h3>
      <p align="center"><b>Full-Stack Developer</b></p>
      <p>Kanban platform with RBAC (Admin/Manager/Collaborator), drag-and-drop boards, i18n (PT-BR/EN). Clean Architecture with 4-layer separation, dependency injection via tsyringe, JWT + Bcrypt auth. Jest testing.</p>
      <p><code>React 18</code> <code>Express</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Docker</code> <code>Jest</code></p>
      <p align="center"><a href="https://github.com/oguarni/status-point"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
</table>

---

## 💼 Experience

### AWS Cloud Data Engineer Intern — Compass UOL
**May – Oct 2025** · Remote

- Provisioned AWS infrastructure (EC2, S3, RDS, IAM, Lambda) and built Python automation via **Boto3**
- Migrated data pipelines from Pandas to **PySpark** for distributed-scale processing with SQL integrity checks
- Applied **IAM least-privilege** and **RBAC** practices aligned with Bacen 4658 compliance requirements
- Containerized environments with Docker and gained practical understanding of cloud governance and permission auditing

---

### Full Stack Developer Intern — Procfy
**Nov 2023 – Nov 2024** · Dois Vizinhos, PR

- Shipped production features in Ruby on Rails / PostgreSQL: granular search filters, multi-criteria search, date range selectors, dynamic transaction updates
- Conducted **manual testing with structured documentation**, root cause analysis, and SQL data validation
- Performed REST API testing with **Postman** and validated feature behavior before production releases

---

### IT Assistant — Technical Focal Point — Serviço de Registro de Imóveis
**Apr 2021 – Nov 2023** (2 years 8 months) · Full-time · Dois Vizinhos, PR

- **Key User** for **SAEC/ONR** and **ERP IMOB** (Brainsoft): user training, post-deployment support, technical documentation
- Executed **integration testing** between 5+ external systems (SAEC/ONR, e-Notariado, e-Proc, PJe, Projudi)
- Implemented physical/logical access controls, configured **NTFS permissions** for **LGPD** compliance, and managed **ICP-Brasil** digital certificates
- Administered **Windows Server** environment: **99%+ availability**, **zero findings** in judicial inspections (TJPR)

---

## 🛠️ Technical Arsenal

| Category | Tools & Technologies |
|----------|---------------------|
| **Testing & QA** | Pytest (72 focused tests, 74% coverage), Vitest, Jest, Cypress (E2E), Postman, Manual Testing |
| **Security Analysis** | Bandit, GitLeaks, Trivy, Safety, SonarQube, Nmap, Wireshark, Isolation Forest (Scikit-learn), SBOM (CycloneDX) |
| **Languages** | Python, TypeScript, JavaScript, Ruby, SQL, Bash/Shell |
| **Frameworks** | FastAPI, Express 5, React 19, Ruby on Rails, Material UI (MUI) |
| **Databases** | PostgreSQL, Redis |
| **Infrastructure** | Docker, Linux, Windows Server, Terraform |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS), Boto3, PySpark |
| **CI/CD & Observability** | GitHub Actions (5-stage pipelines), Prometheus, Grafana |
| **Compliance** | Provimento 74/CNJ, ICP-Brasil, LGPD, Bacen 4658 |

---

## 🎓 Education

**B.S. Software Engineering** — UTFPR-DV (Dois Vizinhos, PR) · Apr 2022 – Jul 2026 (Expected)

- Capstone: **TerraVault** — Hybrid IaC Security Scanner (**Grade 9.7/10**)
- Developed end-to-end automated testing suites using **Cypress** through hands-on academic projects
- Gained practical experience with CI/CD pipelines, Terraform, and security-integrated development practices through independent study and academic research

---

## 📈 Metrics Snapshot

<div align="center">

| Metric | Value | Context |
|:------:|:-----:|:--------|
| **Capstone Grade** | 9.7 / 10 | TerraVault Technical Report |
| **Code Quality** | Pylint 10.00 / 10 | 0 Flake8 issues, 0 Bandit findings |
| **Test Discipline** | 74% coverage | 72 focused cases over 1,518 SLOC |
| **Compliance Record** | 0 findings | 2y8m under TJPR judicial oversight |
| **System Availability** | 99%+ | Registry office operations |
| **Alert Triage (AI project)** | 67.4% reduction | 568 → 185 critical alerts |

</div>

---

## 🧭 What Sets Me Apart

```
Compliance Ops (2y8m)  →  Testing & QA (focused, high-signal)  →  Security Analysis
         ↓                            ↓                                    ↓
  Zero-tolerance environment    Pylint 10.00/10 · 0 SAST issues        Tools + compliance
  under judicial oversight      Discipline over volume                 awareness from the field
```

Most junior engineers learn compliance from documentation. I operated systems where failures had legal consequences — and that discipline drives how I test, document, and secure software today.

---

<div align="center">

**📫 Let's connect:** [gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfolio](https://oguarni.github.io)

</div>

---

<div id="-português"></div>

<div align="center">

# Gabriel Felipe Guarnieri

#### QA & Analista de Testes · Analista de Segurança · Desenvolvedor Python · Implantação de Sistemas

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Docker</code> · <code>AWS</code> · <code>CI/CD</code> · <code>Linux</code> · <code>PostgreSQL</code>

**Qualidade é disciplina — Pylint 10,00/10 · 0 achados SAST · 0 achados de auditoria em 2a8m sob supervisão judicial.**

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

Graduando em Engenharia de Software pela UTFPR (8º e último semestre, conclusão em julho de 2026) com **mentalidade testing-first** forjada em ambientes onde falhas têm consequências legais. Criei o **TerraVault** (nota **9,7/10**) — scanner híbrido de segurança para IaC com suíte de testes deliberadamente focada (**72 casos pytest de alto sinal, 74% de cobertura de linhas, Pylint 10,00/10, zero achados SAST**). Realizei testes manuais com documentação estruturada na Procfy e desenvolvi suítes E2E com Cypress em projetos acadêmicos.

Quase **3 anos como Ponto Focal Técnico** em cartório de registro sob regulação judicial: Key User do SAEC/ONR e ERP IMOB (Brainsoft), responsável por testes de integração entre 5+ sistemas externos, treinamento de usuários, suporte pós-implantação e documentação de compliance sob supervisão do TJPR — **99%+ de disponibilidade, zero achados em auditoria**. Python é minha linguagem principal: TerraVault (FastAPI, SQLAlchemy, Scikit-learn), automação AWS (Boto3, Lambda, PySpark) e scripting em todas as posições.

Experiência em análise de segurança através das 7 regras determinísticas do TerraVault, toolchain SAST (Bandit, GitLeaks, Trivy, SonarQube) e análise prática de redes com Nmap e Wireshark. Background em compliance (Provimento 74/CNJ, LGPD, ICP-Brasil, Bacen 4658) fornece a consciência regulatória que separa analistas de segurança eficazes de operadores de ferramentas.

**Objetivo de longo prazo:** DevSecOps & Cloud Security Engineering.
**Buscando:** QA/Analista de Testes · Analista de Segurança · DevOps / DevSecOps Jr · Analista de Infraestrutura · Desenvolvedor Python — Remoto / Híbrido / Presencial.

---

## 🔬 TCC: TerraVault

> **O Problema:** Ferramentas SAST tradicionais dependem de regras pré-definidas — detectam padrões *conhecidos*, mas falham em identificar anomalias inéditas. Com **66%** das violações rastreadas a configurações incorretas de IaC, essa lacuna de detecção custa em média **US$ 4,5 milhões** por incidente.

**TerraVault** resolve isso com uma abordagem de **motor duplo híbrido**:

| Motor | Método | Detecta |
|-------|--------|---------|
| **Determinístico** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 7 padrões de configuração conhecidos |
| **Probabilístico** | Isolation Forest ML (vetor 7D) | Anomalias de configuração inéditas |

**Resultados:**
- 📊 Nota **9,7/10** — Relatório Técnico (Metodologia e Pesquisa)
- ✅ **72 casos pytest focados** (refatorados de uma suíte verbosa para um conjunto de alto sinal) · **74% de cobertura de linhas** em 1.518 SLOC
- 🧹 **Pylint 10,00/10** · **0 problemas Flake8** · **0 achados Bandit** · **0 avisos do Safety**
- ⚡ Scans por arquivo em menos de 1 segundo — adequado para CI gating
- 🏗️ Clean Architecture · SOLID · Injeção de Dependência · Verificação estática de tipos (Mypy)
- 🔐 Autenticação bcrypt · Cache/rate limiting Redis · Métricas Prometheus · Saída SARIF v2.1.0 para GitHub Code Scanning
- 📏 **1.518 SLOC** aplicação (pacote terravault) · **1.360 SLOC** código de teste — proporção saudável de sinal/ruído

**Stack:** Python 3.10+ · FastAPI · PostgreSQL 15 · SQLAlchemy (async) · Redis 7 · Docker · GitHub Actions (CI/CD 5 estágios) · Prometheus · Grafana · Scikit-learn · NumPy · Joblib

<a href="https://github.com/oguarni/terravault">
  <img src="https://img.shields.io/badge/Ver_Repositório-TerraVault-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Projetos em Destaque

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>Analista de Segurança · Desenvolvedor Python</b></p>
      <p>Priorização de alertas de segurança com ML usando Naive Bayes + BERT fine-tuned. <b>67,4% de redução de alertas</b> (568 → 185 críticos) e <b>83,27% de acurácia</b>. API REST Flask com cache Redis e validação Pydantic. <b>435 casos pytest coletados</b>.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code> <code>pytest</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Analista de Testes · Desenvolvedor Python/JS</b></p>
      <p>Plataforma de compras B2B com validação CNPJ, precificação por faixa, NF-e Módulo 11 e avaliação de fornecedores. <b>106 testes</b> (Vitest + React Testing Library), pipeline CI/CD completo. ~19.733 LOC.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA Analyst · Analista de Testes</b></p>
      <p>Suíte de automação E2E cobrindo 4 fluxos funcionais com comandos Cypress customizados (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), estratégia de retry, gravação de vídeo, captura de tela e relatório HTML. <b>100% de aprovação</b>.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Agiliza — Gestão de Tarefas</h3>
      <p align="center"><b>Desenvolvedor Full-Stack</b></p>
      <p>Plataforma Kanban com RBAC (Admin/Gerente/Colaborador), drag-and-drop, i18n (PT-BR/EN). Clean Architecture com separação em 4 camadas, injeção de dependência via tsyringe, autenticação JWT + Bcrypt. Testes com Jest.</p>
      <p><code>React 18</code> <code>Express</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Docker</code> <code>Jest</code></p>
      <p align="center"><a href="https://github.com/oguarni/status-point"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
</table>

---

## 💼 Experiência

### AWS Cloud Data Engineer (Estágio) — Compass UOL
**Mai – Out 2025** · Remoto

- Provisionei infraestrutura AWS (EC2, S3, RDS, IAM, Lambda) e desenvolvi automações Python com **Boto3**
- Migrei pipelines de dados de Pandas para **PySpark** para processamento em escala distribuída com verificações de integridade SQL
- Apliquei práticas de **least-privilege de IAM** e **RBAC** alinhadas aos requisitos de compliance do Bacen 4658
- Containerizei ambientes com Docker e desenvolvi compreensão prática de governança cloud e auditoria de permissões

---

### Desenvolvedor Full Stack (Estágio) — Procfy
**Nov 2023 – Nov 2024** · Dois Vizinhos, PR

- Entreguei funcionalidades em produção em Ruby on Rails / PostgreSQL: filtros de busca granulares, multibusca, seletores de período, atualizações dinâmicas de transações
- Conduzi **testes manuais com documentação estruturada**, análise de causa raiz e validação de dados SQL
- Realizei testes de API REST com **Postman** e validei comportamento de funcionalidades antes das entregas em produção

---

### Assistente de TI — Ponto Focal Técnico — Serviço de Registro de Imóveis
**Abr 2021 – Nov 2023** (2 anos e 8 meses) · Tempo integral · Dois Vizinhos, PR

- **Key User** do **SAEC/ONR** e **ERP IMOB** (Brainsoft): treinamento de usuários, suporte pós-implantação, documentação técnica
- Executei **testes de integração** entre 5+ sistemas externos (SAEC/ONR, e-Notariado, e-Proc, PJe, Projudi)
- Implementei controles de acesso físico/lógico, configurei **permissões NTFS** para conformidade com a **LGPD** e gerenciei certificados digitais **ICP-Brasil**
- Administrei ambiente **Windows Server**: **99%+ de disponibilidade**, **zero achados** em inspeções judiciais (TJPR)

---

## 🛠️ Arsenal Técnico

| Categoria | Ferramentas & Tecnologias |
|-----------|--------------------------|
| **Testes & QA** | Pytest (72 testes focados, 74% cobertura), Vitest, Jest, Cypress (E2E), Postman, Testes Manuais |
| **Análise de Segurança** | Bandit, GitLeaks, Trivy, Safety, SonarQube, Nmap, Wireshark, Isolation Forest (Scikit-learn), SBOM (CycloneDX) |
| **Linguagens** | Python, TypeScript, JavaScript, Ruby, SQL, Bash/Shell |
| **Frameworks** | FastAPI, Express 5, React 19, Ruby on Rails, Material UI (MUI) |
| **Bancos de Dados** | PostgreSQL, Redis |
| **Infraestrutura** | Docker, Linux, Windows Server, Terraform |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS), Boto3, PySpark |
| **CI/CD & Observabilidade** | GitHub Actions (pipelines de 5 estágios), Prometheus, Grafana |
| **Compliance** | Provimento 74/CNJ, ICP-Brasil, LGPD, Bacen 4658 |

---

## 🎓 Formação

**Bacharelado em Engenharia de Software** — UTFPR-DV (Dois Vizinhos, PR) · Abr 2022 – Jul 2026 (Previsto)

- TCC: **TerraVault** — Scanner Híbrido de Segurança para IaC (**Nota 9,7/10**)
- Desenvolvi suítes de testes automatizados end-to-end com **Cypress** em projetos acadêmicos práticos
- Adquiri experiência prática com pipelines CI/CD, Terraform e práticas de desenvolvimento integrado à segurança através de estudo independente e pesquisa acadêmica

---

## 📈 Resumo de Métricas

<div align="center">

| Métrica | Valor | Contexto |
|:-------:|:-----:|:---------|
| **Nota do TCC** | 9,7 / 10 | Relatório Técnico do TerraVault |
| **Qualidade de Código** | Pylint 10,00 / 10 | 0 problemas Flake8, 0 achados Bandit |
| **Disciplina de Testes** | 74% de cobertura | 72 casos focados em 1.518 SLOC |
| **Histórico de Compliance** | 0 achados | 2a8m sob supervisão judicial (TJPR) |
| **Disponibilidade de Sistema** | 99%+ | Operações do cartório |
| **Triagem de Alertas (projeto IA)** | 67,4% de redução | 568 → 185 alertas críticos |

</div>

---

## 🧭 O Que Me Diferencia

```
Operações de Compliance (2a8m)  →  Testes & QA (focado e de alto sinal)  →  Análise de Segurança
            ↓                                    ↓                                    ↓
   Ambiente de tolerância zero        Pylint 10,00/10 · 0 achados SAST       Ferramentas + compliance
   sob supervisão judicial            Disciplina acima de volume             vivenciado na prática
```

A maioria dos engenheiros juniores aprende compliance pela documentação. Eu operei sistemas onde falhas tinham consequências legais — e essa disciplina direciona como testo, documento e protejo software hoje.

---

<div align="center">

**📫 Vamos conversar:** [gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfólio](https://oguarni.github.io)

</div>
