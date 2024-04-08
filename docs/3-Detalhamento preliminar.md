# 1) Objetivos de Desenvolvimento Sustentável

As ODS (Objetivos de Desenvolvimento Sustentável) são uma série de metas estabelecidas pelas Nações Unidas para promover o desenvolvimento sustentável globalmente. O ODS 4 e o ODS 10 se referem a objetivos específicos dentro dessa estrutura:

ODS 4 - Educação de Qualidade: Este objetivo visa garantir uma educação inclusiva, equitativa e de qualidade, promovendo oportunidades de aprendizado ao longo da vida para todos. Isso inclui desde o acesso à educação pré-escolar até oportunidades de aprendizado para adultos, além de assegurar que todos tenham acesso a uma educação de qualidade em todos os níveis.

ODS 10 - Redução das Desigualdades: Este objetivo busca reduzir as desigualdades dentro e entre países. Isso inclui medidas para garantir a igualdade de oportunidades e reduzir a desigualdade de renda, bem como promover políticas sociais, econômicas e políticas inclusivas. O objetivo é garantir que ninguém seja deixado para trás no processo de desenvolvimento.

Considerando esses dois ODS, observamos que eles estão interligados de acordo com nosso projeto. Nosso objetivo é proporcionar aulas que possam oferecer novos conhecimentos tanto para os profissionais da educação quanto para os alunos. Isso pode contribuir para o desenvolvimento educacional de todos os envolvidos e ajudar a aprimorar o currículo dessas pessoas, ampliando as oportunidades de trabalho.

# 2) Detalhamento preliminar
O projeto Capacita Robótica, buscando levar conhecimentos gerais de robótica e tecnologia para as escolas estaduais de Poços de Caldas através de um curso utilizando o kit de robótica ofertado à elas, será colocado em prática na Escola Padrão, localizada na zona sul da cidade. Realizaremos aulas com os educadores da escola que mostrarem interesse no curso e desejam aprender a utilizar os kits, bem como aplicá-los em suas aulas através de projetos simples. Serão realizadas três aulas em três sábados diferentes, cada uma interligada à anterior, com cerca de 2 horas de duração. 
Para realização dessas aulas, utilizaremos a apostila de robótica criada no semestre anterior por um aluno do curso de Ciência da Computação da PUC Poços de Caldas, que aborda não somente a lista de materiais disponíveis no kit oferecido às escolas, mas também a funcionalidade de cada um, e exemplos de projetos que podem ser feitos com esses materiais.
Na primeira aula, será separado uma parte do tempo, para com os educadores instalar nos computadores o principal sistema que iremos usar (Arduino), detalhando o funcionamento de todas as funções do app que será utilizado para cada projeto. Logo em seguida, na parte teórica, teremos uma especificação da lógica utilizada e sobre cada material a ser usado(fios, leds, protobord, arduino e demais). E no restante da aula, iremos desenvolver o projeto Semáforo, sendo introduzido de forma simples e objetiva para que cada educador entenda os materais e códigos apresentados. 

Na segunda aula, será mais objetiva comparada com a primeira, já que teremos mais tempo para o processo do projeto e um pouco mais de tempo para explicar a lógica e fixar o conhecimento sobre os materiais já conhecidos e os que serão utilizados. Porém mesmo sendo mais objetiva e com o foco maior no projeto Luminária Automática (dado pela dificuldade um pouco maior), teremos um breve momento antes da parte prática para tirar dúvidas dos professores caso ainda haja. 

E no último dia de aula, já com um conhecimento maior sobre cada material, será realizado quase o mesmo procedimento da segunda aula, uma breve explicação sobre a parte lógica e sobre os materiais, juntamente com o momento de tirar dúvidas sobre os demais projetos. Logo em seguida teremos a parte prática com o projeto Jogo Genius de maior dificuldade, com uma interação de todos os educadores no momento final, que jogarão juntos o jogo que projetaram. Sendo assim finalizaremos o curso com todos os educadores cientes sobre o material que lhes foram disponibilizados. 

