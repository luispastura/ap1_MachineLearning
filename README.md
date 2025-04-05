# 🧠 Projeto de Classificação com PyCaret

Este repositório contém um trabalho de grupo desenvolvido para aplicar conceitos de **Ciência de Dados e Machine Learning**, com foco em um problema de **classificação**.

---

## 📁 Arquivos do Projeto

- `Untitled10.ipynb` – Notebook com todas as etapas do projeto, desde a análise dos dados até a criação e avaliação do modelo.
- `luispastura_pastura_RELATORIO_ML.pdf` – Documento com uma explicação detalhada, em linguagem pessoal, sobre cada etapa do trabalho, incluindo reflexões e aprendizados do grupo.
- **Base de Dados**: [`iccmh2020rccsm_p.csv`](https://raw.githubusercontent.com/alvaroriz/datascience_datasets/refs/heads/main/iccmh2020rccsm_p.csv) – Arquivo CSV com os dados utilizados para análise e modelagem.

---

## 🔍 Sobre o Projeto

Neste trabalho, utilizamos uma base de dados com o objetivo de prever uma variável-alvo categórica, aplicando um fluxo completo de modelagem supervisionada. Usamos ferramentas como:

- [`PyCaret`](https://pycaret.org/) para automatizar o processo de comparação entre modelos de classificação;
- [`YData Profiling`](https://docs.ydata.ai/docs/profiling/) para gerar um relatório exploratório dos dados;
- Bibliotecas clássicas como `pandas`, `numpy`, `matplotlib`, `seaborn` e `scikit-learn`.

---

## 🧪 Etapas Realizadas

1. **Instalação das Bibliotecas**  
   Foram instaladas bibliotecas específicas como o PyCaret e YData Profiling para acelerar o processo.

2. **Importação e Carregamento dos Dados**  
   Os dados foram carregados e inspecionados para garantir sua qualidade antes da modelagem.

3. **Análise Exploratória Automatizada**  
   Utilizamos o YData Profiling para obter um diagnóstico completo do dataset.

4. **Configuração do Ambiente com PyCaret**  
   Preparamos os dados e definimos a variável-alvo usando o `setup()`.

5. **Comparação entre Modelos**  
   Aplicamos `compare_models()` para descobrir qual algoritmo se destacou em termos de performance.

6. **Avaliação do Modelo Final**  
   Métricas como matriz de confusão, F1-score, acurácia e curva ROC foram utilizadas para validar o desempenho.

7. **Interpretação do Modelo**  
   Analisamos a importância das variáveis usando técnicas como a permutação.

---

## 👨‍🏫 Relato Pessoal

O relatório pessoal incluso traz um resumo de todas essas etapas com uma linguagem mais leve e reflexiva. Nele, explicamos as decisões tomadas pelo grupo, o uso das ferramentas e os aprendizados obtidos ao longo do desenvolvimento do trabalho.

---

## 🚀 Como Executar

1. Clone ou baixe os arquivos do projeto.
2. Abra o arquivo `.ipynb` em um ambiente como o Jupyter Notebook ou Google Colab.
3. Execute as células em ordem para reproduzir o processo completo de análise e modelagem.

---

## 📌 Requisitos

- Python 3.7+
- Instalar bibliotecas com:  
  ```bash
  pip install pycaret ydata-profiling pandas numpy matplotlib seaborn scikit-learn
