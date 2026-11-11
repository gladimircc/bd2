# Atividade Final - Banco de Dados II

## Objetivo

Desenvolver uma aplicação simples que utilize **dois bancos de dados**:

-   **MySQL ou PostgreSQL** como banco relacional;
-   **MongoDB** como banco não relacional.

A aplicação pode ser desenvolvida em **Python ou JavaScript**.

O objetivo principal é aplicar os conteúdos estudados na disciplina.
**Não é necessário desenvolver uma interface gráfica ou web.** Uma
aplicação executada pelo terminal é suficiente.

## Grupos

Até **4 alunos**.

## Tema

O grupo poderá escolher o tema da aplicação.

Exemplos: loja, biblioteca, cursos, eventos, clínica, oficina etc.

O tema escolhido deve permitir utilizar os dois bancos de forma
coerente.

## Parte 1 - Banco relacional

Utilize **MySQL ou PostgreSQL**.

A aplicação deverá possuir:

-   no mínimo 3 tabelas relacionadas;
-   chaves primárias e estrangeiras;
-   inclusão, consulta, alteração e exclusão de dados;
-   pelo menos uma consulta utilizando `JOIN`.

## Parte 2 - MongoDB

O MongoDB deverá ser realmente utilizado pela aplicação.

Deverá existir:

-   inclusão, consulta, alteração e exclusão de documentos;
-   validação utilizando `$jsonSchema`;
-   campos obrigatórios;
-   validação de tipos;
-   pelo menos uma regra como `minimum`, `maximum`, `minLength`,
    `maxLength` ou `enum`;
-   pelo menos uma validação utilizando `pattern` e expressão regular;
-   pelo menos um índice.

O grupo deverá saber explicar **por que o índice foi criado naquele
campo**.

## Parte 3 - Integração

A aplicação deverá possuir pelo menos uma funcionalidade que utilize
**dados dos dois bancos**.

Exemplo:

``` text
PostgreSQL/MySQL
Produto, preço, estoque
        +
MongoDB
Avaliações do produto
        ↓
Aplicação
        ↓
Produto + preço + avaliação média
```

Não basta criar dois bancos independentes. **A aplicação deverá utilizar
os dois.**

## Parte 4 - Entrega

Entregar:

-   código-fonte da aplicação;
-   script SQL para criação do banco relacional;
-   script MongoDB com criação da coleção, validação e índice;
-   modelo ER do banco relacional;
-   arquivo `README.md`.

O README deverá informar:

-   integrantes;
-   tema da aplicação;
-   linguagem utilizada;
-   SGBD relacional escolhido;
-   como executar a aplicação;
-   como os dois bancos são utilizados;
-   por que determinados dados foram armazenados no banco relacional e
    outros no MongoDB.

## Parte 5 - Apresentação

Cada grupo deverá demonstrar a aplicação funcionando.

Durante a apresentação deverão ser mostrados:

-   acesso ao banco relacional;
-   acesso ao MongoDB;
-   operações realizadas nos dois bancos;
-   integração entre os bancos;
-   validação `$jsonSchema`;
-   tentativa de inserir um documento inválido;
-   expressão regular utilizada;
-   índice criado e sua finalidade.

Todos os integrantes devem conhecer o funcionamento geral do projeto.

Durante a apresentação poderão ser solicitadas **pequenas explicações ou
alterações** no código, nas consultas ou nas regras dos bancos.

## Uso de Inteligência Artificial

**É permitido utilizar ferramentas de Inteligência Artificial como
apoio.**

O grupo, entretanto, é responsável por tudo o que entregar.

Todos os integrantes deverão ser capazes de **explicar e demonstrar a
solução desenvolvida**, mesmo que tenham utilizado IA durante o
desenvolvimento.

## Itens avaliados

  Item                                
  ------------------------------------
  Banco relacional                    
  MongoDB, validação, regex e índice  
  Integração dos dois bancos          
  Aplicação funcionando               
  Organização da entrega              
  Apresentação e domínio individual   

## Checklist antes de entregar

-   [ ] A aplicação conecta ao MySQL ou PostgreSQL.
-   [ ] A aplicação conecta ao MongoDB.
-   [ ] O banco relacional possui pelo menos 3 tabelas relacionadas.
-   [ ] A aplicação realiza inclusão, consulta, alteração e exclusão.
-   [ ] Existe pelo menos uma consulta com `JOIN`.
-   [ ] O MongoDB possui validação com `$jsonSchema`.
-   [ ] Existe validação utilizando expressão regular (`pattern`).
-   [ ] Existe pelo menos um índice no MongoDB.
-   [ ] Existe uma funcionalidade que utiliza dados dos dois bancos.
-   [ ] O modelo ER foi incluído.
-   [ ] Os scripts SQL e MongoDB foram incluídos.
-   [ ] O README explica como executar o projeto.
-   [ ] Todos os integrantes conseguem explicar e demonstrar a
    aplicação.
