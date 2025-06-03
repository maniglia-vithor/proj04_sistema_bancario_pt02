# Sistema Bancário em Python com Persistência de Dados

Este projeto implementa um **sistema bancário** simples em Python, com interface no terminal e **persistência de dados em arquivo JSON**. O usuário pode consultar o saldo, fazer depósitos, realizar saques e visualizar um extrato detalhado com data e hora de cada transação.

##  Funcionalidades

- **Consulta de saldo**: Mostra o valor atual disponível na conta.
- **Depósito**: Permite adicionar valores ao saldo, registrando a transação.
- **Saque**: Permite retirar valores do saldo (caso haja saldo suficiente), registrando a transação.
- **Extrato bancário**: Lista todas as transações realizadas com data, hora, tipo e valor.
- **Persistência de dados**: As informações de saldo e extrato são salvas automaticamente no arquivo `banco_dados.json`, permitindo continuar de onde parou mesmo após fechar o programa.
- **Validação de entrada**: Impede que valores não numéricos sejam inseridos nas operações.

##  Tecnologias Usadas

- **Python 3**
- **Módulos padrão**:
  - `datetime` para registrar data/hora das transações
  - `json` para salvar e carregar dados do usuário
  - `os` para verificar existência do arquivo de dados

##  Como Usar

1. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/maniglia-vithor/proj04_sistema_bancario_pt02.git
