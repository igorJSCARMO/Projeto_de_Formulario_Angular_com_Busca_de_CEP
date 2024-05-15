# Busca de CEP

Este projeto é uma aplicação Angular para buscar informações de CEP via API.

## Estrutura do Projeto

- index.html: Arquivo HTML principal que contém a estrutura da página.
  
- form-control.component.ts: Componente Angular responsável pela lógica de preenchimento dos campos e busca de CEP.
  
- app.module.ts: Módulo principal da aplicação Angular.
  
## Pré-requisitos

- Antes de iniciar, verifique se você possui o seguinte instalado:

- Node.js e Angular CLI.

- Conexão com a internet para acessar a API ViaCEP.

## Como Utilizar

1) Clone o repositório:
- git clone https://caminho-para-o-seu-repositorio.git
  
2) Navegue até o diretório do projeto:
- cd nome-do-seu-projeto
  
3) Instale as dependências:
- npm install
  
4) Inicie o servidor de desenvolvimento:
- ng serve
  
5) Abra o navegador e acesse http://localhost:4200/.

## Funcionalidades

- Preencha os campos (Nome, Data de Nascimento, Email, Telefone, CEP, Rua/Avenida, Número, Complemento, Bairro, Cidade e Estado).

- O campo CEP possui integração com a API ViaCEP para buscar automaticamente os dados de endereço ao clicar no botão "Buscar CEP".
  
- O botão "Resetar" limpa todos os campos do formulário.

## Autor
Igor CARMO - Aluno de Automação Industrial
