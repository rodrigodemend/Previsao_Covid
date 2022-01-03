# Projeto de Previsão de Serie Temporal do Bootcamp de Data Science da Alura

Olá! Bem vindo ao meu repositório relativo ao projeto de previsão de series temporais do Bootcamp Data Science da Alura! Aqui, na pasta notebooks, estará uma analise e uma otimização dos principais parâmetros do Prophet! O objetivo do projeto é prever os novos casos de morte por Covid-19 em Santa Catarina. Abaixo detalherei melhor qual o escopo do projeto, quais dados serão utilizados e como será organizado o projeto.

# Os dados :game_die:

O conjunto de dados diz a respeito do número de novas mortes por Covid-19 de 25 de Fevereiro de 2020 até 20 de Dezembro de 2021.

Os dados foram obtidos através do [Brasil.IO](https://brasil.io/dataset/covid19/caso_full/) onde estão sendo disponibilizados boletins informativos sobre os casos do coronavírus. Afim de organizar melhor o projeto, os dados que utilizaremos foram importados e limpos neste [Notebook](https://github.com/rodrigodemend/Previsao_Covid/blob/main/Notebooks/Importação_e_Limpeza_dos_dados_de_Covid_19.ipynb/) que se encontra nesse mesmo repositório. 

# Como será feito 📈

Primeiramente iremos criar um modelo básico sem otimização alguma com o Prophet. Após isso vamos criar diversos experimentos onde vamos otimizar os principais parâmetros da tendência, sazonalidade, feriados e outliers do modelo. Chegando assim em um modelo com erro bem menor do que o modelo inicial.

# Resultados :dart:

Conseguimos otimizar o modelo e diminuir em mais de 3x as duas métricas que usamos de avaliação do modelo (MAE e RMSE). Com isso chegamos com um erro menor de 6 mortes por dia de previsão, portanto temos uma previsão confiável do número de mortes por Covid-19 em Santa Catarina nos próximos dias.

# Conclusões :memo:

Através de melhores estudos e aperfeiçoamento dos parâmetros, é possível encontrar modelos muitos precisos. Neste caso conseguimos otimizar bem, porém acredito que ainda exista um grande campo de otimização desse modelo para que consiga prever as mortes por Covid-19 com cada vez mais eficiência.

Link para o [Notebook](https://github.com/rodrigodemend/Previsao_Covid/blob/main/Notebooks/Previsão_de_Series_Temporais_usando_Prophet.ipynb) do projeto.
