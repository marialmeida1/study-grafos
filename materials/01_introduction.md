# Introdução aos Grafos

## Definição

- **Grafos:** coleção de vértices e arestas.
- **Vértices:** objeto simples que pode ter nome e outros atributos.
- **Arestas:** conexão entre dois vértices.

*Grafo G=(V,E) em que V é o conjunto de vértices e E o conjunto de arestas.*

## Tipos de Arestas

- **Direcionadas:** no qual cada aresta aponta para um vértice específico.
- **Não-Direcionadas:** aonde uma aresta em dois vértices podem abranger os dois caminhos, de ida e de volta. 

Na modelagem matemática definimos se uma aresta é direcionada ou não direcionada por meio da utilização de 'parênteses' ou 'chaves' na sua notação.

### Arestas Direcionadas

Define que uma aresta é a um conjunto de dois vértices sejam eles a exemplo `u` ou `v`, que possuem uma direção em específico, ou seja, cada um aponta para um local específico e pertencem a um conjunto de vértices. 

**Sua notação matemática ficaria como:**

E={(u,v) ∣ u,v ∈ V}

**Sendo que:**

E -> Conjunto de arestas direcionadas.
(u, v) -> par ordenado de uma aresta de um vértice `u` para o vértice `v`.
V -> conjunto de vértices de um grafo.

**Formando a notação:**

*O conjunto E contém todas as possíveis arestas direcionadas entre dois vértices qualquer pertencentes ao conjunto V.*

## Arestas Não Direcionadas

Define que uma aresta é um conjunto de dois vértices sejam eles a exemplo `u` ou `v`, que não possuem uma direção determinada podendo realizar qualquer caminho de ida ou volta de acordo com o pertencimento ao conjunto de vértices determinado.

**Sua notação matemática ficaria como:**

E={{u,v} ∣ u,v ∈ V}

**Sendo que:**

E -> Conjunto de arestas direcionadas.
{u, v} -> par não ordenado entre arestas de um vértice `u` e `v`.
V -> conjunto de vértices de um grafo.

**Formando a notação:**

*O conjunto E é formado por todos os possíveis pares de vértices de {u,v}, tais que u e v pertencem ao conjunto de vértices V.*


