# Conceitos em Sistemas De Banco De Dados

 A computação sempre teve um elemento central diferente dos processadores, aqueles que enchem os noticiários e que ganham destaque ao nascer de uma nova geração, pois sua verdadeira vedete são os dispositivos e sistemas de armazenamento.

Um sistema não tem utilidade sem dados, muito menos pode ser construído sem alguma espécie de dados como bibliotecas, linhas de comandos, etc., com isso entram em cena os Sistema de Gerenciamento de Banco de Dados (SGBD), que de início podem ser considerados como a justificativa da importância dada aos dados, dentro de um computador.

Para Silberschatz (2020, p. 01) trata-se de uma coletânea de dados com inter-relação assistidos por alguns programas e “A coleção de dados, normalmente conhecida como banco de dados, contém informações relevantes para uma empresa. O principal objetivo de um SGBD é proporcionar uma forma de armazenar e recuperar informações de um banco de dados de maneira conveniente e eficiente.”

Os SGBD começaram a se popularizar na medida com que os dispositivos de armazenamento ganharam maior capacidade, motivados pelo eterno aumento na demanda por espaço em disco, algo visto com muito mais intensidade hoje. Portanto, os SGBD nasceram para lidar com grandes volumes de dados e com isso são capazes de promover sua estruturação, gestão e segurança.

Existe uma grande necessidade de investimento em SGBDs de maior segurança, pois na era da computação em nuvem, empresas e pessoas vem enviando para seus dispositivos de armazenamento dados cada vez mais sensíveis, críticos e com isso alvos certeiros de hackers e outros criminosos digitais, portanto segurança é SGBD e SGBD é segurança, assim como define Silberschatz (2020, p. 01):

Visto que a informação é tão importante na maioria das organizações, cientistas da computação têm desenvolvido um vasto conjunto de conceitos e técnicas de gerenciamento de dados. Esses conceitos e técnicas formam a essência deste livro. Este capítulo apresenta um resumo dos princípios dos sistemas de banco de dados.

 

 

Mas não podemos tratar dos SGBDs como simples barreiras protetoras capazes de armazenar documentos eletrônicos, são muito mais do que isso, pois a sua maior sistemática foge do armazenamento e cai na recuperação dos dados, ou seja, um SGBD é muito eficiente em entregar os arquivos que guarda e em permitir que inúmeras associações sejam feitas com os dados nele guardados, no que chamamos hoje de Big Data.

De acordo Pichetti, Vida e Paixão (2020, p. 12)Um banco de dados é uma coleção de dados relacionados que representam aspectos do mundo real (mini mundo ou universo de discurso). Mudanças no mundo real devem ser refletidas nesse ambiente. Desta forma podemos perceber que ter um banco de dados é uma função dentre tantas dos SGBDs.

Cada SGBD é construído de forma a agregar diversos sistemas, diversas funcionalidades que permitam ao usuário criar e manipular dados, em sua definição básica, mas que costuma também apresentar funcionalidades mais amplas como a definição, a construção, a manipulação e o compartilhamento dos dados que seu usuário cria. Na figura a seguir podemos identificar onde o SGBD entra, em relação ao usuário e aos dados.

Figura 1. Componentes de um sistema gerenciador de banco de dados


Um dos grandes destaques de um SGBD é permitir a consulta estruturada aos dados, um recurso que é amplamente utilizado quando se deseja criar relatórios e valorizado aos que partem para o Big Data, nome que representa na computação um grande volume de dados e que por este motivo necessita de SGBD capaz de armazenar grandes volumes com rapidez e segurança. Mas guardar não é o maior trabalho feito em um SGBD,

Outro mecanismo importante dos SGBDs é o compartilhamento de dados, que dá aos usuários a possibilidade de acessar simultaneamente o banco. Ou seja, o sistema controla os acessos e protege a integridade dos dados. (PICHETTI; VIDA; PAIXÃO 2020, p. 13)

Agora, estudante, você já deve ter compreendido que um SGBD ou até mesmo um “simples” banco de dados é algo que difere e muito do disco rígido (ou SSD) de seu computador pessoal, responsável por guardar seus arquivos pessoais, fotos, vídeos, documentos variados e aplicações.

SGBD e BD (Bancos de Dados) são sistemas de construção complexa, de arquitetura dedicada o que significa que um SGBD vai depender da forma com que for construído o BD, pois os detalhes de sua construção serão determinantes para a sua adequada implementação, pois,

