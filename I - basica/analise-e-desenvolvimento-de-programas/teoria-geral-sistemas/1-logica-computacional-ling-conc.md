# Conceitos de lógica de programação

De forma geral a lógica representa dois aspectos: o estudo normativo e filosófico do raciocínio, e em outro, estuda os pensamentos em geral, e desta forma temos que não se constitui em um único conceito fechado, mas que se admite estar ligada a matemática, com a lógica formal, além de relacionada diretamente a toda e qualquer área do conhecimento e com isso,

Inicialmente, era ligada à matemática (lógica formal) e, atualmente, está relacionada a todas as áreas do conhecimento humano. Podemos relacionar a lógica com a “correção do pensamento”, pois uma de suas preocupações é determinar quais operações são válidas e quais não são, fazendo análises das formas e leis do pensamento. Como filosofia, ela procura saber por que pensamos assim e não de outro jeito; como arte ou técnica, ela nos ensina a usar corretamente as leis do pensamento (FORBELLONE; EBERSPACHER, 2005; MORAIS 2018, p. 09)

 

Dentro deste universo temos o algoritmo, ou seja, um conjunto de passos que orienta a realização de determinada tarefa, e que embora não seja explicitamente ou obrigatoriamente ligado a tecnologia, a todo momento alguma forma de algoritmo é criada em algum lugar.

Os algoritmos são, em essência, construções de pura lógica, pois também possuem (ao menos deveriam possuir) coerência e racionalidade. Para a lógica de programação, o algoritmo representa processos racionalizados formais que tem a intenção de alcançar certos objetivos. Neste universo entram em cena os números, parte do que viabiliza a lógica atual de programação, e que apresentam os seguintes tipos:

