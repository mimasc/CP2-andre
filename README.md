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
---Informações do Dataset Wind Turbine Scada Dataset:---

VISÃO GERAL DO DATASET: É um conjunto de dados obtido de um sistema SCADA (Supervisory Control And Data Acquisition) de uma turbina eólica em operação na Turquia. Ele contém medições em intervalos de 10 minutos de parâmetros operacionais cruciais, como velocidade e direção do vento, e a potência gerada.

TAMANHO DO DATASET: O dataset possui aproximadamente 50.530 observações.

INFORMAÇÕES DAS COLUNAS: 
- Date/Time: A data e hora da medição (intervalos de 10 minutos).
- LV ActivePower (kW): A potência ativa gerada pela turbina em quilowatts (kW).
- Wind Speed (m/s): A velocidade do vento em metros por segundo (m/s).
- Theoretical_Power_Curve (KWh): A curva de potência teórica que a turbina deve gerar com a velocidade do vento correspondente, fornecida pelo fabricante.
- Wind Direction (°): A direção do vento em graus (°).

VARIÁVEL-ALVO: A variável-alvo é a LV ActivePower (kW), que representa a potência ativa gerada pela turbina.
