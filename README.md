# Avalia-o-Integrada-part1
Parte 1: LOPAL

Contextualização:

Imagine que você tem 5 servidores em diferentes regiões da AWS, e está monitorando o uso de CPU de cada um a cada hora. Você coleta esses dados por 10 horas seguidas. O resultado pode ser representado como uma matriz:

Linhas: cada linha representa um registro de tempo (por exemplo, hora 1 até hora 10) Colunas: cada coluna representa um servidor ou região diferente Utilizando esse conceito desenvolva as próximas questões.

Considerando a matriz abaixo, crie um laço for para calcular a média de uso de CPU por linha e imprima os resultados com 2 casas decimais.

Crie uma função chamada alerta_uso que recebe como parâmetro uma lista com os valores de uso de CPU de uma região. A função deve retornar True se algum valor ultrapassar 85% de uso, e False caso contrário. Teste a função para todas as regiões da matriz.