Inteiros: é um número que não possui casas decimais; por exemplo, a idade de uma pessoa ou uma quantidade de itens em estoque.
Real: é um número que possui casas decimais, ou seja, é um número fracionário; por exemplo, a altura de uma pessoa ou o peso de um determinado produto.
Literal ou String (Alfanuméricos): são os textos, que podem conter letras, números e caracteres especiais. Não são utilizados para cálculos.
Booleano (lógicos): é um dado que só pode conter 2 informações (verdadeiro ou falso. (MORAIS, 2018, p. 11)
 

Dentro da lógica de programação os números entram nas expressões, que assim como na matemática, são as sequências de operações feitas através de representações simbólicas, ou seja, entre operadores e operandos, buscando um resultado. Portanto, os algoritmos se fazem valer de dois tipos de expressões: as lógicas e as aritméticas. As expressões aritméticas possuem operadores aritméticos e operandos constantes, mas variáveis do tipo inteiro ou real. A seguir temos os operadores aritméticos:

Soma:                             +
Divisão:                          /
Quociente de divisão inteira:     Div
Radiciação:                     //
Subtração:                      -
Multiplicação:                            *
Resto da Divisão:            Mod (MORAIS, 2018, p. 13)
 

A seguir temos um exemplo que demonstra uma divisão aritmética em forma lógica:

10 div 3 = 3 10 mod 3 = 1 3 div 5 = 0
25 div 5 = 5 25 mod 5 = 0 3 mod 5 = 3
 

Figura: Exemplo de operação de Divisão aritmética


As funções matemáticas, dentro da lógica de programação, vão realizar cálculos de dados entregues pelo usuário e cujos tipos mais comuns constam a seguir:

Quadro: Funções matemáticas


Tanto para a matemática pura, quanto dentro da lógica de programação existe a precedência entre os operadores, que indicam, dentro de uma função, quais operadores são acionados primeiro, o que se feito em qualquer ordem afeta o resultado invalidando a operação. Com isso temos que nas funções, devem ser executados os cálculos primeiro em:

Parênteses mais internos, em seguida

Funções matemáticas, onde primeiro vem:

Multiplicação e divisão; seguido das demais

Soma e subtração. (MORAIS, 2018, p. 14)

Por fim, se a função apresentar diversos operadores com a mesma precedência, o correto será aplicar e executar as operações no sentido da esquerda para a direita, conforme constam na função. A seguir temos alguns exemplos de como aplicar a precedência dos operadores:

5 + 9 + 7 + 8 / 4
5 + 9 + 7 + 2 = 23

1 - 4 · 3 / 6 - 2 · 3
1 - 4 · 3 / 6 - 8

1 - 12 / 6 - 8

1 - 2 - 8 = -9

3 · 2 - 4 / 2 + abs (5 - 3 · 5) / 2
3 · 2 - 4 / 2 + abs (5 - 15) / 2

3 · 2 - 4 / 2 + abs (-10) / 2

3 · 2 - 4 / 2 + 10 / 2

9 – 4 / 2 + 10 / 2

9 - 2 + 5 = 12 (MORAIS, 2018, p. 14)

 

Podemos concluir que a lógica de programação tem sua base na lógica da matemática e com isso vai usurpar de muitas regras comuns em ordem de manter coerente seus códigos, criando programas sofisticados e de qualidade.

 

 

Linguagens de Programação

 

 

A lógica de programação, a matemática, os algoritmos somados levaram a criação das linguagens de programação e com isso podemos dizer que toda a produção de software de décadas atrás passou a ser consideravelmente acelerada, pois uma linguagem de programação representa um método padronizado, um conjunto de regras. E na verdade esta criação humana não é nada nova, pois

Existem relatos de linguagens de programação muito antes de 1940, que foi quando as primeiras linguagens de programação modernas e os computadores começaram a surgir. As linguagens de programação no começo eram códigos matemáticos. A ideia de uma linguagem de programação era um código especializado para uma aplicação. As linguagens de programação surgiram da evolução da lógica matemática, no qual abstraía conceitos complexos da matemática e podia ser utilizada para resolver problemas específicos. (BERTOLINI 2019, p. 13)

 

Em muitos aspectos o processo de criação de um sistema, ou seja, da programação de um computador, tem similaridades com a estrutura dos projetos administrativos, pois começa com a análise da necessidade do cliente e de que forma o processo pode ser traduzido em instruções de máquina. Com isso, a primeira etapa ocorre na concepção do próprio programador a respeito de como ele imagina que deve usar de seus conhecimentos e da linguagem de programação, para dar vida ao programa.

Com isso o programador escreve seu diagrama de blocos, o que o permite realizar o pseudocódigo, ou seja, a linguagem de projeto de programação. A próxima etapa será a codificação em si, onde o programa recebe suas primeiras linhas de comando em português estruturado, que de acordo com Manzano (2016) representa uma linguagem de programação estruturada, mas orientada a objetos informal, pois não gera um software real. Apenas com uma linguagem de programação formal o software é criado.

É possível que existam mais de 700 diferentes linguagens de programação em uso no planeta hoje, ou seja, muito mais linguagens de programação que idiomas falados. Claro que existem as linguagens mais difundidas, mais populares, mas se forem levadas em conta todas elas, até as exclusivas de algumas empresas, o número certamente passa das 2.500. O que é argumento irrelevante para Manzano (2016, pg. 40), pois,

Na prática computacional não importa a linguagem de programação formal existente, pois qualquer programa escrito em qualquer linguagem deve ser traduzido para ser executado em um computador segundo a linguagem interna do próprio computador, que é baseada num formato binário. Assim sendo, um programa escrito em Pascal, C, C++, Assembly ou outra linguagem qualquer deve ser traduzida para o computador para nele ser executada. A tarefa de tradução de uma linguagem formal para a máquina poderá ser feita por um compilador ou interpretador.

 

Se pensarmos na programação do ponto de vista de seu produto final, vamos reconhecer o computador pessoal como sendo um pacote de instruções ordenadas (ao menos sua parte lógica), que condicionam o que pode e como pode fazer algo. Neste sentido, os programas podem ser percebidos como sendo os responsáveis pela manipulação dos dados do usuário para com isso fornecer informações e até mesmo outros dados. Portanto os computadores dependem que lhes sejam informados os dados e os programas capazes de manipular tais dados.

Isso é uma regra geral, uma lógica mais profunda na programação, ou seja, todo computador, independentemente de seu hardware ou software, é construído para manipular dados através de funções por ele executadas. Mas vale ressaltar que entre uma linguagem e outra existirão certas ações que poderão ou não ser executadas, mas não podemos pensar neste aspecto como somente uma questão de qualidade ou falta de, pois

É errado dizer que uma linguagem não presta e que outra é melhor. Não existe esta possibilidade, pois cada linguagem de programação atende certa classe de problemas. Assim sendo, uma linguagem excelente para solucionar certo problema pode ser péssima para solucionar outro tipo de problema. A ciência da programação está em saber qual é a melhor linguagem para aquele tipo de problema e para responder a esta questão é que existem os analistas de sistemas, pois não cabe ao programador traçar este tipo de julgamento. Um analista de sistemas deve possuir entre suas várias competências, a capacidade de perceber e orientar qual é a melhor linguagem para a classe de problema que efetuou sua análise.

Assim como qualquer produto ou serviço que for desenhado para servir a um propósito geral (pense nas roupas tamanho único, por exemplo), existem linguagens de programação de uso geral que terão eficácia em uma grande variedade de aplicações, mas que em casos mais específicos podem não oferecer a verdadeira solução ao problema.

Com esta profusão de linguagens, é preciso uma classificação que facilite a sua escolha pelos programadores, com isso podemos dividir em dois grandes grupos: as de estilo dinâmico e as de estilo estático.

As linguagens tipificadas como dinâmicas são as que apresentam a capacidade de escolher o tipo de dado de acordo com o dado em si, assim como pode ser observado no PHP. “Como exemplo de linguagens de estilo estático podem ser citadas as linguagens Pascal, C, C++, entre outras, e como linguagens de estilo dinâmico podem ser citadas as linguagens Lua, Classic BASIC, entre outras.” (MANZANO 2016, p. 41)

Dentro do universo da programação, o bom programador, o que se diz experiente, jamais vai levantar a bandeira de uma única linguagem de programação como sendo sua única forma de se desenvolver um sistema, pois no final das contas, seu conhecimento lhe permite utilizar ao menos todas as mais populares, com grande confiança.

 

 

Tipos de dados (primitivos)

 

 

A razão de existir de um programa não é necessariamente seu objetivo, após compilado, e sim sua capacidade de lidar com dados. Neste sentido devemos compreender que existem diversos tipos de dados. De acordo com Sebesta (2019) podemos conceituar os tipos de dados como uma coleção de valores de dados junto com um conjunto de operações definidas sobre estes dados.

Vale ressaltar que os sistemas tendem a realizar suas tarefas com maior eficiência se os tipos de dados forem bem compreendidos e isso sendo utilizado para a escolha da melhor linguagem de programação que se adapte ao problema a ser tratado, trocando em miúdos, o tipo de dado certo significa sua maior semelhança com o mundo real.

Nesta dinâmica temos os tipos de dados primitivos, aqueles que não são definidos em termos de outros dados e são compatíveis com a esmagadora maioria das linguagens de programação. E por um lado, de acordo com Sebesta (2019), temos os tipos primitivos reflexo do hardware, como os tipos inteiros, e por outro lado temos os que exigem algum suporte externo ao hardware em ordem de serem implementados.

Os tipos numéricos são a base de constituição das primeiras linguagens de programação, mas que ainda desempenham um papel de destaque nos tipos suportados nas linguagens de programação modernas. O quadro a seguir resume os tipos de dados primitivos:

Quadro 01: Tipos Numéricos



Os tipos de dados primitivos mais simples são os booleanos, pois sua faixa de valores tem apenas 2 elementos: o verdadeiro e o falso. A introdução dos tipos booleanos foi no ALGOL 60 assim como em praticamente todas as outras linguagens gerais desde este período, exceto na C89.

A linguagem C89 usava expressões numéricas como condicionais. Mas existe uma diferenciação no C99, o fato de que usam o tipo booleano e com isso são capazes de trabalhar com expressões numéricas no lugar das booleanas. E “Tipos booleanos'' são geralmente usados para representar escolhas ou como flags em programas. Apesar de outros tipos, como inteiros, poderem ser usados para tais propósitos, o uso de tipos booleanos é mais legível.” (SEBESTA 2019, p. 239)

 

Um valor booleano poderia ser representado por um único bit, mas, como um único bit de memória não pode ser acessado de maneira eficiente em muitas máquinas, eles são armazenados na menor célula de memória eficientemente endereçável, um byte.

Apenas um bit é necessário para que um valor booleano possa ser representado, mas não se constitui um sistema eficiente e necessite acessar sua memória bit por bit. Algo que também é armazenado pelos computadores são os caracteres. Uma das codificações numéricas dos caracteres mais popular é o Padrão Americano de Codificação para Intercâmbio de Informação (ASCII – American Standard Code for Information Interchange) de 8 bits, trabalhando com a faixa entre o valor 0 e o 127 era capaz de codificar até 256 caracteres.

Existem muitas disciplinas de diversas matrizes do ensino superior que vão dialogar sobre algum efeito da globalização, e aqui não é diferente, pois com a globalização acelerou a adoção de computadores nas empresas e em suas operações de negócios internacionais, o que demandou uma mudança na escolha do conjunto de caracteres ASCII.

Com isso surge em 1991 o padrão UCS-2, criado pelo Unicode e que representava um conjunto de caracteres de 16 bits que englobava a maioria das linguagens naturais existentes na época, como por exemplo, o Cirílico da Sérvia, o Tailandês, etc. Um fato interessante é que a primeira parte, os 128 primeiros caracteres do USC-2 é a mesma do ASCII e teve o Java como primeira linguagem a fazer uso de sua codificação Unicode, seguido por JavaScript, Python, Perl, C# e F#. (SEBESTA 2019)

Nos anos seguintes nasceu o USC-4 em cooperação entre a Unicode e a ISO (International Standards Organization, ou Organização Internacional de Padrões). O UCS-4 apresentava codificação de 4 bytes.

Expressões Lógicas

 

De forma geral podemos definir as expressões lógicas como sendo expressões algébricas com operadores lógicos e operandos que podem ser relacionais ou variáveis lógicas.

Neste sentido, de acordo com Moraes (2018, pg. 15) as “Expressões lógicas são aquelas cujos operadores são lógicos e/ou relacionais e cujos operandos são relações e/ou constantes e/ou variáveis de tipo lógico.” Portanto, os resultados possíveis de uma expressão lógica somente podem assumir uma constante lógica sendo F para falsa ou V para verdadeira. Na figura a seguir estão descritos os operadores relacionais, responsáveis pelas operações das expressões lógicas:

Figura 1: Operadores relacionais


Exemplo de cálculo seguindo as prioridades e apresentando o uso de operadores relacionais:

2 + (8 – 7) > = 3 · 6 - 15

2 + 1 > = 18 - 15

3 > = 3 V

Quando certas condições necessitam de que dois ou mais relacionamentos lógicos precisam ser verdadeiros, entra em cena o operador lógico, e desta característica podemos tirar sua forma de financiamento. O quadro a seguir apresenta os símbolos e funções dos operadores lógicos:

Figura 2: Operadores lógicos


A seguir temos exemplos de operações feitas com os operadores lógicos:

Quadro 1: Exemplos de operadores óticos



Portanto, o operador lógico NÃO, de acordo com Moraes (2018, p. 17) pode ser utilizado quando é preciso estabelecer por fato que “uma determinada condição dever ser não verdadeira ou deve ser não falsa. O operador lógico NÃO se caracteriza por inverter o estado lógico de uma condição, isto é, inverter o resultado lógico da condição.”. Observe o exemplo de sua aplicação a seguir:

Algoritmo prog1

Var A, B, C, X: Inteiro

Início Ler (X, A, B)

SE NÃO (X > 5)

Então C: = (A + B) · X Se não

C: = (A – B) · X

Fim-SE

Escrever (C)

Fim

 

Sendo a lógica matemática a base para a lógica da programação, temos na tabela verdade uma importante ferramenta capaz de apresentar o valor lógico de qualquer proposição e com isso conhecer seu status, se é verdadeira ou falsa, e com isso, temos que “A tabela verdade é o conjunto de todas as possibilidades combinatórias entre os valores de diversas variáveis lógicas, as quais se encontram em apenas duas situações, é um conjunto de operadores lógicos.” (MORAIS 2018, p. 17).

Figura 3: Conjunto de oportunidades dos Operador E, OU e NÃO


Sobre as prioridades dos operadores lógicos, temos que NÃO sempre precede OU, e entre todos os operadores lógicos temos que preceder os parênteses mais internos, seguidos de funções matemáticas, operadores aritméticos, relacionais e lógicos.

 

 

Atividade Extra

 

 

Está no centro das atenções os algoritmos das principais redes sociais e vem se destacando quem compreende seu funcionamento. Esta dica é para quem deseja saber mais sobre como funciona o algoritmo do Instagram, basta acessar o vídeo: https://www.youtube.com/watch?v=TrbuQ0iehRo

 

 

Referência Bibliográfica

 

 

BERTOLINI, Cristiano... [et al.]. Linguagem de programação I.Santa Maria, RS: UFSM, NTE, 2019. Disponível em: <https://www.ufsm.br/app/uploads/sites/358/2020/02/linguagem-1.pdf > Acesso em: 13/05/2021.

 

MANZANO, José Augusto N. G. Algoritmos: Logica para desenvolvimento de programação de computadores.São Paulo: Érica, 2016.

 

MORAIS, Izabelly Soares de... [et al.]. Algoritmo e programação (engenharia). Porto Alegre: SAGAH, 2018.

 

SANTOS, Marcela Gonçalves dos. Algoritmos e programação.Porto Alegre: SAGAH, 2018.

 

SEBESTA, Robert W. Conceitos de linguagens de programação.Porto Alegre: Bookman, 2018.