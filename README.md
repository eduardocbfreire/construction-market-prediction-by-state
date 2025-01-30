# Construction Market Prediction by State

Este projeto tem como objetivo analisar e prever o crescimento do mercado de construção civil no Brasil, considerando o crescimento populacional do público potencial e a relação entre a população e o número de empresas do setor em cada estado.

## Sobre o Projeto

A análise foi baseada em dados extraídos do site da Sidra, para obter informações sobre o mercado de construção, e do site do IBGE, para acessar os dados populacionais. O estudo se fundamenta na premissa de que a faixa etária predominante do consumidor desse mercado, cerca de 50%, está entre 38 e 58 anos, conforme apontado pela SCOD Brasil.

## Objetivos

- **Predição do crescimento do mercado:** Estimar o crescimento do número de empresas no setor de construção por estado, com base na evolução da população potencial consumidora.
- **Análise de Saturação do Mercado:** Identificar quais estados possuem mercados mais saturados ou com maior potencial de crescimento, utilizando a proporção de população por empresa do setor.

## Abordagem

O trabalho envolveu coleta, tratamento e análise dos dados, utilizando métodos estatísticos e de machine learning:

1. **Coleta de Dados**
   - Request ao banco de dados da Sidra para obter informações do setor de construção.
   - Uso de arquivos do IBGE para acessar os dados populacionais por estado.*
     * Esse arquivo encontra-se no repositório

2. **Tratamento e Exploração**
   - Limpeza e transformação dos dados para padronização.
   - Cálculo da proporção população/empresa para avaliar a saturação do mercado.

3. **Modelagem Preditiva**
   - Utilização do modelo **RandomForestRegressor** para prever o crescimento do mercado por estado.
   - Uso do **Z-Score** para identificar estados mais saturados e com maior potencial de crescimento.

## Ferramentas Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy e Scikit-learn
- **Processos:** Coleta de dados, análise exploratória, machine learning, visualização de dados

## Resultados

Os resultados foram organizados de forma a apresentar insights sobre o estado atual do mercado de construção em cada região do Brasil, destacando oportunidades para expansão e possíveis riscos de superaquecimento do setor em estados saturados.

