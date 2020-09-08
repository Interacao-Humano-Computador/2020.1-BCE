---
id: metodologia
title: Metodologia do Projeto
sidebar_label: Metodologia do Projeto
---

# Metodologia do projeto e Processos

## Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 08/09/2020 |  0.1   | Criação do documento | Durval Carvalho |

## 1. Introdução

O documento de metodologia busca descrever as abordagens utilizadas durante o processo de desenvolvimento desse projeto.  Nele será descrito quais metodologias foram usadas como referência, e quais métodos foram adotados para o nosso contexto. Esse documento também visa explorar como a equipe se organizou e comunicou durante o projeto.



## 2. Objetivo

Esse documento tem como objetivo documentar as metodologias utilizadas, assim como todos os processos adotados durante o desenvolvimento do projeto.



## 3. Metodologias

Todas as metodologias adotadas durante esse projeto tem relação com dois princípios fundamentais do desenvolvimento ágil de software. Esses princípios são:

> * Os **indivíduos e suas interações** acima de procedimentos e ferramentas
> * A **capacidade de resposta a mudanças** acima de uma plano pré-estabelecido
>
> -- <cite> Manifesto Ágil [1] </cite>

Com base nesses princípios, foi utilizado partes de várias metodologias já conhecidas como SCRUM, XP, Kanban com o objetivo de utilizar uma metodologia que melhor adaptasse ao nosso contexto.


### 3.1 SCRUM

O Scrum é um framework de gerenciamento de projetos, da organização ao desenvolvimento ágil de produtos complexos e adaptativos com o mais alto valor possível, através de várias técnicas, utilizando desde o início de 1990 e que atualmente é utilizado em mais de 60% dos projetos ágeis em todo o mundo. [[2]](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software))

Essa metodologia define várias atividades que devem ocorrer durante o processo de desenvolvimento. No nosso contexto foram adotadas as seguintes atividades: _Product Backlog_, _Sprints_, _Sprint Planning_, _Sprint Review_, _Daily Meeting_, 


#### **3.1.1 Product Backlog**

Product backlog é um dos artefatos descritos pelo SCRUM. Esse artefato é uma lista dinâmica de requisitos do projeto, ou seja, são as atividades e limitações que o projeto deve realizar ou está sujeito para que seja bem sucedido. [[2]](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software)) 

No nosso contexto, essa lista de requisitos são as _issues_ do nosso repositório. Essas issues são abstrações de cartões de tarefas que descrevem o que deve ser feito e as limitações como tempo e pessoas alocadas.

O único campo obrigatório na criação de uma issue é o título e a experiência dos integrantes do projeto demostrou que issues mal escritas são mal intepretadas e resultam em entregas de baixa qualidade. 

Visando padronizar a criação de issues no nosso projeto, foi criado um template de criação onde é preciso definir outros campos. Esses campos são: Descrição, Critérios de aceitação e tarefas.


Na descrição irá descrever a atividade da issue, inserindo informações necessárias para o entendimento. Nesse campo deve ser evitado descrições genéricas e ambíguas.

Nos critérios de aceitação deve descrever quais serão os indicadores usados para verificar a qualidade do trabalho entregue. Alguns exemplos de critérios de aceitação são: 
> * Esse documento deve conter tabela de versionamento
> * Esse documento deve conter as referências bibliográficas
> * O documento deve seguir as normas da ABNT

Por fim, as tarefas são uma lista de sub atividades que devem ser feitas para que a issue seja concluída. Essas atividades são opcionais para a criação da issue, pois nem sempre pode ser possível definí-las durante a criação de uma tarefa. Alguns exemplos de tarefas são:
> * Buscar referência 
> * Analisar os projetos de semestres anteriores

Nosso _project backlog_ pode ser encontrado em [https://github.com/Interacao-Humano-Computador/2020.1-BCE/issues](https://github.com/Interacao-Humano-Computador/2020.1-BCE/issues).


#### **3.1.2 Sprints**

Uma sprint é a unidade básica de desenvolvimento na metodologia Scrum. As sprints podem durar entre uma semana e um mês, e são um esforço dentro de uma faixa de tempo. Esse faixa de tempo deve ser relativamente curta para possibilitar entregas parciais do sistema, gerando valor e permitindo a avaliação dinâmica do trabalho. [[2]](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software))

No nosso contexto, foi definido que as sprints irão durar entre 7 a 10 dias.


