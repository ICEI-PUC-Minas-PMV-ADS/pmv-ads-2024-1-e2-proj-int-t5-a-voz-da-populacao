# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Ana é uma moradora ativa, preocupada com a qualidade de vida em seu bairro. Mãe de dois filhos pequenos, ela busca uma maneira rápida e eficiente de reportar problemas como buracos no asfalto, falta de iluminação pública e acúmulo de lixo nas calçadas à prefeitura. Ana procura se sentir ouvida pelas autoridades locais e deseja contribuir para a melhoria da comunidade.
Ana já tentou contatar a prefeitura por telefone e e-mail, sem sucesso. Ela se sente desanimada com a falta de resposta e a dificuldade de acompanhar o status de suas solicitações, buscando uma solução mais transparente e eficaz para relatar questões locais

João é um empresário bem-sucedido que administra uma pequena rede de restaurantes na cidade. Ele é conhecido por sua paixão pela comunidade local e está sempre em busca de maneiras de contribuir para o desenvolvimento da região. Como proprietário de negócios, João está particularmente preocupado com questões como segurança pública, infraestrutura urbana e limpeza das ruas. O empresário enfrenta constantemente desafios relacionados à segurança e manutenção da área em torno de seus restaurantes, como problemas de iluminação, buracos nas ruas e coleta irregular de lixo.
João já teve experiências frustrantes ao tentar relatar problemas à prefeitura, encontrando dificuldades para obter respostas e soluções eficazes para as questões enfrentadas em sua área de negócios.

Maria é uma estudante universitária que mora sozinha na cidade. Ela é ativa nas redes sociais e tem interesse em questões sociais e ambientais. Maria está preocupada com a preservação do meio ambiente e a sustentabilidade da sua cidade. Como uma jovem preocupada com o futuro, ela deseja uma maneira fácil e eficaz de relatar problemas como poluição em rios e lagos, desmatamento urbano e falta de áreas verdes. Maria acredita que é importante que a prefeitura esteja ciente desses problemas para tomar medidas adequadas e garantir um futuro sustentável para a comunidade.

Carlos é um aposentado que vive há muitos anos na cidade. Ele é um cidadão ativo e participa de grupos comunitários locais. Carlos se preocupa com a qualidade de vida dos moradores mais idosos da cidade e está sempre em busca de maneiras de melhorar a acessibilidade e os serviços para essa população. Como um idoso, ele enfrenta desafios diários, como falta de rampas de acessibilidade, calçadas irregulares e falta de transporte público adequado para pessoas idosas. Carlos quer uma maneira fácil de relatar esses problemas à prefeitura e garantir que a cidade seja mais inclusiva e acessível para todos os seus moradores.

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                                  |PARA ... `MOTIVO/VALOR`                                                                                                             |
|--------------------|-------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
|moradora da cidade  | relatar buracos nas ruas                                                            | para garantir a segurança dos pedestres e motoristas e contribuir para a manutenção adequada da infraestrutura urbana              |
|comerciante local   | comunicar problemas de iluminação pública nas proximidades do meu estabelecimento   | para garantir um ambiente seguro para meus clientes e funcionários, e também contribuir para a segurança geral da região.          |
|pai de família      | reportar a falta de limpeza em parques e áreas de lazer                             | para proporcionar um ambiente mais saudável e seguro para as brincadeiras dos meus filhos.                                         |
|idosa               | relatar a falta de acessibilidade em locais públicos                                |para garantir que pessoas com mobilidade reduzida tenham condições adequadas de locomoção.                                          |
|comerciante local               | relatar problemas de coleta irregular de lixo nas proximidades do meu estabelecimento                                |para manter a área comercial limpa e atrativa para clientes, contribuindo para o desenvolvimento econômico da região.                                          |
|estudante universitária              | relatar casos de poluição em rios e lagos                                |para preservar o meio ambiente local e garantir um futuro sustentável para a comunidade.                                       |
|morador da cidade              | comunicar a presença de focos de dengue em áreas públicas                                |para proteger a saúde da comunidade e prevenir surtos de doenças transmitidas por vetores.                                       |
|mãe de criança              |  relatar problemas encontrados na escola municipal frequentada por meu filho                               |para garantir um ambiente seguro e propício ao aprendizado para meu filho e outros alunos, além de contribuir para a melhoria contínua da educação na comunidade.                                       |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário relate problemas de infraestrutura urbana (buracos, iluminação, etc.) | ALTA |
|RF-002| A aplicação deve permitir que os usuários acompanhem o status de seus relatórios e recebam atualizações sobre as ações tomadas pelo segmento responsável | MÉDIA |
|RF-003| A aplicação deve permitir que o usuário relate problemas de limpeza urbana (lixo, poluição, etc.) | ALTA |
|RF-004| A aplicação deve permitir que o usuário relate problemas de acessibilidade em locais públicos | ALTA |
|RF-005| A aplicação deve permitir que o usuário relate problemas de segurança pública | ALTA |
|RF-006| A aplicação deve permitir que o usuário relate problemas ambientais (desmatamento, falta de áreas verdes, etc.) | ALTA |
|RF-007| A aplicação deve permitir que o usuário relate problemas em escolas municipais | ALTA |
|RF-008| A aplicação deve permitir que o usuário relate focos de dengue em áreas públicas | ALTA |
|RF-009| A aplicação deve fornecer um sistema de notificações para alertar os usuários sobre problemas semelhantes relatados em sua área | MÉDIA |
|RF-010| Os usuários deverão adicionar flags para indicar o seguimento do problema | MÉDIA |
|RF-011| A aplicação deve permitir que o usuário anexe arquivos de até 20MB para complementar o relatório | BAIXA |
|RF-012| Os cadastros de usuários de pessoa fisica deverá ser obrigatório o dado de CPF | ALTA |
|RF-013| Os cadastros de usuários responsáveis por cada setor da prefeitura deverão ser obrigatório o dado de CNPJ | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser de fácil utilização e ter uma interface intuitiva para que usuários de diferentes perfis possam relatar problemas de forma rápida e eficiente | ALTA |
|RNF-002| A aplicação deve ser responsiva e funcionar corretamente em diferentes dispositivos, como smartphones, tablets e computadores | ALTA |
|RNF-003| A aplicação deve garantir a segurança dos dados dos usuários, protegendo as informações pessoais e os relatórios enviados | ALTA |
|RNF-004| A aplicação deve ser compatível com os principais navegadores web (Chrome, Firefox, Safari, Edge) | MÉDIA |
|RNF-005| A aplicação deve ser capaz de suportar vários usuários simultâneos | MÉDIA |
|RNF-006| A aplicação deve processar requisições do usuário em no máximo 3s | BAIXA |
|RNF-007| A aplicação deve ser capaz de enviar notificações em tempo real | BAIXA |
|RNF-008| A aplicação deve ser capaz de armazenar e processar grandes volumes de dados | BAIXA |
|RNF-009| As contas devem ser limitadas a um cadastro por CPF | ALTA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Aplicação deverá ser desenvolvida em um módulo de backend        |
|03| O projeto deverá ser desenvolvido em C#               |
|04| O projeto deverá ser desenvolvido na IDE Visual Studio             |
|04| O projeto deverá utilizar o Entity Framework como ORM |
|05| O projeto deverá utilizar um banco de dados |
|06| O projeto deverá conter testes unitários |
|07| O projeto deverá conter dois CRUDs |
|08| O projeto deverá conter um sistema de autenticação |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
