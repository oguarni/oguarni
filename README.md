<div align="center">
  <a href="#-english" style="text-decoration: none;" title="Read in English">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f310.png" alt="English" height="40" style="vertical-align:middle;" />
  </a>
  &nbsp;&nbsp;
  <a href="#-portugu%C3%AAs" title="Ler em Português">
    <img src="https://flagcdn.com/h40/br.png" alt="Português" height="40" />
  </a>
</div>

<div id="-english"></div>

<div align="center">
  <h4>QA & Test Analyst · Security Analyst · Python Developer · System Implementation</h4>
  <p><code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Docker</code> · <code>AWS</code> · <code>CI/CD</code> · <code>Linux</code> · <code>PostgreSQL</code></p>
  <p><b>Quality is measurable — 397 tests, 100% coverage, zero audit findings.</b></p>
  <p>
    <a href="https://github.com/oguarni/terrasafe">
      <img src="https://img.shields.io/badge/Capstone-TerraSafe-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraSafe"/>
    </a>
    &nbsp;
    <a href="https://oguarni.github.io">
      <img src="https://img.shields.io/badge/Portfolio-Visit_Site-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    &nbsp;
    <a href="https://www.linkedin.com/in/oguarni/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
  </p>
</div>

---

## About Me


Software Engineering student (UTFPR, graduating July 2026) with a testing-first mindset forged in environments where failure carries legal consequences. Built TerraSafe (grade 9.7/10) — a hybrid IaC security scanner with 397 automated tests achieving 100% code coverage across 76 test classes. Practiced manual testing with structured documentation at Procfy and developed Cypress E2E suites in academic projects.

Nearly 3 years as Technical Focal Point in a judicially regulated registry office: Key User for SAEC/ONR and ERP IMOB (Brainsoft), responsible for integration testing between 5+ external systems, user training, post-deployment support, and compliance documentation under TJPR oversight — 99%+ availability, zero audit findings. Python is my primary language: TerraSafe (FastAPI, SQLAlchemy, Scikit-learn), AWS automation (Boto3, Lambda, PySpark), and scripting across every role.

Security analysis experience through TerraSafe's 7 deterministic detection rules, SAST toolchain (Bandit, GitLeaks, Trivy, SonarQube), and hands-on network analysis with Nmap and Wireshark. Compliance background (Provimento 74/CNJ, LGPD, ICP-Brasil) provides the regulatory awareness that separates effective security analysts from tool operators.

Long-term objective: DevSecOps & Cloud Security Engineering.

**Seeking:** QA Analyst · Test Analyst · Security Analyst · System Implementation · Python Developer — Remote

🌐 **Languages:** Portuguese (Native) · English (Full professional proficiency)


---

## 🔬 Capstone: TerraSafe


> **The Problem:** Traditional SAST tools rely on predefined rules — they catch *known* bad patterns but miss novel anomalies. With **66%** of breaches traced to IaC misconfigurations, this detection gap costs organizations an average of **$4.5M** per incident.

**TerraSafe** solves this with a **hybrid dual-engine** approach:


| Engine | Method | Detects |
|--------|--------|---------|
| **Deterministic** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 7 known misconfiguration patterns |
| **Probabilistic** | Isolation Forest ML (7D feature vector) | Novel configuration anomalies |


**Key Results:**
- 📊 Grade **9.7/10** — Technical Report (Methodology & Research Phase)
- ✅ **397 tests** (395 passed, 2 skipped) · **76 test classes** · **100% code coverage** across 24 modules
- ⚡ Mean scan time **~27ms** · API response **<150ms**
- 🔒 **0 SAST issues** (Bandit) · Pylint **9.16/10**
- 🏗️ Clean Architecture · SOLID · Dependency Injection · Static type checking (Mypy)
- 📏 **1,518 SLOC** application + **6,632 SLOC** test code

