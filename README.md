# Projetos Acadêmicos de Modelagem de Dados

Este repositório reúne projetos práticos desenvolvidos na disciplina de Modelagem de Dados do curso de Ciência da Computação. O foco foi a aplicação de conceitos de bancos de dados relacionais para a criação de sistemas funcionais, utilizando o MySQL Workbench como ferramenta de desenvolvimento dos diagramas.

## Projetos

---

### 1. Sistema de Locação de Ciclomotores (MoveRent)

* [cite_start]**Descrição:** Este projeto consiste na modelagem de um banco de dados para a empresa fictícia *MoveRent*, especializada em locação de ciclomotores[cite: 13]. [cite_start]O objetivo é estruturar uma base de dados que controle o cadastro de clientes, a frota de veículos, as locações e os trajetos realizados[cite: 16, 62, 69].

* **Entidades Principais:**
    * [cite_start]`Pessoa`: Armazena os dados dos clientes[cite: 51].
    * [cite_start]`Ciclomotor`: Mantém o registro dos veículos disponíveis para locação[cite: 57].
    * [cite_start]`Locação`: Gerencia as informações de cada aluguel, vinculando um cliente a um ciclomotor[cite: 62].
    * [cite_start]`Trajeto`: Registra os detalhes de cada percurso realizado durante uma locação[cite: 69].

* **Tecnologias:**
    * [cite_start]Modelagem: **MySQL Workbench**[cite: 14].

---

### 2. Sistema de Gerenciamento de Biblioteca Universitária

* [cite_start]**Descrição:** Foi desenvolvido um Diagrama Entidade-Relacionamento (DER) para gerenciar o sistema de empréstimos de uma biblioteca universitária[cite: 93]. [cite_start]A estrutura de dados visa controlar o acervo de livros, o cadastro de alunos e colaboradores, e o histórico de empréstimos e devoluções[cite: 96].

* **Entidades Principais:**
    * [cite_start]`Aluno`: Cadastra os estudantes autorizados a realizar empréstimos[cite: 124].
    * [cite_start]`Livro`: Armazena as informações do acervo da biblioteca, como título, autor e ISBN[cite: 129].
    * [cite_start]`Colaborador`: Registra os funcionários da biblioteca responsáveis pelos empréstimos[cite: 134].
    * [cite_start]`Empréstimo`: Tabela central que relaciona um aluno, um livro e um colaborador para registrar cada operação de empréstimo[cite: 139].

* **Tecnologias:**
    * [cite_start]Modelagem: **MySQL Workbench**[cite: 94].

---
[cite_start]*Projetos elaborados por Gabriel Alves Izaias (RA: 2024198938)[cite: 2, 3, 82, 83].*
