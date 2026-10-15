# Mapa-do-Rio-Grande-do-Sul
Este projeto implementa diferentes algoritmos de busca em grafos para encontrar rotas partindo de diferentes cidades do estado do Rio Grande do Sul com destino à capital, Porto Alegre.

Nós iniciais: Santa Vitória do Palmar, Erexim e Uruguaiana.

Nó objetivo: Porto Alegre

### Modelagem
O mapa foi modelado utilizando:

    Custo Real (Grafo) : Distância real em quilômetros entre as cidades.

    Heurística: Estimativa da distância em linha reta de cada cidade até o nó objetivo.

### Algoritmos Implementados
    1. Busca em Largura (Breadth-First Search - BFS);
    2. Busca em Profundidade (Depth-First Search -DFS);
    3. Busca com Aprofundamento Iterativo (Iterative Deepening Search - IDS);
    4. A* (A-Estrela);
    5. Busca pela melhor escolha (Best-First search);
    6. Busca de Custo Uniforme (Uniform Cost Search)

### Métricas de Avaliação
Para cada algoritmo testado (partindo de Santa Vitória do Palmar, Erexim e Uruguaiana), é avaliado: 

      - Complexidade de Tempo: Medida através da quantidade de nós expandidos (cidades) durante a busca.
      - Complexidade de Espaço: Medida pelo número máximo de nós armazenados na memória.
      - Otimalidade: O menor custo total (em km) do caminho é encontrado.

### Integrantes do Grupo
      -Ana Bilhalva
      -Eduarda Louzada
      -Júlia Costa
      -Maikely Moura
      -Silvana Furtado
