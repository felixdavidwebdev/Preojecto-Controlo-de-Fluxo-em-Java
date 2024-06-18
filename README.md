O Projeto Controlo de Fluxo em Java é um desafio lançado pelo professor
Gleyson Sampaio da DIO (Digital Innovation One) para exercitar conceitos
relacionados ao controle de fluxo e exceções em Java1. Vamos dar uma
olhada nos detalhes:

Objetivo do Projeto: O objetivo é criar um programa que recebe dois
parâmetros via terminal, representando dois números inteiros. Com base
nesses números, o programa deve realizar a seguinte lógica:
Calcular a quantidade de iterações (usando um loop for).
Imprimir no console os números incrementados durante as iterações.
Regras:
Se o primeiro parâmetro for MAIOR que o segundo, o programa deve lançar
uma exceção customizada chamada ParametrosInvalidosException com a
mensagem: “O segundo parâmetro deve ser maior que o primeiro”.
O projeto deve conter duas classes principais:
Contador.java: Responsável por implementar a lógica do programa.
ParametrosInvalidosException.java: Representa a exceção de negócio no
sistema.
