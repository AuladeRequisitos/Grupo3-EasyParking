
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet: https://padlet.com/mpinheiro16/kanban-requisitos-de-software-7dfmfb8ahzn9mcz3

O projeto se encaixa no Objetivo 9: Construir infraestruturas resilientes, promover a industrialização inclusiva e sustentável e fomentar a inovação.

## 1. Introdução

***1.1.  Nome do Grupo***

GRUPO 3 - SOFTWARE DE GERENCIAMENTO DE ESTACIONAMENTO


KENJI KATO - GITHUB: @Kenji1-maker  
MAURICIO AQUINO - GITHUB: @aqu1no1  
LUÍS FERNANDO - GITHUB: @luinsta  
MARIA FERNANDA - GITHUB: @mariaferleal  
GIOVANA SENA - GITHUB: @giovanaxs  
 

Nome do sistema:
 - EasyParking

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela EasyParking, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do nosso sistema de gerenciamento de estacionamentos é gerenciar o uso de vagas de forma eficiente, segura e automatizada. A plataforma permite que usuários cadastrem seus dados pessoais e veiculares, reservem vagas com antecedência e controlem o fluxo de entrada e saída dos veículos, proporcionando mais comodidade e agilidade.

Nosso aplicativo é voltado para estacionamentos modernos que contam com cancelas automáticas, sensores de vagas e câmeras de vigilância. Ele foi desenvolvido para oferecer mais praticidade, segurança e eficiência tanto para os gestores quanto para os usuários do estacionamento. Através da integração com sensores, o app permite o monitoramento em tempo real da ocupação das vagas, facilitando a organização e otimizando o uso do espaço. A cancela automatizada pode ser controlada diretamente pelo sistema, permitindo a entrada e saída de veículos de forma rápida e segura, sem a necessidade de intervenção manual. Além disso, as câmeras de segurança integradas ao sistema garantem maior controle e vigilância, registrando toda a movimentação no local e contribuindo para a proteção de veículos e pessoas.

Com essas funcionalidades integradas, o projeto contribui para a melhoria da gestão de estacionamentos, aumentando a segurança, reduzindo o tempo de busca por vagas e promovendo uma experiência mais fluida e organizada para os usuários.


***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes e demais partes interessadas que participarão do desenvolvimento do sistema.

O público-alvo do sistema é dividido em dois grupos principais:

- Motoristas: usuários que utilizam estacionamentos de alta rotatividade, como os localizados em shoppings, universidades, empresas e centros comerciais. Estes buscam praticidade, agilidade e segurança no momento de estacionar seus veículos.

- Administradores: responsáveis pela gestão dos estacionamentos, interessados em um sistema moderno e eficiente para aprimorar a organização, o controle de entrada e saída de veículos, a supervisão do uso das vagas e o aumento da segurança no local.

***1.3. Descrição dos usuários***

Os usuários finais do sistema EasyParking são motoristas que utilizam estacionamentos de alta rotatividade e buscam mais agilidade, segurança e praticidade na ocupação de vagas. Entre os perfis atendidos pelo sistema estão:
 - Motoristas em geral, que enfrentam dificuldades recorrentes para encontrar vagas disponíveis, o que compromete seu tempo e produtividade diária.
 - Pessoas com deficiência (PCDs), que frequentemente encontram vagas especiais ocupadas de forma indevida ou indisponíveis, prejudicando sua mobilidade.
 - Administradores e funcionários operacionais, responsáveis pelo gerenciamento do estacionamento, controle de entrada e saída de veículos, e supervisão da ocupação das vagas.
   
Esses usuários interagem com o sistema de maneiras distintas, conforme suas necessidades, utilizando recursos como reserva de vagas, visualização em tempo real da disponibilidade, e controle automatizado de acesso e uso.

***Personas:***

