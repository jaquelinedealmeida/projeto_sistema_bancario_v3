# PROJETO SISTEMA BANCÁRI0

## Objetivo:
Implementar as seguintes funcionalidades no sistema:

-  Decorador de log;
-  Gerador de relatórios;
-  Iterador personalizado
  
Estabelecer um limite de 10 transações diárias para uma conta

Se o usuário tentar fazer uma transação apo atingir o limite, deve ser informado que ele excedeu o número de transações permitidas para aquele dia.

Mostrar o extrato, a data e a hora de todas as transações.

## Decorador de log
- Implementação de um decorador  aplicado a todas as funções de transações(depósito, saque, criação de conta etc). Esse decorador registra a data e a hora da transação, bem como o tipo de transação.

## Gerador de relatório

- Criação de um gerador que permita iterar sobre as transações de conta e retorne, uma a uma, as transações que foram realizadas. Esse gerador deve ter também uma forma de filtrar as tranações baseado em seu tipo(saque ou apenas depósitos).

## Gerador de relatório

- Implementação de iterado personalizado ContaIterador que permita iterar sobre todas as contas do banco, retornando informações básicas de cada conta(número, saldo atual, etc).
  