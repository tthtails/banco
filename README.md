Crie um programa para um banco que tenha as seguintes funcionalidades:
Uma classe Cliente:
    -Nome do cliente
    -CPF
    -Telefone
    -Data de nascimento
    -Idade (calcular a partir da data de nascimento)
Uma classe Conta:
    -Número da conta
    -Saldo da conta
    -Dono da conta (objeto Cliente)
Crie os métodos necessários para realizar as seguintes funcionalidades para o site do banco:
-Cadastrar um cliente
-Cadastrar uma conta (obrigatório por o dono)
-Listar em formato de tabela as contas com seus respectivos donos
-Consultar o saldo
-Transferir dinheiro de uma conta pra outra
-Sacar uma quantia
-Depositar uma quantia

OBS: Uma conta não pode ter mais que um dono, porém um cliente pode ter várias contas.

Dica: Na interface faça o usuário escolher entre Administrador ou Cliente:
O administrador terá acesso aos campos de input necessários para criar um cliente, uma conta e para listar as contas
Quando o usuário escolher cliente, mostre um campo de input para digitar seu nome e a partir disso:
O Cliente terá acesso aos campos de input necessários para sacar, depositar, transferir dinheiro e consultar o seu saldo
