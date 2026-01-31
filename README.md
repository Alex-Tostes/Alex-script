# Calculadora
Calculadora simples com cada passo e requisito detalhado e comentado.

Tornar executável:

./Alex-script.sh

Esta seção detalha a lógica de desenvolvimento do script Python para a Calculadora.

### 1. Objetivo do Projeto
O script foi criado para realizar operações matemáticas fundamentais através de uma interface de linha de comando (CLI). O foco principal foi criar um código limpo, funcional e que trate possíveis erros de entrada do usuário.

### 2. Fluxo de Funcionamento
A lógica do programa está dividida nos seguintes pilares:

* *Interface de Interação:* O programa utiliza um laço de repetição (while True) que mantém a calculadora ativa, permitindo que o usuário realize múltiplos cálculos sem precisar reiniciar o script.
* *Menu de Opções:* Através de estruturas condicionais (if, elif, else), o código identifica a operação escolhida pelo usuário (Soma, Subtração, Multiplicação ou Divisão).
* *Funções Matemáticas:* Cada operação está encapsulada em sua própria lógica, garantindo que os dados inseridos sejam processados corretamente como números de ponto flutuante (float).
* *Tratamento de Exceções:* O código prevê erros comuns, como a tentativa de divisão por zero, exibindo uma mensagem de alerta em vez de encerrar o programa abruptamente.

### 3. Tecnologias e Métodos
* *Linguagem:* Python 3.x
* *Entrada de Dados:* Função input() com conversão de tipo.
* *Saída de Dados:* Função print() com formatação para exibição dos resultados.

