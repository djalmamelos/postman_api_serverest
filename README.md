
# Serverest API Testing with Postman 🚀

Este repositório contém um projeto de automação de testes para a API Serverest utilizando Postman. A API Serverest está disponível no [site oficial](https://serverest.dev/) e o repositório no GitHub pode ser encontrado [aqui](https://github.com/ServeRest/ServeRest). Os testes foram divididos em diversos cenários principais.

## Índice 📚

- [Introdução](#introdução)
- [Pré-requisitos](#pré-requisitos)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Executar os Testes](#como-executar-os-testes)
- [Casos de Teste](#casos-de-teste)
- [Contribuição](#contribuição)

## Introdução 🌟

Este projeto foi criado para demonstrar habilidades em automação de testes de API usando Postman. A API Serverest foi utilizada como base para os testes, os quais foram divididos nos seguintes cenários:

- **Cenário 01**: Cadastrar Novo Usuário
- **Cenário 02**: Cadastrar um usuário já existente
- **Cenário 03**: Consultar os dados de um usuário
- **Cenário 04**: Logar com o novo usuário criado

Além disso, a API Serverest possui uma seção de endpoints de produtos, onde é possível buscar produtos e adicionar produtos mediante o uso de token com email e senha cadastrados. Os cenários de teste adicionais incluem:

- **Cenário 05**: Criar Produto
- **Cenário 06**: Listar Produtos

## Pré-requisitos ✅

Antes de começar, você vai precisar ter o seguinte instalado em sua máquina:

- [Postman](https://www.postman.com/downloads/)
- Conta no Postman (opcional, mas recomendada para salvar e sincronizar seus testes)

## Estrutura do Projeto 📁

```plaintext
serverest-postman-automation/
├── collections/
│   ├── SERVEREST.postman_collection
├── README.md
```

- **collections/**: Contém a coleção de testes do Postman para a API Serverest.

## Como Executar os Testes ▶️

1. **Importar a Coleção e o Ambiente no Postman**

    -  tem que ver iss aqui kkk 

2. **Selecionar o Ambiente**

    - No canto superior direito do Postman, selecione o ambiente "Serverest".

3. **Executar os Testes**

    - Na aba "Collections", expanda a coleção "ServerestAPI".
    - Clique em "Run" para abrir a Collection Runner.
    - Clique em "Run ServerestAPI" para executar todos os testes da coleção.

## Casos de Teste 📝

### Cenário 01: Cadastrar Novo Usuário

Este teste verifica a funcionalidade de cadastro de um novo usuário na API Serverest.

### Cenário 02: Cadastrar um Usuário Já Existente

Este teste verifica a resposta da API ao tentar cadastrar um usuário que já existe.

### Cenário 03: Consultar os Dados de um Usuário

Este teste verifica a funcionalidade de consulta dos dados de um usuário cadastrado na API Serverest.

### Cenário 04: Logar com o Novo Usuário Criado

Este teste verifica a funcionalidade de login com um usuário recém-cadastrado na API Serverest.

### Cenário 05: Criar Produto

Este teste verifica a funcionalidade de adicionar um novo produto na API Serverest utilizando um token de autenticação.

### Cenário 06: Listar Produtos

Este teste verifica a funcionalidade de listar todos os produtos disponíveis na API Serverest.

## Contribuição 🤝

Contribuições são bem-vindas! Por favor, abra um problema ou envie um pull request para discutir mudanças que você gostaria de fazer.



