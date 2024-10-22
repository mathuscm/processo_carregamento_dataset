# Processo Carregamento Dataset

## VERIFICAR QUAIS ARQUIVOS SERÃO ESSENCIAIS PARA RESPONDER A QUESTÃO:
- Para abrir um e-commerce de um produto x estamos analisando o ticket médio de compra das pessoas e qual região do brasil
- compra mais de comercios digitais. A justificativa desta investigação é que iremos direcionar nossas propagandas patrocinadas
- para a região que - primeiramente compra mais do mercado digital; em segundo, possui ticket médio adequado ao nosso produto: saúde, beleza, cosméticos


## Quais tabelas serão utilizadas?

'''
1. olist_customers_dataset.csv --> costumer_id, customer_zip_code_prefix
2. olist_geolocation_dataset.csv --> zip_code_prefix
3. olist_order_items_dataset.csv --> order_id, product_id
4. olist_products_dataset.csv --> product_id
5. product_category_name_translation.csv --> utilizado apenas para verificar o ranking do nosso produto (a escolher)
'''

## Nota Geral

Para a execução do arquivo _projeto_ada.ipynb_, é necessário executar a seguinte linha (caso não tenha instalado previamente):

_pip install fastparquet_

Obs.: é possível instalar também o _pyarrow_ no lugar do _fastparquet_. Além disso, após a instalação de uma dessas bibliotecas não é necessário chamar durante a execução, basta baixar uma vez e rodar o projeto.

