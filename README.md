GRUPO:

André Ayello de Nobrega RM561754

André Gouveia de Lima RM564219

Caio Castelão Carminato RM563630

Guilherme Vasques Tamai RM563276

Mirella Mascarenhas RM562092

Vitor Komura de Freitas RM563694

---------------------------------------------------------------------------------------------

INSTRUÇÕES DA ENTREGA:

A atividade pode ser desenvolvida em grupo

Apenas um integrante submete o arquivo

Enviar apenas o link do repositório. Não envie arquivos .txt ou .pdf

---------------------------------------------------------------------------------------------

LINK COLAB COM OS EXERCÍCIOS EM PYTHON:

https://colab.research.google.com/drive/1ECeFvDkoqQKuO175yY6xveR58AHNTiwI?usp=sharing

---------------------------------------------------------------------------------------------
---Informações do Dataset Appliances Energy Prediction:---

VISÃO GERAL DO DATASET: Dados experimentais usados ​​para criar modelos de regressão do uso de energia de aparelhos em um edifício de baixo consumo de energia.

TAMANHO DO DATASET: O dataset tem 19735 linhas e 29 colunas.

INFORMAÇÕES DAS COLUNAS: 
- date: time year-month-day hour:minute:second 
- Appliances: uso da energia em Wh
- lights: energia usada pelas luzes da casa em Wh
- T1: Temperature na cozinha, em Celsius
- RH_1: Umidade na área da cozinha, em %
- T2: Temperatura na sala de estar, em Celsius
- RH_2: Umidade na sala de estar, em %
- T3: Temperatura na lavanderia, em Celsius
- RH_3: Umidade na lavanderia, em %
- T4: Temperatura no escritório, em Celsius
- RH_4: Umidade no escritório, em %
- T5: Temperatura no banheiro, em Celsius
- RH_5: Umidade no banheiro, em %
- T6: Temperatura fora do prédio (lado norte), em Celsius
- RH_6: Umidade fora do prédio (lado norte), em %
- T7: Temperatura na sala de passar roupa, em Celsius
- RH_7: Umidade na sala de passar roupa, em %
- T8: Temperatura no quarto do adolescente 2, em Celsius
- RH_8: Umidade no quarto do adolescente 2, em %
- T9: Temperatura no quarto dos pais, em Celsius
- RH_9: Umidade no quarto dos pais, em %
- To: Temperatura externa (da estação meteorológica de Chievres), em Celsius
- Pressure (from Chievres weather station): Pressão (da estação meteorológica de Chievres), em mm Hg
- RH_out: Umidade externa (da estação meteorológica de Chievres), em %
- Wind speed (from Chievres weather station): Velocidade do vento (da estação meteorológica de Chievres), em m/s
- Visibility (da estação meteorológica de Chievres): Visibilidade, em km
- Tdewpoint (da estação meteorológica de Chievres): Ponto de orvalho, em °C
- rv1: Variável aleatória 1, adimensional
- rv2: Variável aleatória 2, adimensional

VALORES FALTANDO: zero.

-----------------------------------------------------------------------------------------------
---Informações do Dataset Smart Grid Stability:---

VISÃO GERAL DO DATASET: O dataset corresponde a uma versão aumentada do dataset "Electrical Grid Stability Simulated Dataset".

TAMANHO DO DATASET: O dataset possui 60.000 linhas e 14 colunas.

INFORMAÇÕES DAS COLUNAS: 
- tau1:	Tempo de reação - Produtor de Energia
- tau2:	Tempo de reação - Consumidor 1
- tau3:	Tempo de reação - Consumidor 2
- tau4:	Tempo de reação - Consumidor 3
- p1:	Power balance -  Produtor de Energia
- p2: Power balance -  Consumidor 1
- p3:	Power balance -  Consumidor 2
- p4:	Power balance -  Consumidor 3
- g1:	Elasticidade do preço coeficiente (gamma) - Produtor de Energia
- g2:	Elasticidade do preço coeficiente (gamma) - Consumidor 1
- g3:	Elasticidade do preço coeficiente (gamma) - Consumidor 2
- g4:	Elasticidade do preço coeficiente (gamma) - Consumidor 3
- stab:	classificações de estabilidade
- stabf:	classificações de estabilidade

VALORES FALTANDO: zero.

-----------------------------------------------------------------------------------------------
---Informações do Dataset Solar Radiation Prediction:---

VISÃO GERAL DO DATASET: Dados meteorológicos da HI-SEAS weather station de setembro de 2016 a dezembro de 2016.

TAMANHO DO DATASET: O dataset tem 32686 linhas e 11 colunas.

INFORMAÇÕES DAS COLUNAS: 
- Solar radiation: Watts por metro^2
- Temperature: Graus Fahrenheit
- Humidity: Percentual
- Barometric pressure: Hg
- Wind direction: Graus
- Wind speed: Milhas por hora
- Sunrise/sunset: Horário do Hawaii 

VARIÁVEL-ALVO: A variável-alvo (Radiation_Class) foi criada usando a mediana da coluna 'Radiation' como limiar, onde 1 = Alta Radiação e 0 = Baixa Radiação

-----------------------------------------------------------------------------------------------
---Informações do Dataset Wind Turbine Scada:---

VISÃO GERAL DO DATASET: É um conjunto de dados obtido de um sistema SCADA (Supervisory Control And Data Acquisition) de uma turbina eólica em operação na Turquia. Ele contém medições em intervalos de 10 minutos de parâmetros operacionais cruciais, como velocidade e direção do vento, e a potência gerada.

TAMANHO DO DATASET: O dataset possui aproximadamente 50.530 observações.

INFORMAÇÕES DAS COLUNAS: 
- Date/Time: A data e hora da medição (intervalos de 10 minutos).
- LV ActivePower (kW): A potência ativa gerada pela turbina em quilowatts (kW).
- Wind Speed (m/s): A velocidade do vento em metros por segundo (m/s).
- Theoretical_Power_Curve (KWh): A curva de potência teórica que a turbina deve gerar com a velocidade do vento correspondente, fornecida pelo fabricante.
- Wind Direction (°): A direção do vento em graus (°).

VARIÁVEL-ALVO: A variável-alvo é a LV ActivePower (kW), que representa a potência ativa gerada pela turbina.
