Este código implementa um sistema simples de gerenciamento de conta bancária com as seguintes funcionalidades:

1. Depositar (`d`): Permite ao usuário fazer um depósito na conta bancária. O usuário é solicitado a inserir o valor a ser depositado. Se o valor for válido (ou seja, maior que zero), o saldo da conta é atualizado e um registro do depósito é adicionado ao extrato da conta.

2. Sacar (`s`): Permite ao usuário fazer um saque da conta bancária. O usuário é solicitado a inserir o valor a ser sacado. O sistema verifica se o saque excede o saldo disponível, o limite de saques ou o limite de saque por transação. Se o saque for válido, o saldo da conta é atualizado, um registro do saque é adicionado ao extrato da conta e o número de saques é incrementado.

3. Extrato (`e`): Exibe o extrato da conta bancária, mostrando todas as transações de depósito e saque, bem como o saldo atual da conta.

4. Sair (`q`): Encerra o programa.

O programa continua em execução em um loop infinito até que o usuário selecione a opção de sair (`q`). Durante cada iteração do loop, o usuário é apresentado com um menu de opções para escolher a operação desejada. Dependendo da opção escolhida, uma das funções correspondentes é chamada para processar a operação.
