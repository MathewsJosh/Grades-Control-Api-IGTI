# Grades-Control-Api-IGTI
Desenvolver uma API chamada “grades-control-api” para controlar notas de alunos em matérias de um curso. Exercitando os conceitos trabalhados no módulo para criação de uma API, criando endpoints utilizando Node.js e Express.

O desafio final consiste em desenvolver uma API chamada “grades-control-api” para controlar notas de alunos em matérias de um curso.  Você deverá desenvolver endpoints para criação, atualização, exclusão e consulta de notas, aqui chamadas de grades. As grades deverão ser salvas em um arquivo json, chamado “grades.json”. Esse arquivo será previamente fornecido e seus endpoints devem atuar considerando os registros já existentes.

Uma grade deve possuir os campos abaixo:

- id (int): identificador único da grade. Deve ser gerado automaticamente pela API e garantir que não se repita.

- student (string): nome do aluno. Exemplo: “Guilherme Assis”.

- subject (string): nome da matéria. Exemplo: “Matemática”.

- type (string): nome da atividade. Exemplo: “Prova final”.

- value (float): nota da atividade. Exemplo: 10.

- timestamp (string): horário do lançamento. Exemplo: 2020-05-19T18:21:24.964Z. Dica: utilizar o “new Date()” do JavaScript.

O arquivo grades.json será previamente fornecido com alguns registros inseridos, seus endpoints devem trabalhar considerando a existência deles, não devendo criar um arquivo limpo para utilização. A estrutura do arquivo é a seguinte:

<p align="center">
  <img src=".\img\structure-example.png" width="350" title="hover text">
</p>