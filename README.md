# Regressão: Previsão de séries temporais com Prophet 

Conhecendo o projeto
Neste curso, desenvolveremos um projeto para uma empresa de consultoria ambiental que deseja ter um modelo capaz de prever os valores de um poluente atmosférico nos próximos meses. Além de criar e validar um modelo, criaremos uma aplicação web que permitirá à pessoa usuária fazer uma previsão com esse modelo.

A aplicação servirá para prever os níveis de ozônio utilizando a biblioteca Prophet. Na página inicial dela, temos uma descrição do projeto, de como ele foi feito e qual é o erro do modelo, além de um campo para inserir o número de dias para fazer a previsão.

Para adicionar um período de previsão de 60 dias, inserimos esse número no campo, e pressionamos um botão abaixo dele para realizar a previsão. Após clicar nesse botão, o modelo vai trabalhar internamente e criar a previsão.

O resultado será um gráfico interativo que contém a série temporal e os novos valores previstos pelo modelo. Além desse gráfico interativo, também conseguiremos acessar uma tabela que contém os valores de previsão - neste caso, para 60 dias.

A tabela contém a data, o dia, o mês, o ano e a concentração do ozônio em microgramas por metros cúbicos. Inclusive, é possível baixá-la no formato CSV, clicando em um botão abaixo dela.

Para contextualizar, trabalharemos com poluentes atmosféricos, um grande problema, tanto para a saúde física quanto para o meio ambiente. Um desses poluentes é o ozônio atmosférico, formado a partir de poluentes secundários, que são emitidos pela fumaça dos carros e das indústrias, em conjunto com a radiação solar.

Este poluente pode ser prejudicial para a saúde física - especialmente para o sistema respiratório - e para a produção agrícola. Portanto, a ideia é pensar em como resolver esse problema ambiental e em políticas ambientais para melhorar essa situação.

Para isso, precisamos entender como está a concentração de ozônio ao longo do tempo. Uma empresa de consultoria ambiental nos contratou, como cientistas de dados, para criar um modelo preditivo que consiga prever a quantidade de ozônio que será liberada e qual será a concentração diária nos próximos meses, para nos antecipar e nos preparar em relação ao futuro.

Além disso, essa empresa solicitou que criássemos uma aplicação web, na qual poderemos inserir o número de dias para os quais queremos fazer a previsão do ozônio diário, e essa previsão é feita. Teremos um gráfico mostrando esses valores de ozônio diários e uma tabela que mostrará o valor de ozônio para os próximos meses. Ainda poderemos fazer o download dessa tabela e usá-la para análises futuras e tomada de decisões.