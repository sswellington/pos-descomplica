# Governança de Dados e Transparência

## Qualidade de dados

Um dos grandes problemas em nível mundial é a pobreza dos dados, isso mesmo! Por exemplo, imagine uma empresa que lá pelos anos 2000 aqui no Brasil vivia numa onda crescente chamada call center. Eles estavam em ascensão e prometiam o mundo aos seus clientes. Principalmente porque era um tipo de operação que encarecia demais as infraestruturas das empresas, a cobrança.

Quando esse pessoal começou a trabalhar com os cadastros que lhes passavam para entrar em contato descobriram que eles normalmente estavam bastante defasados e em boa parte das vezes ou o telefone estava desatualizado, quando o logradouro não era mais o mesmo. Os próprios clientes não podiam ajudar e as cobranças de call center viviam de conversão e recuperação como qualquer outra, mas com um agravante, “deveriam se virar para achar os contatos, atualizarem e encontrarem o devedor” senão ganhavam menos.

E assim, juntamente com a ideia e a vontade de aproveitadores iniciaram as jornadas de tráfico de dados e mercados paralelos de dados cadastrais no Brasil. Porque, bem grande parte das empresas tinha seus sistemas com bases bastante defasadas e desatualizadas e agora precisavam de dados, mas não somente para cobrança, mas para vender também.

Naquela época não existiam todas esses ferramentais, arquiteturas, nuvem, big data, machine learning, deep learning, data mining, etc, etc, etc. tudo acabou virando um enorme ecossistema de dados pessoais que fluíam de um lado para o outro sem controle e sem fronteira, até que...

Sugiram leis, em 2009 iniciaram para valer as iniciativas de atualização de sistemas e bancos de dados e os bancos começaram a ser multados pelo BACEN por cadastros desatualizados ou tinham pessoas públicas expostas, seus dados voando aos quatro cantos. Pressões europeias começaram a repercutir aqui em nosso país como as leis de governança para bancos como a Sarbanes-Oxley entre outras.

Nessa época surgiram iniciativas como a QIBras e a chegada do Capítulo da DAMA – Data Management Association aqui no país. Tive a honra de ser cofundador do DAMA no Brasil e seu primeiro vice-presidente em 2010 juntamente com Rossano Tavares, já falecido, seu primeiro presidente. Muita coisa mudou e evoluiu, mas vamos recordar os pioneiros da qualidade de dados e da governança. Pessoas como Richard Wang, John Talburt, Peter Aiken, Larry English e tantos outros estiveram aqui no Brasil em 2010 para passarem um pouco de suas experiências para aquela nova fronteira que se abria naquela época.

Vamos começar com o porquê das coisas.

Por causa da qualidade de dados ruins o pessoal de marketing das empresas perceberam que não conseguiriam fazer campanhas mais dirigidas, o pessoal de produtos ficava em dúvida se continuava ou não os produtos ou se jogava tudo para o alto e começava do zero, pior ainda a área comercial que não tinha dados viáveis para fazerem previsões melhores com base em cliente em sua carteira porque eram tantas as trocas de sistemas e tantas as perdas de dados e recadastramentos desde o zero, porque alguém quis instalar um ERP porque era moda, ou qualquer outra coisa que também era moda lá para 2009 que era difícil dar conta de tudo.

A qualidade pobre desses sistemas que não possuíam regras de negócios e de sistemas poderosas, para fazer com que um digitador em alguma loja fizesse a entradas dos dados de forma correta, consistente e livre de erro era quase impossível, o importante era colocar o cliente para dentro na maior velocidade possível e faturar.

