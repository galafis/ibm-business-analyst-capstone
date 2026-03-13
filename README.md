# IBM Business Analyst Capstone

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![IBM](https://img.shields.io/badge/IBM-052FAD?style=for-the-badge&logo=ibm&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED.svg?logo=docker)](Dockerfile)

**[PT-BR](#sobre-o-projeto) | [English](#about-the-project)**

</div>

---

<a name="sobre-o-projeto"></a>

## Sobre o Projeto

> Projeto Capstone do certificado profissional **IBM Business Analyst** no [Coursera](https://www.coursera.org/)

Este projeto aplica tecnicas de analise de negocios para coletar, documentar e analisar requisitos de negocio, demonstrando competencias em levantamento de requisitos, documentacao de processos e analise de dados com Python.

---

## Pipeline de Analise de Negocios

```mermaid
flowchart LR
    A[Levantamento\\nde Requisitos] --> B[Documentacao\\nde Processos]
    B --> C[Analise\\nde Dados]
    C --> D[Visualizacao\\ne Relatorios]
    D --> E[Recomendacoes\\nEstrategicas]

    style A fill:#052FAD,color:#fff,stroke:#031f7a
    style C fill:#3776AB,color:#fff,stroke:#2a5a8a
    style E fill:#155724,color:#fff,stroke:#0e3a18
```

---

## Conteudo do Repositorio

| Arquivo / Pasta | Descricao |
|---|---|
| `src/main_platform.py` | Plataforma principal de analise |
| `docs/business_requirements.md` | Documento de requisitos de negocio |
| `docs/api_documentation.md` | Documentacao da API |
| `docs/user_guide.md` | Guia do usuario |
| `tests/` | Testes unitarios e de performance |
| `LICENSE` | Licenca MIT |

## Como Executar

```bash
git clone https://github.com/galafis/ibm-business-analyst-capstone.git
cd ibm-business-analyst-capstone
pip install -r requirements.txt
python src/main_platform.py
```

## Aplicacao na Industria

A analise de negocios e essencial para alinhar solucoes de TI com objetivos estrategicos, garantindo que projetos entreguem valor mensuravel para a organizacao.

---

<a name="about-the-project"></a>

## English

### About the Project

> Capstone project from the **IBM Business Analyst Professional Certificate** on [Coursera](https://www.coursera.org/)

This project applies business analysis techniques to collect, document, and analyze business requirements, demonstrating competencies in requirements gathering, process documentation, and data analysis with Python.

### How to Run

```bash
git clone https://github.com/galafis/ibm-business-analyst-capstone.git
cd ibm-business-analyst-capstone
pip install -r requirements.txt
python src/main_platform.py
```

---

## Licenca | License

Este projeto esta licenciado sob a [Licenca MIT](LICENSE). | This project is licensed under the [MIT License](LICENSE).

---

Developed by [Gabriel Demetrios Lafis](https://github.com/galafis)
