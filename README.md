### Desafio DEV Full Stack - CODED

## Objetivo Geral

Criar uma pequena aplicação para que um usuário possa gerenciar uma lista de contatos.

Objetivos Específicos

O candidato deverá disponibilizar o código em um repositório privado do github compartilhado com @patrezelopes e @raf4lb;

## Criar uma API REST de lista de contatos telefônicos (preferencialmente utilizando python + django):

O objeto JSON de um contato deverá conter a seguinte estrutura:

'''
{
"id" : 1,
      	"name" : "Patreze Lopes",
   	"phones" : [
      		{
"id" : 1,
          			“number" : "88997776813"
      		},
      		{
"id" : 2,
"number" : "8836951962"
      		}
   	]
  }
  '''

Deve possuir um endpoint para listar todos os contatos;

Deve possuir um endpoint para criação de contatos que não permita inserir um telefone já cadastrado;

Deve possuir um endpoint para atualização de contatos que não permita inserir um telefone já cadastrado;

Deve possuir um endpoint para exclusão de contatos;

## Criar um Frontend para consumir a API (preferencialmente utilizando  Angular):

O usuário deve poder ver a lista todos contatos;
O usuário deve poder criar contatos;
O usuário deve poder atualizar dados de um contato;
O usuário deve poder excluir contatos;
 

# Observações:

Faça commits compreensíveis;
Crie uma documentação mínima para conseguirmos executar e interagir com a sua aplicação;
Envie um e-mail para patreze.lopes.ced@prof.ce.gov.br e rafael.albuquerque.ced@prof.ce.gov.br para sinalizar que finalizou o desafio;
Prazo para entrega 06/06/2021.
