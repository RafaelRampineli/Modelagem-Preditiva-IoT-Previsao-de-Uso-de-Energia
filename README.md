# Modelagem-Preditiva-IoT-Previsao-de-Uso-de-Energia

Projeto Final 2 do Curso de Machine Learning da Formação Cientista de Dados fornecido pela Data Science Academy(DSA).

Este projeto de IoT tem como objetivo a criação de modelos preditivos para a previsão de consumo de energia de eletrodomésticos. Os dados utilizados incluem medições de sensores de temperatura e umidade de uma rede sem fio, previsão do tempo de uma estação de um aeroporto e uso de energia utilizada por luminárias.

Nesse projeto de aprendizado de máquina iremos realizar a filtragem de dados para remover parâmetros não-preditivos e selecionar os melhores recursos (melhores features) para previsão. 

O conjunto de dados foi coletado por um período de 10 minutos por cerca de 5 meses. As condições de temperatura e umidade da casa foram monitoradas com uma rede de sensores sem fio ZigBee.

Cada nó sem fio transmitia as condições de temperatura e umidade em torno de 3 min. Em seguida, a média dos dados foi calculada para períodos de 10 minutos. Os dados de energia foram registrados a cada 10 minutos com medidores de energia de barramento m. O tempo da estação meteorológica mais próxima do aeroporto (Aeroporto de Chievres, Bélgica) foi baixado de um conjunto de dados públicos do Reliable Prognosis (rp5.ru) e mesclado com os conjuntos de dados experimentais usando a coluna de data e hora. 

Duas variáveis aleatórias foram incluídas no conjunto de dados para testar os modelos de regressão e filtrar os atributos não preditivos (parâmetros).

O objetivo é construir um modelo preditivo que possa prever o consumo de energia com base nos dados de sensores IoT coletados.

Os datasets de treino e de teste estão em anexo.

# TO DO:

- Fazer o teste com outros Algoritmos;
- Implementar gráfico para acompanhamento da queda do erro durante o Gradient Boosting
