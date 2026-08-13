<div align="center">
  <a href="#gabriel-felipe-guarnieri" title="Read in English">
    <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f310.png" alt="English" height="40" style="vertical-align:middle;" />
  </a>
    
  <a href="#gabriel-felipe-guarnieri-1" title="Ler em Português">
    <img src="https://flagcdn.com/h40/br.png" alt="Português" height="40" />
  </a>
</div>

<div align="center">

# Gabriel Felipe Guarnieri

#### Software Engineer · QA Automation & Python Backend

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Terraform</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/Capstone-TerraVault_9.7%2F10-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
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
  <img src="https://img.shields.io/badge/Open_to_Work-Remote_%7C_Hybrid_%7C_On--site-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Location-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Languages-PT_(Native)_%7C_EN_(Full_Professional)-blueviolet?style=flat-square"/>
</p>

</div>

---

Software Engineer (B.S., UTFPR, July 2026). I tested software professionally — functional, regression and API testing on a production ERP — and I build Python backends, with security wired in before release. Heading toward DevSecOps and cloud security.

**Open to:** QA / Test Automation · Python / Backend · Full Stack Jr — Remote / Hybrid / On-site.

---

## TerraVault — Capstone (9.7/10)

Hybrid security scanner for Terraform: **11 deterministic rules** + an Isolation Forest trained on **35,594 real feature vectors** mined from public Terraform on GCE.

**Quality** — 137 pytest cases · 76.80% coverage · Pylint 10.00/10 · 0 Bandit/Safety/Flake8/Mypy · CI gate with a non-regression ratchet · SARIF v2.1.0 for GitHub Code Scanning.

**Measured, not claimed** — **83% recall** on third-party KICS fixtures inside the declared rule scope; Checkov's broader catalogue still wins the aggregate (F1 73.5 vs 64.4), and the ablation shows the rules, not the ML, doing the separating. All three numbers are in the repo.

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

