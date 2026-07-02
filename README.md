# REPOSITORIO-TESTE-AVA01SUBS
AVA 01 SUBSTITUTA DE ESTRUTURA DE DADOS AVANCADA



Implementação de Grafo utilizando Matriz de Incidência em C

Objetivo acadêmico

Este projeto tem como objetivo demonstrar o funcionamento da representação de grafos por Matriz de Incidência, possibilitando a compreensão dos conceitos fundamentais da Teoria dos Grafos e sua implementação utilizando a linguagem C.



Sobre o projeto

Este projeto consiste na implementação de um Grafo Não Direcionado utilizando a estrutura de Matriz de Incidência, desenvolvido na linguagem C.

O programa permite criar um grafo de forma interativa, inserindo vértices e arestas, além de visualizar sua representação matricial e realizar operações básicas da Teoria dos Grafos.

Este projeto foi desenvolvido com fins acadêmicos para estudo da disciplina de Estruturas de Dados e Teoria dos Grafos.



Funcionalidades

O sistema possui um menu interativo que permite:

Inserir arestas no grafo
Exibir a Matriz de Incidência
Calcular o grau de um vértice específico
Exibir o grau de todos os vértices
Listar todas as arestas existentes
Limpar completamente o grafo
Encerrar o programa


Conceitos abordados
Grafos
Matriz de Incidência
Vértices
Arestas
Grau de um vértice
Estruturas de Dados
Programação em C
Manipulação de Matrizes


Tecnologias utilizadas
Linguagem C
Biblioteca padrão <stdio.h>
   Estrutura do Projeto
   Grafo-Matriz-Incidencia
      │
      ├── main.c
      └── README.md


Como funciona

O programa solicita inicialmente o número de vértices.

Após isso, apresenta um menu com as opções disponíveis.

=========================
   MENU - GRAFO
=========================
1 - Inserir aresta
2 - Mostrar matriz
3 - Grau de um vértice
4 - Graus de todos os vértices
5 - Listar arestas
6 - Limpar grafo
0 - Sair

Cada aresta inserida conecta dois vértices e é armazenada na matriz de incidência.


Exemplo de utilização
Entrada
Número de vértices: 4

Inserir aresta:
(0,1)

Inserir aresta:
(0,2)

Inserir aresta:
(1,3)
Saída
MATRIZ DE INCIDENCIA

      e0  e1  e2
v0    1   1   0
v1    1   0   1
v2    0   1   0
v3    0   0   1

Graus dos vértices

Grau(0) = 2
Grau(1) = 2
Grau(2) = 1
Grau(3) = 1


Estrutura da Matriz de Incidência

Na matriz de incidência:

Cada linha representa um vértice.
Cada coluna representa uma aresta.
O valor 1 indica que o vértice pertence àquela aresta.
O valor 0 indica ausência de incidência.

Exemplo:

      e0 e1 e2
v0    1  1  0
v1    1  0  1
v2    0  1  0
v3    0  0  1


Como compilar
GCC
gcc main.c -o grafo
Executar
Windows
grafo.exe
Linux / macOS
./grafo


Autor
Eduardo Nascimento

Estudante de Engenharia da Computação

Licença
Este projeto está disponível para fins de estudo e aprendizado. Sinta-se à vontade para utilizá-lo e adaptá-lo para projetos acadêmicos.
