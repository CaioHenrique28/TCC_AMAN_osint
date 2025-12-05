# 📊 Análise de Sentimentos do Exército Brasileiro (NLP)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## 🎯 Objetivo do Projeto
Monitorar a reputação institucional do Exército Brasileiro através da análise de sentimentos em comentários públicos do YouTube. O projeto utiliza técnicas de **Processamento de Linguagem Natural (NLP)** e **Deep Learning** para classificar a opinião pública em larga escala, visando apoiar a tomada de decisão estratégica.

> **Nota:** Este projeto é parte do Trabalho de Conclusão de Curso (TCC) do Curso de Ciências Militares da Academia Militar das Agulhas Negras (AMAN).

## 🛠️ Arquitetura e Tecnologias
O projeto segue um pipeline de dados (ETL) moderno:

* **Coleta (Extraction):** `YouTube Data API v3` para extração massiva de comentários.
* **Processamento (Transformation):** Limpeza e normalização com `Pandas` e `RegEx`.
* **Inteligência (Analysis):**
    * Arquitetura **Transformers** (Modelo BERTimbau).
    * Rotulagem assistida por IA Generativa (LLMs).
* **Infraestrutura:** Google Colab, Google Drive e Git.

## 📂 Estrutura do Repositório
```text
tcc-aman-nlp-2025/
├── notebooks/       # Notebooks interativos (Passo a passo)
├── src/             # Scripts de automação (ETL puro)
├── data/            # (Ignorado) Armazenamento local de dados
├── .gitignore       # Configuração de segurança
├── requirements.txt # Lista de dependências
└── README.md        # Documentação do projeto
