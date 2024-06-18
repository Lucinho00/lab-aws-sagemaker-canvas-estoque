# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Projeto de Previsão de Estoque Inteligente na AWS com SageMaker Canvas
Este projeto tem como objetivo utilizar o AWS SageMaker Canvas para criar um modelo de previsão de estoque, passando pelas etapas de seleção de dataset, construção e treinamento do modelo, análise de resultados e uso do modelo para previsões.

1. Selecionar Dataset
Navegar até a pasta datasets:

Acesse a pasta de datasets no repositório designado. Este repositório contém os datasets que você poderá escolher para treinar e testar seu modelo de machine learning.
Exemplo de datasets que você pode encontrar: histórico de vendas, inventário, demanda de produtos, etc.
Escolher o dataset:

Selecione o dataset que será usado para o treinamento do modelo de previsão de estoque. Por exemplo, um dataset com colunas como data, produto_id, vendas, estoque_atual, etc.
Fazer o upload do dataset no SageMaker Canvas:

No SageMaker Canvas, navegue até a seção de importação de dados.
Faça o upload do dataset selecionado.
2. Construir/Treinar
Importar o dataset:

No SageMaker Canvas, importe o dataset que você fez upload.
Configurar variáveis:

Defina as variáveis de entrada (features) e a variável de saída (target). Por exemplo:
Variáveis de entrada: data, produto_id, estoque_atual
Variável de saída: vendas
Iniciar o treinamento do modelo:

Configure os parâmetros de treinamento conforme necessário.
Inicie o treinamento do modelo. O tempo de treinamento pode variar dependendo do tamanho do dataset.
3. Analisar
Examinar as métricas de performance:

Após o treinamento, revise as métricas de performance do modelo, como precisão, erro quadrático médio, etc.
Verificar as principais características:

Analise as características mais importantes que influenciam as previsões, por exemplo, sazonalidade, promoções, etc.
Ajustes e re-treinamento:

Se necessário, ajuste os parâmetros do modelo ou modifique as variáveis de entrada e re-treine o modelo até obter um desempenho satisfatório.
4. Prever
Usar o modelo para previsões:

Utilize o modelo treinado para fazer previsões de estoque futuros.
Exportar e analisar os resultados:

Exporte os resultados das previsões para análise adicional.
Analise as previsões geradas, comparando com dados reais, se disponíveis.
Documentar conclusões:

Documente suas conclusões e qualquer insight obtido a partir das previsões, como tendências de demanda, períodos de alta e baixa no estoque, etc.
Exemplo de Implementação
Seleção do Dataset
Suponha que você tenha um dataset chamado historico_vendas.csv com as seguintes colunas:

data: Data da venda
produto_id: Identificador do produto
vendas: Número de unidades vendidas
estoque_atual: Quantidade atual em estoque
Construção e Treinamento do Modelo
Upload do Dataset:

Navegue até a seção de importação no SageMaker Canvas e faça o upload de historico_vendas.csv.
Configuração das Variáveis:

Variáveis de entrada: data, produto_id, estoque_atual
Variável de saída: vendas
Início do Treinamento:

Inicie o processo de treinamento no SageMaker Canvas. Aguarde até a conclusão.
Análise do Modelo
Métricas de Performance:

Examine métricas como erro absoluto médio (MAE), erro quadrático médio (RMSE), etc.
Ajustes Necessários:

Se a precisão não estiver satisfatória, ajuste as variáveis de entrada e parâmetros e re-treine o modelo.
Previsões e Conclusões
Previsões:

Utilize o modelo treinado para prever as vendas futuras e, consequentemente, o estoque necessário.
Análise dos Resultados:

Exporte as previsões e compare com os dados reais para validar o modelo.
Documentação:

Documente os insights obtidos, como períodos de maior demanda e sugestões para otimização de estoque.
