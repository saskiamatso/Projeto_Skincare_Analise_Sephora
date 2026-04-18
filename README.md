# Skincare de Luxo: Análise de Preços com Dados da Sephora

Análise exploratória de dados do catálogo de skincare da Sephora (EUA),
com foco nas marcas de maior preço médio e comparação com o mercado brasileiro.

## Objetivo

Identificar as marcas de skincare mais caras disponíveis na Sephora americana
e entender por que esse perfil de luxo difere do que é consumido no Brasil.

## Dataset

- **Fonte:** (https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data) - Kaggle
- **Extração:** Abril de 2026
- **Dados de Março de 2023**
- **Mercado de referência:** Estados Unidos (sephora.com)

## O que foi feito

- Carregamento e inspeção do dataset `product_info.csv`
- Filtragem de produtos da categoria Skincare, excluindo aparelhos e ferramentas
- Cálculo da média de preço por marca
- Visualização do Top 10 marcas mais caras com gráfico de barras horizontal

## Tecnologias utilizadas

- Python 3
- pandas
- matplotlib
- seaborn
- kagglehub
- Google Colab

## Como executar

1. Abra o arquivo `analise_skincare.ipynb` no Google Colab
2. Execute as células em ordem
3. O kagglehub fará o download automático do dataset

## Arquivos

| Arquivo | Descrição |
|---|---|
| `Projeto_Skincare_Analise_Sephora.ipynb` | Notebook com o código e o gráfico |
| `Projeto_Skincare_Analise_Sephora.md` | Análise textual comparando os mercados EUA e Brasil |
| `requirements.txt` | Bibliotecas utilizadas |

## Leitura complementar

O artigo [`Projeto_Skincare_Analise_Sephora.md`]([./artigo_mercado_luxo.md](https://github.com/saskiamatso/Projeto_Skincare_Analise_Sephora/blob/main/Projeto_Skincare_Analise_Sephora.md)) contextualiza
os resultados da análise com uma comparação entre o mercado americano e o
brasileiro, abordando barreiras regulatórias, perfil de consumo e o papel do Grey Market.

## Autora
Saskia Matoba

Estudante de Ciência de Dados — UNIVESP  
[LinkedIn](https://www.linkedin.com/in/saskia-matoba-/)
