Linguagem Java

Stair e Reynolds (2018, p. 314) definem Java como “Uma linguagem de programação orientada a objeto da Sun Microsystems com base em linguagem C++, que permite aos pequenos programas, denominados applets, serem embutidos em um documento HTML”.

A linguagem Java foi concebida em 1991, devido à necessidade de uma linguagem independente de plataforma que pudesse ser usada na criação de software embutido em vários dispositivos eletrônicos domésticos, como torradeiras, fornos de micro-ondas e controles remotos. Entretanto, a internet ajudou a impulsionar Java, afinal, era necessário simplificar a programação geral na Web, além de resolver problemas de portabilidade e segurança (HERBERT, 2015).

A linguagem Java inovou com um tipo de programa de rede chamado applet. Um applet é um tipo especial de programa Java projetado para ser transmitido pela Internet e executado automaticamente por um navegador Web compatível com Java. Além disso, ele é baixado sob demanda, sem nenhuma interação com o usuário. Se o usuário clicar em um link que contém um applet, este será automaticamente baixado e executado no navegador. Os applets são projetados como programas pequenos. Normalmente, são usados para exibir dados fornecidos pelo servidor, tratar entradas do usuário ou fornecer funções simples, como uma calculadora de empréstimos que é executada localmente em vez de no servidor. Basicamente, os applets permitem que uma funcionalidade seja movida do servidor para o cliente.

Para que possamos compreender sobre as funções dos applets, é necessário distinguir duas grandes categorias que são transmitidas entre o servidor e o cliente: informações passivas e programas dinâmicos. Quando você navega no Instagram, está visualizando dados passivos. Quando você faz o download de um programa, até que você o execute, você está interagindo com dados passivos. Já os dados ativos, dinâmicos, são aqueles de execução automática, ou seja, os apletts; Já que esses programas dinâmicos de rede são tão desejáveis, eles também têm que evitar problemas sérios nas áreas de segurança e portabilidade. É claro que um programa que é baixado e executado automaticamente no computador cliente deve ser impedido de causar danos. Ele também deve poder ser executado em vários ambientes diferentes e em sistemas operacionais distintos (HERBERT, 2015).

 

Obtendo o Java Development Kit

O Java Development Kit (JDK) é uma ferramenta utilizada para aplicações Java. O site da Oracle disponibiliza o download da versão Java SE (Standard Edition) gratuitamente. Esta versão permite o desenvolvimento de aplicações desktop de linha de comando e interfaces gráficas Swing.

Para fazer o download acesse o seguinte link: https://www.oracle.com/downloads/

Na página inicial, selecione a opção “JAVA”, em seguida escolha “JavaSE” e selecione o sistema correspondente à sua máquina. Faça o download do arquivo com terminação .exe, a fim de que a instalação seja executada. Aceite todos os passos necessários. Após a instalação, execute o prompt de comando da sua máquina e digite os comandos java –version e em seguida, javac para verificar se as instalações estão em funcionamento.

Agora, vamos executar um programa simples.

No Disco Local (C:) crie uma pasta denominada Java para armazenar o código que será criado. Abra um editor de texto. Uma sugestão é o “Notepad++, que pode ser adquirido gratuitamente pelo seguinte link:

https://notepad-plus-plus.org/downloads/

Crie o novo arquivo, ajustando para a linguagem Java (caso o editor permita). Digite o código conforme representado na Figura 1.

Exemplo de programa na Linguagem Java
Exemplo de programa na Linguagem Java

Agora, siga o seguinte passo a passo:

