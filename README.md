
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

O objetivo do nosso sistema de gerenciamento de estacionamentos é gerenciar o uso de vagas de estacionamentos de forma eficiente, segura e automatizada. A plataforma permite que usuários cadastrem seus dados pessoais e veiculares, reservem vagas com antecedência e controlem o fluxo de entrada e saída dos veículos, proporcionando mais comodidade e agilidade. Além disso, o sistema realiza o monitoramento em tempo real da ocupação das vagas, utilizando sensores para detectar a presença de veículos, prevenir o uso indevido das vagas e garantir a correta utilização dos espaços disponíveis. Com essas funcionalidades integradas, o projeto contribui para a melhoria da gestão de estacionamentos, aumentando a segurança, reduzindo o tempo de busca por vagas e promovendo uma experiência mais fluida e organizada para os usuários.


***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes e demais partes interessadas que participarão do desenvolvimento do sistema. O público-alvo do sistema inclui motoristas que utilizam estacionamentos de alta rotatividade — como os localizados em shoppings, universidades, empresas e centros comerciais —, administradores que buscam um sistema moderno e eficiente para aprimorar a organização e segurança das vagas, bem como funcionários operacionais responsáveis pelo controle de entrada e saída e pela supervisão do uso das vagas.

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



***Cenário: Antes***

Júlia trabalha em uma grande empresa de tecnologia e precisa estar em seu local de trabalho às 8h, sem se atrasar nem perder tempo procurando vaga. Em um dia comum, ela chega à empresa por volta das 7h30, mas se depara com uma longa fila de carros na entrada, já que o controle de acesso é manual e lento.
Após alguns minutos de espera, Júlia consegue entrar no estacionamento, mas começa a rodar pelas dependências da empresa em busca de uma vaga. Todas as vagas já estão ocupadas, e o sistema atual não oferece nenhuma informação em tempo real sobre a disponibilidade.
Com o tempo apertado e sem alternativa, ela decide estacionar fora da empresa, em uma rua próxima, porém sem segurança. Júlia chega atrasada para o início do expediente e ainda fica preocupada com a segurança do seu veículo. Esse tipo de situação é frequente e afeta sua produtividade e tranquilidade logo no início do dia.

***Cenário: Depois***

Júlia trabalha numa grande empresa de tecnologia, onde precisa estar 8h no seu trabalho, sem se atrasar nem perder tempo procurando vaga. 
Na noite anterior ao expediente, ela acessa a plataforma EasyParking, visualiza o mapa com as vagas disponíveis e realiza a reserva de uma vaga próxima à entrada do prédio onde trabalha. Júlia preenche seus dados pessoais e do veículo, definindo o horário de uso da vaga das 7h30 às 18h.
Na manhã seguinte, ao chegar à empresa por volta das 7h30, a cancela de entrada reconhece automaticamente a placa do seu veículo e libera a passagem sem necessidade de parar. Um painel digital orienta o caminho até a vaga reservada, que está sinalizada como “reservada” para garantir seu uso exclusivo.
Ela estaciona com rapidez e segurança, sem precisar procurar por vagas ou enfrentar filas, chegando com tranquilidade ao seu setor, no horário correto e sem estresse.


**Cenário: Antes**

Roberto é um senhor de 68 anos, aposentado, que costuma passear pelo centro da cidade durante a semana para resolver pendências e encontrar amigos. Em uma dessas saídas, ele decide ir ao centro resolver algumas coisas. Ao chegar lá, enfrenta dificuldades para encontrar uma vaga de estacionamento com acessibilidade. Após muito tempo procurando e sem sucesso, acaba deixando o carro longe do local desejado. O trajeto a pé é cansativo, o que o desanima. Ao final do dia, Roberto retorna para casa frustrado, sentindo-se menos independente e um pouco isolado por não conseguir realizar suas atividades com automonia.

**Cenário: Depois**

Roberto é um senhor de 68 anos, aposentado, que costuma passear pelo centro da cidade durante a semana para resolver pendências e encontrar amigos. Na noite anterior, com a ajuda de um familiar, ele acessa a plataforma EasyParking em seu celular e encontra vagas acessíveis próximas ao local que deseja visitar. Ele realiza a reserva das vagas, informando o horário estimado de uso e os dados do veículo. Na manhã seguinte, ao chegar ao centro, a cancela reconhece a placa do carro e libera sua entrada. Um painel direciona Roberto até a vaga reservada, sinalizada como acessível. Ele estaciona com segurança e tranquilidade, realiza suas tarefas sem pressa e ainda aproveita a tarde com os amigos.



## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

## Requisitos Funcionais (RF)

| Identificador | Descrição | Prioridade | Depende de |
|---------------|-----------|------------|------------|
| RF01 | O sistema deve permitir o cadastro de usuários com dados pessoais. | Alta | — |
| RF02 | O sistema deve permitir o registro de veículos (marca, modelo, tipo, placa e cor). | Alta | RF01 |
| RF03 | O sistema deve gerar um código de identificação único para cada usuário. | Alta | RF01 |
| RF04 | O sistema deve permitir a consulta em tempo real das vagas disponíveis. | Alta | RF01 |
| RF05 | O sistema deve permitir a reserva de uma vaga específica. | Alta | RF04 |
| RF06 | O sistema deve permitir o controle de entrada por meio do código de identificação. | Alta | RF03, RF05 |
| RF07 | O sistema deve permitir o controle de saída utilizando o código de identificação e senha. | Alta  | RF06 |
| RF08 | O sistema deve exibir o tempo de permanência do veículo na vaga. | Média | RF06 |
| RF09 | O sistema deve calcular o valor da estadia com base no tempo registrado. | Alta | RF08 |
| RF10 | O sistema deve alertar o porteiro se um veículo não autorizado ocupar uma vaga. | Média | RF06, RF05 |

***2.2. Requisitos Não Funcionais***

## Requisitos Não Funcionais (RNF)  

| Identificador | Descrição | Prioridade | Depende de |
|---------------|-----------|------------|------------|
| RNF01 | O sistema deve estar disponível 99,5% do tempo. | Alta | — |
| RNF02 | O sistema deve utilizar HTTPS para criptografar todos os dados. | Alta | — |
| RNF03 | As respostas do sistema devem ser retornadas em até 2 segundos. | Média | RF04, RF05 |
| RNF04 | O sistema deve ser compatível com navegadores modernos e dispositivos móveis | Alta | — |
| RNF05 | O sistema deve suportar até 500 usuários simultâneos.| Alta | RF01, RF09 |
| RNF06 | A interface deve seguir padrões de acessibilidade (WCAG 2.1). | Média | — |
| RNF07 | O sistema deve enviar confirmações de ações (reserva, entrada, saída) em até 5 segundos | Alta | RF05, RF06, RF07 |
| RNF08 | O backup do banco de dados deve ser feito automaticamente a cada 24 horas. | Média | — |
| RNF09 | O banco de dados deve ter replicação geográfica na nuvem.| Alta | RF01, RF02 |
| RNF10 | A autenticação deve utilizar senhas criptografadas e políticas de segurança. | Alta | RF07 |

***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Matrizes de Rastreabilidade***

*<Imagem, arquivo (PDF), link com Matriz de Rastreabilidade.>*

***2.9. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