**Stack:** Python · FastAPI · PostgreSQL · Redis · Docker · GitHub Actions (5-stage CI/CD) · Prometheus · Grafana · Scikit-learn


<a href="https://github.com/oguarni/terrasafe">
  <img src="https://img.shields.io/badge/View_Repository-TerraSafe-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Featured Projects


<table>
  <tr>
    <td width="50%">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>Security Analyst · Python Developer</b></p>
      <p>ML-powered security alert prioritization using Naive Bayes + fine-tuned BERT. Achieved <b>67.4% alert reduction</b> (568 → 185 critical) and <b>83.27% accuracy</b>. Production-grade Flask REST API with Redis caching and Pydantic validation.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code> <code>pytest</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Test Analyst · Python/JS Developer</b></p>
      <p>B2B industrial procurement platform with CNPJ validation, tier pricing, NF-e Módulo 11, and supplier ratings. <b>106 tests</b> (Vitest + React Testing Library), full CI/CD pipeline with GitHub Actions. ~19,733 LOC.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA Analyst · Test Analyst</b></p>
      <p>E2E test automation suite covering 4 functional flows with custom Cypress commands (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), retry strategy, video recording, screenshot capture, and HTML report generation. <b>100% pass rate</b>.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%">
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
| **Testing & QA** | Pytest (397 tests, 100% coverage), Vitest, Jest, Cypress (E2E), Postman, Manual Testing |
| **Security Analysis** | Bandit, GitLeaks, Trivy, SonarQube, Nmap, Wireshark, Isolation Forest (Scikit-learn), SBOM |
| **Languages** | Python, TypeScript, JavaScript, Ruby, SQL, Bash/Shell |
| **Frameworks** | FastAPI, Express 5, React 19, Ruby on Rails, Material UI |
| **Databases** | PostgreSQL, Redis |
| **Infrastructure** | Docker, Linux, Windows Server, Terraform |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS), Boto3, PySpark |
| **CI/CD** | GitHub Actions, Prometheus, Grafana |
| **Compliance** | Provimento 74/CNJ, ICP-Brasil, LGPD, Bacen 4658 |

---

## 🎓 Education


**B.S. Software Engineering** — UTFPR-DV (Dois Vizinhos, PR) · Apr 2022 – Jul 2026 (Expected)

- Capstone: TerraSafe — Hybrid IaC Security Scanner (Grade 9.7/10)
- Developed end-to-end automated testing suites using **Cypress** through hands-on academic projects
- Gained practical experience with CI/CD pipelines, Terraform, and security-integrated development practices through independent study and academic research

---

## 📊 What Sets Me Apart

```
Compliance Ops (2y8m)  →  Testing & QA (397 tests, 100% cov)  →  Security Analysis
         ↓                            ↓                                  ↓
  Zero-tolerance environment   Quality is measurable            Tools + Compliance
  under judicial oversight     (76 classes, 24 modules)         awareness from the field
```


Most junior engineers learn compliance from documentation. I operated systems where failures had legal consequences — and that discipline drives how I test, document, and secure software today.

---

<div id="-português"></div>

<div align="center">
  <h4>QA & Analista de Testes · Analista de Segurança · Desenvolvedor Python · Implantação de Sistemas</h4>
  <p><code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Docker</code> · <code>AWS</code> · <code>CI/CD</code> · <code>Linux</code> · <code>PostgreSQL</code></p>
  <p><b>Qualidade é mensurável — 397 testes, 100% de cobertura, zero achados em auditoria.</b></p>
  <p>
    <a href="https://github.com/oguarni/terrasafe">
      <img src="https://img.shields.io/badge/TCC-TerraSafe-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraSafe"/>
    </a>
    &nbsp;
    <a href="https://oguarni.github.io">
      <img src="https://img.shields.io/badge/Portfólio-Visitar-181717?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    &nbsp;
    <a href="https://www.linkedin.com/in/oguarni/">
      <img src="https://img.shields.io/badge/LinkedIn-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
    </a>
  </p>
