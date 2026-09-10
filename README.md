# Simulador_Vendas_Xbox_Game_pass
Projeto desenvolvido como atividade prática de aprendizado em Excel, análise de dados e construção de dashboards, com foco na transformação de uma base de dados em informações visuais e análises úteis para tomada de decisão.
# 🎮 Xbox Game Pass – Análise de Vendas e Assinaturas

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático de **Excel**, com o objetivo de organizar, analisar e apresentar dados relacionados às assinaturas do **Xbox Game Pass**.

A solução utiliza uma base de dados de assinantes para gerar análises sobre planos, tipos de assinatura, renovação automática, produtos adicionais e valores das assinaturas.

O projeto também conta com uma área de **Dashboard**, desenvolvida para facilitar a visualização e interpretação dos principais resultados.

---

## 🎯 Objetivo

O objetivo do projeto é transformar uma base de dados de assinaturas em informações que possam auxiliar na análise do comportamento dos clientes e dos resultados de vendas.

Entre os principais pontos analisados estão:

- Tipos de planos contratados;
- Modalidades de assinatura;
- Renovação automática;
- Receita gerada pelas assinaturas;
- Adesão ao EA Play Season Pass;
- Adesão ao Minecraft Season Pass;
- Valores associados aos produtos adicionais;
- Distribuição dos resultados por plano.

---

## 📊 Estrutura do Projeto

O arquivo Excel está dividido em quatro abas principais:

### 🎨 Assets

A aba **Assets** reúne elementos visuais utilizados na construção da solução, como:

- Paleta de cores;
- Cores utilizadas na identidade visual;
- Elementos gráficos;
- Logos e ícones.

A organização desses elementos ajuda a manter uma identidade visual consistente no projeto.

---

### 🗃️ Bases

A aba **Bases** contém a principal base de dados utilizada nas análises.

Entre as informações disponíveis estão:

| Informação | Descrição |
|---|---|
| Subscriber ID | Identificação do assinante |
| Name | Nome do assinante |
| Plan | Plano contratado |
| Start Date | Data de início da assinatura |
| Auto Renewal | Indicação de renovação automática |
| Subscription Price | Valor da assinatura |
| Subscription Type | Modalidade da assinatura |
| EA Play Season Pass | Adesão ao EA Play |
| EA Play Season Pass Price | Valor do EA Play |
| Minecraft Season Pass | Adesão ao Minecraft Season Pass |
| Minecraft Season Pass Price | Valor do Minecraft Season Pass |
| Coupon Value | Valor de desconto |
| Total Value | Valor total da assinatura |

A base contém **295 registros de assinantes** e foi estruturada para permitir análises e consolidações por diferentes dimensões.

---

### 🧮 Cálculos

A aba **Cálculos** concentra as análises utilizadas para alimentar o projeto.

Foram utilizadas **Tabelas Dinâmicas** para consolidar informações e facilitar a análise dos dados.

Entre os cálculos realizados estão:

- Soma do valor total das assinaturas;
- Comparação de valores de acordo com a renovação automática;
- Análise da utilização do EA Play Season Pass por plano;
- Análise dos valores do Minecraft Season Pass por plano;
- Consolidação dos resultados gerais.

#### Exemplos de análises

Para assinaturas com renovação automática:

- **Renovação automática: Não:** 2.824
- **Renovação automática: Sim:** 747
- **Total:** 3.571

Também foram realizadas análises específicas dos produtos adicionais, como:

- **EA Play Season Pass:** 1.350 em valores consolidados;
- **Minecraft Season Pass:** 1.800 em valores consolidados.

---

### 📈 Dashboard

A aba **Dashboard** apresenta a visão visual do projeto, com o título:

> **XBOX GAME PASS SUBSCRIPTIONS SALES**

O objetivo do dashboard é transformar os dados consolidados em uma apresentação mais intuitiva, facilitando a interpretação das informações relacionadas às vendas e assinaturas.

---

## 🛠️ Recursos do Excel Utilizados

Durante o desenvolvimento do projeto foram aplicados recursos de análise e organização de dados, incluindo:

- **Tabelas estruturadas**
- **Tabelas Dinâmicas**
- **GETPIVOTDATA**
- **Fórmulas e cálculos**
- **Filtros**
- **Organização e tratamento de dados**
- **Formatação condicional e visual**
- **Dashboard**
- **Padronização de identidade visual**

---

## 🔎 Principais Análises

O projeto permite analisar diferentes aspectos da base de assinantes, como:

### Planos

Comparação entre os planos:

- Core
- Standard
- Ultimate

### Assinaturas

Análise das modalidades:

- Monthly
- Quarterly
- Annual

### Renovação automática

Avaliação dos assinantes que possuem ou não a opção de renovação automática.

### Produtos adicionais

Análise da adesão e dos valores relacionados a:

- EA Play Season Pass
- Minecraft Season Pass

Essas informações permitem uma visão mais ampla sobre o comportamento dos assinantes e sobre a composição do valor das assinaturas.

---

## 📚 Aprendizados

O desenvolvimento deste projeto permitiu aplicar conhecimentos de **Excel e análise de dados** em um cenário prático.

Entre os principais conhecimentos trabalhados estão:

- Organização de bases de dados;
- Estruturação de informações;
- Criação de Tabelas Dinâmicas;
- Análise e consolidação de dados;
- Utilização de fórmulas;
- Utilização da função GETPIVOTDATA;
- Construção de indicadores;
- Desenvolvimento de dashboards;
- Criação de uma apresentação visual orientada a dados.

---

## 📁 Estrutura do Repositório

```text
desafio-xbox/
│
├── README.md
└── desafio 3 - venda xbox.xlsx
