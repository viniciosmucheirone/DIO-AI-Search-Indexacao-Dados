# Criando um Board de Tarefas com Java

<h1 align="center">
    <img alt="Gobarber" src="img\board.jpg" width="300px" />
</h1>

## Descrição do Projeto

Neste projeto, desenvolvi uma aplicação de gerenciamento de tarefas utilizando Java, com foco nas melhores práticas de desenvolvimento. O objetivo foi criar um board de tarefas funcional, passando por todas as etapas do processo, desde o planejamento e estruturação até a implementação de funcionalidades como gerenciamento de dados e integração entre camadas. A aplicação foi desenvolvida seguindo as melhores práticas de programação e boas práticas de design de software.

A aplicação permite gerenciar tarefas em diferentes estágios, como **To Do**, **In Progress** e **Done**, com uma interface para a movimentação de cards de tarefa entre esses estados.

O principal desafio foi a integração com o SQL Server, onde foram enfrentados problemas relacionados ao uso de aliases nas consultas SQL. Durante o processo de integração, surgiram dificuldades ao configurar a conexão e ao adaptar a estrutura de código para funcionar adequadamente com o banco de dados SQL Server. A solução envolveu a reconfiguração das dependências no projeto para garantir a compatibilidade com o SQL Server, incluindo a configuração do driver JDBC apropriado. Essas mudanças levaram à reescrita de várias classes responsáveis por realizar inserções no banco de dados, como as classes DAO (Data Access Object), para garantir que os dados fossem inseridos corretamente nas tabelas. 


###  Objetivos do Projeto:

- Criar um board de tarefas funcional com **movimentação de cards** entre diferentes estados.
- Implementar uma **camada de persistência** eficiente, com integração a um banco de dados.
- Aplicar boas práticas de **arquitetura de software**, como camadas bem definidas (DTO, DAO, Service).
- Utilizar o **Liquibase** para controle de versão do banco de dados e migrações.

### Capturas de Tela da Execução do Projeto

Aqui estão algumas capturas de tela que ilustram o funcionamento do board de tarefas:

####  Tela 1: Cadastro de um board de tarefas  e visualização no banco de dados
<h1 align="center">
    <img alt="Gobarber" src="img\board_execucao.png"/>
</h1>
<h1 align="center">
    <img alt="Gobarber" src="img\board_db.png"/>
</h1>

####  Tela 2: Cadastro de um card e visualização no banco de dados
<h1 align="center">
    <img alt="Gobarber" src="img\board_cadastro_card.png"/>
</h1>
<h1 align="center">
    <img alt="Gobarber" src="img\board_card_db.png"/>
</h1>

####  Tela 3: Alteração do status do Card e visualização no banco de dados
<h1 align="center">
    <img alt="Gobarber" src="img\board_card_modificado.png"/>
</h1>
<h1 align="center">
    <img alt="Gobarber" src="img\board_card_modificado_db.png"/>
</h1>

####  Tela 4: Exclução do Board 
<h1 align="center">
    <img alt="Gobarber" src="img\board_excluir.png"/>
</h1>

<h1 align="center">
    <img alt="Gobarber" src="img\board_excluir_db.png"/>
</h1>

---

## Conclusão
Este projeto foi uma excelente oportunidade para aplicar os conceitos aprendidos no Decola Tech. A criação de um board de tarefas em Java me permitiu praticar e melhorar minhas habilidades em desenvolvimento de software e arquitetura de sistemas. Além disso, a implementação de uma solução escalável e eficiente com boas práticas de codificação foi fundamental para o aprendizado.
