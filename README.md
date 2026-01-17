# pandas × polars × PySpark --- Comparativo Prático

Este repositório contém um notebook de análise exploratória usando um
dataset sintético de varejo do Kaggle para comparar, na prática, como
executar as mesmas operações em **pandas, polars e PySpark**.

## 🎯 Objetivo

O objetivo principal é ajudar analistas e engenheiros de dados a:

-   Entender que o raciocínio é o mesmo, mesmo mudando a biblioteca\
-   Comparar sintaxes entre as três ferramentas\
-   Ver exemplos reais de uso em um mesmo dataset\
-   Desenvolver pensamento independente de engine

## 📂 Conteúdo do repositório

-   `notebook_pandas_polars_spark_retail.ipynb`\
    Notebook principal com análises equivalentes nas três bibliotecas.

## 📊 Dataset utilizado

Foi utilizado o dataset **RetailStoreProductSalesDataset.csv**, que
simula dados diários de varejo com variáveis como:

price, discount, promotion_intensity, footfall, ad_spend,
competitor_price, stock_level, weather_index, customer_sentiment e
return_rate.

O dataset possui 15.000 linhas e é totalmente sintético.

## 🔧 Como rodar o projeto

1.  Clone este repositório\

``` bash
git clone <URL_DO_SEU_REPO>
```

2.  Instale as dependências necessárias\

``` bash
pip install pandas polars pyspark jupyter
```

3.  Abra o notebook\

``` bash
jupyter notebook
```

4.  Execute as células na ordem.

## 🧠 O que você vai aprender

No notebook você verá exemplos de:

-   Somar colunas\
-   Filtrar dados\
-   Contar valores\
-   Contar distintos\
-   Agrupar e agregar\
-   Transformar colunas em linhas\
-   Estatísticas descritivas\
-   Criar novas colunas\
-   Remover colunas

Tudo isso feito em **pandas, polars e PySpark** lado a lado.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas.\
Sinta-se à vontade para abrir issues ou pull requests.
