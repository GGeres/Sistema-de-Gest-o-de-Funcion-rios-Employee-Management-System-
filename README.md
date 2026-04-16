# Sistema-de-Gest-o-de-Funcion-rios-Employee-Management-System-

``` mermaid
classDiagram
    class Funcionario {
        -long id
        -String nome
        -String matricula
        -Date admissao
        -Date demissao
        -float salario
        -String horario
        +exibir() void
        +getNome() String
        +setNome(String nome)
        +getMatricula() String
    }

    class GestaoFuncionarios {
        -int indice
        -Funcionario[] funcionarios
        +criar() void
        +exibir() void
        +excluir() void
        +atualizar() void
        +menu() void
        +main(String[] args) static
    }

    GestaoFuncionarios "1" --> "0..50" Funcionario : gerencia
```

Descrição

    Este projeto é uma aplicação Java 21 focada no gerenciamento de recursos humanos de uma empresa. 
    Ele implementa operações de CRUD para funcionários, utilizando arrays para armazenamento em memória 
    e seguindo os princípios de encapsulamento da Programação Orientada a Objetos.



Funcionalidades

    Cadastro: Registro de funcionários com ID, Matrícula, Salário, Horário e datas de Admissão/Demissão.
    Busca por Matrícula: Localização rápida de registros no sistema.
    Gestão de Ciclo de Vida: Possibilidade de atualizar dados e registrar datas de desligamento (demissão).
    Remoção Segura: Exclusão de registros com reorganização automática do array.

---------------------------------------------------------------------------------------------------------------------------------

Description

    This Java 21 application is designed for corporate human resources management. 
    It implements CRUD operations for employees, using arrays for in-memory storage 
    and adhering to Object-Oriented Programming principles such as encapsulation.

Features

    Registration: Records employees with ID, Registration Number, Salary, Schedule, and Admission/Dismissal dates.
    Search by ID: Quick lookup of employee records using their registration number.
    Lifecycle Management: Capability to update data and record termination (dismissal) dates.
    Secure Removal: Deletion of records with automatic array reorganization to maintain data integrity.








  
