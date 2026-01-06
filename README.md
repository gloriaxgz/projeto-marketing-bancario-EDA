# Análise de Campanha de Marketing Bancário

Este projeto consiste em uma **Análise Exploratória de Dados (EDA)** aplicada a uma campanha de marketing bancário realizada por um banco português, cujo objetivo é compreender **quais fatores influenciam a adesão de clientes a um depósito a prazo** promovido por meio de contatos telefônicos.

O foco do projeto é **transformar dados operacionais e demográficos em insights acionáveis**, capazes de apoiar decisões estratégicas de marketing, segmentação de clientes e otimização de campanhas.

---

## TL;DR (RESUMO)

- Análise exploratória de uma **campanha de marketing telefônico bancário**, com foco na adesão a depósitos a prazo.
- Investigação de fatores **demográficos, profissionais, comportamentais e econômicos** que influenciam a resposta do cliente.
- Identificação de padrões relacionados a **idade, profissão, escolaridade, histórico de contato e duração das chamadas**.
- Avaliação do impacto de **variáveis macroeconômicas** (taxa de juros, índice de emprego, inflação).
- Geração de **insights estratégicos** para aumentar a taxa de conversão e reduzir contatos ineficientes.
- Ênfase em **visualização clara e comunicação de resultados**, seguindo princípios de storytelling com dados.
- Dashboard analítico em **Power BI** consolidando métricas de conversão, perfil dos clientes e desempenho temporal da campanha.
- Visualizações orientadas à decisão para identificar **perfis com maior propensão à adesão** e **períodos mais eficientes** para contato.

---
## Estrutura do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| `analise-marketing-bancario.ipynb` | Notebook principal do projeto. Contém toda a EDA, visualizações, análise de variáveis e interpretação dos resultados. |
| `Dashboard.pdf` | Visualização de dados realizada no PowerBI, visando trazer insights importantes e que gerem ações para benefício da empresa. |
| `README.md` | Documentação do projeto, descrição do problema, metodologia e principais insights. |

---

## Contexto do Problema

Campanhas de marketing bancário via telefone possuem **alto custo operacional** e, quando mal direcionadas, resultam em baixas taxas de conversão e desgaste na relação com o cliente.

O desafio central é entender:

> **Quais perfis de clientes e quais características da abordagem aumentam a probabilidade de adesão ao produto financeiro?**

Responder a essa pergunta permite:
- Direcionar campanhas para públicos com maior propensão
- Reduzir chamadas improdutivas
- Otimizar tempo, custo e estratégia comercial

---

## Objetivos do Projeto

Os principais objetivos da análise são:

- Analisar o perfil **demográfico e profissional** dos clientes
- Avaliar o impacto do **histórico de contatos** (frequência, duração, período)
- Investigar a influência de **variáveis econômicas externas**
- Identificar **padrões comportamentais** associados à resposta positiva
- Comunicar os resultados por meio de **visualizações claras e interpretáveis**
- Propor **hipóteses e estratégias** baseadas nos dados

---

## Dashboard de Conversão – Campanha de Marketing Bancário

Como etapa final do projeto, foi desenvolvido um **dashboard analítico em Power BI** com o objetivo de consolidar os principais achados da análise exploratória e **facilitar a tomada de decisão por equipes de marketing e negócios**.

O painel foi construído seguindo princípios de *Storytelling with Data*, priorizando:
- Clareza visual
- Hierarquia da informação
- Destaque para padrões relevantes
- Comunicação orientada à decisão, e não apenas à métrica

### Visão Geral do Painel

O dashboard apresenta uma visão integrada da performance da campanha, combinando **indicadores de volume, conversão e perfil dos clientes**, permitindo responder rapidamente à pergunta:

> **Quem converte mais, em que contexto e sob quais condições?**

---
## Caracterísitcas abordadas no Dashboard:

- Indicadores-Chave (KPIs)
- Análise Temporal da Conversão
- Impacto do Histórico de Contato
- Perfil Profissional e Conversão
- Situação Financeira e Endividamento
- Estado Civil e Propensão ao Crédito


---

### Objetivo do Dashboard

O painel foi desenvolvido para:

- Apoiar **decisões estratégicas de marketing**
- Identificar **perfis prioritários de clientes**
- Otimizar o **timing e o público-alvo** das campanhas
- Reduzir custos com contatos de baixa conversão
- Transformar análises exploratórias em **insights operacionais**

Em conjunto com o notebook de EDA, o dashboard demonstra como **dados podem ser traduzidos em decisões práticas**, reforçando o valor analítico do projeto mesmo sem a aplicação direta de modelos preditivos.

---

## Sobre o Dataset

O dataset representa uma campanha real de marketing bancário e contém informações como:

- **Dados demográficos:** idade, estado civil, escolaridade
- **Dados profissionais:** profissão, tipo de emprego
- **Histórico de campanha:** número de contatos, duração das chamadas, dia da semana, mês
- **Variáveis financeiras e econômicas:** taxa de juros, índice de emprego, inflação
- **Variável alvo:** adesão (`yes` / `no`) ao depósito a prazo

A variável alvo indica se o cliente **aceitou ou não** a oferta do produto financeiro.

---

## Metodologia de Análise

O projeto segue uma abordagem estruturada de **Análise Exploratória de Dados (EDA)**:

### 1. Compreensão e Limpeza dos Dados
- Análise de tipos de variáveis
- Verificação de valores ausentes
- Padronização de categorias

### 2. Análise Univariada
- Distribuição de idade, profissões e escolaridade
- Proporção de adesão ao produto

### 3. Análise Bivariada
- Relação entre variáveis demográficas e adesão
- Impacto da duração das chamadas na resposta
- Influência do número de contatos prévios

### 4. Análise de Variáveis Econômicas
- Avaliação do efeito da taxa de juros e indicadores macroeconômicos
- Comparação de períodos econômicos distintos

### 5. Visualização dos Dados
- Gráficos de barras, histogramas e comparações proporcionais
- Foco em clareza, simplicidade e leitura rápida dos resultados

---

## Principais Insights

Alguns padrões importantes identificados na análise incluem:

- **Duração da chamada é um fator crítico:** Chamadas mais longas apresentam maior taxa de adesão, sugerindo maior engajamento do cliente.
- **Idade influencia a decisão:** Certas faixas etárias demonstram maior propensão à adesão ao depósito a prazo.
- **Profissão e escolaridade importam:** Perfis profissionais mais estáveis tendem a apresentar maior resposta positiva.
- **Excesso de contatos reduz eficácia:** Múltiplas tentativas podem gerar desgaste e diminuir a chance de conversão.
- **Cenário econômico impacta o resultado:** Períodos com taxas de juros mais atrativas aumentam a aceitação do produto.

Esses resultados reforçam que **o sucesso da campanha não depende de um único fator**, mas da combinação entre perfil do cliente, abordagem e contexto econômico.

---

## Storytelling e Comunicação dos Resultados

A análise foi conduzida com foco em **storytelling com dados**, priorizando:

- Gráficos que respondem perguntas claras
- Redução de ruído visual
- Destaque para diferenças relevantes entre grupos
- Títulos que comunicam conclusões, não apenas métricas

O objetivo não é apenas analisar os dados, mas **traduzir os achados em decisões práticas** para equipes de marketing e negócios.

---


## Conclusão

Este projeto demonstra como a **análise exploratória de dados** pode revelar padrões valiosos em campanhas de marketing, permitindo decisões mais informadas e estratégicas.

Ao entender melhor **quem abordar, quando e como**, instituições financeiras podem:
- Aumentar a taxa de conversão
- Reduzir custos operacionais
- Melhorar a experiência do cliente

O projeto reforça o papel dos dados como **ferramenta central de apoio à decisão**, mesmo antes da aplicação de modelos preditivos mais complexos.