Neste curso abordaremos os seguintes projetos práticos:
- Protótipo de Semáforo: consiste no desenvolvimento de um protótipo de um semáforo de trânsito, fazendo os LEDs mudarem de cor alternadamente em um determinado espaço de tempo.
    - Materiais:
        - 3 leds (verde, amarelo e vermelho);
        - 1 protoboard;
        - 3 resistores;
        - Jumpers diversos;
- Luminária automática: os alunos vão desenvolver uma luminária inteligente que funciona através de um sensor de movimento, fazendo a lâmpada ser acendida somente com presença de movimentação no local.
    - Materiais:
        - Arduino Uno;
        - Protoboard;
        - Sensor de Movimento PIR (Passive Infrared);
        - LED (qualquer cor);
        - Resistor (limita a corrente do LED);
        - Cabos Jumper (fios de conexão);
- Jogo Genius: será desenvolvido uma espécie de jogo de memória, onde uma sequência de luzes são acendidas e os jogadores devem replicar a sequência nos botões em ordem correta.
    - Materiais:
        - LEDs Coloridos (4);
        - Botões de Pressão (4);
        - Resistores (4);
        - Jumpers;
        - Arduino UNO;

Esta seção deverá ser adaptada a proposta do grupo, de forma que:
a) Caso seu grupo vá desenvolver uma solução de software, as seções "projeto de interface" e "_user flow_" deverão ser feitas.
b) Caso seu grupo vá desenvolver cursos/oficinas na PUC, ou na comunidade, um "cronograma preliminar" das atividades a serem realizadas deverá ser proposto.
c) Caso seu grupo tenha realizado alguma pesquisa de campo, entrevistas ou reuniões com representantes do público-alvo, os registros das entrevistas/reuniões, os resultados obtidos e as conclusões encontradas deverão ser descritas aqui.
Caso seu trabalho demanda outro tipo de detalhamento preliminar, os artefatos a serem entregues nesta etapa deverão ser alinhados junto com seu(sua) professor(a).

## Projeto de Interface

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

Visão geral da interação do usuário pelas telas do sistema e protótipo interativo das telas com as funcionalidades que fazem parte do sistema (wireframes).

Apresente as principais interfaces da plataforma. Discuta como ela foi elaborada de forma a atender os requisitos funcionais, não funcionais e histórias de usuário abordados nas <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a>.

## User Flow

![Exemplo de UserFlow](img/userflow.jpg)

Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor mapear todo fluxo de telas do site ou app. Essa técnica funciona para alinhar os caminhos e as possíveis ações que o usuário pode fazer junto com os membros de sua equipe.

> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)

## Cronograma preliminar

Neta seção, deverá ser proposto o cronograma de execução das atividades/encontros ou então, de desenvolvimento das demais etapas do projeto.
Ainda não é necessário incluir, neste momento, o material de apoio a ser utilizado em cada um dos encontros.

|Aula   | Descrição do conteúdo a ser abordado  | Tempo necessário |
|------|-----------------------------------------|----|
|| Primeira aula | 2 horas| 
|1| Instalação do Arduino IDE e explicação sobre o mesmo  | 20 minutos |
|2| Explicação sobre os componentes que serão utilizados  | 30 minutos |
|3| Realização do primeiro projeto: Semáforo  | 1 hora e 10 minutos |
|| Segunda aula | 2 horas| 
|1| Revisão dos componentes gerais | 30 minutos |
|2| Realização do segundo projeto: Luminária automática | 1 hora e 30 minutos |
|| Terceira aula | 2 horas| 
|1| Revisão dos componentes gerais | 20 minutos |
|2| Realização do terceiro projeto: Jogos Genius | 1 hora e 30 minutos |
|3| Momento para responder possíveis dúvidas | 10 minutos |

## Resultados obtidos com pesquisa de campo, reuniões e/ou entrevistas

Nesta seção, deverão ser apresentados os registros das reuniões realizadas com representantes do público-alvo, os gráficos/tabelas com os resultados das pesquisas/entrevistas feitos e também, às conclusões que o grupo pode alcançar por meio destes artefatos.