Os sistemas eram cheios de falhas e possibilidades que os usuários descobriram e burlavam campos chave como CPF, e outras chaves que iam em branco, incompletas entre outros. Já passei por clientes que possuíam 4 ou 5 sistemas diferentes com os mesmos dados em bases diferentes sem unificação, todos sistemas criados de puxadinhos operacionais para manter esse ou aquele feudo gerencial feliz. Agora isso facilmente quebraria um empresa porque os endereços eram diferentes para o mesmo cliente, que tinha nomes diferentes com cpfs iguais ou cpfs diferentes com nomes iguais e outras variações de quase 300 clientes com o cpf 999.999.999-99, sim, pérolas da programação e da falta de teste com certeza. Mas todos esses clientes estavam lá “no mesmo balaio de gato” e eram “felizes”, quer dizer até o momento em que após irem em feiras e receberem visitas de representantes de grandes empresas do Vale do Silício, os comandantes dessas empresas resolverem usar seus dados junto com a estatística para fazerem previsões, extraírem os dados de suas bases enferrujadas com técnicas de ETL iniciarem os tratamentos obrigatórios dos dados com deduplicação e por fim enriquecerem tudo isso e importarem novamente para as bases.

Mas só se consegue pouca coisa, porque havia muito mais dados interessantes após enriquecimentos sobre esses clientes do que cabiam nos sistemas e aí, o dilema, fazemos novamente ou remendamos? Bem, se possível, remende.

A história é boa, mas onde estão esses problemas, de onde surgem?

Aqui para iniciarmos o entendimento coloco para você, quais os problemas de qualidade de dados a serem levados em consideração e as fontes de sua ocorrência:

Qualidade de entrada: normalmente causada por uma pessoa inserindo dados em um sistema. O problema pode ocorrer devido a um erro de digitação ou uma decisão intencional, como fornecer um número de telefone ou endereço fictício. A identificação desses outliers ou dados ausentes é facilmente realizada com ferramentas de criação de perfil ou consultas simples.
Qualidade do processo: esses problemas ocorrem sistematicamente à medida que os dados são movidos por uma organização. Eles podem resultar de uma falha do sistema, perda de arquivo ou qualquer outra ocorrência técnica que resulte de sistemas integrados. Muitas vezes são difíceis de identificar, especialmente se os dados passaram por várias transformações no caminho até seu destino. A qualidade do processo geralmente pode ser corrigida facilmente, uma vez que a origem do problema é identificada. Verificações e controle de qualidade adequados em cada ponto de contato ao longo do caminho são necessários para garantir que os problemas sejam eliminados, embora essas verificações possam frequentemente estar ausentes em processos legados.
Qualidade da identificação: Resultante do não reconhecimento da relação entre dois objetos. Por exemplo, dois produtos semelhantes com identificadores chave diferentes são incorretamente considerados iguais. A qualidade da identificação pode ter custos associados significativos, como enviar pelo correio para a mesma família mais de uma vez, vi muitas vezes isso acontecer não apenas com produtos, mas também com cobranças. Os processos de qualidade de dados podem eliminar amplamente esse problema combinando registros, identificando duplicatas e colocando uma pontuação de confiança na similaridade dos registros.
Qualidade da integração: Ocorre devido à falha na integração de todas as informações conhecidas sobre um objeto, o que, normalmente, deve ser feito para fornecer uma representação precisa do objeto.
Qualidade de uso: Causada pelo uso e interpretação incorreta das informações no ponto de acesso.
Qualidade de envelhecimento: ocorre como a informação que não é mais confiável devido ao fato de que o tempo passa e a informação fica desatualizada. Chamo isso também de problemas de acurácia, quando a informação perde a sua representatividade no mundo real, ficando cada vez mais “distante” da realidade do seu próprio fato.
Qualidade organizacional: que pode ocorrer quando as informações são reconciliadas entre dois sistemas com base na forma como a organização constrói e visualiza os dados. Lembra do caso da empresa com 4 sistemas diferentes com a mesma informação quadruplicada em bases diferentes não conectadas, quando muito conectadas com chaves indiretas.
Além disso, como disse logo no início desse texto, os sistemas que permitem entradas mistas de dados podem gerar problemas graves no futuro. Reflita da seguinte forma, as instruções sobre como os dados devem ser inseridos estão abertas à interpretação, portanto, pessoas diferentes às vezes povoam incorretamente um campo sem nem perceber. Um exemplo é uma configuração de gerenciamento de ativos de clientes numa sessão de cadastro do sistema inserindo a nomenclatura de um cliente de forma diferente. Vários colaboradores que entram nesses dados podem inserir (Alpha Aviação Ltda) ou (Alfa Aviação Ltd) ou (Alpha Ltda) para o mesmo cliente, mesmo que este seja pessoa física, por exemplo, (José Maria da Silva Santos) ou (J. Maria da S. Santos) ou (José M. da S. Santos). As ferramentas de gerenciamento de qualidade de dados devem ser usadas para normalizar essas variações. Outra coisa é que devem existir funções que permitam trazer os dados a partir de algum documento chave, como CPF, RG ou PIS para pessoas físicas ou CNPJ para pessoas jurídicas, prestando atenção aqui para o final do CNPJ antes dos dois dígitos de controles finais para cadastrar a filial correta e impedir que seja cadastrada apenas os dados da matriz, fora isso é boa prática utilizar o repositório central de CEP dos correios por exemplo para evitar que cada um coloque o nome da rua, av, praça ou outra coisa do jeito que ele quiser e não sob um padrão.

