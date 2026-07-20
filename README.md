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

#### QA & Test Automation · Python / Backend

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>Postman</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

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

Software Engineer (B.S., UTFPR, 2026), working in QA and building toward test automation and Python backend. I test ERP software professionally, write my own test suites in Python, and I am learning by measuring — including when the measurement says my idea did not work.

**Open to:** QA / Test Automation · Python / Backend · Full Stack Jr — Remote / Hybrid / On-site.

---

## TerraVault — Capstone (9.7/10)

Hybrid security scanner for Terraform: **11 deterministic rules** + an **Isolation Forest** over an 8-feature structural vector.

**Benchmark** — 22 labeled Terraform modules:

| Scanner | Precision | Recall | F1 |
|---------|:---------:|:------:|:--:|
| **TerraVault** | **100%** | **100%** | **100%** |
| Checkov | 100% | 95.7% | 97.8% |
| tfsec | 100% | 87.0% | 93.0% |
| Terrascan | 100% | 47.8% | 64.7% |

**ML on Google Cloud** — retrained over **35,594 real feature vectors** mined from 10,639 Terraform Registry modules and 30,303 public GitHub files, on self-terminating GCE jobs.

**The ablation** — rules alone separate safe from vulnerable by **33.3 points**, the hybrid by **21.4**, the model alone by **3.2**. The ML adds an orthogonal signal, not better separation. I published that as measured. Closing that gap is my current work: using the model to classify findings and suppress false positives.

**Quality** — 137 pytest cases · 76.8% coverage · Pylint 10.00/10 · 0 Bandit/Safety/Flake8/Mypy · CI gate with a non-regression ratchet · SARIF v2.1.0.

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn` `Prometheus`

---

## Projects

| Project | What it is | Stack |
|---------|-----------|-------|
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | ML alert prioritization — Naive Bayes + fine-tuned BERT. 67.4% alert reduction at 83.27% accuracy. 435 pytest cases. | `Python` `Flask` `PyTorch` `BERT` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | B2B procurement platform, ~57k LOC TypeScript. 87 test files, GitHub Actions CI/CD. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Cypress E2E Suite](https://github.com/oguarni/automacao-vv-cypress)** | 5 E2E specs with custom resilient commands, retry strategy, HTML reporting. | `Cypress` `JavaScript` |
| **[Agiliza](https://github.com/oguarni/agiliza)** | Kanban platform — 4-layer Clean Architecture, DI via Inversify, JWT/RBAC, Jest. | `React` `Express` `TypeScript` `Docker` |

---

## Experience

**ERP Software Tester (QA)** — PRECISA Software · May 2026 – Present
Functional, regression and API testing on an ERP product. Validate fixes against reported defects, verify data with SQL, and document each case with reproducible evidence.

**AWS Cloud Data Engineer, Intern** — Compass UOL · May – Oct 2025 · Remote
Python/Boto3 automations across EC2, S3, RDS, IAM and Lambda. Migrated batch pipelines to PySpark and validated data integrity with SQL.

**Full Stack Developer, Intern** — Procfy · Nov 2023 – Nov 2024
Shipped features in Ruby on Rails/PostgreSQL. REST API testing with Postman, root cause analysis, SQL validation.

**IT Assistant** — Serviço de Registro de Imóveis · Apr 2021 – Nov 2023
Kept an ERP integrated with external mission-critical systems under judicial oversight. 99%+ availability, zero findings across inspections.

---

## Skills

| | |
|---|---|
| **Testing** | Pytest · Cypress · Playwright · Jest · Vitest · Postman · SQL validation · functional, regression, integration & API testing |
| **Backend** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC |
| **ML** | Scikit-learn · Isolation Forest · NumPy · feature engineering · model versioning · ablation studies |
| **Cloud & CI/CD** | AWS (Boto3, PySpark) · Google Cloud (GCE, Cloud Storage, BigQuery) · Docker · GitHub Actions · Prometheus |
| **Data** | PostgreSQL · Redis |

---

## Education

**B.S. Software Engineering** — UTFPR, Dois Vizinhos · 2022 – 2026
Capstone TerraVault (9.7/10), approved by the examining board. Cypress E2E suites in coursework.

---

<div align="center">

[gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfolio](https://oguarni.github.io)

</div>

---

<div id="-português"></div>

<div align="center">

# Gabriel Felipe Guarnieri

#### QA & Automação de Testes · Python / Back-end

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>Postman</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

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

Engenheiro de Software (Bacharel, UTFPR, 2026), atuando em QA e construindo carreira em automação de testes e back-end Python. Testo software ERP profissionalmente, escrevo minhas próprias suítes de teste em Python e aprendo medindo — inclusive quando a medição diz que minha ideia não funcionou.

**Aberto a:** QA / Automação de Testes · Python / Back-end · Full Stack Jr — Remoto / Híbrido / Presencial.

---

## TerraVault — TCC (9,7/10)

Scanner híbrido de segurança para Terraform: **11 regras determinísticas** + **Isolation Forest** sobre um vetor estrutural de 8 características.

**Benchmark** — 22 módulos Terraform rotulados:

| Scanner | Precisão | Recall | F1 |
|---------|:--------:|:------:|:--:|
| **TerraVault** | **100%** | **100%** | **100%** |
| Checkov | 100% | 95,7% | 97,8% |
| tfsec | 100% | 87,0% | 93,0% |
| Terrascan | 100% | 47,8% | 64,7% |

**ML no Google Cloud** — re-treinado sobre **35.594 vetores reais**, extraídos de 10.639 módulos do Terraform Registry e 30.303 arquivos públicos do GitHub, em jobs GCE que se desligam sozinhos.

**A ablação** — as regras sozinhas separam seguro de vulnerável por **33,3 pontos**, o híbrido por **21,4** e o modelo sozinho por **3,2**. O ML entrega sinal ortogonal, não separação melhor. Publiquei como medido. Fechar essa lacuna é meu trabalho atual: usar o modelo para classificar achados e suprimir falsos positivos.

**Qualidade** — 137 casos pytest · 76,8% de cobertura · Pylint 10,00/10 · 0 Bandit/Safety/Flake8/Mypy · quality gate com catraca de não regressão · SARIF v2.1.0.

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn` `Prometheus`

