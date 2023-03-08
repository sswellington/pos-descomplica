# Gestão de DW e BI

Um data warehouse (DW) é composto de dois componentes principais: uma base de dados para suporte à decisão e programas relacionados à coleta, limpeza, transformação e armazenamento de dados. Nesse sentido, DW pode ser imaginado como um armazém de dados agrupados por assuntos que auxiliam na tomada de decisão. O DW tem os requisitos de dados históricos e analíticos para business intelligence (BI), onde BI permite: consultar, analisar e reportar atividades para monitoramento e compreensão das operações da empresa; e auxiliar nas decisões estratégicas da empresa com dados resumidos.

A gestão de DW e BI procura fazer a coleção, integração e apresentação dos dados para auxiliar na análise do negócio e na tomada de decisão. As principais atividades são: mover e transformar os dados para uma base em comum; prover diversos meios de acesso e manipulação dos dados; e reportar dados integrados da base em comum.

Dentro da gestão de DW e BI, os projetos envolvem: prover armazenamento integrado de dados, atuais e históricos, organizado por assunto; garantir qualidade e acesso apropriado aos dados; garantir ambiente confiável, estável e de alto desempenho para aquisição, gestão e acesso aos dados; prover ambiente de fácil uso e flexível para acesso aos dados; entregar conteúdo e acesso de maneira incremental, alinhados aos objetivos da empresa; definir, construir e suportar o armazenamento, processo e infraestrutura de dados.

No quesito de BI, uma parte muito importante é a definição de ferramentas de consulta e relatórios. Uma vez que os dados estejam organizados no DW, os processos de BI viabilizam a produção de consultas e relatórios nos dados agregados para auxiliar na tomada de decisão, sendo as principais ferramentas de mercado: Power BI, Tableau e Qlik.

Para organizar os dados no DW, etapas de pré-processamento são necessárias. Nesse processo, pode-se elencar: definição de staging; mapeamento origem-destino; limpeza; transformação; reconciliação; e, por fim, carga. A definição de staging se refere ao espaço virtual que será utilizado como temporário durante as transformações dos dados. O mapeamento origem-destino indicará quais tabelas transacionais do sistema serão utilizadas para compor cada agrupamento dentro do DW. Quanto à limpeza, é necessário observar quais registros estão prontos e em condições para serem utilizados, e os que não estão poderão ser removidos dentro do staging. A transformação modifica as informações para que o mapeamento aconteça e seja mantido no agrupamento da maneira esperada. A reconciliação diz respeito à junção das informações provenientes de diferentes domínios, por exemplo, vendas e região onde o cliente mora. E por último, a carga diz respeito ao processo que fará o carregamento das informações do staging para o repositório final, onde se tornará disponível para os processos de BI.

Dentro dessa gestão, o monitoramento é uma das atividades essenciais devido a tratar de um conjunto de dados isolado do resto das bases de dados vinculadas ao negócio da empresa. Assim, todo cuidado com as bases de origem é necessário ter com a base onde reside o DW. No monitoramento, é importante observar: os gargalos das consultas (se elas levam mais tempo que o combinado com os usuários); as dependências de dados (se todas as tabelas estão sendo carregadas normalmente e se estão disponíveis durante a janela de processamento; refinamento dos índices (para manter as consultas e as integrações operando da maneira mais rápida, dentro do possível); recuperação após falhas (se há processos bem definidos para backup e contenção de falhas quando a carga não for realizada na janela de processamento); e arquivamento dos dados.

Nos cenários mais atuais, uma alternativa que tem ganhado força e oferecido vantagem competitiva para as empresas são os data lakes. A diferença entre data lake e data warehouse é que no data lake, todos os dados crus são mantidos no repositório, enquanto o data warehouse organiza e agrupa os dados para fazer o armazenamento. Isso dá flexibilidade para que novas consultas e novas estratégias sejam avaliadas rapidamente no data lake, enquanto no data warehouse seria necessário criar novos processos para transformar e salvar as informações.

 

 

Atividade extra:

Vídeo no Youtube, “O que é um data lake?”:

https://www.youtube.com/watch?v=U6WS0mNOQ5Y

 

 

Referência Bibliográfica:

Data Management Body of Knowledge, Dama International, Data Management Association, 2017.

Barbieri, Carlos. Governança de Dados: práticas, conceitos e novos caminhos. Brazil, Altas Books, 2019.

Rêgo, Bergson. Simplificando a Governança de Dados: governe os dados de forma objetiva e inovadora. Brasport, 2020.