Qualidade de dados envolve alta padronização e regras de entrada de dados precisas, muitas vezes em caixa alta por exemplo.

Lembre-se também que nos velhos tempos, os programas aplicativos ou programas transacionais (não eram necessariamente sistemas, eram apenas uma coleção de programas não interligados, talvez com sorte utilizavam a mesma base como era feito nos sistemas em COBOL) eram executados em um único computador. Os aplicativos de hoje, ao contrário, interagem com muitos computadores, tornando-os muito mais complexos. Se esses sistemas não tiverem redundância suficientemente embutida, eles também podem ser muito frágeis e sujeitos a falhas. Os sistemas tradicionais eram menos propensos a corromper os dados, pois eram mais simples. À medida que os aplicativos aumentam de complexidade e são distribuídos em mais computadores, as corrupções de dados se tornam mais comuns e mais difíceis de isolar e corrigir.

Richard Wang pesquisador do MIT é considerado um dos pioneiros em qualidade de dados no mundo e ele realizou uma pesquisa fundamental e publicou um artigo em 1994 que é reconhecido como um divisor de águas até hoje no incremento da qualidade de dados nas bases de dados em todo o mundo e na preocupação com esse tema recorrentemente em desenvolvimento de sistemas de informação e levantamento/modelagem de negócios, vamos conhecer as 20 dimensões ou atributos desejáveis para que um dado seja o mais útil possível.

Tabela: Descrição das dimensões dos dados
Tabela: Descrição das dimensões dos dados

Temos cinco principais consequências dos dados de baixa qualidade a partir dessa lista de 20 atributos iniciais:

Má tomada de decisão: Dados de baixa qualidade levam a decisões ruins. Uma decisão não pode ser melhor do que as informações nas quais se baseia, e decisões críticas baseadas em dados de baixa qualidade podem ter consequências muito sérias. Esse é outro motivo que devemos nos certificar de que os dados realmente representam a realidade.

Ineficiências de negócios: Dados de baixa qualidade causam ineficiências nos processos de negócios que dependem de dados de relatórios a pedidos de produtos e quase tudo entre os quais os fatos são necessários. Essas ineficiências podem resultar em esforços de retrabalho muito caros, validando e corrigindo erros de dados, em vez de se concentrar nas tarefas essenciais.

Desconfiança: Dados de baixa qualidade geram desconfiança. Especialmente em setores onde os regulamentos regem os relacionamentos ou o comércio com determinados clientes, como o financeiro. Manter dados de boa qualidade pode ser a diferença entre conformidade e milhões de reais em multas. Se os dados estiverem errados, tempo, dinheiro e reputação podem ser perdidos, refletindo negativamente nos negócios e diminuindo a confiança do cliente.

