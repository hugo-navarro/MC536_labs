# Aluno
198893:Hugo Carvalho de Almeida Navarro

# Marcadores e Taxonomia em Cypher
*Lab de Bancos de Dados em 17/09/2021*

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.
~~~
MATCH (m:Marcador)
MATCH (c:Categoria)
RETURN (m)-[:Pertence]->(:Categoria{id:"Serviços"})
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.
~~~
...
~~~
