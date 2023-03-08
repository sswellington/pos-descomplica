# Definições de Dados

De acordo com Stair e Reynolds (2018), dados consistem em fatos brutos, como o número de funcionários, horas totais de trabalho em uma semana, número de peças em estoque ou pedidos de venda. Já um banco de dados “ é o mesmo de uma coleção de registros ou de informações”, conforme exposto por Baltzan e Phillips (2012, p. 147).

Em uma definição ampla, um banco de dados armazena informações sobre vários tipos de objetos (estoque), eventos (transações), pessoas (funcionários) e lugares (depósitos). Os bancos de dados surgiram na seguinte ordem: em rede, hierárquico, relacional, não relacional, entre outros. Em um modelo de rede existem vários níveis de correlação entre os dados. Já no modelo hierárquico de banco de dados, a informação é organizada dentro de uma estrutura semelhante a uma árvore, a qual permite a repetição de informações usando relações de pai/filho, de tal forma que não existam demais relações.

Fique atento: Enquanto no modelo hierárquico as relações são de um para um ou um para muitos, no modelo em redes um filho pode estar associado a diferentes pais.

Embora haja alguns modelos de banco de dados diferentes que incluem os arquivos simples, hierárquicos e modelos em rede, o modelo de banco de dados relacional tornou-se o mais popular. DB2, Oracle e Sybase são bancos de dados relacionais. De acordo com o modelo relacional, em um banco de dados estruturado, todos os elementos de dados são colocados em tabelas bidimensionais chamadas relações, que são o equivalente lógico dos arquivos. As tabelas nos bancos de dados relacionais organizam os dados em linhas e colunas ao simplificar o acesso e a manipulação de dados.

Um modelo de banco de dados relacional possui entidades, atributos e chaves. Uma entidade no modelo de banco de dados relacional é uma pessoa, lugar, coisa, transação ou evento sobre o qual informações são armazenadas. Uma tabela no modelo relacional é uma coleção de entidades similares. Os atributos, também chamados de campos ou colunas, são características ou propriedades de uma classe de entidade. Cada entidade específica em uma classe de entidades ocupa uma linha na sua respectiva tabela. As colunas da tabela contêm os chamados atributos.

Para gerenciar e organizar várias classes de entidades dentro de um modelo de banco de dados relacional, os desenvolvedores devem identificar as chaves principais e as externas e utilizá-las para criar relações lógicas. Uma chave principal é um campo (ou grupo de campos) que identifica unicamente uma determinada entidade em uma tabela. As chaves principais são importantes porque fornecem uma forma de distinguir cada entidade em uma tabela.

Uma chave externa no banco de dados relacional é a chave principal de uma tabela que aparece como um atributo em outra tabela e fornece uma relação entre as duas.
 

## Aplicações de Banco de Dados

Informações organizacionais são armazenadas em um banco de dados. Aplicações e programas, como sistemas de gestão da cadeia de fornecimento e sistemas de gestão de relacionamento, acessam o banco de dados para responder às questões. Os registros recuperados nas respostas se tornam informações que podem ser usadas na tomada de decisões. O programa de computador usado para gerenciar e consultar o banco de dados é conhecido como sistema de gerenciamento de bancos de dados (DBMS - database management system), ou, na língua portuguesa SGBD (sistema de gestão de banco de dados), que consiste em um grupo de programas que manipula o banco de dados e fornece uma interface entre eles, seus usuários e outros programas aplicativos.

Geralmente adquirido de uma empresa de banco de dados, o DBMS fornece um único ponto de gestão e controle sobre os recursos de dados, o que pode ser fundamental para manter a integridade e a segurança dos dados. Em SGBDs, os dados são independentes de linguagem de programação das aplicações. De modo geral, eles trazem agilidade no acesso aos dados, mais segurança nestes, acesso concorrente entre várias aplicações (usuários), alto controle a falhas e fácil administração dos dados.

O DBMS da Oracle, por exemplo, lançou um firewall para banco de dados para ajudar seus clientes a proteger seus bancos de dados. Um banco de dados, o DBMS e os programas aplicativos que utilizam os dados compõem o ambiente do banco de dados.

 
## Persistência de dados

Persistência é a capacidade de manter os dados, de maneira íntegra e continuamente, acessíveis para o uso destinado. De acordo com Mannino (2014, p. 4), “significa que os dados são armazenados de modo permanente, como em um disco magnético. Por exemplo, as organizações necessitam reter dados sobre clientes, fornecedores e estoque em armazenamento permanente porque esses dados são usados repetitivamente.”

No aspecto social, os dados hoje precisam estar resguardados e protegidos sob pena de responsabilidade civil e até criminal por parte da organização ou empresa prestadora do serviço de armazenamento dos dados. Por esse motivo, tanto empresas que cuidam de servidores e prestam serviços do tipo host quanto empresas desenvolvedoras e mantenedoras de sistemas gerenciadores de bancos de dados (DBMS/SGBD) têm grande preocupação com a forma de disponibilidade dos dados e, principalmente, com a proteção dos dados.

