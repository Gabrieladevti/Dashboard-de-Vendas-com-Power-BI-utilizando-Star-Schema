# Dashboard de Vendas com Power BI utilizando Star Schema

Este projeto apresenta um **dashboard de vendas interativo** desenvolvido no **Power BI**, utilizando o **Star Schema (Esquema Estrela)** como modelo de dados para garantir eficiência na análise e visualização.

## 📌 Objetivo

O objetivo deste projeto é demonstrar como construir um **relatório dinâmico de vendas**, permitindo análises detalhadas e insights estratégicos para melhorar a tomada de decisões empresariais.

## 📊 Funcionalidades

✔️ Relatórios interativos de vendas e lucros.  
✔️ Análise de desempenho por período, produto e região.  
✔️ Indicadores de KPI (Key Performance Indicators).  
✔️ Filtros dinâmicos para segmentação de dados.  
✔️ Gráficos e tabelas para facilitar a interpretação dos dados.  

## 📌 Modelagem de Dados - **Star Schema**  

O modelo de dados segue o **Esquema Estrela**, garantindo eficiência e desempenho nas consultas. Ele é composto por:

- **Tabela Fato** (`FatoVendas`): Contém as métricas de vendas, como quantidade vendida, receita e lucro.
- **Tabelas Dimensão**:
  - `DimProduto`: Informações sobre os produtos (nome, categoria, preço unitário, etc.).
  - `DimCliente`: Dados dos clientes (nome, localização, segmento, etc.).
  - `DimTempo`: Datas para análise temporal (ano, mês, trimestre, dia da semana, etc.).
  - `DimLoja`: Detalhes das lojas (localização, tipo, etc.).
  
Essa estrutura melhora a performance das consultas no Power BI e permite relacionamentos bem definidos entre as tabelas.

## 🛠️ Tecnologias Utilizadas  

- **Power BI** → Para a criação do dashboard e visualizações interativas.  
- **SQL / Power Query** → Para a modelagem e transformação de dados.  
- **DAX (Data Analysis Expressions)** → Para cálculos e métricas avançadas.  
- **Excel / CSV** → Fonte de dados simulada para alimentar o modelo.  
