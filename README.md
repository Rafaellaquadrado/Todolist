# Todolist

Projeto simples de gerenciamento de tarefas desenvolvido com **Spring Boot**, **Spring Data JPA**, **MySQL** e **Bean Validation**.

---

## Descrição

Aplicação backend para gerenciamento de tarefas com funcionalidades básicas para criar, listar, atualizar e excluir tarefas. Cada tarefa possui uma descrição e um status indicando se está concluída.

---

## Tecnologias utilizadas

- Java 17
- Spring Boot 3.3.0
- Spring Data JPA
- MySQL Connector/J
- Bean Validation (Jakarta Validation)
- Lombok
- Maven

---

## Funcionalidades

- Criar uma nova tarefa com descrição não vazia
- Listar todas as tarefas
- Atualizar status da tarefa (concluída ou não)
- Remover tarefa por ID

---

## Estrutura do projeto

- `model` - Entidade Task com validações
- `repository` - Interface JpaRepository para persistência
- `controller` - Endpoints REST para operações CRUD
- `application.properties` - Configurações do banco de dados e JPA

---

## Requisitos

- JDK 17 instalado
- MySQL rodando localmente ou remotamente
- Maven para gerenciamento de dependências

---

## Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/Rafaellaquadrado/Todolist.git
Como contribuir
Faça um fork do projeto

Crie uma branch com sua feature: git checkout -b minha-feature

Faça commit das suas alterações: git commit -m 'Minha nova feature'

Faça push para a branch: git push origin minha-feature

Abra um Pull Request

Autor
Rafaella Quadrado

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para detalhes.

Contato
LinkedIn: [seu-linkedin](https://www.linkedin.com/in/lara-rafaella-de-oliveira-quadrado-faria-25b624178/)