Oportunidades perdidas: Um controlador pode perder uma oportunidade lucrativa de desenvolvimento de novos produtos ou necessidades do cliente que um concorrente com um conhecimento mais avançado de dados pode aproveitar.

Receita perdida: Dados de baixa qualidade podem levar à perda de receita de várias maneiras. Considere, por exemplo, comunicações que não são convertidas em vendas porque os dados subjacentes do cliente estão incorretos. Dados de baixa qualidade podem resultar em segmentação e comunicações imprecisas, especialmente prejudicial na venda multicanal . (CHAN, 2019, p.1)

 

Todavia não precisamos nos desesperar em colocar as 20 dimensões de WANG no ar. Elas dependem de sua adoção de acordo com a especificidade do negócio. Atualmente é comum os administradores de dados e desenvolvedores, além dos especialistas em negócios estarem preocupados com 5 dimensões:

Exatidão ou Acurácia: diz respeito à exatidão dos valores contidos nos vários campos do registro do banco de dados. O nome está escrito corretamente? Os valores estão registrados corretamente? Os endereços estão corretos?

Completude: os usuários devem compreender o escopo dos dados e ser absolutamente claros quanto ao que compreende um elemento de dados específico.

Consistência: às informações resumidas estão de acordo com os detalhes subjacentes.

Exclusividade: um objeto, uma instância ou entidade no mundo real deve corresponder a uma e apenas uma coisa em seus dados, é algo que chamamos em dados de univocidade, ou seja, tem que ser unívoco. Por exemplo, lembra do (José Maria da Silva Santos) e do (José M. da S. Santos) representam a mesma entidade ou pessoa no mundo real, portanto, é necessário eliminar a duplicidade. Quando trabalhamos com ETL – extração, transformação e carga de dados executamos rotinas de deduplicação que fazem isso.

Oportunidade: os dados devem estar atualizados com relação às necessidades do negócio do controlador e deve haver sistemas em funcionamento para que os usuários verificados atualizem ou alterem os dados manualmente sempre que preciso.

Como dicas importantes, posso te escrever que uma das melhores maneiras de criar dados de boa qualidade é validá-los automaticamente. Isso significa fazer com que o sistema verifique se há informações ausentes, inconsistentes e imprevistas. Certifique-se de que todas as fórmulas estão funcionando e os cálculos não estão quebrados. Isso lhe dará consistência e garantia de que seus dados estão um passo mais perto de serem de melhor qualidade. Além disso, tente diminuir a quantidade de texto de formato livre em sistemas. Isso inclui nomes, endereços, descrições curtas e notas.

Pense também quando num controlador, há uma variedade de sistemas rastreando dados, é relativamente provável que eles se misturem e forneçam dados insatisfatórios em algum momento. Uma das melhores táticas para melhorar a qualidade dos dados é consolidar todos eles. Portanto, reúna todos os seus sistemas em um único programa ou, melhor ainda, considere mudar para sistemas baseados em nuvem que se integram entre si. Sim, haverá investimento nisso, mas pense bem, já estava na hora. Dessa forma, é mais fácil controlar e rastrear o que está entrando e o que está fora do seu sistema.

Fora isso tudo, se o controlador tiver porte para isso, contrate urgentemente um responsável pelos dados ou DPO, se não tiver, melhor contratar um terceiro que faça esse papel, assim como para a cibersegurança.

 

Governança de Dados

Governança de dados é o processo e procedimento que as organizações usam para gerenciar, utilizar e proteger seus dados. Pense nisso como quem, o quê, quando, onde e o por quê sobre os dados em poder do controlador. Outro aspecto da governança de dados é proteger os dados privados do controlador e do cliente, o que deve ser uma tarefa de alta prioridade para as organizações nos dias de hoje.

Dessa forma podemos definir governança de dados como sendo um conjunto de princípios e práticas que garantem alta qualidade durante todo o ciclo de vida de seus dados.

Uma estrutura de governança de dados bem gerenciada apoiará a transformação dos negócios para operar em uma plataforma digital em muitos níveis dentro de um controlador:

Gestão: Para a alta administração, isso garantirá a supervisão dos ativos de dados corporativos, seu valor e seu impacto nas mudanças nas operações de negócios e nas oportunidades de mercado.

Finanças: Para finanças, isso permitirá relatórios consistentes e precisos.

Vendas: para vendas e marketing, isso permitirá uma visão confiável das preferências e comportamento do cliente.

Compras: Para compras e gerenciamento da cadeia de suprimentos, isso fortalecerá as iniciativas de redução de custos e eficiência operacional com base na exploração de dados e colaboração do ecossistema de negócios.

Produção: Para a produção, isso será essencial na implantação de automação.

Legal: para questões legais e de conformidade, esta será a única maneira de atender aos crescentes requisitos regulamentares.

Percebe-se que sem uma governança de dados eficaz, as inconsistências de dados em diferentes sistemas em uma organização podem não ser resolvidas. Por exemplo, os nomes dos clientes podem ser listados de forma diferente nos sistemas de vendas (já escrevi sobre isso anteriormente nesse mesmo texto), logística e atendimento ao cliente. Isso pode complicar os esforços de integração de dados e criar problemas de integridade que afetam a precisão das iniciativas de BI das empresas, relatórios corporativos e regulamentação no próprio uso dos dados dos titulares.

Isso pode impedir que um negócio vá para frente baseado no que eles possuem de dados do titulares e como esses dados se relacionam com as fontes transacionais para entender comportamento e prestar um melhor serviço.

Reflitamos: como vamos responder às perguntas feitas pelos titulares de dados se não temos controle e nem precisam do que acontece com eles e nem onde eles estão, pior, se são precisos?

Um programa de governança de dados corporativos normalmente resulta no desenvolvimento de definições de dados comuns e formatos de dados padrão que são aplicados em todos os sistemas de negócios, aumentando a consistência dos dados para uso comercial e de conformidade.

A governança de dados está muito atrelada a conformidade regulatória, afinal é objetivo focal garantir que os dados sejam usados corretamente, tanto para evitar a introdução de erros de dados nos sistemas quanto para bloquear o uso indevido potencial de dados pessoais sobre clientes e outras informações confidenciais. Isso pode ser feito criando políticas sobre o uso de dados, juntamente com procedimentos para monitorar o uso e aplicar as políticas continuamente. Percebeu a importância de ter políticas sobre proteção e tratamento de dados pessoais não apenas no papel como muitos fazem, mas como documento vivo e atuante.

Os benefícios que a governança de dados oferece incluem qualidade de dados aprimorada; custos mais baixos de gerenciamento de dados; e maior acesso aos dados necessários para cientistas de dados, outros analistas e usuários de negócios.

Uma das coisas importantes que é exigida quando vamos iniciar um projeto de LGPD num controlador, por exemplo, diz respeito ao mapeamento e classificação de dados, pois ele dentro de um processo de governança ajuda a documentar ativos de dados e como os dados fluem por uma organização. Diferentes conjuntos de dados podem ser classificados com base em fatores como o fato de conterem informações pessoais ou outros dados confidenciais. As classificações influenciam como as políticas de controle de dados são aplicadas a conjuntos de dados individuais.

Outro fator importante associado a conformidade da LGPD e que se correlaciona com o catálogo dos dados, ou dicionário dos dados da organização controladora e seus sistemas por onde esses dados passam.

Os catálogos de dados coletam metadados de sistemas e os usam para criar um inventário indexado de ativos de dados disponíveis que inclui informações sobre linhagem de dados, funções de pesquisa e ferramentas de colaboração. As informações sobre políticas de governança de dados e mecanismos automatizados para aplicá-las também podem ser incluídas em catálogos.

O que devemos fazer para termos governança? Qual a estrutura?

Olavo Rud (2021) nos dá uma estruturação padrão para ajudar a entender o que uma estrutura deve abranger, a DAMA – Data Management Association como organização criada efetivamente para auxiliar a estabelecer padrões de governança prevê o gerenciamento de dados como um ciclo, com a governança de dados desse ciclo com as 10 áreas de conhecimento ao redor:

Arquitetura de dados: a estrutura geral de dados e recursos relacionados a dados como parte integrante da arquitetura corporativa

Modelagem e projeto de dados: análise, projeto, construção, teste e manutenção

Armazenamento e operações de dados: implantação e gerenciamento de armazenamento de ativos de dados físicos estruturados

Segurança de dados: garantia de privacidade, confidencialidade e acesso apropriado

Integração e interoperabilidade de dados: aquisição, extração, transformação, movimentação, entrega, replicação, federação, virtualização e suporte operacional

Documentos e conteúdo: armazenar, proteger, indexar e permitir o acesso a dados encontrados em fontes não estruturadas e disponibilizar esses dados para integração e interoperabilidade com dados estruturados

Dados de referência e mestre: gerenciamento de dados compartilhados para reduzir a redundância e garantir melhor qualidade de dados por meio da definição padronizada e do uso de valores de dados

Data warehousing (DW) e business intelligence (BI): Gerenciando o processamento de dados analíticos e permitindo o acesso a dados de suporte de decisão para relatórios e análises

Metadados: coleta, categorização, manutenção, integração, controle, gerenciamento e entrega de metadados

Qualidade dos dados: definir, monitorar, manter a integridade dos dados e melhorar a qualidade dos dados. (OLAVSRUD ,2021, p.2)

 

As principais metas de uma boa governança de dados diz respeito a:

Minimize os riscos.

Estabeleça regras internas para o uso de dados.

Implementar requisitos de conformidade.

Melhorar a comunicação interna e externa.

Aumente o valor dos dados.

Facilite a administração do acima.

Reduzir custos.

Ajudar a garantir a continuidade da existência da empresa por meio da gestão e otimização de riscos.

Figura: Funções da Governança de Dados. Segundo Data Management Body of Knowledge (DAMA DMBOK®) 
Figura: Funções da Governança de Dados. Segundo Data Management Body of Knowledge (DAMA DMBOK®)

Áreas críticas para LGPD nas empresas

Claro que não existe uma receita de bolo ou regra universal para determinar quais áreas dentro de um controlador são importantes ou impactantes para se implementar a LGPD. Todavia, devemos ter o conceito de os dados em geral independente de serem de titulares de dados pessoais ou não fluem pela organização como se fossem, usando uma analogia simplista para exemplificar, “a água vinda da rua fluindo pelos encanamentos de uma casa levando-a onde ela é necessária, cozinha, quintais, caixa d´água...”

Mas podemos ter algumas certeza de onde realmente iniciar nossa preocupação, todavia não podemos nos esquecer que um projeto de LGPD é um ato corporativo em si, mas aqui vão algumas áreas para que nos preocupemos:

Recursos Humanos

Comercial

Marketing

Jurídico

Tecnologia da Informação

Logística

Área financeira principalmente (Contas a pagar e Contas a receber)

Fiscal

Contabilidade

Com certeza existem outras, mas essas são as consagradas, e sim, os dados dos titulares passam por essas áreas com certeza.

Como já descrevi anteriormente, lembremos que algumas indústrias são críticas para a LGPD.

Bancos. Mercados de capitais e Fintechs

Seguradoras e corretoras

Comércio e todas as suas nuance e modalidades incluindo as da internet

Saúde e todas os seus congêneres como operadoras, corretoras, hospitais, clinicas, consultórios, dentistas, fisioterapeutas, academias etc

Segurança e vigilância remota

Governos e poderes nas 3 esferas, sindicatos, ONGs, partidos políticos

Imprensa, jornalismo de rua, jornalismo televisivo, programas de rádio e tv,  incluindo canais abertos ou pagos.

Entretenimento no geral, parques temáticos, documentários, filmes e similares

Entre outros, a lista é grande e não se esgota por aqui.

 