A arquitetura de um banco de dados sofre grande influência do sistema de computadores no qual um SGBD está instalado. Logo, saber mensurar a capacidade de processamento exigida por um SGBD será determinante para a escolha da arquitetura mais adequada em um projeto.  (PICHETTI; VIDA; PAIXÃO 2020, p. 11)

A arquitetura do sistema computacional que vai abrigar o Banco de Dados e com isso seu SGBD, também influencia na estruturação do BD e implementação do SGBD e com isso os BDs podem ser centralizados, quando o BD se localiza em um único servidor (o servidor garante capacidade de armazenamento e tempo de resposta) com acesso a ele pelas aplicações ou clientes.

Figura 2. Tipos de arquiteturas dos sistemas de gerenciamento de banco de dados.


Ou ainda descentralizado, quando o BD se hospeda em múltiplos servidores, o que lhe concede a característica de descentralização dos dados armazenados. Se destaca pela autonomia local e facilidade de comunicação com os sistemas dos usuários.

 

Modelagem De Banco De Dados

 

Embora os bandos de dados dos sistemas e softwares fiquem por trás destes sistemas, ou seja, não fiquem disponíveis para acesso direto pelo usuário, podemos dizer que um dos momentos mais complexos e tensos do processo de construção de um software está na estruturação do seu banco de dados, pois desta base lógica serão viabilizadas as funções e especificações demandadas pelo cliente que solicita o seu desenvolvimento. Portanto o cuidado com o software final representa um BD de base bem construído, portanto representa uma estrutura prévia, ou seja,

Previamente à construção de bancos de dados, são utilizados padrões em textos e gráficos para modelar, sendo propostos três níveis de abstração de dados: modelo conceitual, modelo lógico e modelo físico. Como muitos usuários de banco de dados são leigos nas técnicas de informática, faz se necessário simplificar em um projeto a sua estrutura, para oferecer uma visão geral dos dados com os aspectos de interesse, possibilitando bancos de dados flexíveis (COUGO, 1997; PICHETTI; CORTES; PAIXÃO 2020, p. 32).

Mas claro que a modelagem de dados representa muito mais do que a estruturação do banco, pois trabalha nas inter-relações entre os dados que o BD vai abrigar avaliando seu contexto e com isso construindo um modelo que represente este contexto, de forma a permitir que os dados possam ser minerados e não apenas recuperados.

Figura 1. Etapas de modelagem de dados.


Diferenciar mineração de dados de recuperação significa que o primeiro é capaz de reaver dados em um determinado contexto, relacionado a um panorama, uma especificação, já recuperar um dado é simplesmente buscar por ele diretamente e o receber como resultado. Outro detalhe importante sobre a modelagem de dados é sua capacidade de abstrair estes dados e com isso o usuário final não precisa se preocupar com o processo. Para Machado (2020, p. 17), o modelo de dados representa,

[...] um conjunto de conceitos que podem ser utilizados para descrever as estruturas lógicas e físicas de um banco de dados. Já um modelo de classes de objetos não se limita às informações e aos dados, sendo mais amplo no momento em que integra as informações e os seus métodos de acesso, recuperação, processamento e outros em um único objeto. .(MACHADO 2020, p. 17)

Tratando um pouco de contexto histórico, os primeiros bancos de dados surgiram na década de 1960 e não pararam de evoluir desde este momento. A evolução destes bancos de dados primitivos foi no sentido de usar da pesquisa científica para buscar novos modelos capazes de representar com perfeição os dados da realidade que será trabalhada pelo sistema que estão sendo construídos a servir.

Os modelos de dados precisam ser detalhados, mas não apenas de forma com que sejam uma representação mais próxima da realidade, mas para que os implementadores sejam capazes de os manipular com maior facilidade, ou seja,

O modelo de dados também deve ser detalhado o bastante para ser usado pelo implementador (DBA) do banco de dados como uma espécie de fotocópia para construir o banco de dados físico. Será utilizada toda a informação que está no modelo de dados lógico para definir as tabelas de um banco de dados relacional, chaves primárias e chaves estrangeiras, procedimentos armazenados (stored procedures) e gatilhos (triggers). (MACHADO 2020, p. 18)

Se uma pessoa entra num arquivo de uma empresa qualquer, daqueles arquivos com imensos armários de metal e grandes gavetas, e começa a procurar por algo, provavelmente esta pessoa deve procurar pela gaveta onde acredita que vai encontrar o que precisa. A pessoa encontrará a gaveta certa e consequentemente aquilo que procurava (um documento, por exemplo) se tudo estiver corretamente identificado e no local designado.

