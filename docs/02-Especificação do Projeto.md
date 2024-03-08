# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Ana é uma moradora ativa, preocupada com a qualidade de vida em seu bairro. Mãe de dois filhos pequenos, ela busca uma maneira rápida e eficiente de reportar problemas como buracos no asfalto, falta de iluminação pública e acúmulo de lixo nas calçadas à prefeitura. Ana procura se sentir ouvida pelas autoridades locais e deseja contribuir para a melhoria da comunidade.
Ana já tentou contatar a prefeitura por telefone e e-mail, sem sucesso. Ela se sente desanimada com a falta de resposta e a dificuldade de acompanhar o status de suas solicitações, buscando uma solução mais transparente e eficaz para relatar questões locais

João é um empresário bem-sucedido que administra uma pequena rede de restaurantes na cidade. Ele é conhecido por sua paixão pela comunidade local e está sempre em busca de maneiras de contribuir para o desenvolvimento da região. Como proprietário de negócios, João está particularmente preocupado com questões como segurança pública, infraestrutura urbana e limpeza das ruas. O empresário enfrenta constantemente desafios relacionados à segurança e manutenção da área em torno de seus restaurantes, como problemas de iluminação, buracos nas ruas e coleta irregular de lixo.
João já teve experiências frustrantes ao tentar relatar problemas à prefeitura, encontrando dificuldades para obter respostas e soluções eficazes para as questões enfrentadas em sua área de negócios.

Pedro é uma morador ativo da comunidade, Ela utiliza regularmente a academia ao ar livre próxima à sua casa para fazer exercícios físicos. Recentemente, Pedro percebeu existia aguá parada devido a lixo no local, podendo acarretar na presença de focos de dengue em áreas públicas. Preucupado coma situação , Pedro decidiu fazer uma visita pessoal à sede da prefeitura para relatar o problema . Ele deixou seu nome e informações de contato na recepção, mas não obteve retorno algum.

Prefeito Antônio, há dois anos no cargo, é reconhecido por sua integridade e compromisso com a transparência na gestão pública. Ele valoriza a participação dos cidadãos e vê na aplicação de abertura de chamados uma oportunidade para fortalecer o diálogo direto com a comunidade. Seu objetivo é construir confiança com os eleitores, demonstrando responsabilidade e eficiência na resolução dos problemas locais.

Lucas, secretário de Obras e Infraestrutura, lidera os esforços para desenvolver e manter a infraestrutura urbana da cidade. Busca eficiência e transparência, esperando que a aplicação forneça métricas para avaliar o progresso dos Chamados abertos pelo cidadão. Seu objetivo é utilizar essas métricas para demonstrar a eficácia e a transparência do trabalho da secretaria.



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

|EU COMO... `PERSONA`   | QUERO/PRECISO ... `FUNCIONALIDADE`                                                    |PARA ... `MOTIVO/VALOR`                                                                                                                           |
|-----------------------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|Ana                    | relatar buracos nas ruas                                                              | para garantir a manutenção adequada da infraestrutura urbana e facilitar a minha comunicação com a prefeitura                                    |
|João                   | comunicar problemas de iluminação pública nas proximidades do meu estabelecimento     | para contribuir para a segurança geral da região. e conseguir me comunicar com a prefeitura direto pelo meu computador no conforto da minha casa |
|Pedro                  | comunicar a presença de focos de dengue em áreas públicas                             | para proteger a saúde da comunidade e prevenir surtos de doenças transmitidas por vetores.                                                       |          
|Antônio                | Desejo me comunicar de forma transparente e eficiente o cidadão                       | Mostrar com clareza as atividades realizadas pela prefeitura em atender as solicitações e esclarecer eventuais duvidas do cidadão                |
|Lucas                  | Quero resolver e retornar os chamados referente a minha pasta                          | Mostrar o compromisso em atender as demandas da população e ter métricas para demonstrar a eficácia e a transparência do trabalho da secretaria. |                                   |

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
|RF-001| O sistema deve permitir o usuário acessar seu site com o login | ALTA |
|RF-002| O sistema deve permitir o usuário criar o seu cadastro na página | ALTA |
|RF-003| O sistema deve permitir o registro de usuários com diferentes níveis de permissão (cidadão e agente), assim como recuperação/alteração de senha e edição de permissionamento | ALTA |
|RF-004| A aplicação deve permitir que o usuário relate problemas de infraestrutura urbana (buracos, iluminação, etc.) | ALTA |
|RF-005| A aplicação deve permitir que os usuários acompanhem o status de seus relatórios e recebam atualizações sobre as ações tomadas pelo segmento responsável | MÉDIA |
|RF-006| A aplicação deve permitir que o usuário relate problemas de limpeza urbana (lixo, poluição, etc.) | ALTA |
|RF-007| A aplicação deve permitir que o usuário relate problemas de acessibilidade em locais públicos | ALTA |
|RF-008| A aplicação deve permitir que o usuário relate problemas de segurança pública | ALTA |
|RF-009| A aplicação deve permitir que o usuário relate problemas ambientais (desmatamento, falta de áreas verdes, etc.) | ALTA |
|RF-010| A aplicação deve permitir que o usuário relate problemas em escolas municipais | ALTA |
|RF-011| A aplicação deve permitir que o usuário relate focos de dengue em áreas públicas | ALTA |
|RF-012| A aplicação deve fornecer um sistema de notificações para alertar os usuários sobre problemas semelhantes relatados em sua área | MÉDIA |
|RF-013| Os usuários deverão adicionar flags para indicar o seguimento do problema | MÉDIA |
|RF-014| A aplicação deve permitir que o usuário anexe arquivos de até 20MB para complementar o relatório | BAIXA |
|RF-015| Os cadastros de usuários de pessoa fisica deverá ser obrigatório o dado de CPF | ALTA |
|RF-016| Os cadastros de usuários responsáveis por cada setor da prefeitura deverão ser obrigatório o dado de CNPJ | ALTA |

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
|RNF-010| O projeto deverá ser desenvolvido em C# | MÉDIA |
|RNF-011| O projeto deverá ser desenvolvido na IDE Visual Studio             | MÉDIA |
|RNF-012| O projeto deverá utilizar o Entity Framework como ORM | MÉDIA |

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
|03| O projeto deverá utilizar um banco de dados |
|04| O projeto deverá conter testes unitários |
|05| O projeto deverá conter dois CRUDs |
|06| O projeto deverá conter um sistema de autenticação |


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
