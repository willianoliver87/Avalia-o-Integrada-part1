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

Na realidade atual das empresas de tecnologia e análise de dados, é comum que dados e aplicações estejam distribuídos em ambientes de nuvem. O uso de plataformas como a AWS permite escalabilidade, disponibilidade e segurança.

Por sua vez, a linguagem Python é amplamente usada para: Automatizar tarefas administrativas, Processar grandes volumes de dados e Conectar aplicações locais a bancos de dados remotos

A integração entre Python e AWS RDS permite que scripts sejam escritos para ler e gravar dados diretamente em bancos SQL na nuvem.

A ABC Organization compra uma assinatura do Microsoft 365 para todos os seus funcionários. Qual modelo de serviço em nuvem a ABC Organization adotou? IAAS SAAS PAAS FAAS

SaaS.

Qual modelo de serviço de nuvem as máquinas virtuais EC2 da AWS representam? IAAS SAAS PAAS FAAS

IaaS.

(40) Crie um servidor de banco de dados MYSQL, utilizando algum serviço da AWS. Coloque abaixo o hostname, senha e usuário para acesso ao banco.
database-1.c21fjnvngsvf.us-east-1.rds.amazonaws.com

Crie um script para conexão com o banco de dados, e também a lógica para criação de um banco para receber a tabela do exercício da primeira seção.