</div>

---

## Sobre Mim


Graduando em Engenharia de Software (UTFPR, conclusão jul./2026) com mentalidade testing-first forjada em ambientes onde falhas têm consequências legais. Criei o TerraSafe (nota 9,7/10) — scanner híbrido de segurança para IaC com 397 testes automatizados alcançando 100% de cobertura de código em 76 classes de teste. Realizei testes manuais com documentação estruturada na Procfy e desenvolvi suítes E2E com Cypress em projetos acadêmicos.

Quase 3 anos como Ponto Focal Técnico em cartório de registro sob regulação judicial: Key User do SAEC/ONR e ERP IMOB (Brainsoft), responsável por testes de integração entre 5+ sistemas externos, treinamento de usuários, suporte pós-implantação e documentação de compliance sob supervisão do TJPR — 99%+ de disponibilidade, zero achados em auditoria. Python é minha linguagem principal: TerraSafe (FastAPI, SQLAlchemy, Scikit-learn), automação AWS (Boto3, Lambda, PySpark) e scripting em todas as posições.

Experiência em análise de segurança através das 7 regras determinísticas do TerraSafe, toolchain SAST (Bandit, GitLeaks, Trivy, SonarQube) e análise prática de redes com Nmap e Wireshark. Background em compliance (Provimento 74/CNJ, LGPD, ICP-Brasil) fornece a consciência regulatória que separa analistas de segurança eficazes de operadores de ferramentas.

Objetivo de longo prazo: DevSecOps & Cloud Security Engineering.

**Buscando:** QA Analyst · Analista de Testes · Analista de Segurança · Implantação de Sistemas · Desenvolvedor Python — Remoto

🌐 **Idiomas:** Português (Nativo) · Inglês (Proficiência profissional completa)


---

## 🔬 TCC: TerraSafe


> **O Problema:** Ferramentas SAST tradicionais dependem de regras pré-definidas — detectam padrões *conhecidos*, mas falham em identificar anomalias inéditas. Com **66%** das violações rastreadas a configurações incorretas de IaC, essa lacuna de detecção custa em média **US$ 4,5 milhões** por incidente.

**TerraSafe** resolve isso com uma abordagem de **motor duplo híbrido**:


| Motor | Método | Detecta |
|-------|--------|---------|
| **Determinístico** | AST + Regex + SAST (Bandit, GitLeaks, Safety) | 7 padrões de configuração conhecidos |
| **Probabilístico** | Isolation Forest ML (vetor 7D) | Anomalias de configuração inéditas |


**Resultados:**
- 📊 Nota **9,7/10** — Relatório Técnico (Metodologia e Pesquisa)
- ✅ **397 testes** (395 aprovados, 2 ignorados) · **76 classes de teste** · **100% de cobertura** em 24 módulos
- ⚡ Tempo médio de scan **~27ms** · Resposta da API **<150ms**
- 🔒 **0 problemas SAST** (Bandit) · Pylint **9,16/10**
- 🏗️ Clean Architecture · SOLID · Injeção de Dependência · Verificação estática de tipos (Mypy)
- 📏 **1.518 SLOC** aplicação + **6.632 SLOC** código de teste

**Stack:** Python · FastAPI · PostgreSQL · Redis · Docker · GitHub Actions (CI/CD 5 estágios) · Prometheus · Grafana · Scikit-learn


<a href="https://github.com/oguarni/terrasafe">
  <img src="https://img.shields.io/badge/Ver_Repositório-TerraSafe-2ea44f?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🚀 Projetos em Destaque


