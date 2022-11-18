#Pix2PIX

A pasta 'normal T1' possui os dados de treino, validação e teste com relação a transformação de séries temporais em imagens sem considerar a ordem espaço-temporal já a pasta 'por data T2'  possui os dados de treino, validação e teste com relação a transformação  proposta de séries temporais em imagens considerando a ordem espaço-temporal.
A pasta 'por janelas' possui csv's dos janelamentos contendo em colunas as imputações de todos os métodos bem como da rede Pix2Pix e o valor real.
A pasta 'por dataset' possui csv's por dataset contendo em colunas as imputações de todos os métodos bem como da rede Pix2Pix e o valor real.
A psta 'metricas' possui csv's contendo o MAE , RMSE e ASMAPE de cada método em cada dataset bem como da rede Pix2Pix.
O arquivo Pix2Pix.ipynb comtem o código da rede bem como o código dos métodos de imputação. Esse arquivo asta configurando para uso no https://www.kaggle.com/. Os resultados podem variar conforme a inicialização dos pesos e tempo de treino, podendo apresentar desempenho melhor em datasets diferentes do apresentado no artigo, contudo matém a proporção de superioridade em 50% dos datasets. Os valores de  MAE , RMSE e ASMAPE também podem variar devido a natureza aletória do treino da rede.