É possível manter os dados persistidos de diversas formas, como em arquivos de texto, em bancos de dados estruturados, em planilhas ou outras formas de armazenamento. A persistência não é algo “eterno”, afinal os dados também podem ter vida útil ou perderem a relevância, como afirma Mannino (2014, p. 4) quando diz que “a persistência não quer dizer que os dados duram para sempre. Quando os dados não são mais relevantes (como no caso de um fornecedor saindo do negócio), eles são retirados ou arquivados”.

 
## Infraestrutura de redes

De acordo com Baltzan e Philips (2012), as redes vão desde uma pequena de dois computadores até a maior de todas, a internet. Uma rede fornece dois benefícios principais: a possibilidade de se comunicar e a de compartilhar. Laudon e Laudon (2014) descrevem que os principais componentes de hardware, software e transmissão de dados usados em uma rede simples são: um computador cliente e um computador dedicado, interfaces de rede, um meio de conexão, software de sistema operacional de rede, um hub (ou concentrador) ou switch (ou comutador).

Cada computador contém um dispositivo de interface para conectá-lo à rede. O meio de conexão para interligar os componentes de rede pode ser um fio telefônico, um cabo coaxial ou sinais de rádio, no caso de telefone celular e redes locais sem fio (redes wi-fi).

O sistema operacional de rede (Networking Operating System – NOS) encaminha e administra comunicações e coordena os recursos de rede. Esse sistema pode residir em todos os computadores de rede ou em um único servidor designado para todas as aplicações da rede. Dentro de uma rede, um computador servidor é um computador que realiza importantes funções para computadores clientes, tais como mostrar páginas da Web, armazenar os dados e os sistema operacional de rede (e, assim, controlá-la). Microsoft Windows Server, Linux e Novell Open Enterprise Sever são os sistemas operacionais de redes mais utilizados.

A maioria das redes também conta com um switch ou um hub que atua como ponto de conexão entre os computadores. Os hubs são dispositivos muito simples que conectam os componentes de rede, enviando um pacote de dados para todos os outros dispositivos conectados. O switch é mais inteligente do que um hub, pois pode filtrar e encaminhar dados para um destinatário específico na rede.

Para se conectar com outra rede como a internet, é preciso utilizar um roteador, que processa as comunicações para encaminhar pacotes de dados por diferentes redes, assegurando que a mensagem enviada chegue ao endereço correto.

As switches e roteadores possuem software proprietário embutido em seu hardware para direcionar a movimentação dos dados pela rede. Isso pode criar gargalos e tornar o processo de configuração de uma rede mais complicado e demorado. Uma rede definida por Software (Software-Defined Networking – SDN) é uma abordagem em que muitas dessas funções de controle são gerenciadas por um programa central, que pode ser executado em servidores básicos de baixo custo que são separados dos próprios dispositivos de rede. Isso é especialmente útil em um ambiente de computação em nuvem com muitos componentes diferentes de hardware, pois permite que um administrador gerencie as cargas de tráfego de uma forma flexível e mais eficiente.

 
## Terceirização e computação sob demanda 

Devido a necessidade de armazenar e permitir consultas a dados gigantes de maneira rápida e confiável, surgiram novas estruturas de banco de dados para big data. Além dos sistemas de gerenciamento de banco de dados populares, alguns pacotes especializados são utilizados com objetivos em setores específicos.

Os NoSQL (Not only SQL) são sistemas de gestão de bancos de dados que podem manejar ou acomodar dados que não se encaixam nas tabelas requeridas pelos bancos relacionais tradicionais discutidos anteriormente. Os bancos de dados NoSQL são próprios para o mundo big data. Muitos bancos de dados NoSQL são de fonte aberta, como o Hadoop, o Cassandra, o Hypertable e outros. Outro exemplo é o programa iTunes da Apple, que utiliza um sistema de banco de dados com propósito especial que incluem campos para o nome da música, avaliação, tamanho de arquivo, tempo, artista, álbum e gênero. Quando os usuários do iTunes vão à loja virtual e procuram por algum artista, eles acessam na verdade o banco de dados da central iTunes (STAIR e REYNOLDS, 2018).

 
## Atividade Extra

Saiba mais sobre como surgiu a Internet! Assista esse vídeo de 15 minutos que conta toda a história da internet com detalhes.

https://www.youtube.com/watch?v=pKxWPo73pX0&t=27s

 
## Referência Bibliográfica

BALTZAN, P; PHILLIPS, A. Sistemas de Informação. Porto Alegre: AMGH, 2012.

LAUDON, K.C; LAUDON, J.P. Sistemas de Informação gerenciais. São Paulo: Pearson Education do Brasil, 2014.

MANNINO, M. V. Projeto, desenvolvimento de aplicações e administração de banco de dados. 3. ed. Porto Alegre: AMGH, 2014.

STAIR, R.M; REYNOLDS, G.W. Princípios de Sistemas de Informação. São Paulo: Cengage Learning, 2018.