<table>
  <tr>
    <td width="50%">
      <h3 align="center">AI Vulnerability Triage</h3>
      <p align="center"><b>Analista de Segurança · Desenvolvedor Python</b></p>
      <p>Priorização de alertas de segurança com ML usando Naive Bayes + BERT fine-tuned. <b>67,4% de redução de alertas</b> (568 → 185 críticos) e <b>83,27% de acurácia</b>. API REST Flask com cache Redis e validação Pydantic.</p>
      <p><code>Python</code> <code>Flask</code> <code>PyTorch</code> <code>BERT</code> <code>scikit-learn</code> <code>Redis</code> <code>pytest</code></p>
      <p align="center"><a href="https://github.com/oguarni/ai-vulnerability-triage"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%">
      <h3 align="center">CresceBR B2B Marketplace</h3>
      <p align="center"><b>Analista de Testes · Desenvolvedor Python/JS</b></p>
      <p>Plataforma de compras B2B com validação CNPJ, precificação por faixa, NF-e Módulo 11 e avaliação de fornecedores. <b>106 testes</b> (Vitest + React Testing Library), pipeline CI/CD completo. ~19.733 LOC.</p>
      <p><code>React 19</code> <code>Express 5</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Vitest</code> <code>Docker</code></p>
      <p align="center"><a href="https://github.com/oguarni/crescebr-b2b-marketplace"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Kurzgesagt Cypress Tests</h3>
      <p align="center"><b>QA Analyst · Analista de Testes</b></p>
      <p>Suíte de automação E2E cobrindo 4 fluxos funcionais com comandos Cypress customizados (<code>cy.waitForContent()</code>, <code>cy.safeClick()</code>), estratégia de retry, gravação de vídeo, captura de tela e relatório HTML. <b>100% de aprovação</b>.</p>
      <p><code>Cypress</code> <code>JavaScript</code> <code>Node.js</code></p>
      <p align="center"><a href="https://github.com/oguarni/automacao-vv-cypress"><img src="https://img.shields.io/badge/Ver_Repo-181717?style=flat-square&logo=github"/></a></p>
    </td>
    <td width="50%">
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
| **Testes & QA** | Pytest (397 testes, 100% cobertura), Vitest, Jest, Cypress (E2E), Postman, Testes Manuais |
| **Análise de Segurança** | Bandit, GitLeaks, Trivy, SonarQube, Nmap, Wireshark, Isolation Forest (Scikit-learn), SBOM |
| **Linguagens** | Python, TypeScript, JavaScript, Ruby, SQL, Bash/Shell |
| **Frameworks** | FastAPI, Express 5, React 19, Ruby on Rails, Material UI |
| **Bancos de Dados** | PostgreSQL, Redis |
| **Infraestrutura** | Docker, Linux, Windows Server, Terraform |
| **Cloud** | AWS (EC2, Lambda, S3, IAM, RDS), Boto3, PySpark |
| **CI/CD** | GitHub Actions, Prometheus, Grafana |
| **Compliance** | Provimento 74/CNJ, ICP-Brasil, LGPD, Bacen 4658 |

---

## 🎓 Formação


**Bacharelado em Engenharia de Software** — UTFPR-DV (Dois Vizinhos, PR) · Abr 2022 – Jul 2026 (Previsto)

- TCC: TerraSafe — Scanner Híbrido de Segurança para IaC (Nota 9,7/10)
- Desenvolvi suítes de testes automatizados end-to-end com **Cypress** em projetos acadêmicos práticos
- Adquiri experiência prática com pipelines CI/CD, Terraform e práticas de desenvolvimento integrado à segurança através de estudo independente e pesquisa acadêmica

---

## 📊 O Que Me Diferencia

```
Operações de Compliance (2a8m)  →  Testes & QA (397 testes, 100% cob)  →  Análise de Segurança
           ↓                                  ↓                                    ↓
   Ambiente de tolerância zero       Qualidade é mensurável              Ferramentas + Compliance
   sob supervisão judicial           (76 classes, 24 módulos)            vivenciado na prática
```


A maioria dos engenheiros juniores aprende compliance pela documentação. Eu operei sistemas onde falhas tinham consequências legais — e essa disciplina direciona como testo, documento e protejo software hoje.

---
