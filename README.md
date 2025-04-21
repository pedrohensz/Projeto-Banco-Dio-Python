# 💰 Banco Python - Projeto de Sistema Bancário Simples

Este é um projeto simples de terminal em Python que simula algumas operações básicas de um sistema bancário: **depósito, saque e extrato**.

## 🧠 Funcionalidades

- **Depósito**
  - Aceita apenas valores positivos.
  - Armazena o histórico da operação com data e hora.

- **Saque**
  - Limite de até R$500 por saque.
  - Máximo de 3 saques diários permitidos.
  - Verifica se o valor está disponível no saldo.
  - Registra a operação no extrato com data e hora.

- **Extrato**
  - Lista todas as movimentações (depósitos e saques) com valor, tipo e data/hora formatada.
  - Mostra o histórico ordenado por ordem de inserção.

## 🛠️ Tecnologias

- Python 3
- Módulo `datetime` para registrar os horários das operações

## ▶️ Como executar

1. **Clone o repositório:**

git clone https://github.com/seu-usuario/banco-python.git
cd banco-python
Execute o script:
python banco.py
Escolha uma das opções do menu:
[1] Sacar
[2] Depositar
[3] Extrato
[0] Sair
🧪 Exemplo de uso
[2] Depositar
Insira o valor desejado para depósito: 200
Depositando...
Seu saldo é de: R$200.00
[1] Sacar
Insira o valor desejado para saque: 50
Sacando...
Seu saldo é de: R$150.00
[3] Extrato
Depósito de R$200.00 em 21/04/2025 14:35:20
Saque de R$50.00 em 21/04/2025 14:36:10
⚠️ Regras do Sistema
Não é permitido depositar valores negativos.
Não é permitido sacar valores negativos ou acima do saldo.
O valor máximo por saque é R$500.
Limite de 3 saques por execução do programa.

🧩 Possíveis melhorias
Controle de saques por dia (com data real).
Suporte a múltiplos usuários.
Armazenamento em arquivo ou banco de dados.
Interface gráfica ou versão web.

🤝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou fazer um pull request com sugestões e melhorias.

Feito com 💻 por Pedro Henrique