---

## Projetos

| Projeto | O que é | Stack |
|---------|---------|-------|
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | Priorização de alertas com ML — Naive Bayes + BERT fine-tuned. 67,4% de redução de alertas, 83,27% de acurácia. 435 casos pytest. | `Python` `Flask` `PyTorch` `BERT` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | Plataforma de compras B2B, ~57 mil LOC TypeScript. 87 arquivos de teste, CI/CD com GitHub Actions. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Suíte E2E Cypress](https://github.com/oguarni/automacao-vv-cypress)** | 5 specs E2E com comandos resilientes customizados, retry e relatório HTML. | `Cypress` `JavaScript` |
| **[Agiliza](https://github.com/oguarni/agiliza)** | Plataforma Kanban — Clean Architecture em 4 camadas, DI via Inversify, JWT/RBAC, Jest. | `React` `Express` `TypeScript` `Docker` |

---

## Experiência

**Testador de Software ERP (QA)** — PRECISA Software · Mai 2026 – Atual
Testes funcionais, de regressão e de API em produto ERP. Valido correções frente a defeitos reportados, verifico dados com SQL e documento cada caso com evidências reprodutíveis.

**Engenharia de Dados Cloud AWS, Estágio** — Compass UOL · Mai – Out 2025 · Remoto
Automações Python/Boto3 em EC2, S3, RDS, IAM e Lambda. Migrei pipelines batch para PySpark e validei integridade de dados com SQL.

**Desenvolvimento Full Stack, Estágio** — Procfy · Nov 2023 – Nov 2024
Entreguei funcionalidades em Ruby on Rails/PostgreSQL. Testes de API REST com Postman, análise de causa raiz e validação via SQL.

**Assistente de TI** — Serviço de Registro de Imóveis · Abr 2021 – Nov 2023
Mantive um ERP integrado a sistemas externos de missão crítica sob fiscalização judicial. 99%+ de disponibilidade, zero achados em inspeções.

---

## Competências

| | |
|---|---|
| **Testes** | Pytest · Cypress · Playwright · Jest · Vitest · Postman · validação via SQL · testes funcionais, de regressão, integração e API |
| **Back-end** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC |
| **ML** | Scikit-learn · Isolation Forest · NumPy · engenharia de características · versionamento de modelos · estudos de ablação |
| **Cloud & CI/CD** | AWS (Boto3, PySpark) · Google Cloud (GCE, Cloud Storage, BigQuery) · Docker · GitHub Actions · Prometheus |
| **Dados** | PostgreSQL · Redis |

---

## Formação

**Bacharelado em Engenharia de Software** — UTFPR, Dois Vizinhos · 2022 – 2026
TCC TerraVault (9,7/10), aprovado pela banca. Suítes E2E com Cypress em projetos acadêmicos.

---

<div align="center">

[gfguarnieri@gmail.com](mailto:gfguarnieri@gmail.com) · [LinkedIn](https://www.linkedin.com/in/oguarni/) · [Portfólio](https://oguarni.github.io)

</div>
