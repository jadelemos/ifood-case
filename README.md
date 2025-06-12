# Case técnico IFood

# Instruções:
1) Instale as bibliotecas descritas no arquivo `requirements.txt`. Para instalar elas rapidamente, use o comando `pip install -r requirements.txt` 
2) Execute o notebook `1_data_processing.ipynb` localizado na pasta `/notebooks`. Ele irá realizar a leitura dos dados `raw`, realizar o processamento necessário e gerar a base de dados `data_processed.json` na pasta `data/processed/` para ser utilizada na modelagem.
3) Execute o notebook `2_modeling.ipynb` localizado na pasta `/notebooks`. Ele irá ler os dados processados na pasta `raw`, realizar as etapas de preparação dos dados, treinar o sistema de classificação e gerar os resultados. O notebook também irá salvar os resultados obtidos em `data/processed/resultados_modelo.csv' para fácil conferência no futuro.
