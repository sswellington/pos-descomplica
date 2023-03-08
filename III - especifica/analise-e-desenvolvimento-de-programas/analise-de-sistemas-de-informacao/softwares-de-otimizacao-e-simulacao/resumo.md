Modelagem de Dados

A modelagem é utilizada em diferentes organizações a fim de representar possíveis cenários e auxiliar na tomada de decisões. Com a utilização de técnicas de otimização, é possível identificar a alocação ideal de recursos, máquinas e equipamentos, a quantidade de itens a serem produzidos, entre outras decisões que possam minimizar custos ou maximizar lucros, dependendo da situação desejada. Para que um problema de otimização seja resolvido, existem restrições, como por exemplo a demanda máxima de um produto, a quantidade de horas trabalhadas em um dia ou o número de operadores disponíveis. Para desenvolver um modelo de otimização é necessário definir o objetivo e as restrições, utilizando a programação matemática, ou simplesmente, equações matemáticas. O primeiro passo para se obter uma otimização é estabelecer relações entre os dados de uma determinada situação. Vamos ver um exemplo:

Uma fábrica de computadores produz 2 modelos de computador: A e B. O modelo A fornece um lucro de R$ 180,00 e B um lucro de R$ 300,00. O modelo A requer, na sua produção, um gabinete pequeno e uma unidade de disco. O modelo B requer 1 gabinete grande e 2 unidades de disco. Existem no estoque: 60 unidades do gabinete pequeno, 50 do gabinete grande e 120 unidades de disco. Pergunta-se: qual deve ser o esquema de produção que maximiza o lucro?

Neste caso, devemos escrever o modelo matemático que represente o problema. Este modelo contém três elementos, denominadas variáveis de decisão, função objetivo e restrições. As variáveis de decisão são as quantidades de computadores dos modelos A e B, que podem ser chamadas simplesmente de A, B. A função objetivo, é o lucro, matematicamente descrita por:

Lucro = 180 A + 300 B.

As restrições deste problema estão associadas às limitações de número de peças em estoque, denominadas gabinete pequeno, gabinete grande e disco. Sendo assim, as restrições podem ser definidas como:

(Gabinete pequeno) A ≤ 60.

(Gabinete grande) B≤ 50.

(Disco) A+ 2B ≤ 120.

Para encontrar a resolução deste problema vamos utilizar uma ferramenta do Microsoft Excel denominada Solver. Para ativar essa ferramenta, clique em Ferramentas + Suplementos e ative o Solver. Observe como o problema é modelado no Microsoft Excel.


Usando o Arena em Simulação

Simulação é uma palavra que recebe várias definições, mas é de conhecimento geral que, quando alguém “simula” algo, está reproduzindo ou imitando alguma coisa. A simulação reproduz o comportamento dinâmico de sistemas como células produtivas, transporte e armazenagem, siderurgia, centrais de atendimento telefônico, entre outros. Permitindo medir seu desempenho e testar novas situações. Um dos softwares amplamente utilizado para realizar simulação é o Arena. Este sistema tem um conjunto de blocos (ou módulos) que são utilizados para descrever uma aplicação real. Esses blocos funcionam como comandos de uma linguagem de programação como o Fortran, Cobol, VB, Delphy, etc. Obviamente foram projetados sob a ótica da simulação e, por isso, facilitam muito a tarefa de programação (PRADO e YAMAGUCHI, 2019).

Para simplificar o processo de construção de modelos, o ARENA usa uma interface gráfica para o usuário (ou GUI – Graphical User Interface), que automatiza o processo e reduz a necessidade do teclado pois o mouse é a ferramenta principal utilizada.

 

Aplicação no Arena

Considere o seguinte problema:

Navios chegam a um porto a um intervalo de EXPO (8) horas e gastam TRIA (3,5,10) horas para descarregar. Faça o diagrama de blocos e submeta-o ao ARENA. Simule 8760 horas (1 ano).

Neste caso, observe como fica representado o diagrama de blocos no Arena após a simulação.


A representação indica que no período de um ano, 1152 navios entraram no porto para realizar o processo de descarga. No momento final da simulação, haviam 4 navios na fila e 1148 navios completaram o processo de descarga. O software Arena disponibiliza um relatório com as informações detalhadas da simulação, que permitem identificar que a taxa de ocupação do porto foi de 78,65%, enquanto a fila atingiu um valor máximo de 10 navios em espera. O tempo médio de espera na fila foi de 10 horas. A partir dessa resposta, é possível identificar que a capacidade do porto deve ser aumentada, uma vez que os tempos de espera e o tamanho da fila são longos. O experimentador poderia simular o que aconteceria caso fossem inseridos novos pontos de descarga.



Atividade Extra

Ficou curioso sobre como funciona o Arena? Acesse o link a seguir e faça a instalação da versão estudante em sua máquina.

https://www.paragon.com.br/arena-academico-student/

Para aprender mais sobre os módulos e funcionalidades do Arena, sugere-se a leitura do livro intitulado “Usando o Arena em Simulação” dos autores Darci Prado e Magno Yamaguchi.

 

Referência Bibliográfica

PRADO, D; YAMAGUCHI, M. Programação Linear Série Pesquisa Operacional. 7ª ed. Nova Lima: Falconi Editora, 2016.

 

PRADO, D; YAMAGUCHI, M. Usando o Arena em Simulação. 6ª ed. Nova Lima: Falconi Editora, 2019.

 

STAIR, R.M; REYNOLDS, G.W. Princípios de Sistemas de Informação. São Paulo: Cengage Learning, 2018.