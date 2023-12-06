## Previsão de Precipitação Máxima Mensal utilizando Redes Neurais Recorrentes e Redes Convolutivas
Este repositório abriga um projeto de aprendizado de máquina focado na previsão da precipitação máxima mensal na região de Alto Merim Grajau, localizada no estado do Maranhão. Os dados históricos de 1950 a 2004 foram utilizados para desenvolver e comparar três modelos distintos: redes neurais convolutivas (CNNs), redes neurais recorrentes LSTM (Long Short-Term Memory) e GRU (Gated Recurrent Unit).

## Objetivo
O objetivo central deste projeto é desenvolver um modelo preciso capaz de realizar previsões confiáveis da precipitação máxima mensal. A abordagem adotada engloba a análise e comparação de diferentes arquiteturas de redes neurais, permitindo a identificação da mais eficaz para capturar os padrões temporais presentes nos dados climáticos.

## Resultados
Os modelos foram avaliados usando métricas de erro para determinar a precisão das previsões para a precipitação máxima mensal:

- LSTM (128 camadas): O erro médio foi de 28.48.
- Redes Neurais Convolutivas (CNNs - 256 camadas): O erro médio foi de 34.47.
- GRU (Gated Recurrent Unit - 256 camadas): O erro médio foi de 29.38.
Surpreendentemente, mesmo com uma estrutura mais enxuta de 128 camadas, o modelo LSTM demonstrou uma capacidade superior na captura de padrões sequenciais para prever a precipitação máxima mensal. Apesar das CNNs e GRU possuírem o dobro de camadas, o modelo LSTM mostrou-se mais eficaz na representação e previsão dos passos seguintes na série temporal.

Este resultado ressalta a capacidade única das LSTM em capturar e reter informações de longo prazo, isso a partir de decisões das portas de entrada e esquecimento na atualização con contexto, demonstrando um melhor desempenho na previsão da precipitação máxima mensal para a região de Alto Merim Grajau no período estudado.
