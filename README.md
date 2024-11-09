# Estudo de Testes com Cypress - Coffee Cart

Este é um projeto de estudo para aprender e praticar automação de testes com Cypress. O objetivo é testar as funcionalidades de um site d# Estudo de Testes com Cypress - Coffee Cart

Este é um projeto de estudo para aprender e praticar automação de testes com Cypress. O objetivo é testar as funcionalidades de um site de carrinho de compras simulado [Coffee Cart](https://coffee-cart.app), cobrindo cenários como adicionar produtos, verificar itens no carrinho, aplicar promoções e remover itens.

## Índice

- [Objetivo](#objetivo)
- [Funcionalidades Testadas](#funcionalidades-testadas)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação e Execução](#instalação-e-execução)

## Objetivo

Este projeto foi desenvolvido para exercitar habilidades de QA em automação, utilizando o framework Cypress para testes de UI (User Interface) em um site de carrinho de compras.

## Funcionalidades Testadas

- **Adicionar Produto ao Carrinho**: Verifica se produtos podem ser adicionados ao carrinho.
- **Verificar Carrinho Vazio e Cheio**: Confirma se o carrinho exibe a mensagem correta quando vazio e quando contém itens.
- **Aplicar Desconto ao Carrinho**: Testa a funcionalidade de promoções no carrinho de compras.
- **Remover Produto do Carrinho**: Testa a remoção de um item do carrinho.
- **Alterar Quantidade de Itens**: Aumenta a quantidade de um item no carrinho e verifica o preço total.
- **Verificar Promoção**: Verifica se a promoção foi ativada ou não após 3 itens adicionados ao carrinho.
- **Limite de Promoção**: Verifica se a promoção é ativada mais de uma vez para o mesmo usuário.
  
## Tecnologias Utilizadas

- **Cypress**: Framework de automação de testes end-to-end.
- **JavaScript**: Linguagem principal para escrita dos testes.

## Estrutura do Projeto

A estrutura de pastas e arquivos é organizada para facilitar a manutenção e entendimento dos testes.

   ```bash
   ├── cypress/
   │   ├── e2e/
   │   │   ├── cart.cy.js         # Testes do carrinho de compras
   |   |   ├── promo.cy.js        # Testes de promoção
   │   ├── pages/
   |   |   ├── cart_page.cy.js    # Contém os elementos e ações relacionadas à página de carrinho
   |   |   ├── menu_page.cy.js    # Contém os elementos e ações relacionadas ao menu do site
   │   ├── support/
   │   │   ├── commands.js        # Comandos customizados do Cypress
   │   │   ├── e2e.js             # Configurações globais para o Cypress
   ├── README.md                  # Documentação do projeto
   ```
## Instalação e Execução

Para rodar os testes em sua máquina local, siga os passos abaixo:

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/MateusFels/coffee-cart_QA.git
   cd "seu_repositorio"

2. **Instale as dependências**:

   ```bash
   npm install

3. **Execute os testes**:

 - Para rodar os testes em modo interativo:

   ```bash
   npx cypress open

 - Para rodar os testes em modo headless (sem interface):

   ```bash
   npx cypress run
e carrinho de compras simulado [Coffee Cart](https://coffee-cart.app), cobrindo cenários como adicionar produtos, verificar itens no carrinho, aplicar promoções e remover itens.

## Índice

- [Objetivo](#objetivo)
- [Funcionalidades Testadas](#funcionalidades-testadas)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação e Execução](#instalação-e-execução)

## Objetivo

Este projeto foi desenvolvido para exercitar habilidades de QA em automação, utilizando o framework Cypress para testes de UI (User Interface) em um site de carrinho de compras.

## Funcionalidades Testadas

- **Adicionar Produto ao Carrinho**: Verifica se produtos podem ser adicionados ao carrinho.
- **Verificar Carrinho Vazio e Cheio**: Confirma se o carrinho exibe a mensagem correta quando vazio e quando contém itens.
- **Aplicar Desconto ao Carrinho**: Testa a funcionalidade de promoções no carrinho de compras.
- **Remover Produto do Carrinho**: Testa a remoção de um item do carrinho.
- **Alterar Quantidade de Itens**: Aumenta a quantidade de um item no carrinho e verifica o preço total.
- **Verificar Promoção**: Verifica se a promoção foi ativada ou não após 3 itens adicionados ao carrinho.
- **Limite de Promoção**: Verifica se a promoção é ativada mais de uma vez para o mesmo usuário.
  
## Tecnologias Utilizadas

- **Cypress**: Framework de automação de testes end-to-end.
- **JavaScript**: Linguagem principal para escrita dos testes.

## Estrutura do Projeto

A estrutura de pastas e arquivos é organizada para facilitar a manutenção e entendimento dos testes.

   ```bash
   ├── cypress/
   │   ├── e2e/
   │   │   ├── cart.cy.js         # Testes do carrinho de compras
   |   |   ├── promo.cy.js        # Testes de promoção
   │   ├── pages/
   |   |   ├── cart_page.cy.js    # Contém os elementos e ações relacionadas à página de carrinho
   |   |   ├── menu_page.cy.js    # Contém os elementos e ações relacionadas ao menu do site
   │   ├── support/
   │   │   ├── commands.js        # Comandos customizados do Cypress
   │   │   ├── e2e.js             # Configurações globais para o Cypress
   ├── README.md                  # Documentação do projeto
   ```
## Instalação e Execução

Para rodar os testes em sua máquina local, siga os passos abaixo:

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/MateusFels/coffee-cart_QA.git
   cd "seu_repositorio"

2. **Instale as dependências**:

   ```bash
   npm install

3. **Execute os testes**:

 - Para rodar os testes em modo interativo:

   ```bash
   npx cypress open

 - Para rodar os testes em modo headless (sem interface):

   ```bash
   npx cypress run