## Persona 1
![Activity](https://github.com/user-attachments/assets/5d603e3c-9dec-4c7f-aaf4-dde3026f942d)

## Persona 2
![Activity (2)](https://github.com/user-attachments/assets/2c6fd6ac-d80f-4ef8-a9b0-701ec3f5a0e2)

## Persona 3

![Activity (3)](https://github.com/user-attachments/assets/921159e1-c816-4ced-8bc2-83631b7ccbac)


***Análise da situação atual: antes da introdução de sua solução***

*`1. O que as pessoas fazem?`*

Antes do sistema, os clientes precisavam ir fisicamente a vários estacionamentos até encontrarem uma vaga disponível, o que demandava tempo e causava cansaço. O administrador controlava as informações manualmente.

*`2. Quais os artefatos envolvidos?`*

- Os clientes precisavam saber os preços, horários de funcionamento e localização do estacionamento.
- O administrador precisava ter controle sobre horários de entrada/saída, placas dos veículos, RGs e outras informações dos clientes.

*`3. O que elas precisam saber?`*


- Um caderno ou ficha de papel, utilizado pelo administrador para anotar dados como horário de entrada/saída, número da placa e dados pessoais.

- Comunicação verbal entre cliente e administrador.


***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

*`1. O que as pessoas fazem?`*

Os clientes agora têm duas opções:

1 - Reserva antecipada pelo sistema, cadastrando seus dados pessoais e veiculares.

2 - Chegada presencial, consultando o administrador sobre a disponibilidade de vagas.

*`2. Quais os artefatos envolvidos?`*

Para usar o sistema, é necessário fazer login ou se cadastrar.

- Em caso de chegada presencial sem reserva, o cliente precisa conversar com o administrador.

- O funcionamento do sistema, como horários, preços e regras de uso.

*`3. O que elas precisam saber?`*

1- Software de gerenciamento de estacionamento, com:

 - Interface web (para computadores e notebooks).

 - Interface adaptada para dispositivos móveis.

2- Computador para o administrador, usado para acompanhar reservas e monitorar a ocupação.

3 - Documentos pessoais dos clientes, exigidos para cadastro e controle.


## Persona 1
***Cenário: Antes***

Júlia trabalha em uma grande empresa de tecnologia e precisa estar em seu local de trabalho às 8h, sem se atrasar nem perder tempo procurando vaga. Em um dia comum, ela chega à empresa por volta das 7h30, mas se depara com uma longa fila de carros na entrada, já que o controle de acesso é manual e lento.
Após alguns minutos de espera, Júlia consegue entrar no estacionamento, mas começa a rodar pelas dependências da empresa em busca de uma vaga. Todas as vagas já estão ocupadas, e o sistema atual não oferece nenhuma informação em tempo real sobre a disponibilidade.
Com o tempo apertado e sem alternativa, ela decide estacionar fora da empresa, em uma rua próxima, porém sem segurança. Júlia chega atrasada para o início do expediente e ainda fica preocupada com a segurança do seu veículo. Esse tipo de situação é frequente e afeta sua produtividade e tranquilidade logo no início do dia.

***Cenário: Depois***

Júlia trabalha numa grande empresa de tecnologia, onde precisa estar 8h no seu trabalho, sem se atrasar nem perder tempo procurando vaga. 
Na noite anterior ao expediente, ela acessa a plataforma EasyParking, visualiza o mapa com as vagas disponíveis e realiza a reserva de uma vaga próxima à entrada do prédio onde trabalha. Júlia preenche seus dados pessoais e do veículo, definindo o horário de uso da vaga das 7h30 às 18h.
Na manhã seguinte, ao chegar à empresa por volta das 7h30, a cancela de entrada reconhece automaticamente a placa do seu veículo e libera a passagem sem necessidade de parar. Pelo aplicativo, ela recebe instruções em tempo real com o caminho até a vaga reservada, que aparece destacada no mapa interativo e sinalizada como “reservada” para garantir seu uso exclusivo.
Ela estaciona com rapidez e segurança, sem precisar procurar por vagas ou enfrentar filas, chegando com tranquilidade ao seu setor, no horário correto e sem estresse.

## Persona 2
***Cenário: Antes***

Roberto é um senhor de 68 anos, aposentado, que costuma passear pelo centro da cidade durante a semana para resolver pendências e encontrar amigos. Em uma dessas saídas, ele decide ir ao centro resolver alguns compromissos. 
Ao chegar lá, enfrenta dificuldades para encontrar uma vaga de estacionamento com acessibilidade. Após muito tempo procurando e sem sucesso, acaba deixando o carro longe do local desejado. 
O trajeto a pé é cansativo, o que o desanima. Ao final do dia, Roberto retorna para casa frustrado, sentindo-se menos independente e um pouco isolado por não conseguir realizar suas atividades com automonia.

***Cenário: Depois***

Roberto é um senhor de 68 anos, aposentado, que costuma passear pelo centro da cidade durante a semana para resolver pendências e encontrar amigos. Na noite anterior, com a ajuda de um familiar, ele acessa a plataforma EasyParking em seu celular e encontra vagas acessíveis próximas ao local que deseja visitar. Ele realiza a reserva das vagas, informando o horário estimado de uso e os dados do veículo. 
Na manhã seguinte, ao chegar ao centro, a cancela reconhece a placa do carro e libera sua entrada. Pelo aplicativo, Roberto recebe orientações em tempo real sobre como chegar até a vaga que reservou, identificada no mapa interativo da plataforma. 
Ele estaciona com segurança e tranquilidade, realiza suas tarefas sem pressa e ainda aproveita a tarde com os amigos.

## Persona 3
***Cenário: Antes***

Diego é administrador e um dos fundadores de um estacionamento no centro da cidade, ele está sempre presente acompanhando tudo de perto. No entanto, nos horários de maior movimento, o estacionamento enche rapidamente, o que causa insatisfação nos clientes e aumenta a carga de trabalho dos funcionários. 
Como o controle de acesso é feito manualmente, a entrada fica mais lenta e a organização das vagas mais difícil, o que exige mais colaboradores e aumenta os custos operacionais. 
Durante o dia, Diego fica ocupado resolvendo problemas do dia a dia e tentando equilibrar a qualidade do serviço com os gastos, o que acaba dificultando o foco em melhorias e no crescimento do negócio.

***Cenário: Depois***

Diego é administrador e um dos fundadores de um estacionamento no centro da cidade, ele decidiu implementar a plataforma EasyParking para tornar seu negócio mais eficiente. Com essa solução, os clientes podem reservar suas vagas com antecedência pelo aplicativo, que também mostra em tempo real quais lugares estão disponíveis. 
O controle de acesso agora é feito por leitura automática das placas, o que ajuda a evitar filas e acelera a entrada e saída dos veículos. Além disso o próprio aplicativo direciona os motoristas até a vaga reservada por meio de instruções simples na tela, melhorando a experiência deles e reduzindo a necessidade de tantos funcionários para organizar tudo internamente. 
Com o sistema mais eficiente, Diego consegue diminuir os custos operacionais, aumentar a satisfação dos clientes e dedicar mais tempo para pensar em estratégias de crescimento.

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

## Requisitos Funcionais (RF)

| Identificador | Descrição | Prioridade | Depende de |
|---------------|-----------|------------|------------|
| RF01 | O sistema deve permitir o cadastro de usuários com dados pessoais. | M | — |
| RF02 | O sistema deve permitir o registro de veículos (marca, modelo, tipo, placa e cor). | M | RF01 |
| RF03 | O sistema deve gerar um código de identificação único para cada usuário. | M | RF01 |
| RF04 | O sistema deve permitir a consulta em tempo real das vagas disponíveis. | S | RF01 |
| RF05 | O sistema deve permitir a reserva e o cancelamento de uma vaga específica. | M | RF04 |
| RF06 | O sistema deve permitir o controle de entrada por meio do código de identificação. | M | RF03, RF05 |
| RF07 | O sistema deve permitir o controle de saída utilizando o código de identificação e senha. | M  | RF06 |
| RF08 | O sistema deve exibir o tempo de permanência do veículo na vaga. | S | RF06 |
| RF09 | O sistema deve calcular o valor da estadia com base no tempo registrado. | M | RF08 |
| RF10 | O sistema deve alertar o porteiro se um veículo não autorizado ocupar uma vaga. A identificação é feita via imagem de câmera | S | RF06, RF05 |
| RF11 | O sistema deve permitir que o usuário visualize imagens ao vivo da vaga onde seu veículo está estacionado. | C | RF06 |
| RF12 | O sistema deve registrar a entrada e saída com data, hora e imagem capturada pela câmera. | C | RF06 |
| RF13 | O sistema deve permitir o envio de notificações em tempo real para o usuário (ex: entrada, saída, tempo restante). | S | RF06, RF08 |
| RF14 | O sistema deve gerar relatórios mensais (faturamento, horários de maior ou menor movimentação, etc) de uso para os administradores. | C | RF01, RF06 |
| RF15 | O sistema deve permitir a recuperação de senha por e-mail cadastrado. | M | RF01 |

***2.2. Requisitos Não Funcionais***

## Requisitos Não Funcionais (RNF)  

| Identificador | Descrição | Prioridade | Depende de |
|---------------|-----------|------------|------------|
| RNF01 | O sistema deve estar disponível 99,5% do tempo. | M | — |
| RNF02 | O sistema deve utilizar HTTPS para criptografar todos os dados. | M | — |
| RNF03 | As respostas do sistema devem ser retornadas em até 2 segundos. | S | RF04, RF05 |
| RNF04 | O sistema deve ser compatível com navegadores modernos e dispositivos móveis | M | — |
| RNF05 | O sistema deve suportar até 500 usuários simultâneos.| M | RF01, RF09 |
| RNF06 | A interface deve seguir padrões de acessibilidade (WCAG 2.1). | S | — |
| RNF07 | O sistema deve enviar confirmações de ações (reserva, entrada, saída) em até 5 segundos | M | RF05, RF06, RF07 |
| RNF08 | O backup do banco de dados deve ser feito automaticamente a cada 24 horas. | M | — |
| RNF09 | O banco de dados deve ter replicação geográfica na nuvem.| M | RF01, RF02 |
| RNF10 | A autenticação deve utilizar senhas criptografadas e políticas de segurança. | M | RF07 |
| RNF11 | O sistema deve suportar transmissão de vídeo ao vivo com latência inferior a 3 segundos. | S | RF11 |
| RNF12 | O tempo de carregamento inicial da aplicação não deve ultrapassar 3 segundos em conexões 4G. | S | — |
| RNF13 | O sistema deve exibir mensagens de erro claras e responsivas em caso de falha de conexão ou ações inválidas. | M | — |
| RNF14 | 	O sistema deve ser capaz de restaurar o serviço automaticamente em até 1 minuto após falhas críticas. | M | 	RNF01 |
| RNF15 | As imagens capturadas pelas câmeras devem ser armazenadas por no mínimo 7 dias em ambiente seguro. | S | RF12 |

***2.3. Perguntas***

`1- Como você costuma procurar vagas de estacionamento atualmente?`  
`2- Com que frequência você enfrenta dificuldade para encontrar uma vaga disponível?`  
`3- Você já teve problemas com ocupação indevida de vagas especiais, como as destinadas a PCD's? Se sim, com que frequência?`  
`4- Você consideraria reservar uma vaga com antecedência, caso essa funcionalidade estivesse disponível? Por que?`   
`5- Quais informações você gostaria de ver em tempo real sobre o estacionamento? `  
`6- Feedback sobre a aplicação. Após ver tudo que foi feito, você aprova nossa aplicação?`  

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***  


| ID   | Como...         | Quero...                                                                 | Para...                                                                                       |
|------|------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| RF1  | Cliente           | Fazer o meu cadastro                                                    | Ter acesso aos benefícios do sistema                                                         |
| RF2  | Cliente           | Registrar os dados do meu veículo                                       | Poder utilizá-lo em uma vaga                                                                 |
| RF3  | Administrador     | Que cada usuário receba um código único após o cadastro                 | Conseguir identificá-lo com segurança                                                        |
| RF4  | Cliente           | Consultar as vagas disponíveis em tempo real                            | Decidir qual vaga irei escolher                                                              |
| RF5  | Cliente           | Reservar ou cancelar uma vaga específica                                | Garantir a minha vaga no estacionamento quando eu chegar                                     |
| RF6  | Cliente           | Entrar no estacionamento usando o código de identificação               | Entrar sem necessidade de novo registro                                                      |
| RF7  | Administrador     | Validar a saída do veículo com código e senha                           | Garantir que apenas usuários autorizados saiam com segurança                                 |
| RF8  | Cliente           | Visualizar o tempo de permanência do meu veículo                        | Acompanhar por quanto tempo estou estacionado                                                |
| RF9  | Cliente           | Que o sistema calcule o valor da estadia com base no tempo              | Saber quanto devo pagar ao sair                                                              |
| RF10 | Porteiro          | Ser alertado se um veículo não autorizado ocupar uma vaga               | Impedir acessos indevidos, com base em imagem da câmera                                      |
| RF11 | Motorista         | Visualizar imagens ao vivo da vaga onde meu carro está                 | Acompanhar com segurança meu veículo                                                         |
| RF12 | Administrador     | Visualizar os registros de entrada e saída com data e hora              | Ter controle e histórico de acesso                                                           |
| RF13 | Motorista         | Receber notificações em tempo real do sistema                           | Estar sempre informado sobre minha reserva                                                   |
| RF14 | Administrador     | Ter um relatório mensal com dados importantes gerados pelo sistema      | Ter maior controle e embasamento para tomada de decisão                                      |
| RF15 | Cliente           | Recuperar a minha senha por e-mail cadastrado                           | Recuperar meu acesso ao aplicativo                                                           |



***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***
![Page%201](https://github.com/user-attachments/assets/84def1b9-4bf2-42d1-93d0-8985571350b5)
![Page%205](https://github.com/user-attachments/assets/19be63b4-7c61-45f8-95f2-a8ec0bf59a6b)
![Page%202](https://github.com/user-attachments/assets/f22aa0e8-e596-4ecc-a06c-7b85f067b1c5)
![Page%203](https://github.com/user-attachments/assets/ddad2d09-88fb-4228-8277-24c17b120f29)
![Page%204](https://github.com/user-attachments/assets/1cbea8fb-4597-400f-a185-2a94d8972133)

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