#### **3.1.3 Sprint Planning**

_Sprint planning_ é um evento de planejamento onde será definido quais tarefas (no nosso caso _issues_) do _product backlog_ serão feitas na próxima _sprint_. [[2]](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software))

No nosso contexto, o projeto e suas entregas estão definidos no plano de ensino da disciplina. Assim foi criado 7 milestones, isso é pontos de entrega do trabalho, e suas respectivas entregas.

Desse modo, todas as atividade e seus prazos são conhecidas, restando somente a definição dos responsáveis pela sua realização. 

Com isso em mente, é realizado reuniões nas segundas-feiras para definir quais as atividades devem ser priorizadas, com base na milestones mais próxima da data atual. Uma vez definido as atividades, é definido os responsáveis e a data de término da sprint.


#### **3.1.4 Sprint Review**

_Sprint Review_ é um evento de validação e verificação que ocorre antes do _Sprint planning_. Durante esse evento é analisado as entregas da sprint anterior e sua qualidade. Após essa análise a atividade pode ser concluída ou pode voltar para o _product backlog_, associada com um pedido de correção. Durante esse evento também é discutido dificuldades enfrentadas e pontos de melhoria para a próxima sprint. [[2]](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software))

No nosso contexto, os _sprints review_ ocorrem em duas etapas. A etapa de validação e verificação ocorre durante a sprint, sempre que um _pull request_ é criado. Pull request é a abstração da entrega de uma atividade. As atividades são realizadas em um ambiente individual de desenvolvimento, esse ambiente é um clone do ambiente original onde fica as atividades entregues, esse ambiente é conhecido por branches. Sempre uma atividade é concluída em seu ambiente clone, é criado um _pull request_, isso é, um pedido para que as alterações criadas no ambiente clone vá para o ambiente original. É nessa etapa que ocorre a validação e verificação. Antes do _pull request_ ser aceito é revisionado a atividade.

A segunda etapa ocorre antes da _sprint review_, onde é discutido as dificuldades enfrentadas e as sugestões de melhoria para a próxima sprint.

#### **3.1.5 Daily Meeting**

Na metodologia Scrum é recomendado que se realize reuninões de status do projeto diariamente, sendo essa reunião conhecida como _daily meeting_. Essa reunião é sempre realizada em um mesmo horário e deve durar no máximo 15 minutos. O objetivo é deixar todos os integrantes cientes do trabalho um do outro, desse modo cada participante deve responder a três perguntas: 
* O que você tem feito da daily passada para a daily atual?
* O que você está planejando fazer da daily atual para a daily de amanhã?
* Você tem algum problema impedindo você de realizar sua atividade?

No nosso contexto, as _dailies_ serão realizadas no meio das sprints. O grupo não julgou necessário a realização de reuniões diárias, desse modo ficou determinado que ocorreriam reuniões de status no meio da daily, geralmente na quarta-feira.

### 3.1 KANBAN

Kanban é um quadro de cartões, sendo que cada cartão representa uma atividade, onde é controlado os fluxos em que cada cartão se encontra. Esses fluxos podem ser vários, dependendo do processo em questão, mas no geral são 3 fluxos principais: "a fazer", "fazendo" e "feito". 

No nosso contexto, o kanban foi dividido em 5 fluxos: _project backlog_, _sprint backlog_, _in progress_, _review_ e _done_. No primeiro processo é onde ficam todos os cartões de tarefas mapeados até o momento. No segundo fluxo ficam os cartões de tarefa que serão realizados na sprint atual, no terceiro fluxo ficam as cartões cuja as tarefas já foram iniciadas, no fluxo _review_ ficam as tarefas que já foram concluídas e estão esperando por revisão de terceiros, e no último fluxo, _done_, ficam as tarefas que já foram revisadas e aprovadas. [[3]](https://pt.wikipedia.org/wiki/Kanban)

## 5. Referências

* [1] Manifesto Ágil, Disponível em: [https://agilemanifesto.org/iso/ptbr/manifesto.html](https://agilemanifesto.org/iso/ptbr/manifesto.html)

* [2] SCRUM, Metodologia Ágil. Disponível em: [https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software)](https://pt.wikipedia.org/wiki/Scrum_(desenvolvimento_de_software))

* [3] KANBAN. Disponível em [https://pt.wikipedia.org/wiki/Kanban](https://pt.wikipedia.org/wiki/Kanban)