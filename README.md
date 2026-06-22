# FIAP - Challenge Sprint 2 | Machine Learning Modelling

Projeto acadêmico desenvolvido para a Challenge Sprint 2 da FIAP, com foco em Machine Learning aplicado à análise preditiva de risco em equipamentos agrícolas.

## Objetivo do projeto

O objetivo deste projeto é aplicar técnicas de Machine Learning para classificar equipamentos em situação de risco, utilizando dados de sensores como temperatura e umidade.

## Contexto

A Sompo propôs uma solução com inteligência artificial para prever riscos em equipamentos agrícolas. A plataforma deve integrar dados, gerar indicadores, alertas preventivos e recomendações operacionais, com o objetivo de reduzir sinistros, apoiar decisões e melhorar a produtividade.

## Descrição da solução

Neste notebook, foi criada uma base de dados simulada com leituras de sensores de equipamentos ao longo do tempo. A partir desses dados, foram realizadas etapas de preparação, análise exploratória e treinamento de um modelo de classificação.

O modelo utilizado foi uma Árvore de Decisão, com o objetivo de identificar equipamentos em situação de risco com base em variáveis operacionais.

## Etapas desenvolvidas

* Criação de dataset simulado
* Análise dos dados de temperatura e umidade
* Verificação de valores nulos e duplicados
* Preparação dos dados para modelagem
* Criação da variável de risco
* Separação entre treino e teste
* Treinamento de modelo de classificação
* Avaliação do modelo com métricas
* Visualização dos resultados

## Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

## Arquivo principal

```text
CS02_machine_Learning.ipynb
```

## Como executar

1. Clone este repositório.
2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Abra o notebook:

```text
CS02_machine_Learning.ipynb
```

4. Execute as células em ordem.

## Resultado esperado

O projeto demonstra como um modelo de Machine Learning pode apoiar a identificação de equipamentos com maior risco operacional, auxiliando na tomada de decisão preventiva.

## Autor

* Tiago Thomaz Cesaro - RM: 569374

## Instituição

FIAP - Faculdade de Informática e Administração Paulista
Curso: Inteligência Artificial
Challenge Sprint 2 - 2026
