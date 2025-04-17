# Avalia-o-Integrada-part1
Parte 1: LOPAL

Contextualização:

Imagine que você tem 5 servidores em diferentes regiões da AWS, e está monitorando o uso de CPU de cada um a cada hora. Você coleta esses dados por 10 horas seguidas. O resultado pode ser representado como uma matriz:

Linhas: cada linha representa um registro de tempo (por exemplo, hora 1 até hora 10) Colunas: cada coluna representa um servidor ou região diferente Utilizando esse conceito desenvolva as próximas questões.

Considerando a matriz abaixo, crie um laço for para calcular a média de uso de CPU por linha e imprima os resultados com 2 casas decimais.

Crie uma função chamada alerta_uso que recebe como parâmetro uma lista com os valores de uso de CPU de uma região. A função deve retornar True se algum valor ultrapassar 85% de uso, e False caso contrário. Teste a função para todas as regiões da matriz.
Utilizando a biblioteca pandas, crie um DataFrame com os dados da matriz acima. Os nomes das linhas devem ser ["hora_1", "hora_2",..., "hora_10"] e as colunas representam as regiões ["us-east-1", "us-west-2", "eu-central-1", "sa-east-1", " ap-southeast-1" ].

Dentre as questões anteriores escolha uma delas para fazer uma leve explicação do seu funcionamento.

Escolhi a opção acima. Eu criei um DataFrame organizando os dados em uma matriz de listas, onde cada lista interna representa os valores para uma hora específica em cada região. Defini os nomes das linhas ("hora_1", "hora_2", ..., "hora_10") e das colunas (nomes das regiões). Depois, usei a função pd.DataFrame() para criar o DataFrame, passando a matriz de dados e os nomes das linhas e colunas.


