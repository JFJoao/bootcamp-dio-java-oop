# Sistema de Bootcamp

Este projeto implementa um sistema de gerenciamento de Bootcamps em Java, utilizando conceitos de Orientação a Objetos (OOP).

## Funcionalidades

- **Nome do Bootcamp**: Permite definir o nome do Bootcamp.
- **Descrição do Bootcamp**: Permite fornecer uma descrição detalhada do Bootcamp.
- **Data de Início e Término**: Automaticamente define a data de início como o dia atual e a data de término como 45 dias após o início.
- **Devs Inscritos**: Permite armazenar e gerenciar os desenvolvedores inscritos no Bootcamp.
- **Conteúdos do Bootcamp**: Permite armazenar e gerenciar os conteúdos oferecidos no Bootcamp.

## Estrutura do Projeto

O projeto consiste nas seguintes classes:

### Bootcamp

Representa um Bootcamp com as seguintes propriedades:

- `nome`: Nome do Bootcamp.
- `descricao`: Descrição detalhada do Bootcamp.
- `dataInicial`: Data de início do Bootcamp (automática).
- `dataFinal`: Data de término do Bootcamp (automática, 45 dias após o início).
- `devsInscritos`: Conjunto de Devs inscritos no Bootcamp.
- `conteudos`: Conjunto de Conteúdos oferecidos no Bootcamp.

### Métodos Disponíveis

- `getNome()`: Retorna o nome do Bootcamp.
- `setNome(String nome)`: Define o nome do Bootcamp.
- `getDescricao()`: Retorna a descrição do Bootcamp.
- `setDescricao(String descricao)`: Define a descrição do Bootcamp.
- `getDataInicial()`: Retorna a data de início do Bootcamp.
- `getDataFinal()`: Retorna a data de término do Bootcamp.
- `getDevsInscritos()`: Retorna o conjunto de Devs inscritos.
- `setDevsInscritos(Set<Dev> devsInscritos)`: Define o conjunto de Devs inscritos.
- `getConteudos()`: Retorna o conjunto de Conteúdos oferecidos.
- `setConteudos(Set<Conteudo> conteudos)`: Define o conjunto de Conteúdos oferecidos.

## Requisitos

- JDK 8 ou superior.

## Executando o Projeto

1. Abra um terminal e navegue até o diretório do projeto.
2. Compile as classes Java:

