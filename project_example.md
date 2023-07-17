# < NomeDoProjeto >
<fig>
<img src="project_ex.jpg" alt="Uma imagem relacionada ao projeto">
<figcaption>Uma imagem relacionada ao projeto</figcaption>
</fig>

## Inicialização
Para executar o projeto, utilize as ferramentas descritas na sessão *Ferramentas*.

### Tecnologias utilizadas


* [Pandas](https://pandas.pydata.org/) - Biblioteca para análise de dados com Python
* [Requests](https://requests.readthedocs.io/en/latest/) - Biblioteca de requisições HTTP

# < NomeDoProjeto >

## Introdução

> Visão geral  

Este projeto possui o objetivo principal **< descreva o objetivo principal >**.  
Com os objetivos gerais de realizar a inserção de **< objeto >** e verificação de **< objeto >**. 

## Análise técnica

### Descrição do ambiente técnico

O sistema é composto por um banco de dados, uma interface web e um sistema embarcado. Funcionalidades principais:
> Indique os grandes blocos do sistema.

* **F1** - Nome da funcionalidade 1.
* **F2** - Nome da funcionalidade 2.
* **F3** - Nome da funcionalidade 3.
> Coloque somente o nome principal, por exemplo: Controle de usuários.

As ferramentas utilizadas para o desenvolvimento incluem **< linguagem para back-end >** que é uma linguagem de programação utilizada para o Back-end, para front-end foi utilizado **< linguagem para o front-end >** . **< Banco de dados >** atuando como sistema gerenciador de banco de dados relacional e **< gerenciador de container >** para utilizar o ambiente em container.

### Levantamento de requisitos  
Os requisitos devem ser validados com a cliente e aprovados.
> Aprovar os requisitos com o cliente é o mais importante, se não for validado o documento não será válido.

## Regras de Negócio

_Solicitação_  

**RGN1** -  A variável X + Y deve ser somada todas as vezes que tivermos requisições via API.

_Agendamento_  

**RGN2** - O cliente só fará a agendamento se estiver 2 anos no sistema.   


## Casos de Uso

**UC1** - *Login no sistema*

Ao entrar no sistema pela primeira vez o usuário deve cadastrar suas informações. O usuário deverá informar seu perfil.

<img src="https://www.programiz.com/sites/tutorial2program/files/flowchart-2.jpg">

> Imagine que fosse necessário enviar um email sempre que realizado o login, esse email deveria estar no fluxograma. Esse fluxograma pode ser mais simples, apenas com o objetivo de validar com o cliente que as dependências de negócio estão validadas em cada caso de negócio.

### Mensagens internas

Rotas utilizadas pela aplicação web para executar metodos de **POST** e **GET** no banco de dados. Onde o retorno de cada uma das funções estara contido em uma sessão para renderização de páginas web.

> Aqui ficam descritos os endpoints, que podem estar em outra documentação também.  
> É interessante colocar essa documentação aqui quando a API é pequena.

| Nome | Funcionalidade|
|------|--------------|
|```GET``` /listarUsuario|Informa todos usuários registrados no banco.|
|```POST``` /insereUsuario|Insere um novo usuário.|
|```PUT``` /atualizaUsuario|Atualiza o usuário.|

## Conceitos básicos
* [Design pattern](https://www.opus-software.com.br/design-patterns/) - Design Patterns ou padrões de projetos são soluções generalistas para problemas recorrentes durante o desenvolvimento de um software. Mais informações no [catalogo de design pattern](https://refactoring.guru/design-patterns). 
