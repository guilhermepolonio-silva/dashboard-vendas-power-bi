# Dashboard de Vendas | Power BI

Projeto acadêmico desenvolvido na USCS para analisar vendas entre 2017 e 2019, utilizando Power BI e medidas DAX.

## Visão geral

![Dashboard de vendas](dashboard%20vendas%20bi.png)

## Objetivo

Transformar uma planilha de vendas em um relatório visual que permita acompanhar o faturamento, comparar marcas e identificar o produto com maior quantidade vendida.

## Análises disponíveis

- Faturamento total.
- Evolução anual do faturamento e da quantidade vendida.
- Comparação da quantidade vendida por marca.
- Distribuição do faturamento por localidade.
- Identificação dinâmica do produto mais vendido.

## Principais resultados

Na visão geral, sem filtros aplicados:

- Faturamento total de aproximadamente 64,17 milhões.
- 2018 apresentou o maior faturamento e a maior quantidade vendida entre os anos analisados.
- USCS liderou o volume de vendas entre as marcas da base.
- DVD M360 Preto foi o produto mais vendido, com 42.527 unidades.

Os resultados descrevem a base utilizada na atividade acadêmica.

## Ferramentas e conhecimentos aplicados

- Power BI Desktop.
- Importação de dados de planilha.
- Criação de medidas DAX.
- Gráficos de comparação e evolução temporal.
- Visualização geográfica.
- Organização de indicadores em um relatório.

## Lógica dos indicadores

**Faturamento total:** soma do preço unitário multiplicado pela quantidade vendida em cada registro, utilizando SUMX.

**Produto mais vendido:** classificação dos produtos pela soma das unidades vendidas, utilizando TOPN, ADDCOLUMNS e CALCULATE. CONCATENATEX retorna o nome do produto e permite exibir nomes empatados.

## Como visualizar

A imagem acima permite conhecer o painel sem instalar programas.

Para explorar o relatório:

1. Baixe o arquivo [dashboard-vendas.pbix](dashboard-vendas.pbix).
2. Abra o arquivo no Power BI Desktop.
3. Explore os gráficos e as medidas disponíveis.

O GitHub apresenta os arquivos e a documentação. A interação com o relatório ocorre no Power BI Desktop.

Para atualizar os dados, será necessário ter acesso à planilha de origem e ajustar seu caminho de conexão, caso seja diferente do computador em que o projeto foi criado.

## Autor

Guilherme Silva Polonio

Projeto acadêmico — USCS