O mesmo processo, vale aos bandos de dados, pois se a construção de um banco de dados contiver erros, uma constante serão os retrabalhos, o que nos leva a compreender que tal construção demanda planejamento e análise cuidadosa. Se o banco de dados falha no processo de recuperação ou apresenta uma contextualização equivocada, os efeitos em um sistema podem ser catastróficos ao ponto de impedir seu funcionamento e em casos brandos causar frequentes travamentos.

A boa construção de um banco de dados contribui para a criação de um sistema que permita futuras inovações, ao passo de um BD mal construído exigir tantas correções que o caminho correto será a sua substituição.

 

Projeto De Banco De Dados

 

Para o gestor eficiente não existe nenhum aspecto de sua empresa que não deva ter sido cuidadosamente projetado, pois empresas de qualidade, com boa fatia de mercado são organizações coerentes, com métodos e processos bem definidos, com isso, nada mais evidente do que compreender que um banco de dados também precisa ser construído, modelado seguindo os preceitos de um projeto formal.

Existem empresas que não possuem todos seus aspectos administrativos, financeiros e produtivos descritos formalmente ou que passaram por um projeto que os conceberam, mas os detalhes críticos da operação sempre ganham maior atenção da parte da gestão, onde em muitos casos entram os bancos de dados.

Os bancos de dados carregam as informações mais valiosas de uma empresa, em alguns casos a empresa está totalmente centrada nas informações que mantém, como em empresas dos ramos financeiros, empresas com produtos digitais. Desta forma, construir um banco de dados coerente e eficiente não é uma opção ou benefício.

Faz sentido que os bancos de dados sejam projetados, pense, estudante, no processo que ocorre quando um município deseja criar um novo bairro, ou residencial e necessita de um projeto. Se o projeto do bairro for feito equivocadamente, ruas podem não ser interligadas, o desempenho hidráulico do esgoto pode ser insuficiente a demanda populacional, etc. Desta forma os projetos de bancos de dados envolvem,

[...] principalmente, o projeto do esquema de banco de dados. O projeto de um ambiente de aplicação de banco de dados completo que atenda às necessidades da empresa sendo modelada requer atenção para um conjunto de problemas mais amplo. Neste texto, focalizamos, inicialmente, a escrita de consultas de banco de dados e o projeto de esquemas de banco de dados. (SILBERSCHATZ 2020, p. 09)

Dentro do projeto de um banco de dados, será através do modelo de dados de alto nível que o seu projetista fará a leitura das necessidades dos usuários que terão acesso ao banco de dados assim como terá os detalhes de como deverá atender tais necessidades. Este passo representa a fase inicial do projeto de construção do banco de dados e de acordo com Silberschatz (2020, p. 09),

A fase inicial do projeto de banco de dados consiste em caracterizar completamente as necessidades de dados dos potenciais usuários do banco de dados. O projetista de banco de dados precisa interagir bastante com especialistas e usuários do domínio para realizar essa tarefa. O resultado dessa fase é uma especificação dos requisitos do usuário. (SILBERSCHATZ 2020, p. 09)

Assim como existem diferentes técnicas de construção de projetos, o responsável pela construção do banco de dados deverá escolher o modelo que vai nortear sua composição, que melhor se encaixa nos tipos de dados e nos interesses e necessidades dos usuários.

Modelo relacional

 

De acordo com Silberschatz (2020) ao utilizar o modelo relacional, o projetista do banco de dados foca suas decisões em quais atributos deseja agregar e como agregar e com isso formar suas tabelas. Assim, o projetista pode seguir com uma abordagem entidade/relacionamento, ou adotar a estratégia dos conjuntos de algoritmos (a normalização).

Modelo Entidade-Relacionamento MER

 

Surgindo primeiramente em 1976, o modelo MER tinha como foco a unificação de versões de bancos de dados relacionais, portanto utilizada a teoria relacional, conceitual, onde o mundo real era visto como entidades e relacionamentos. Parte estrutural deste modelo, portanto, seria o diagrama Entidade-Relacionamento, utilizado para representar objetos e dados. Este metamodelo apresentava a visão de que determinada realidade seria a soma do relacionamento entre entidades, assim como definido por Chen (1970, apud, MACHADO, 2020, p. 24)

