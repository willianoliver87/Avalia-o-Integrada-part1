# Avaliação Integrada - README

## 📌 Descrição da Prova

Este repositório contém os arquivos e informações referentes à **Avaliação Integrada**, aplicada como parte do conteúdo da disciplina ministrada pelo professor **Julio Favero Miranda**.

O objetivo desta prova é integrar os conhecimentos adquiridos ao longo do curso, permitindo ao aluno aplicar conceitos teóricos e práticos em uma única atividade avaliativa. A prova aborda temas relevantes ao conteúdo estudado e exige habilidades de análise, desenvolvimento e/ou resolução de problemas práticos.

## Objetivo da Atividade

O principal objetivo desta Avaliação Integrada é:

- Verificar a capacidade do aluno de aplicar na prática os conhecimentos adquiridos.
- Estimular o raciocínio lógico, técnico e crítico.
- Consolidar o aprendizado por meio da resolução de problemas reais ou simulados.
- Avaliar a autonomia e o domínio das ferramentas estudadas.

  
## Como Utilizar este Repositório

  
# Avalia-o-Integrada-part1
Parte 1: LOPAL

Contextualização:

 Imagine que você tem 5 servidores em diferentes regiões da AWS, e está monitorando o uso de CPU de cada um a cada hora. Você coleta esses dados por 10 horas seguidas. O resultado pode ser representado como uma matriz:

Linhas: cada linha representa um registro de tempo (por exemplo, hora 1 até hora 10) 
Colunas: cada coluna representa um servidor ou região diferente Utilizando esse conceito desenvolva as próximas questões.

1- Considerando a matriz abaixo, crie um laço for para calcular a média de uso de CPU por linha e imprima os resultados com 2 casas decimais.


2- Crie uma função chamada alerta_uso que recebe como parâmetro uma lista com os valores de uso de CPU de uma região. A função deve retornar True se algum valor ultrapassar 85% de uso, e False caso contrário. Teste a função para todas as regiões da matriz.

3- Crie uma função chamada dados_crescente que recebe como parâmetro uma lista com os valores de uso de CPU de uma região. A função deve retornar a lista organizada em ordem crescente, do menor uso de CPU para o maior. Teste a função para todas as regiões da matriz

4- Utilizando a biblioteca pandas, crie um DataFrame com os dados da matriz acima. Os nomes das linhas devem ser ["hora_1", "hora_2",..., "hora_10"] e as colunas representam as regiões ["us-east-1", "us-west-2", "eu-central-1", "sa-east-1", " ap-southeast-1" ].

5- Dentre as questões anteriores escolha uma delas para fazer uma leve explicação do seu funcionamento.

Parte 2: VER
Contextualização:

Com o código gerado da seção anterior, o próximo passo será salvar essas atualizações em um ambiente em que possa gerar registros de modificações e controlar as versões. Para essa operação o indicado será utilizar o github junto com git para interação repositório local e remoto.

6- Dentre as opções abaixo, qual seria o comando para clonar o repositório de uma branch remota:
git init
git clone
git push
git pull
git status

7- Qual comando inicia o versionamento em uma pasta local?
git init
git clone
git push
git pull
git status

8- Quais seriam os dois comandos para associar o commit com os dados de identidade do usuário (e-mail e username)

9- Criar um repositório remoto contendo os arquivos da seção 1. Deve constar minimamente um README.md com as informações gerais da atividade e pelo menos dois commits no histórico.
Enviar o link do repositório público. 







