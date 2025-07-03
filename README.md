#ProjectMVC

##Passo a passo para execução

1. Instale o MySQL Server e o MySQL Workbench, configurando ambos corretamente.

2. Crie um Schema no MySQL Workbench (não é necessário criar as tabelas manualmente).

3. Instale o Flyway para gerenciamento de versões do banco de dados.

4. Adicione o driver JDBC:
   * Abra o projeto;
   * Vá até as configurações de dependência do módulo em "Estrutura do Projeto";
   * Adicione o arquivo `mysql-connector-j-8.4.0.jar` localizado na pasta `lib`.

5. Configure os arquivos `application.properties` e `flyway.conf` de acordo com o seu banco de dados.

6. Compile o arquivo `ProjectMaromoApplication`.

7. Por padrão, o projeto será executado em: http://localhost:8080.

8. Acesse a página de Clientes para visualizar:
   * A lista de todos os clientes;
   * As opções de Adicionar Cliente, Editar e Excluir.
