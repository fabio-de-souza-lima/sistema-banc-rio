# Sistema Bancário em Python

Este projeto é uma simulação de um sistema bancário simples, desenvolvido em Python.  
Ele permite criar clientes, abrir contas correntes e realizar operações básicas como **depósitos, saques e extratos**.

## Funcionalidades
- Criar clientes (Pessoa Física)
- Criar contas correntes vinculadas a clientes
- Realizar depósitos
- Realizar saques (com limite de valor e quantidade)
- Exibir extrato com histórico de transações

## Estrutura do Código
- `Cliente` e `PessoaFisica`: representam os usuários do banco
- `Conta` e `ContaCorrente`: representam as contas bancárias
- `Transacao`, `Saque` e `Deposito`: operações financeiras
- `Historico`: registra todas as movimentações
- Funções auxiliares para menu e fluxo do sistema

## Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/fabio-de-souza-lima/sistema-banco-rio.git

## Acesse a pasta do projeto:
cd sistema-banco-rio

## Execute o programa:
python sistema_bancario.py

## Exemplo de uso
## Ao rodar o programa, você verá um menu interativo:
=============== MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta
[nu] Novo usuário
[q] Sair

## Próximos passos
## Implementar autenticação de clientes

## Adicionar suporte a diferentes tipos de contas

## Criar testes automatizados


👉 Sugestão: copie esse conteúdo para um arquivo chamado `README.md` na raiz do repositório e faça o commit. Assim seu projeto vai ficar bem mais apresentável.  

Quer que eu te mostre o comando exato para criar esse `README.md` direto pelo terminal e já subir para o GitHub?