---

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | Cut 568 dependency alerts to 185 (67.4%) at 83.27% accuracy — Naive Bayes + fine-tuned BERT behind a validated Flask API. 435 pytest cases. | `Python` `Flask` `PyTorch` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | B2B procurement platform live on Firebase Hosting — ~61k LOC TypeScript, 90 test files, strict CSP, GitHub Actions CI/CD. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Cypress E2E Suite](https://github.com/oguarni/kurzgesagt-cypress-tests)** | 5 E2E specs with custom resilient commands, retry strategy and HTML reporting. | `Cypress` `JavaScript` |
| **[crash-loop](https://github.com/oguarni/crash-loop)** | Browser-playable SRE puzzle — deterministic sim engine, 110 Vitest cases with enforced coverage thresholds. [Play it live.](https://oguarni.github.io/crash-loop/) | `TypeScript` `Vite` `Vitest` |
| **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** | Isolated attack-and-defense lab built and destroyed by 4 Bash scripts — five Cyber Kill Chain techniques, each answered with cloud-native detection. | `GCP` `Bash` `Nmap` `Wireshark` |

---

## Experience

**ERP Software Tester (QA)** — PRECISA Software · May – Aug 2026
Functional, regression and performance testing on a production ERP (financial, fiscal, sales orders, purchasing, billing). Validated developer fixes against customer-reported defects through a ticket workflow, checked report data with SQL, documented each case with reproducible evidence. Brazilian fiscal domain: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, IBS/CBS transition. Method: cover the whole screen, not only the reported item — every flag set and unset, and both print layouts, where the surviving defect usually is.

**AWS Cloud Data Engineer, Intern** — Compass UOL · May – Oct 2025 · Remote
Python/Boto3 automations across EC2, S3, RDS, IAM and Lambda. Migrated batch pipelines to PySpark, validated data integrity with SQL.

**Full Stack Developer, Intern** — Procfy · Nov 2023 – Nov 2024
Shipped features in Ruby on Rails/PostgreSQL. REST API testing with Postman, root cause analysis, SQL validation.

**IT Assistant** — Serviço de Registro de Imóveis · Apr 2021 – Nov 2023
Integration testing across court and registry systems (SAEC/ONR, e-Proc, PJe, Projudi) under judicial oversight, LGPD access controls, Windows Server. 99%+ availability, zero findings in inspections.

---

## Skills

|     |     |
| --- | --- |
| **Testing & QA** | Pytest · Cypress · Playwright · Jest · Vitest · Postman · SQL validation · functional, regression, integration & API testing · defect lifecycle and fix validation (homologation/UAT) |
| **Backend** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC · PostgreSQL · Redis |
| **Cloud & DevSecOps** | AWS (EC2, S3, RDS, IAM, Lambda, Boto3, PySpark) · GCP (Compute Engine, VPC, BigQuery) · Terraform · Docker · GitHub Actions · Bandit · Trivy · GitLeaks · SARIF |
| **ML** | Scikit-learn · Isolation Forest · feature engineering |

---

## Education

**B.S. Software Engineering** — UTFPR, Dois Vizinhos · 2022 – Jul 2026 · graduated
Capstone: TerraVault (9.7/10), approved by the examining board.

**Containers & Kubernetes Essentials** — Coursera, IBM-authored course · Jul 2026 · [verify](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)

---

<div align="center">

# Gabriel Felipe Guarnieri

#### Engenheiro de Software · QA & Automação de Testes · Back-end Python

<code>Python</code> · <code>Pytest</code> · <code>Cypress</code> · <code>Playwright</code> · <code>SQL</code> · <code>FastAPI</code> · <code>Terraform</code> · <code>Docker</code> · <code>AWS</code> · <code>GCP</code>

<p>
  <a href="https://github.com/oguarni/terravault">
    <img src="https://img.shields.io/badge/TCC-TerraVault_9.7%2F10-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="TerraVault"/>
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
  <img src="https://img.shields.io/badge/Aberto_a_Oportunidades-Remoto_%7C_Híbrido_%7C_Presencial-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Localização-Dois_Vizinhos,_PR,_BR-informational?style=flat-square"/>
  <img src="https://img.shields.io/badge/Idiomas-PT_(Nativo)_%7C_EN_(Profissional_Completo)-blueviolet?style=flat-square"/>
</p>

</div>

---

Engenheiro de Software (Bacharel, UTFPR, julho de 2026). Testei software profissionalmente — testes funcionais, de regressão e de API em um ERP em produção — e construo back-end em Python, com segurança integrada antes do release. Caminhando para DevSecOps e segurança em cloud.

**Aberto a:** QA / Automação de Testes · Python / Back-end · Full Stack Jr — Remoto / Híbrido / Presencial.

---

## TerraVault — TCC (9,7/10)

Scanner híbrido de segurança para Terraform: **11 regras determinísticas** + Isolation Forest treinado sobre **35.594 vetores reais** extraídos de Terraform público, em GCE.

**Qualidade** — 137 casos pytest · 76,80% de cobertura · Pylint 10,00/10 · 0 Bandit/Safety/Flake8/Mypy · quality gate com catraca de não regressão · SARIF v2.1.0 para o GitHub Code Scanning.

**Medido, não afirmado** — **83% de recall** em fixtures de terceiros do KICS, dentro do escopo declarado das regras; o catálogo mais amplo do Checkov ainda vence no agregado (F1 73,5 contra 64,4), e a ablação mostra que quem separa são as regras, não o ML. Os três números estão no repositório.

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions` `Scikit-learn`

---

## Projetos

| Projeto | O que é | Stack |
| --- | --- | --- |
| **[AI Vulnerability Triage](https://github.com/oguarni/ai-vulnerability-triage)** | Reduziu 568 alertas de dependências para 185 (67,4%) com 83,27% de acurácia — Naive Bayes + BERT fine-tuned atrás de uma API Flask validada. 435 casos pytest. | `Python` `Flask` `PyTorch` `Redis` |
| **[CresceBR](https://github.com/oguarni/crescebr-b2b-marketplace)** | Plataforma de compras B2B em produção no Firebase Hosting — ~61 mil LOC TypeScript, 90 arquivos de teste, CSP estrita, CI/CD com GitHub Actions. | `Express 5` `React 19` `TypeScript` `PostgreSQL` |
| **[Suíte E2E Cypress](https://github.com/oguarni/kurzgesagt-cypress-tests)** | 5 specs E2E com comandos resilientes customizados, retry e relatório HTML. | `Cypress` `JavaScript` |
| **[crash-loop](https://github.com/oguarni/crash-loop)** | Puzzle SRE jogável no navegador — motor de simulação determinístico, 110 casos Vitest com thresholds de cobertura. [Jogue online.](https://oguarni.github.io/crash-loop/) | `TypeScript` `Vite` `Vitest` |
| **[Cloud Security Lab — GCP](https://github.com/oguarni/cloud-security-lab-gcp)** | Laboratório isolado de ataque e defesa criado e destruído por 4 scripts Bash — cinco técnicas da Cyber Kill Chain, cada uma respondida com detecção nativa da nuvem. | `GCP` `Bash` `Nmap` `Wireshark` |

---

## Experiência

**Testador de Software ERP (QA)** — PRECISA Software · Mai – Ago 2026
Testes funcionais, de regressão e de performance em um ERP em produção (financeiro, fiscal, pedidos de venda, compras, faturamento). Validei correções dos desenvolvedores frente a defeitos reportados por clientes dentro de um fluxo de tickets, conferi dados de relatórios com SQL e documentei cada caso com evidências reprodutíveis. Domínio fiscal brasileiro: NF-e/NFC-e/CT-e, SPED, PIS/COFINS, transição IBS/CBS. Método: cobrir a tela inteira, não só o item reportado — cada flag marcada e desmarcada, e os dois layouts de impressão, que é onde o defeito costuma sobreviver.

**Engenharia de Dados Cloud AWS, Estágio** — Compass UOL · Mai – Out 2025 · Remoto
Automações Python/Boto3 em EC2, S3, RDS, IAM e Lambda. Migrei pipelines batch para PySpark e validei integridade de dados com SQL.

**Desenvolvimento Full Stack, Estágio** — Procfy · Nov 2023 – Nov 2024
Entreguei funcionalidades em Ruby on Rails/PostgreSQL. Testes de API REST com Postman, análise de causa raiz e validação via SQL.

**Assistente de TI** — Serviço de Registro de Imóveis · Abr 2021 – Nov 2023
Testes de integração com sistemas judiciais e registrais (SAEC/ONR, e-Proc, PJe, Projudi) sob fiscalização judicial, controles de acesso para a LGPD, Windows Server. 99%+ de disponibilidade, zero achados em inspeções.

---

## Competências

|     |     |
| --- | --- |
| **Testes & QA** | Pytest · Cypress · Playwright · Jest · Vitest · Postman · validação via SQL · testes funcionais, de regressão, integração e API · ciclo de vida de defeitos e validação de correções (homologação/UAT) |
| **Back-end** | Python (FastAPI, async, Pydantic, SQLAlchemy) · Node.js/Express · Ruby on Rails · REST/OpenAPI · JWT/RBAC · PostgreSQL · Redis |
| **Cloud & DevSecOps** | AWS (EC2, S3, RDS, IAM, Lambda, Boto3, PySpark) · GCP (Compute Engine, VPC, BigQuery) · Terraform · Docker · GitHub Actions · Bandit · Trivy · GitLeaks · SARIF |
| **ML** | Scikit-learn · Isolation Forest · engenharia de características |

---

## Formação

**Bacharelado em Engenharia de Software** — UTFPR, Dois Vizinhos · 2022 – Jul 2026 · graduado
TCC: TerraVault (9,7/10), aprovado pela banca.

**Containers & Kubernetes Essentials** — Coursera, curso da IBM · Jul 2026 · [verificar](https://www.credly.com/badges/3f51aed5-1893-41dd-9fcb-8a752c9fe71d)
