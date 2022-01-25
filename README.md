
 <img src="https://img.shields.io/github/license/Ricnaga/finapi?style=for-the-badge"/>

# <div align="center"> FinAPI </div>

#### <div align="right">- Projeto Finalizado <div>

### <div align="center"> Aplicação criada pela equipe Rocketseat abordando conceitos básicos sobre: </div>

- Nodejs
- CRUD: Create, read, update and delete com rotas
- Status code
- Middleware
- Recebendo dados das requisições


## <div align="center"> Sumário </div>
<!--ts-->
   - [Requisitos](#<div-align="center">Requisitos</div>)
   - [Tecnologias utilizadas](#<div-align="center">Tecnologias-utilizadas</div>)
   - [Autor](#<div-align="center">Autor</div>)
<!--te-->

## <div align="center">Requisitos</div>
Para executar a aplicação é necessário instalar algumas ferramentas tais como um editor de códigos para realizar compilação dos mesmos. Nesse projeto foi utilizado o [Visual Studio Code](https://code.visualstudio.com/), [NodeJS](https://nodejs.org/en/) para compilação do código, [Git Bash](https://gitforwindows.org/) para baixar o repositório e baixar todas as dependências necessárias. Para realizar testes foi utilizado o [Insomnia](https://insomnia.rest/download/)

```bash
# Baixe o repositório.
$ git clone https://github.com/Ricnaga/finapi.git

# Acesse a pasta do projeto.
$ cd finapi

# Agora que baixou e acessou o repositório, vamos começar a instalação das dependências.
$ yarn ( caso não utilize o yarn execute apenas npm -i)

# Depois de instalado todas as dependências, abra a aplicação via vscode
$ code .

# Agore execute a aplicação.
$ yarn dev (caso não utilize o yarn: npm run dev)

# A aplicação iniciará na porta 3333
# utilize o insomnia para executar as rotas, no insomnia as rotas são:

#POST:
-http://localhost:3333/account
no body:{"cpf": "número do cpf", "name": "nome"}

-http://localhost:3333/deposit
no body:{"amount":"titulo inserido", "description": "descrição do conteúdo"}
no header:{"cpf": "número do cpf"}

-http://localhost:3333/withdraw
no body:{"amount":"titulo inserido"}
no header:{"cpf": "número do cpf"}

#GET
-http://localhost:3333/statement
no header:{"cpf": "número do cpf"}

-http://localhost:3333/statement/date
na query:{"date": "aaaa-mm-dd"}
no header:{"cpf": "número do cpf"}

-http://localhost:3333/account
no header:{"cpf": "número do cpf"}

-http://localhost:3333/balance
no header:{"cpf": "número do cpf"}

#PUT
-http://localhost:3333/account
no body:{"name": "nome"}
no header:{"cpf": "número do cpf"}

#DELETE
-http://localhost:3333/account
no header:{"cpf": "número do cpf"}
```

##  <div align="center">Tecnologias utilizadas</div>
- [HTML](https://www.w3.org/HTML)
- [CSS](https://www.w3.org/Style/CSS/)
- [NodeJS](https://nodejs.org/en/)
- [Git Bash](https://gitforwindows.org/)
- [Express](https://expressjs.com/pt-br/starter/installing.html)


## <div align="center">Autor</div>
<div align="center">Atividade desenvolvida durante o curso ignite pela equipe <a href="https://rocketseat.com.br/">Rocketseat</a>, realizados por minha pessoa.
Gostou? tem alguma sugestão de melhoria? por favor, entre em contato e ja aproveita e me adiciona.<br>
<a href="https://www.linkedin.com/in/ricardo-nagatomy"><img src="https://img.shields.io/badge/-RicardoNaga-blue?style=flat-square&logo=Linkedin&logoColor=white"></a>
<a href="https://app.rocketseat.com.br/me/ricardo-nagatomy"><img src="https://img.shields.io/badge/-Rocketseat-000?style=flat-square&logo=&logoColor=white"></a>
</div>
