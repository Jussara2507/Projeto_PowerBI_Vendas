# Projeto_PowerBI_Vendas
Desafio Plataforma DIO Power BI com tratamento em DAX
# 📊 Relatório de Análise de Vendas (Power BI)

Este repositório contém um projeto completo de Business Intelligence desenvolvido no Power BI, abrangendo desde o tratamento de dados no Power Query, modelagem dimensional, criação de medidas em DAX, até o design final e refinamento estético do painel.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Power BI Desktop:** Modelagem de dados, DAX e construção de visuais.
* **Power Query:** Limpeza, transformação e tratamento inicial das tabelas.
* **GitHub:** Versionamento e hospedagem do código/projeto.

---

## 🏗️ Estrutura do Projeto e Modelagem
O painel foi construído seguindo boas práticas de modelagem de dados:
1. **Tabela Fato (`F_Vendas`):** Contém os registros transacionais de vendas, conectando métricas como *Sales* e *COGS*.
2. **Tabela Dimensão de Produtos (`D_Produtos`):** Armazena os atributos e dados consolidados dos produtos.
3. **Tabela Calendário (`D_Calendario`):** Criada via DAX para estruturar a dimensão temporal, estabelecendo um relacionamento de 1 para N (1:N) com a tabela fato na coluna de data.

---

## 📈 Principais Indicadores e Visuais do Painel
* **KPI / Cartão de Resumo:** Exibição do valor total de vendas (`Sales`) com layout limpo e integrado.
* **Filtro de Segmentação de Dados:** Permite filtrar o relatório de forma dinâmica por `Mês/Ano`.
* **Gráfico de Colunas:** Análise comparativa de vendas por produto (`Product`).
* **Gráfico de Linhas:** Acompanhamento da evolução temporal das vendas ao longo dos meses.

---

## 📂 Arquivos no Repositório
* `Relatorio_Vendas_Dax.pbix`: Arquivo principal do Power BI contendo o relatório, modelo e visuais.
* Bases de dados e planilhas de suporte utilizadas no projeto.

---
*Desenvolvido por Jussara Ferreira dos Santos.*
