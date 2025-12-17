# 📊 Sistema Inteligente de Previsão de Vendas e Recomendação de Estoque

## 📌 Descrição do Projeto (para o repositório)

Projeto de Ciência de Dados desenvolvido de forma colaborativa com o objetivo de **prever vendas futuras e gerar recomendações inteligentes de estoque**, utilizando dados históricos, técnicas de análise exploratória, modelagem estatística e algoritmos de Machine Learning.

O sistema simula um cenário real de empresas do varejo, auxiliando na **tomada de decisão estratégica**, redução de custos operacionais e prevenção de rupturas ou excesso de estoque.

---

## 🎯 Objetivo

Desenvolver um pipeline completo de dados capaz de:

* Analisar padrões históricos de vendas
* Prever demanda futura por produto
* Recomendar quantidades ideais de estoque
* Apoiar decisões comerciais e operacionais

O projeto também serve como **base para Trabalho de Conclusão de Curso (TCC)** e **portfólio profissional**.

---

## 🏗️ Arquitetura do Projeto

1. **Ingestão de Dados**

   * Dados de vendas armazenados em banco MySQL
   * Importação e consultas via SQL

2. **Análise Exploratória (EDA)**

   * Análise temporal
   * Sazonalidade
   * Impacto de promoções
   * Comportamento por produto

3. **Feature Engineering**

   * Criação de variáveis temporais
   * Indicadores de promoção
   * Agregações por período

4. **Modelagem Preditiva**

   * Modelos de regressão
   * Algoritmos baseados em árvores (ex: Gradient Boosting)
   * Avaliação com métricas como RMSE e MAE

5. **Recomendação de Estoque**

   * Baseada na previsão de demanda
   * Ajuste por margem de segurança

---

## 🗂️ Estrutura de Pastas

```
projeto-previsao-vendas/
│
├── data/
│   ├── raw/            # Dados brutos
│   └── processed/      # Dados tratados
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_modelagem.ipynb
│
├── src/
│   ├── ingestao.py
│   ├── treino_modelo.py
│   └── previsao.py
│
├── sql/
│   └── consultas.sql
│
├── README.md
└── requirements.txt
```

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas / NumPy**
* **Scikit-learn**
* **MySQL**
* **SQL**
* **Jupyter Notebook**
* **Git & GitHub**
* **VS Code + Live Share**

---

## 🤝 Trabalho Colaborativo

O desenvolvimento é realizado de forma colaborativa utilizando:

* Controle de versão com GitHub
* Edição em tempo real via VS Code Live Share
* Organização de tarefas e evolução incremental

---

## 📈 Aplicabilidade nas Empresas

Este sistema pode ser aplicado em:

* Varejo físico e online
* E-commerce
* Indústrias com controle de estoque
* Pequenas e médias empresas

Benefícios diretos:

* Redução de desperdícios
* Melhor planejamento de compras
* Aumento de eficiência operacional
* Suporte à tomada de decisão baseada em dados

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido como parte da graduação em **Ciência de Dados**, com foco em aplicar conceitos teóricos em um cenário prático e realista.

---

## 🚀 Próximos Passos

* Integração com dashboard (Power BI / Streamlit)
* Testes com dados reais
* Deploy do modelo
* Documentação acadêmica para TCC

---

## 📬 Contato

Projeto em desenvolvimento. Feedbacks e sugestões são bem-vindos.