[...] as quais retratam os fatos que governam essa mesma realidade, e cada um (entidade ou relacionamento) pode possuir atributos (qualificadores descritivos dessa realidade). Grande parte das extensões ao metamodelo tem por base alguns mecanismos de abstração: classificação, generalização e agregação. (MACHADO 2020, p. 24)

Por se tratar de modelos para projetos aplicados a bancos de dados, nada impede que sejam utilizados em aspectos admirativos de uma empresa. Como se tratam de modelos, que com o perdão da redundância, são capazes de modelar diversos aspectos da empresa que, assim como os bancos de dados, seguem a sistemática relacional com suas entidades e relacionamentos.

Por fim, modelar e projetar a estrutura do banco de dados, deve-se observar o objeto, o ambiente com cuidado e detalhe, pois dele virá a estrutura base a ser desenhada dentro do que preconiza o modelo.

 

Implementação De Banco De Dados

 

A informática entrou na vida das pessoas, tanto na sua parte pessoal quanto na profissional. Do lado profissional fez com que muitas tarefas e funções mais mecânicas e menos sensíveis passassem a ser realizadas pelos computadores. Atualmente não se encontra empresas que não tenham ao menos um computador e muitas delas nem existiriam sem eles e seus avanços, como as empresas da internet.

A computação veio para agregar ao processo de tomada de decisão, o deixando mais rápido, assertivo e até mesmo rastreável, graças a suas formas sofisticadas de lidar com as informações. Desta forma os bancos de dados perdem a posição de recurso básico para se tornarem um dos componentes mais valiosos das empresas, origem de muita inovação e desempenho.

A implementação do banco de dados é sua codificação, pois neste momento é definido qual será a forma de codificação do BD e quais as tecnologias que serão utilizadas, principalmente para programar o Banco de Dados Temporário-BDT e o Banco de Dados Relacional-BDR.

Tais componentes serão distribuídos pela arquitetura, e onde os stored procedures, ou seja, os procedimentos de armazenamento, serão codificados ao ponto de oferecer seus dados ao banco. Desta maneira, podemos compreender que quando um banco de dados é implementado, ele cria o SGBD, ou seja, de toda a estrutura de dados correspondente ao banco de acordo com a estrutura física proposta.

De acordo com Machado (2020, p. 26) “É fundamental para o projetista de BD que ele possua capacitação na navegação do banco de dados proposto e implementado e, principalmente, compreensão do modelo, conhecendo seus caminhos de navegação.” Desta forma podemos concretizar a álgebra, mais especificamente a relacional, como sendo o ponto focal da construção dos projetos de bancos de dados, pois ajuda o projetista a responder algumas perguntas como:

De que adianta projetar banco de dados se não sei como recuperar suas informações?

De que adianta saber comandos SQL se não sei como é a estrutura interna de um comando para recuperar dados de um conjunto de tabelas? (MACHADO 2020, p. 26)

Embora processos como a implementação de um banco de dados demandam muita estrutura, o conhecimento de seus responsáveis deve causar o maior impacto. Desta forma, aos que seguem o modelo relacionam para projetos de bancos de dados necessita ter boa bagagem com relação a álgebra relacional, pois da compreensão deste analista que serão feitas as estruturas de consulta e recuperação.

 

 

Atividade Extra

 

 

Big data é praticamente um novo universo na computação e para os mais interessados em bancos de dados e leva em consideração dois fatores: que estamos a cada dia gerando mais informação que em anos, no passado, e que só se destaca em seu mercado que sabe tirar melhor proveito das informações que tem acesso. Saiba mais sobre Big Data com o vídeo especial do canal Código Fonte TV no link:

 

https://www.youtube.com/watch?v=IpfE8B9H9cI

 

 

Referência Bibliográfica

 

 

DUTRA, Luís Fernando Giacomini. Aplicando o conceito de banco de dados relacional e temporal no aplicativo calendar tatoo. 2017. Disponível em: < http://repositorio.roca.utfpr.edu.br/jspui/bitstream/1/9837/1/PB_EBD_02_2017_13.pdf> Acesso em: 15/05/2021.

 

MACHADO, Felipe Nery Rodrigues. Banco de dados: projeto e implementação. – São Paulo: Érica, 2020.

 

PICHETTI, Roni Francisco; VIDA, Edinilson da Silva; PAIXÃO, Vanessa Stangherlin Machado. Banco de dados. – Porto Alegre: SAGAH, 2020.

 

SILBERSCHATZ, Abraham. Sistema de banco de dados. - Rio de Janeiro: LTC, 2020.

