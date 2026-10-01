# 👋 Olá, eu sou Jackeline

Sou formada em **Ciência de Dados**, pós-graduanda em **Engenharia de Dados e Inteligência Artificial** e estou **cursando Engenharia de Software**. Atuo com **Análise de Dados** e **Engenharia de Dados**, com foco em automação de pipelines, visualização estratégica e soluções orientadas por IA.

Antes da tecnologia, construí mais de **15 anos de carreira em coordenação administrativa e financeira** — e é essa visão de negócio que trago para os dados: entender o problema antes de escolher a ferramenta, e entregar soluções que apoiam decisões reais.

---

## 🧠 Áreas de Atuação

- 🏗️ Engenharia de Dados & Pipelines ETL
- 📊 Análise de Dados & Business Intelligence
- 🤖 Automação e Inteligência Artificial
- 📈 Visualização de Dados & Dashboards Executivos

---

## 📂 Portfólio de Projetos

### 💉 Radar de Risco Vacinal — homologado no 2º Concurso de Reúso de Dados Abertos da CGU
Modelo preditivo que identifica os municípios brasileiros com maior risco de ficar abaixo da meta de cobertura vacinal infantil e estima quantas crianças podem ficar sem vacina, para orientar onde agir primeiro.

- **Destaques:** ~150 GB de dados públicos (PNI/OpenDataSUS, SINASC, CNES, IBGE) processados em blocos; comparação de Regressão Logística, Random Forest e XGBoost com validação temporal walk-forward; Random Forest escolhido (AUC-ROC 0,82); modelo de regressão para estimar o déficit de crianças vacinadas; interpretabilidade por município com SHAP; decisões técnicas documentadas.
- **Tecnologias:** Python, Pandas, Scikit-Learn, XGBoost, SHAP, Streamlit, GeoJSON (malha IBGE).
- 🔗 [Repositório](https://github.com/JackelineTesch/reuso-cobertura-vacinal) · [🚀 App ao vivo](https://radar-risco-vacinal.streamlit.app/)

---

### 🏦 Pipeline de Indicadores Financeiros — Banco Central do Brasil
Pipeline de dados E2E automatizado que extrai indicadores econômicos (SELIC, CDI, IPCA, Câmbio) via API pública do BACEN, transforma, carrega em banco analítico e disponibiliza em duas visualizações públicas.

- **Destaques:** Arquitetura ETL completa, lógica de idempotência, atualização automática diária via GitHub Actions, dashboard executivo no Power BI e app interativo em Streamlit publicado online.
- **Tecnologias:** Python, Pandas, DuckDB, SQL, ETL, Power BI, Streamlit, Plotly, GitHub Actions, REST API.
- 🔗 [Repositório](https://github.com/JackelineTesch/pipeline-indicadores-financeiros-bcb) · [🚀 App ao vivo](https://pipeline-indicadores-financeiros-bcb.streamlit.app/)

---

### 🤖 Pipeline RAG Automático & Ingestão Vetorial
Pipeline para extração, chunking, vetorização e armazenamento de documentos do Google Drive para suporte a sistemas RAG (Retrieval-Augmented Generation).

- **Destaques:** Ingestão orientada a eventos, geração de embeddings com o modelo `gemini-embedding-2` (3072 dimensões), busca vetorial por similaridade de cosseno via função RPC no PostgreSQL e persistência estruturada de metadados para rastreabilidade e limpeza automática.
- **Tecnologias:** n8n, Google Drive API, Google Gemini API, PostgreSQL, Supabase (`pgvector`), SQL.
- 🔗 [Repositório](https://github.com/JackelineTesch/n8n-rag-drive-supabase)

---

### 💳 Previsão de Risco de Crédito & Inadimplência
Pipeline completo de Machine Learning para estimar a probabilidade de inadimplência de cobranças financeiras a partir de histórico em painel.

- **Destaques:** Modelagem sem *data leakage*, pré-processamento e imputação temporal inteligente, validação *Out-of-Time* (OOT) simulando safras futuras.
- **Resultados:** Modelo LightGBM com **ROC-AUC de 0.9200** e **Log-Loss de 0.1348** na validação Out-of-Time.
- **Tecnologias:** Python, Pandas, NumPy, LightGBM, Scikit-Learn.
- 🔗 [Repositório](https://github.com/JackelineTesch/credito-inadimplencia-lightgbm)

---

## 🛠️ Tecnologias & Ferramentas

**Linguagens:** Python, SQL, JavaScript

**Engenharia de Dados:** ETL, Data Pipeline, DuckDB, PostgreSQL, Supabase (`pgvector`)

**Visualização:** Power BI, Streamlit, Plotly, Looker Studio

**Cloud & DevOps:** GitHub Actions, Git

**IA & Machine Learning:** LightGBM, Scikit-Learn, Google Gemini API, RAG, Embeddings, XGBoost, SHP, Streamlit

**Orquestração & Automação:** n8n

**Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn

**Em aprofundamento (pós-graduação):** Apache Spark / PySpark, Databricks, Arquitetura Medallion, AWS, GCP, Azure

---

## 🎯 Objetivo Profissional

Atuar nas áreas de **Engenharia de Dados**, **Análise de Dados** e **IA**, aplicando arquitetura de pipelines, inteligência artificial e análise estatística, aliadas a boas práticas de engenharia de software para resolver problemas reais de negócio.

📫 **Vamos conversar?**
Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/jackelinestesch)!
