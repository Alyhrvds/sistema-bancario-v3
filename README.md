# Sistema Bancário em Python - V3 (Orientado a Objetos)

Este é o projeto da **versão 3** do sistema bancário simples, desenvolvido como parte de um desafio da [DIO](https://www.dio.me/).  
Agora o sistema foi **refatorado com programação orientada a objetos**, seguindo um diagrama UML com boas práticas e estrutura de classes.

---

## Funcionalidades

- **Criação de clientes (Pessoa Física)**
- **Criação de contas correntes**
- **Depósitos e saques com validações**
- **Histórico de transações com data e tipo**
- **Limite de saque por valor e por quantidade diária**

---

## Estrutura de Classes

O sistema foi desenvolvido com base em um diagrama de classes, contendo:

- `Cliente` (classe base)
- `PessoaFisica` (subclasse de Cliente)
- `Conta` (classe base)
- `ContaCorrente` (subclasse de Conta com regras de saque)
- `Historico` (composição com Conta)
- `Transacao` (interface abstrata)
- `Deposito` e `Saque` (implementam a interface Transacao)

---

## Tecnologias Utilizadas

- Python 3.11+
- Paradigma de Programação Orientado a Objetos (POO)
- Módulo `abc` para interfaces abstratas
- Módulo `datetime` para registro de transações

---

##  Como Executar

1. Clone este repositório:
   bash
   git clone https://github.com/seu-usuario/sistema-bancario-v3.git

2. Acesse a pasta do projeto:

   bash
   cd sistema-bancario-v3

3. Execute o arquivo principal:

   bash
   python sistema_bancario.py

---

## Autor

Feito com 💙 por **Alice**, durante o bootcamp da DIO.

---

## Possíveis melhorias futuras

* Cadastro de usuários via terminal
* Persistência de dados em arquivos ou banco de dados
* Interface gráfica com Tkinter ou PyQt
* Geração de relatórios em PDF ou CSV

---

## Licença

Este projeto é livre para fins de estudo e aprendizado. Sinta-se à vontade para modificar e expandir.