Salve o arquivo na pasta Java, com o nome Exemplo.java. (Observação: o nome do arquivo deve ser o mesmo nome contido em public class.
Execute o prompt de comando.
 Digite cd \java
Digite dir
Digite javac Exemplo.java
Digite dir e observe que foi criado um arquivo denominado class.
Agora, digite Java Exemplo e observe a mensagem de boas-vindas!
 

Aplicação Java

Muitos serviços oferecidos na web são entregues por programas e scripts. Um programa da web pode ser algo tão simples como um menu que se expande quando você clica nele ou tão complicado como um aplicativo completo de planilha. Os serviços de software liberados na web podem ser executados nos servidores web, distribuindo os resultados do processamento para o usuário, ou podem também ser executados diretamente no PC do usuário. Essas duas categorias são comumente chamadas software voltado ao cliente e ao servidor (STAIR E REYNOLDS, 2018).

É muito importante que não se confunda JavaScript com Java, uma vez que o desenvolvimento JavaScript é voltado para o cliente, enquanto Java é uma linguagem voltada para o servidor. O JavaScript pode ser usado para validar a entrada de dados em um formulário web, exibir fotos em um estilo de apresentação de slides, incorporar jogos de computador simples em uma página web e fornecer uma calculadora de conversão de moeda.

Por outro lado, Java permite aos applets serem embutidos em um documento denominado HTML. Java refere-se tanto a uma linguagem de programação quanto a uma plataforma. Quando um usuário clica na parte apropriada de uma página HTML para recuperar um applet de um servidor web, ele é baixado para a estação de trabalho do cliente, onde ele começa a executar. Diferentemente de outros programas, o software Java pode ser executado em qualquer tipo de computador. Ele pode ser utilizado para desenvolver diversas aplicações na internet. Os programadores usam Java para obter páginas web mais vivas, adicionando gráficos chamativos e fáceis de notar, animações e atualizações em tempo real.

De acordo com Laudon e Laudon (2014), a linguagem Java migrou para telefones celulares, smartphones, automóveis, players de música, máquinas de jogo e finalmente, sistemas interativos de televisão a cabo que oferecem serviços de conteúdo interativo.  O software Java foi projetado para executar em qualquer computador ou dispositivo de computação, independente de microprocessadores específicos ou do sistema operacional usado. Para cada um dos ambientes de computação no qual o Java é usado, a Sun Microsystems criou uma Máquina Virtual Java (Java Virtual Machine) que interpreta o código de programação Java para essa máquina. Dessa forma, o código é escrito uma vez e pode ser usado em qualquer máquina para a qual existe uma Máquina Virtual Java.

 

Significados de comandos

Conforme pode ser observado na Figura 1, existem normas de sintaxe e semântica a serem seguidas na linguagem Java. Seguem alguns significados de comandos básicos.

// permite inserir um comentário em uma linha
 Uma classe é um modelo que define a forma de um objeto. Ela especifica tanto os dados quanto o código que operará sobre eles. Java usa uma especificação de classe para construir objetos. Os objetos são instâncias de uma classe. Logo, uma classe é basicamente um conjunto de planos que especifica como construir um objeto. Uma classe é uma abstração lógica. Só quando um objeto dessa classe é criado é que existe uma representação física dela na memória. Uma classe bem projetada deve definir apenas uma entidade lógica e agrupar informações logicamente conectadas. A inserção de informações não relacionadas na mesma classe desestruturará o código.
O método main( ) é necessário quando a classe é o ponto de partida do programa. Alguns tipos de aplicativos Java, como os applets, também precisam de um método main( ).
Public class significa que o método é visível e pode ser chamado de outros objetos de outros tipos.  As classes também podem ser do tipo private, protected, packagee e packafe private.
Agora, vamos entender a expressão public static void main (String args[]) Neste caso, tem-se uma classe pública; static significa estático, que o método está associado à classe, não a uma instância específica (objeto) dessa classe; void significa que o método não tem valor de retorno. Se no lugar de void estivesse int, isso significa que o método retornaria um número inteiro.
 Main é a porta de entrada para executar o programa. Por esse motivo ele é estático e não retorna valor
Stringargs [] é utilizado para que o programa seja executado pelo prompt de comando.
System.out.println é o comando que imprime o texto a ser executado.
 

Atividade Extra

Recomenda-se a leitura do livro “Java para iniciantes: crie: compile e execute programas Java rapidamente. ” do autor Herbert Schildt.  O livro é ideal para quem nunca programou e deseja aprender a compilar programas e interpretar códigos Java.

 

Referência Bibliográfica

HERBERT, S. Java para iniciantes: crie: compile e execute programas Java rapidamente.  6ª ed. Porto Alegre: Bookman, 2015.

 

LAUDON, K.C; LAUDON, J.P. Sistemas de Informação gerenciais. São Paulo: Pearson Education do Brasil, 2014
 

STAIR, R.M; REYNOLDS, G.W. Princípios de Sistemas de Informação. São Paulo: Cengage Learning, 2018.