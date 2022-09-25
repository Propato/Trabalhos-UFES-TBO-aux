# Trabalho 1
## Union & Find aplicado no Algoritmo de Kruskal

### Descrição do projeto

Este trabalho é voltado para o estudo e implementação de um código em C de um algoritmo de agrupamento de espaçamento máximo. Assim, é utilizado o Algoritmo de Kruskal para processar dados de entrada e encontrar uma árvore geradora mínima parcial a fim de agrupar os objetos de análise (nesse caso, pontos m-dimensionais) pelas suas características (distâncias entre os pontos) em K grupos, sendo K um valor passado no início da execução do código.

Uma árvore geradora mínima (minimum spanning tree - MST) é um conceito amplamente conhecido na computação e que se baseia em: Tendo um grafo completo, não-direcionado e ponderado, ela será o subconjunto das arestas que incluem todos os vértices de forma não cíclica (ou seja, não tendo dois caminhos diferentes, direta ou indiretamente, para dois pontos distintos), formando uma árvore, onde o peso total, dado pela soma dos pesos das arestas da árvore, é minimizado.

Assim, o algoritmo de Kruskal, elemento principal deste trabalho, é um algoritmo que utilizando das funções Union Find busca essa árvore geradora mínima. Conectando os vértices de menor peso (distância) até que quase seja formada a MST, não sendo conectada às últimas K-1 arestas a fim de que se obtenha K grupos desses pontos.


O objetivo deste trabalho é entender e implementar um algoritmo de agrupamento, chamado de agrupamento de espaçamento máximo, utilizando uma MST (Minimum Spanning Tree), que é encontrada através do algoritmo de Kruskal e das funções Union Find estudadas em aula.

O foco deste trabalho é a eficiência, sendo realizadas medições de tempo e análises de complexidade.

### Ferramentas utilizadas

<img src="https://user-images.githubusercontent.com/84464307/192127831-3cbad648-e690-43c5-9772-c6db2d13641c.png" alt="Icone linguagem C" width="70"/>

### Comentários

### Pontuação
# 10
