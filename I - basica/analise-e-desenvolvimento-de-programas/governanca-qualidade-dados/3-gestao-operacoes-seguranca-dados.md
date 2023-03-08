# Gestão de Operações e Segurança dos Dados

A gestão da operação dos dados se define como as atividades de planejamento, controle e suporte durante o ciclo de vida dos dados. Os objetivos da gestão de operação de dados são: proteger e garantir a integridade dos dados estruturados; gerenciar a disponibilidade dos dados durante seu ciclo de vida; e otimizar o desempenho das operações no banco de dados.

Por sua vez, a gestão da segurança de dados se refere à autenticação, autorização, acesso e auditoria dos dados. Nesta gestão, os objetivos são: promover acesso autorizado e negar acesso inapropriado aos dados; e atender aos requisitos regulatórios de privacidade e confidencialidade.

As duas gestões estão relacionadas no que diz respeito à proteção e integridade dos ativos de dados. Tanto a operação quanto a segurança estão em sincronia com o ciclo de vida dos dados. Basicamente há dois pontos neste assunto: a permissão de leitura e escrita aos dados; e a adequação ao modelo de dados.

A gestão de operações tem também como foco acompanhar a disponibilidade dos dados. A disponibilidade dos dados é um dos componentes do desempenho de um banco de dados. Além de ter consultas que sejam atendidas dentro do tempo combinado, é importante que os dados estejam disponíveis para essas consultas. Assim, a disponibilidade é medida pelo percentual de tempo que o banco está disponível.

As exigências de disponibilidade aumentam à medida que o negócio cresce e o risco aumenta com a indisponibilidade. São pontos de observação: consumo de dados de terceiros; controle do banco de dados; planejamento para recuperação dos dados; planejamento de retenção dos dados; suporte a bancos especializados.

Além da disponibilidade, também interessa que as consultas e a utilização de um modo geral do banco de dados sejam otimizadas. A otimização de transações consiste em medir o desempenho daquilo que se deseja otimizar, verificar se atende aos requisitos iniciais previamente combinados de tempo esperado para obter uma resposta e, por último, de fato implementar a otimização, observando as oportunidades. São oportunidades de otimização os seguintes pontos: alocação de memória (buffer/cache); falha na atualização das estatísticas de uso; falta de indexação; locking e bloqueio; código SQL de baixa qualidade; e aumento de número de usuários, tamanho ou do uso do banco de dados.

Em termos de segurança, a principal preocupação são os acessos inapropriados e o vazamento de informações que pode originar a partir disso. Os acessos inapropriados podem levar a: execução de comandos que podem fazer os dados perderem a integridade;

E execução de consultas que permitem usuários verem informações confidenciais (internas e externas).

Os acessos inapropriados ainda podem ser divididos em quatro pontos: autenticação (onde é verificado se os usuários dizem ser quem são por meio de alguma informação particular, como senha); autorização (identifica quais direitos individuais o usuário tem e seus privilégios, se a nível de tabela ou a nível de coluna/informação); acesso (habilita os usuários e seus privilégios no esquema de dados, após ter sido previamente identificadas as necessidades); e auditoria (revisa as ações e atividades dos usuários em termos de conformidade regulatória, verificando os dados que estão acessados, com qual frequência e o alinhamento com suas tarefas).

O acesso a informação confidencial ou privilegiada é impactante para a empresa porque ela normalmente está ou deve estar em conformidade regulatória (compliance) com entidades da própria empresa ou entidades externas, como órgãos regulatórios. Por exemplo, as instituições financeiras devem seguir as diretrizes do Banco Central (BACEN) no Brasil. São exemplos: os contratos de confidencialidade (NDA) com terceiros; NDA com os funcionários internos (venda de informações); e a Lei Geral de Proteção aos Dados (LGPD).

 

 

Atividade extra:

Vídeo no Youtube, “Alta disponibilidade em bancos de dados”:

https://www.youtube.com/watch?v=GMsocIQmhPI

 

 

Referência Bibliográfica:

Data Management Body of Knowledge, Dama International, Data Management Association, 2017.

Barbieri, Carlos. Governança de Dados: práticas, conceitos e novos caminhos. Brazil, Altas Books, 2019.

Rêgo, Bergson. Simplificando a Governança de Dados: governe os dados de forma objetiva e inovadora. Brasport, 2020.