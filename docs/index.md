# Documentação: Evasão 360

## O que é

O **Evasão 360** é um sistema web desenvolvido para a disciplina do prof Henry, Engenharia de Software II, pela equipe das Meninas Malvadas: Julia Jaeger, Nicole Grazzioli e Willian Potkova. 

A aplicação tem como objetivo principal auxiliar coordenadores e professores de instituições de ensino a identificar estudantes que apresentam um alto risco de evasão (abandono do curso).

## O que faz (funcionalidades)

* **Autenticação de login:** Acesso restrito a usuários autorizados (administradores, coordenadores) através de uma tela de login. Se o login (email e senha) existir na base de dados, o acesso é liberado.
* **Painel de Monitoramento:** Após o login, o usuário é direcionado a um painel central que exibe uma tabela com a lista de alunos: matrícula, nome, curso, centro e nível de risco de cada aluno (baixo, moderado ou alto). 
* **Detalhamento de Alunos:** É possível visualizar as informações completas de um aluno específico: como matrícula, curso, e-mail, frequência e média geral, através de uma janela modal.
* **Geração de Relatórios:** Uma página que permite a geração de relatórios para análises mais aprofundadas sobre os dados. É possível gerar relatórios de XXXXXXXXX

## Tecnologias Utilizadas

* **Ferramentas:** IntelliJ IDEA
* **Backend:** Java 21, Spring Boot, Spring Web e Spring Data JPA
* **Frontend:** JavaServer Pages (JSP) com JSTL renderizado pelo servidor
* **Build e Dependências:** Apache Maven
* **Banco de Dados:** PostgreSQL
    * **Gerenciamento de Migrações:** Flyway, para versionamento e automação do schema do banco de dados