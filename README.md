# Análise - Receita dos Candidatos (Deputado Federal)
Esse projeto é um trabalho de Análise Exploratória de Dados (AED) que investiga a base de dados dos candidatos a Deputado Federal, do TSE, em 2018 e 2022. 

## Como começar?
1. Abrindo o site "https://dadosabertos.tse.jus.br" e baixando as seguintes bases de dados: ```consulta_cand_2022_BRASIL.csv```, ```receitas_candidatos_2022_BRASIL.csv```, ```consulta_cand_2018_BRASIL.csv``` e ```receitas_candidatos_2018_BRASIL.csv```;
2. Abrindo o notebook ```analise_cand-receita.ipynb``` para dar entrada nos bancos de dados do TSE e trata-los para realizar a análise e visualização de dados;

## Sobre os dados:
Os dados utilizados nessa análise são oriundos do site de Dados Abertos do TSE. A base total utilizada na análise é uma junção e concatenação dos dados dos candidatos, junto com as receitas que foram dispostas para eles nas campanhas eleitorais. Os dados cobrem os anos de 2018 e 2022. 

## Sobre os arquivos nesse repositório:

### ```comp_estado_2022.csv```:
Agrupamento dos valores da Unidade Federativa, Gênero e Raça e seu resumo estatístico.

### ```distribuicao_estado.csv```:
Agrupamento dos valores da Unidade Federativa, Gênero e Raça e seu resumo estatístico personalizado, mostrando desigualdades da distruição de verba do fundo eleitoral por Gênero e Raça. 

## Equipe
Ananda Ridart, Gabriel Ronan, Géssica Brandino e Vitor Arthur

## Finalidade do projeto
Trabalho realizado como projeto final da disciplina Mineração de Dados Não Estruturados, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper.
O link para a matéria que os dados foram utiizados é esse: https://medium.com/@vitorarthur/desigualdade-racial-predomina-na-distribui%C3%A7%C3%A3o-de-recursos-para-candidatos-a-deputado-federal-em-6bd5cdece90f
