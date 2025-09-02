# 💳 Banking System Python

Projeto desenvolvido durante o **Bootcamp Santander Backend com Python - DIO**, com o objetivo de praticar os fundamentos da linguagem Python aplicados a um sistema bancário simples.

## 📌 Funcionalidades

O sistema implementa operações básicas de um banco, simulando o fluxo de cadastro de contas, depósitos, saques e extratos.

- **Cadastro de usuários**
  - Registra um cliente pelo **CPF** (não permite duplicidade).
  - Armazena informações como **nome**, **data de nascimento** e **endereço**.

- **Listagem de contas**
  - Mostra todas as contas já cadastradas no sistema.

- **Depósito**
  - Permite adicionar valores positivos ao saldo.
  - Registra a movimentação no extrato.

- **Saque**
  - Limite de **R$ 500,00 por saque**.
  - Máximo de **3 saques por dia**.
  - Permite saque com **auxílio do limite** (cheque especial).
  - Registra as transações no extrato.

- **Extrato**
  - Exibe todas as movimentações da conta.
  - Mostra o saldo atualizado.

- **Menu interativo**
  - Interface em linha de comando para acessar as opções do sistema.

## 🛠️ Estrutura do Código

- `cadastrar_usuario()` → Cadastra novos clientes.
- `listar_contas()` → Lista todas as contas registradas.
- `depositar()` → Realiza depósitos.
- `sacar()` → Realiza saques com regras de limite.
- `exibir_extrato()` → Exibe o extrato da conta.
- `menu()` → Exibe o menu principal.
- `main()` → Função principal que controla o fluxo do programa.

## 🚀 Como Executar

Clone o repositório:

```bash
git clone https://github.com/jrs1lva/banking-system-python.git
```

Acesse a pasta do projeto:

```bash
cd banking-system-python
```

Execute o programa:

```bash
python main.py
```

📚 Aprendizados

✅ Estruturação de funções no Python
✅ Manipulação de dicionários para armazenar dados
✅ Boas práticas com parâmetros posicionais e nomeados
✅ Controle de fluxo com if/elif/else
✅ Simulação de regras reais do sistema bancário

##

👨‍💻 Desenvolvido por Adailton Júnior durante o Bootcamp Santander/DIO 🚀
