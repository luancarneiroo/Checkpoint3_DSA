# Checkpoint3_DSA
- Nome do projeto;
  Projeto Integrador: Sistema ATM em C

- Nome completo dos integrantes;
  Luan de Araujo Carneiro
  RM: 573691

- Descrição do sistema;
  O projeto simula o funcionamento de um caixa eletrônico (ATM) em modo texto, permitindo que o usuário interaja com um menu para realizar operações bancárias sobre um saldo inicial predefinido. Toda a lógica é gerenciada via terminal, com entrada e saída formatadas em português.
  Linguagem: C (padrão C99)
  Compilador: GCC
  Bibliotecas: stdio.h, stdlib.h
  
- Funcionalidades implementadas;
  Consultar Saldo - Exibe o saldo atual da conta formatado em reais (R$)
  Realizar Saque - Solicita um valor, valida se há saldo suficiente e debita o montante
  Realizar Depósit - oSolicita um valor positivo e adiciona ao saldo atuaL
  Sair
  
- Instruções de compilação e execução;
  Compilador GCC instalado - gcc checkpointB -o checkpoint
  Após compilar, execute o programa com - checkpoint
  
  Exemplo de uso:
===================================
       CAIXA ELETRONICO
===================================
1 - Consultar Saldo
2 - Realizar Saque
3 - Realizar Deposito
0 - Sair
===================================
Escolha uma Opcao: 1

---- SALDO ATUAL ----
R$ 1000.00
---------------------
  
