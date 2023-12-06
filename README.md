# Requisitos

- MySQL versão 5.6 ou superior.
- Cerca de 15 minutos
- Um editor de texto ou IDE favorito
- Java 17 ou posterior
- Gradle 7.5+ ou Maven 3.5+

Você também pode importar o código diretamente para a sua IDE:
- Spring Tool Suite (STS)
- IntelliJ IDEA
- VSCode

# Criação do Banco de Dados

Execute os seguintes comandos SQL para configurar o banco de dados:

```sql
create database db_example; -- Cria o novo banco de dados
create user 'springuser'@'%' identified by 'ThePassword'; -- Cria o usuário
grant all on db_example.* to 'springuser'@'%'; -- Concede todos os privilégios ao novo usuário no banco de dados recém-criado
