<div align="center">

  <!-- Theme-Aware Animated SVG Hero Banner -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg" />
    <img src="assets/hero-dark.svg" alt="Dyone Andrade - Hero Banner" width="100%" />
  </picture>

  <br />
  <br />

  <!-- Primary Status & Quick Badges -->
  <a href="https://dyonedev.com.br" target="_blank">
    <img src="https://img.shields.io/badge/Portfólio-dyonedev.com.br-0D1117?style=for-the-badge&logo=google-chrome&logoColor=38BDF8" alt="Portfólio" />
  </a>
  <a href="https://linkedin.com/in/dyonenunes" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Dyone_Andrade-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:dyone.andrade.l@gmail.com">
    <img src="https://img.shields.io/badge/Email-dyone.andrade.l@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://wa.me/5527996571418" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-(27)_99657--1418-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="tel:+5527920040271">
    <img src="https://img.shields.io/badge/Telefone-(27)_92004--0271-0284C7?style=for-the-badge" alt="Telefone para Chamadas" />
  </a>
  <img src="https://img.shields.io/badge/Localização-Vitória_--_ES,_Brasil-0D1117?style=for-the-badge&logo=linux&logoColor=10B981" alt="Localização" />

  <br /><br />

  <!-- Quick Navigation Bar -->
  <p align="center">
    <a href="#-visão-geral">Visão Geral</a> •
    <a href="#-bento-grid--especialidades">Especialidades</a> •
    <a href="#-arquitetura-do-ecossistema-de-ia--dados">Arquitetura de Dados & IA</a> •
    <a href="#-stack-tecnológica">Stack Tecnológica</a> •
    <a href="#-trajetória-acadêmica--conquistas">Trajetória & Conquistas</a> •
    <a href="#-telemetria--github-stats">Estatísticas</a> •
    <a href="#-vamos-conversar">Contato</a>
  </p>

</div>

---

### 👨‍💻 Visão Geral

Desenvolvedor Full Stack e Engenheiro de Software em aprofundamento contínuo e consolidação estratégica em **Data Science, Inteligência Artificial e Engenharia de Dados**. Atualmente graduando MBA em **Data Science, IA e Analytics (USP/Esalq)** e graduado em **Tecnologia em Análise e Desenvolvimento de Sistemas (TADS)**.

Minha atuação é pautada na convergência entre **software de altíssima performance** (Python, TypeScript e C++20), **modelagem analítica & pipelines distribuídos** (PySpark, Big Data, LangChain, LLMs) e **infraestrutura resiliente self-hosted** com rigor em **Linux Hardening e Cyber Security**.

> [!TIP]
> **Foco de Atuação:** Construção de ecossistemas orientados a dados em tempo real, orquestração de pipelines analíticos resilientes, integração de sistemas multi-agente autônomos e hardening de ambientes de produção.

---

### 🍱 Bento Grid // Especialidades

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🧠 Data Science, IA &amp; LLMs</h4>
      <ul>
        <li><b>Big Data &amp; Distributed Processing:</b> Pipelines distribuídos com PySpark, Pandas e NumPy.</li>
        <li><b>Arquiteturas Agênticas &amp; GenAI:</b> Orquestração de LLMs via LangChain, Gemini API e modelos locais via Ollama.</li>
        <li><b>Geospatial Analytics:</b> Processamento analítico geoespacial com GeoPandas.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>⚡ Engenharia de Software &amp; Core</h4>
      <ul>
        <li><b>Alta Performance:</b> Desenvolvimento de sistemas e algoritmos eficientes em C++20 e Python.</li>
        <li><b>APIs &amp; Microserviços:</b> Construção de endpoints assíncronos e escaláveis em FastAPI e Node.js.</li>
        <li><b>Modern Frontend:</b> Interfaces reativas e dados em tempo real com React e Next.js.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🛡️ Cyber Security &amp; Linux Hardening</h4>
      <ul>
        <li><b>Certificação IBSec Essencial:</b> Princípios de defesa cibernética, testes de integridade e auditoria.</li>
        <li><b>Linux Hardening:</b> Configuração de servidores com foco em segurança em profundidade, iptables/UFW e isolamento.</li>
        <li><b>Infraestrutura Self-Hosted:</b> Deploy e gestão de containers Docker em homelab próprio.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏆 Hackathons &amp; Liderança Técnica</h4>
      <ul>
        <li><b>1º Lugar — HackFAESA 2026:</b> Campeão geral desenvolvendo a solução de alto impacto <i>NexoPit</i>.</li>
        <li><b>3º Lugar — HackFAESA 2024:</b> Destaque no desenvolvimento da plataforma <i>Taokay</i>.</li>
        <li><b>Resolução Sob Pressão:</b> Prototipação rápida da concepção à entrega funcional em maratonas de programação.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🧬 Arquitetura do Ecossistema de IA & Dados

O fluxo abaixo sintetiza o ciclo de vida dos dados e inferência implementado em minhas arquiteturas:

