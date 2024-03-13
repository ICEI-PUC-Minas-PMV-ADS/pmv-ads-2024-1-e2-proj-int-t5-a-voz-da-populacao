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

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir o usuário acessar seu site com o login | ALTA |
|RF-002| O sistema deve permitir o usuário criar o seu cadastro na página | ALTA |
|RF-003| O sistema deve permitir o registro de usuários com diferentes níveis de permissão (cidadão e agente), assim como recuperação/alteração de senha e edição de permissionamento | ALTA |
|RF-004| O sistema deve permitir que o cidadão realize abertura de demandas para relatar problemas com status inicial "Em espera" | ALTA |
|RF-005| O sistema deve permitir que o cidadão acompanhe o status de suas demandas | MÉDIA |
|RF-006| O sistema deve permitir que o agente altere o status (Em espera, Em andamento e Concluído) das suas demandas | MÉDIA |
|RF-007| O sistema deverá enviar atualizações sobre as ações tomadas pelo segmento responsável | ALTA |
|RF-008| O cidadão deverá selecionar categorias para indicar o seguimento no inicio do cadastro da demanda | MÉDIA |
|RF-009| O sistema deve permitir que o usuário anexe arquivos de até 20MB para complementar o relatório | BAIXA |
|RF-010| O sistema deve permitir ao cidadão editar a demanda antes dela ter o status inicial alterado | BAIXA |
|RF-011| Os cadastros de usuários de pessoa fisica (cidadão) deverá ser obrigatório o dado de CPF | ALTA |
|RF-012| Os cadastros de usuários responsáveis (agente) por cada setor da prefeitura deverão ser obrigatório o dado de CNPJ | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser de fácil utilização e ter uma interface intuitiva para que usuários de diferentes perfis possam relatar problemas de forma rápida e eficiente | ALTA |
|RNF-002| A aplicação deve ser responsiva e funcionar corretamente em diferentes dispositivos, como smartphones, tablets e computadores | ALTA |
|RNF-003| A aplicação deve garantir a segurança dos dados dos usuários, protegendo as informações pessoais e os relatórios enviados | ALTA |
|RNF-004| A aplicação deve ser compatível com os principais navegadores web (Chrome, Firefox, Safari, Edge) | MÉDIA |
|RNF-005| As contas devem ser limitadas a um cadastro por CPF | ALTA |
|RNF-006| O projeto deverá ser desenvolvido em C# | MÉDIA |
|RNF-007| O projeto deverá ser desenvolvido na IDE Visual Studio             | MÉDIA |
|RNF-008| O projeto deverá utilizar o Entity Framework como ORM | MÉDIA |

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

## Diagrama de Casos de Uso

O diagrama de casos de uso apresentado na Figura 1 ilustra as principais interações entre os usuários e um sistema de abertura de chamados de demandas municipais.

> Para visualizar o protótipo, acesse o [Lucidchart](https://lucid.app/lucidchart/8ea78e16-93af-44e9-8f13-99974dd91e47/edit?viewport_loc=-180%2C627%2C4986%2C2454%2C.Q4MUjXso07N&invitationId=inv_65d7f556-c976-44ad-a796-bb88e2529b10) do projeto.

![image](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e2-proj-int-t5-a-voz-da-populacao/assets/139129269/3f09bced-0482-4cb5-b758-4e547808bd3e)





