# Estatística Descritiva Aplicada a Dados de Vendas de Supermercado

## Objetivo

O objetivo desse projeto é aplicar conceitos de estatística descritiva em uma base de dados de produtos de um supermercado localizado no Chile. Além disso, serão criados gráficos que auxiliam na visualização e discussão dos principais resultados obtidos.

O foco está em explorar as características das categorias de produtos, como média, mediana e desvio padrão, para identificar padrões e possíveis outliers. O projeto está dividido em 6 exercícios, cada um com seu respectivo enunciado e resolução apresentada logo abaixo.

## Dicionário de Variáveis

O dataframe utilizado neste projeto contém as seguintes colunas:

- **title**: Nome do produto.
- **Marca**: A marca do produto.
- **Preco_Normal**: Preço em que o produto costuma ser vendido quando não há desconto.
- **Preco_Desconto**: Preço do produto após o desconto ser aplicado.
- **Preco_Anterior**: Preço em que o produto era comercializado antes do desconto atual.
- **Desconto**: Total de desconto aplicado.
- **Categoria**: Categoria do produto.

> Observações:
- As entradas que apresentam valores de desconto igual a 0 indicam que o produto não teve desconto aplicado.
- As variáveis categóricas estão em espanhol, conforme a base de dados original.

## Bibliotecas Utilizadas

- `pandas`
- `matplotlib`
- `seaborn`
- `plotly.express`

## Conclusões

A análise estatística descritiva permitiu identificar assimetrias nos preços por categoria, com destaque para os **lácteos**, que apresentaram alta variação e possível presença de outliers.

Em relação aos descontos, **congelados** e **belleza-y-cuidado-personal** foram as categorias com os maiores valores médios, enquanto outras, como **frutas**, **instantaneos-y-sopas** e **verduras**, não apresentaram desconto.

A visualização de mapa interativo destacou as **marcas responsáveis pelos maiores descontos** em cada categoria, oferecendo uma visão útil para decisões comerciais futuras.

## Arquivos

- `estatistica_basica_supermercado.ipynb` - Notebook principal do projeto, que contém a análise estatística e visualizações.

## Autoria

**Graciela Rozza** - Projeto desenvolvido como parte dos estudos em **Ciência de Dados**, com foco em **visualização e exploração de dados com Python**.

## Licença

MIT