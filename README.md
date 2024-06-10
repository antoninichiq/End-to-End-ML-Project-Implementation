# Modelo de Predição do Índice de Tempo de Incêndio (FWI) para Incêndios Florestais na Argélia
Este repositório contém um modelo de aprendizado de máquina treinado para prever o Índice de Tempo de Incêndio (FWI) com base em dados meteorológicos da Argélia. O modelo foi treinado utilizando um algoritmo de regressão Ridge e os dados do conjunto de dados "Algerian Forest Fires Dataset".
## Descrição do Conjunto de Dados
O conjunto de dados usado para treinar o modelo contém as seguintes variáveis:
  - Temp: Temperatura máxima diária em graus Celsius (22 a 42).
  - RH: Umidade relativa em porcentagem (21 a 90).
  - Ws: Velocidade do vento em km/h (6 a 29).
  - Rain: Precipitação total diária em mm (0 a 16,8).
  - FFMC: Índice Fine Fuel Moisture Code do sistema FWI (28,6 a 92,5).
  - DMC: Índice Duff Moisture Code do sistema FWI (1,1 a 65,9).
  - ISI: Índice Initial Spread Index do sistema FWI (0 a 18,5).
  - FWI: Índice de Tempo de Incêndio (0 a 31,1). **(Variável alvo)**
## Como Usar
  1. Clone o repositório: git clone https://github.com/antoninichiq/End-to-End-ML-Project-Implementation.git
  2. Instale as dependências: pip install -r requirements.txt
  3. Utilize o script ``application.py`` como guia para carregar o modelo e fazer previsões.
## Observações
O modelo foi treinado com dados específicos da Argélia e seu desempenho pode variar para outras regiões.
É importante lembrar que este modelo serve como ferramenta auxiliar e não substitui a avaliação profissional de risco de incêndio.
