# Estudos de Machine Learning
Este repositório contém projetos e estudos focados em Ciência de Dados e Machine Learning, abrangendo desde a análise exploratória e tratamento de dados até a construção de modelos preditivos.

## 🚀 Projetos Principais
1. **Previsão de Conversão de Leads (LeadsDataset)**  
O objetivo principal deste estudo é desenvolver um modelo capaz de prever se um lead será convertido (se tornará um cliente) ou não.
- **Análise Exploratória:** Identificação de variáveis qualitativas como Lead Origin e Lead Source.
- **Tratamento de Dados**:
  - Agrupamento de categorias com poucas entradas (como 'Quick Add Form' em 'Lead Add Form') para evitar viés no modelo.
  - Criação de categorias generalistas (ex: 'Others') para simplificar fontes de leads pouco frequentes.

- **Tecnologias**: Python, Pandas, Seaborn, Plotly.

2. **Aprendizado Supervisionado:**  Saúde Cardiovascular  
Estudo focado na classificação de doenças cardíacas utilizando o dataset heart.csv.

- **Pré-processamento**:

    - Codificação de variáveis categóricas (Sex, ChestPainType, etc.) para formato numérico interpretável por algoritmos.
    - Escalonamento de atributos para normalizar grandezas.
    - Aplicação de técnicas como LDA (Linear Discriminant Analysis) para redução de dimensionalidade e análise de variância.

- **Persistência**: Uso da biblioteca pickle para salvar variáveis processadas (heart.pkl), facilitando o reuso em diferentes modelos.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Python 3
- **Manipulação de Dados**: Pandas, NumPy
- **Visualização**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-Learn (LDA, Preprocessing)
- **Ferramentas**: Jupyter Notebooks / Google Colab

## 📂 Estrutura do Repositório

```text
├── LeadsDataset  
│   ├── Analise_e_tratamento.ipynb  # Estudo focado em limpeza e EDA  
│   └── Leads.csv                   # Dataset de marketing  
├── aprendizado_supervisionado  
│   ├── Pre_processamento.ipynb     # Preparação de dados para modelos  
│   ├── heart.csv                   # Dataset original  
│   └── heart_tratado.csv           # Dataset após limpeza básica  
└── README.md  
```

## 📈 Objetivos de Estudo
1. Compreender o ciclo de vida de um projeto de ML (EDA -> Tratamento -> Modelagem).
2. Praticar engenharia de atributos (Feature Engineering).
3. Avaliar o impacto do pré-processamento na performance dos algoritmos.

----
Este repositório é utilizado para fins didáticos e documentação de evolução em Ciência de Dados.
