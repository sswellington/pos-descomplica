# Estruturas de dados avançadas

Nesse módulo foram mostradas as estruturas de dados clássicas, como as árvores auto balanceadas, destacando suas aplicações no universo computacional e pequenas partes de código mostrando suas implementações. Outras estruturas que merecem destaque são o Hash, Heap e a Partição Dinâmica, cujas aplicações são de extrema importância nos campos da segurança da informação, filas de prioridades e junção de conjuntos disjuntos, para manipulação de banco de dados. Por fim, foi apresentada a estrutura de dados conhecida como grafo, suas aplicações em complexidade de algoritmos e seus principais algoritmos.

Na ciência da computação, uma Estrutura de Dados (ED) representa um modo específico de armazenamento e organização de dados, ao passo que possam ser usados eficientemente, facilitando diretamente as busca e modificação. No momento em que estes dados estão dispostos de forma coerente, representam uma forma, uma estrutura de dados. O trabalho e os métodos para manipular essa estrutura e que lhe confere uma particularidade (como a minimização do espaço ocupado na memória RAM), além de tornar o código-fonte mais sucinto e simples. O destaque para as principais estruturas de dados clássicas:

• Vetor: Um arranjo (array) é uma estrutura de dados que guarda uma coleção de elementos de tal forma que cada um dos elementos possa ser apresentado por, pelo menos, um índice ou uma chave.

• Lista: Uma lista ou sequência é uma estrutura de dados abstrata que forma uma coleção ordenada de valores, onde o mesmo valor pode ocorrer mais de uma vez.

• Pilha: Uma pilha (stack) é um tipo abstrato de dado e estrutura de dados baseado no princípio de Last In First Out (LIFO), isto é, "o último que entra é o primeiro que sai" caracterizando uma organização de dados.

• Fila: o primeiro elemento a sair é o primeiro que entrar, onde um algoritmo de escalonamento não preemptivo que entrega processos por chegada a CPU.

• Árvore: diferente das listas, em que os dados estão numa sequência, nas árvores os dados estão dispostos de forma hierárquica, seus elementos se encontram "acima" ou "abaixo" de outras partes da árvore.

 

Uma árvore binária de busca balanceada ou árvore binária de busca auto-balanceada pode ser qualquer árvore de busca binária que mantém a sua altura menor mesmo depois de sucessivas inserções e exclusões arbitrárias.

Árvore AVL (ou árvore balanceada pela altura) é uma árvore de busca binária auto-balanceada. Em tal árvore, a altura de dois nós, folha, difere no máximo em uma unidade. As operações de busca, inserção e eliminação de elementos possuem complexidade 0. O balanceamento é requerido para as operações de adição e exclusão de elementos.

Uma função hash é um algoritmo que organiza dados de comprimento variável para dados de comprimento fixo. A função hash também é útil em criptografia. A função hash criptográfica possibilita verificar facilmente alguns mapeamentos de dados de entrada para um valor hash fornecido, mas se conhecemos os dados de entrada, é extremamente difícil reconstruí-lo (ou alternativas equivalentes) conhecendo o valor do hash guardado.

O heap é uma estrutura de dados formada em árvore especializada que é particularmente uma árvore quase completa que atende a propriedade heap: em um heap máximo, para qualquer nó C dado, se P for um nó pai de C, então a chave de P é maior ou igual à chave de C. Em uma pilha mínima, a chave de P é menor ou igual à chave de C. O nó no "topo" da pilha é chamado o nó raiz.

A Partição Dinâmica é uma estrutura de dados de conjuntos disjuntos (Disjoint-set data structure), também conhecida como "Union Find" ou ainda "Merge Find", é uma estrutura de dados que manipula um conjunto de elementos disjuntos particionados em subconjuntos.

A teoria dos grafos é um campo da matemática que estuda as relações entre os objetos de um determinado conjunto.

Dependendo do uso, arestas podem ou não ter direção, pode ser permitido ou não arestas ligarem um vértice a ele próprio e vértices e/ou arestas podem ter um peso associado.

Os grafos são frequentemente representados graficamente da seguinte maneira: é desenhado um círculo para cada vértice, para cada aresta é traçado um arco conectando suas extremidades. Para um grafo direcionado, seu sentido é indicado na aresta por uma seta.

 

 

 

Atividade Extra

O vídeo em que é apresentado o algoritmo de Dijkstra, bem como sua aplicação na teoria dos grafos, irá contribuir na consolidação dos elementos teóricos estudados neste módulo.

Link do vídeo: https://youtu.be/hsJBilAiZDY.

 

 

 

Referência Bibliográfica

SOMMERVILLE, I. Engenharia de  Software, 9ª Edição. Pearson  Education, 2011.

SOMMERVILLE, I. Software engineering 10th Edition. ISBN-10, 137035152, 18., 2015.

VALENTE, M. T. Engenharia de Software Moderna (Livro Digital)., 2020.

JEFFRIES, R.; ANDERSON, A.; HENDRICKSON, C.  Extreme programming installed. Addison-Wesley Professional., 2001.

REIS, E. The lean startup. New York: Crown Business, 27.   – MVP, 2011.

VALENTE, M. T. Engenharia de Software Moderna (Livro Digital). Disponível em: <https://engsoftmoderna.info/cap0.html>. Acesso em: 04 jun. 2021., 2020.

VELOSO, P., dos SANTOS, C., AZEREDO, P.; FURTADO, A. Estrutura de dados. Campus. Editra Campus, 1986.

MARINHO, A. L. Análise e modelagem de sistemas. Person Education do Brasil, 2016.

LIMA, D. Arrays em Java. www.plugmasters.com.br. Consultado em 21 de junho de 2012. Arquivado do original em 31 de maio de 2012

GOODRICH, M. T.; TAMASSIA, R. Estruturas de Dados e Algoritmos em Java 5ª ed. Porto Alegre: Bookman. ISBN 978-85-8260-018-4, 2013.

KNUTH, D. E. The Art of Computer Programming. 4, Fascicle 4: Generating All Trees—History of Combinatorial Generation. ISBN 978-0-321-33570-8., 2006.

 The MD4 Message-Digest Algorithm. April 1992. Disponível em: < https://www.ietf.org/rfc/rfc1320.txt >. Acesso em: 04 ago. 2021.

CORMEN, T. H.  INTRODUCTION TO ALGORITHMS. United States of America: The MIT Press Cambridge, Massachusetts London, England. pp. 151–152. ISBN 978-0-262-03384-8., 2009.

BIGGS, N.; LLOYD, E.; WILSON, R. Graph Theory, 1736-1936, Oxford University Press, 1986.