Podemos num esforço nos atentar independente da área ou indústria a qual estivermos inseridos os seguintes itens, atitudes e ações necessárias.

Aumente a conscientização em toda a organização tanto controladora quanto operadora dos dados pessoais.

Auditar todos os dados pessoais.

Atualize os avisos de privacidade em sites e outras mídias do controlador e do operador, se for o caso. Lembre-se que a responsabilidade é solidária.

Revise os procedimentos de apoio aos direitos dos indivíduos.

Revise os procedimentos de suporte às solicitações de acesso de assunto

Identifique e documente a base legal para o processamento de dados pessoais, isso é mandatório, tem que ler a LGPD e anotar quais as bases legais e se adequar para cada etapa e para cada processo no controlador e pedir ao operador se for o caso se adequar e demonstrar competência técnica e operacional para lidar com os dados confiados ao processamento ou transformação dele, tem que ser forma, se for baseado em contrato com cláusulas duras, claras e específicas, mas acima de tudo comprováveis, melhor.

Revise como se busca, obtém e registra o consentimento, precisa ter um software para isso, evite soluções domésticas e planilhas, é um pedido, a área jurídica vai agradecer em muito, caso ainda estejam com esse controlador.

Revise os dados que você tem sobre as crianças, caso isso se aplique ao controlador ou operador o qual você está ou presta serviço. Aqui todo cuidado é pouco e lembre-se sempre, a imprensa é avida em ter notícias referentes a esse tipo de situação ou vazamento.

Estabeleça procedimentos para detectar, relatar e investigar uma violação de dados pessoais, portanto, contrate empresas experientes em cibersecurity e que saibam principalmente como lidar com situações críticas e crises.

Revise os processos em torno das avaliações de impacto de privacidade de dados, é um documento obrigatório e vivo, precisa ser avisado toda vez que mudar algo. E, quer saber, algo muda toda hora nas organizações.

Nomear um Responsável pelos dados interno ou então um Escritório de Proteção de Dados, não se esqueça disso.

Atividade Extra

Uma qualidade de dados insatisfatória afeta negativamente orçamentos, iniciativas de marketing e, mais importante, a satisfação dos clientes. As organizações que não conseguem controlar a qualidade de seus dados não conseguem se comunicar de forma eficaz com sua base de clientes. Essa palestra se encontra aqui: CARNEIRO, M. E-COMMERCE BRASIL. Qualidade de Dados na Prática: como aumentar a eficiência operacional e reduzir custos. 2016. Disponível em: https://www.youtube.com/watch?v=-QXZK1-B0aw&t=44s Acesso em: 26 jun. 2021.

 

Qual o limite e o equilíbrio entre o uso das tecnologias e a quantidade de dados que expomos nas redes? Confira aqui: AFFONSO, C. Privacidade e Proteção de Dados no Brasil. TEDx Petrópolis. 2020. Disponível em: https://www.youtube.com/watch?v=Zau-x-j_Uu8 Acesso em: 26 jun. 2021.

 

 

Referência Bibliográfica

BRASIL. Lei Geral de Proteção de Dados Pessoais (LGPD). Disponível em: <http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm>. Acesso em: 26 jun. 2021.

CHAN, M. 5 principais consequências de dados de baixa qualidade e como evitá-los. 2019. Disponível em: <https://www.unleashedsoftware.com/blog/5-major-consequences-poor-quality-data-how-avoid> Acesso em: 26 jun. 2021.

OLAVSRUD, T. O que é governança de dados? Uma estrutura de melhores práticas para o gerenciamento de ativos de dados. 2021. Disponível em: <https://www.cio.com/article/3521011/what-is-data-governance-a-best-practices-framework-for-managing-data-assets.html#:~:text=Data%20governance%20definition&text=It%20encompasses%20the%20people%2C%20processes,manage%20and%20protect%20data%20assets.&text=The%20Data%20Management%20Association%20(DAMA,and%20data%2Drelated%20sources.%E2%80%9D> Acesso em: 26 jun. 2021.

