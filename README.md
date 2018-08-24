![ethinkers](./images/top-ethinkers.jpg)

# Teste Full Stack - E-thinkers

O teste consiste em criar uma API REST que busca usuarios pelo nome e username a partir de uma palavra chave. 
Faça o download do arquivo [users.csv.gz](https://s3.amazonaws.com/ethinkers-teste/users.csv.gz) que contém o banco de dados que deve ser usado na busca. 
Ele contém os IDs, nomes e usernames dos usuários.

###### Exemplo
| ID                                   | Nome              | Username             |
|--------------------------------------|-------------------|----------------------|
| 065d8403-8a8f-484d-b602-9138ff7dedcf | Thiago Santos     | thiago.santos        |
| 5761be9e-3e27-4be8-87bc-5455db08408  | Arthur Carvalho   | arthur.carvalho      |
| ef735189-105d-4784-8e2d-c8abb07e72d3 | Lucas Reis   	   | lucas.reis           |



Também são fornecidas duas listas de usuários que devem ser utilizadas para priorizar os resultados da busca. 
 - A lista 1 tem mais prioridade que a lista 2. Ou seja, se dois usuarios casam com os criterios de busca, aquele que está na lista 1 deverá ser exibido primeiro em relação àquele que está na lista 2. Os que não estão em nenhuma das listas são exibidos em seguida.

As listas podem ser encontradas na raiz deste repositório ([lista_relevancia_1.txt](lista_relevancia_1.txt) e [lista_relevancia_2.txt](lista_relevancia_2.txt)).
Os resultados devem ser retornados paginados de 15 em 15 registros.

Escolha as tecnologias que você vai usar e tente montar uma solução completa para rodar a aplicação.

-----

### Requisitos

- Criar um frontend para realizar a busca com uma UX elaborada
- Criar uma solução de autenticação entre o frontend e o backend
- Utilizar o Docker (ao final do teste responder o e-mail enviando o Docker Pull Command para avaliarmos)