```mermaid
flowchart LR
    subgraph INGESTION[" Camada de Ingestão & Fontes "]
        direction TB
        S1["Streams de Sensores & Logs"]
        S2["APIs REST / Webhooks"]
        S3["Bancos Relacionais (SQL)"]
    end

    subgraph PROCESSING[" Motor de Processamento & Core "]
        direction TB
        E1["PySpark (Batch & Stream)"]
        E2["Python & GeoPandas"]
        E3["C++20 (Rotinas Críticas)"]
    end

    subgraph AI_LAYER[" Camada de Inteligência & LLMs "]
        direction TB
        A1["Orquestração de Agentes (LangChain)"]
        A2["Modelos Locais (Ollama)"]
        A3["Modelos Fundacionais (Gemini API)"]
    end

    subgraph DELIVERY[" Entrega, APIs & Visualização "]
        direction TB
        D1["FastAPI / Node.js Microservices"]
        D2["Next.js / Dashboards Analíticos"]
        D3["Linux Hardened / Docker Clustered"]
    end

    INGESTION --> PROCESSING
    PROCESSING --> AI_LAYER
    AI_LAYER --> DELIVERY
```

---

### 🛠️ Stack Tecnológica

<div align="center">

#### Linguagens & Sistemas Core
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C++20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++20" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
</p>

#### Data Science, Inteligência Artificial & LLMs
<p>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge&logo=python&logoColor=white" alt="GeoPandas" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini API" />
</p>

#### Backend, Frontend, DevOps & Infraestrutura
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

</div>

---

### 🎓 Trajetória Acadêmica & Conquistas

<details>
<summary><strong>📚 Formação Acadêmica &amp; Certificações Profissionais (clique para expandir)</strong></summary>

<br />

| Nível / Programa | Instituição | Detalhes &amp; Foco |
|:---|:---|:---|
| **MBA em Data Science, IA &amp; Analytics** | **USP / Esalq** | Modelagem preditiva, Machine Learning avançado, Big Data e governança analítica. *(Graduando)* |
| **Tecnologia em Análise e Desenv. de Sistemas (TADS)** | *Graduado* | Engenharia de requisitos, modelagem relacional, arquitetura de software e desenvolvimento full stack. |
| **Certificação IBSec Essencial** | **IBSec** | Cyber Security, Linux Hardening, princípios defensivos, mitigação de vulnerabilidades e segurança operacional. |

</details>

<details>
<summary><strong>🏆 Histórico em Hackathons &amp; Prêmios (clique para expandir)</strong></summary>

<br />

- 🥇 **1º Lugar — HackFAESA 2026 (Projeto *NexoPit*)**:
  - Solução concebida e implementada de ponta a ponta sob regime de maratona, integrando automação inteligente, arquitetura resiliente e proposta de valor assertiva validada por banca avaliadora.
- 🥉 **3º Lugar — HackFAESA 2024 (Projeto *Taokay*)**:
  - Plataforma funcional focada em usabilidade e viabilidade técnica, combinando integração de serviços modernos e entregas em tempo recorde.

</details>

<details>
<summary><strong>🖥️ Homelab, Infraestrutura Self-Hosted &amp; Hardening (clique para expandir)</strong></summary>

<br />

- **Ambiente Self-Hosted:** Cluster de experimentação local com Linux dedicado para prototipagem de pipelines distribuídos, execução de instâncias locais de LLMs (Ollama) e testes de escalabilidade.
- **Segurança em Profundidade:** Políticas rigorosas de firewalling, isolamento em redes virtuais internas, monitoramento ativo de integridade e auditoria de logs.

</details>

---

### 📊 Telemetria // GitHub Stats

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=DyoneNunes&show_icons=true&theme=tokyonight&hide_border=true&bg_color=050811&title_color=38BDF8&icon_color=10B981&text_color=94A3B8" alt="GitHub Stats" height="175" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DyoneNunes&layout=compact&theme=tokyonight&hide_border=true&bg_color=050811&title_color=38BDF8&text_color=94A3B8" alt="Top Languages" height="175" />
      </td>
    </tr>
  </table>

  <br />

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DyoneNunes&theme=tokyonight&hide_border=true&background=050811&ring=38BDF8&fire=F59E0B&currStreakLabel=38BDF8" alt="Streak Stats" />
</div>

---

<div align="center" id="-vamos-conversar">

  <h3>📫 Vamos Conversar?</h3>
  <p>Interessado em colaborar em soluções de IA, engenharia de dados ou sistemas de alta performance?</p>

  <p>
    <a href="mailto:dyone.andrade.l@gmail.com">
      <img src="https://img.shields.io/badge/Email-dyone.andrade.l@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://wa.me/5527996571418" target="_blank">
      <img src="https://img.shields.io/badge/WhatsApp-(27)_99657--1418-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
    </a>
    <a href="tel:+5527920040271">
      <img src="https://img.shields.io/badge/Telefone_(Chamadas)-(27)_92004--0271-0284C7?style=for-the-badge" alt="Telefone para Chamadas" />
    </a>
  </p>

  <p>
    <a href="https://dyonedev.com.br" target="_blank">
      <img src="https://img.shields.io/badge/Portfólio-dyonedev.com.br-0D1117?style=for-the-badge&logo=google-chrome&logoColor=38BDF8" alt="Portfólio" />
    </a>
    <a href="https://linkedin.com/in/dyonenunes" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Dyone_Andrade-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>

  <br />
  <sub><i>Construído com design system limpo, responsividade nativa e zero vazamento de dados.</i></sub>

</div>
