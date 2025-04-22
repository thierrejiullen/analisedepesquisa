# Sistema de Consulta - Cruzamento de Leads e Pesquisa

Este repositório contém um sistema web para cruzamento e análise de dados de leads e pesquisas, com foco na identificação de criativos (utm_term) que trouxeram leads com melhores faixas de renda.

## Funcionalidades

- Upload e cruzamento de arquivos CSV
- Filtros avançados por UTM Term, faixa de renda, etc.
- Visualizações interativas (heatmap, gráficos de barras e pizza)
- Tabela detalhada com funcionalidades de filtro e exportação
- Tabela de criativos com maior número de leads com renda acima de R$2.000

## Como usar

1. Acesse o sistema através do link: [Sistema de Consulta](https://seu-usuario.github.io/nome-do-repositorio/)
2. Faça upload dos arquivos de leads e pesquisa (formato CSV)
3. Clique em "Cruzar Dados" para processar os arquivos
4. Use os filtros para refinar os resultados conforme necessário
5. Explore as visualizações e tabelas para análise dos dados
6. Baixe os resultados filtrados em formato CSV se necessário

## Requisitos dos arquivos

### Arquivo de Leads
- Deve conter colunas com informações de UTM (utm_term, utm_source, utm_medium, utm_campaign)
- Deve conter uma coluna de email para cruzamento com o arquivo de pesquisa

### Arquivo de Pesquisa
- Deve conter uma coluna com informações de faixa de renda
- Deve conter uma coluna de email para cruzamento com o arquivo de leads

## Tecnologias utilizadas

- HTML5, CSS3 e JavaScript
- Bootstrap 5 para estilização
- Plotly.js para visualizações interativas
- PapaParse para processamento de arquivos CSV

## Desenvolvimento

Este sistema foi desenvolvido como uma aplicação web estática, sem necessidade de servidor backend. Todo o processamento é realizado no navegador do cliente.
