# <center>Planejamento da Avaliação do Protótipo de Baixa Fidelidade

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 21.10.2020 |  0.1   | Criação do documento | Durval Carvalho  |
| 21.10.2020 |  0.2   | Definição dos Tópicos Introdução, Objetivos e Metodologia | Durval Carvalho  |
| 21.10.2020 |  0.3   | Definição do Tópico Avaliação | Durval Carvalho  |
| 21.10.2020 |  0.4   | Definição da Conclusão | Durval Carvalho  |
| 22.10.2020 |  0.5   | Correções | Isabella Carneiro  |

<div align="justify">

## 1. Introdução

A utilização de protótipos durante a atividade de design é fundamental para consolidar ideias e corrigir enganos nas etapas iniciais dos projetos.

Visando a correção de erros, é essencial que após a elaboração de uma versão estável do protótipo, seja realizado avaliação e validações juntos com os usuários do sistema, para assim verificar se as decisões tomadas fazem sentido.

Desse modo, este documento visa documentar e planejar como será realizado a avaliação do protótipo de baixa fidelidade desenvolvido pela nossa equipe.

## 2. Objetivo

O objetivo desse documento é detalhar o máximo possível os aspectos referentes a avaliação do protótipo de baixa fidelidade, de modo que o futuro avaliador não tenha dúvidas durante a avaliação e possa realizar uma avaliação metódica e sistemática com diversos usuários.

## 3. Metodologia

A validação do protótipo de baixa fidelidade que será realizada irá seguir as etapas definidas no livro Interação Humano-Computador, de Simone Barbosa e Bruno Silva. No capítulo 10, no tópico 10.2.3. "Prototipação em Papel" são definidas as etapas necessárias desde a concepção do protótipo até o relato de resultados. 

Como esse documento se propõe a planejar a avaliação do protótipo, desse modo, não abordaremos as etapas referentes a concepção do protótipo e começaremos na etapa de preparação da avaliação.

## 4. Avaliação

### 4.1. Definição das tarefas que serão executadas

O primeiro passo para validar um protótipo, independente de seu nível de fidelidade, é definir quais tarefas serão executadas pelos participantes.

As atividades que os usuários devem realizar são as mesmas que o protótipo de baixa fidelidade dá suporte:
- Busca de obras no acervo;
- Agendamento de empréstimo;
- Renovação de prazo de devolução

#### 4.1.1. Busca de Obras no Acervo

A busca de obras no acervo consiste em pesquisar por uma determinada obra (livro, artigo, revista, etc.) no serviço de busca integrada da BCE. Esse serviço irá listar diversas obras que contenham o termo digitado na barra de pesquisa. Será carregada uma lista com o detalhamento das obras encontradas.

Esse detalhamento irá conter informação as informações referentes a:
- Localização física (número da prateleira) da obra na biblioteca.
- Disponibilidade da obra (Quantidade disponível para empréstimo)
- Links para acesso online
- Assuntos chaves (keywords) da obra encontrada
- Nome dos autores
- Data de publicação
- Idioma da obra
- Edição

O objetivo dessa atividade é avaliar se o usuário é capaz de realizar a busca, e identificar informações referentes à obra.

A avaliação deverá ocorrer da seguinte maneira:

1. Mostre a seguinte imagem, referente a capa do livro que deve ser procurada, ao participante da avaliação.

<p align='center'>
    <img src='_media/assets/livro-geologia.jpg' width='20%'>
    <figcaption align='center'>
        <b>Figura 1: Capa do livro que que deve se procurado</b>
        <br> 
        <a href='https://images-americanas.b2w.io/produtos/01/00/oferta/36128/4/36128452_1SZ.jpg'>Fonte: Site da Americanas.com</a>
  </figcaption>
</p>

2. Mostre a seguinte tabela, referente aos detalhes do livro que deve ser procurado

<p align='center'>
    <img src='_media/assets/detalhes-sobre-livro.png' width='100%'>
    <figcaption align='center'>
        <b>Figura 2: Dados referentes ao livro que deve ser procurado</b>
        <br> 
        <a href='http://eds.a.ebscohost.com/eds/detail/detail?vid=4&sid=3eac8a94-57e2-431e-9ecb-9ac334f685b7%40sdc-v-sessmgr02&bdata=Jmxhbmc9cHQtYnImc2l0ZT1lZHMtbGl2ZQ%3d%3d#AN=buin.1041649&db=cat07149a'>Fonte: Site da BCE</a>
  </figcaption>
</p>

3. Peça para que o participante, utilizando o protótipo, realize uma busca e encontre a obra com base nos dados fornecidos.

Mostre a tela com o site principal da BCE, onde estará presente a barra de pesquisa integrada da BCE.

4. Pergunte quais dos termos ele digitaria (título, autor, ano de publicação, etc.)

Dependendo da resposta do participante, mostre a tela com a barra de pesquisa preenchida com os termos citados.

Caso o termo escrito seja muito vago, por exemplo, "geologia", ou somente o nome do autor, mostre a tela com lista de obras encontradas que não contenha a obra desejada.

Caso contrário, o participante use uma string de busca com termos detalhados, por exemplo: "Geologia estrutural Fossen", "Fossen 2017", ou o ISBN da obra.

No caso da ISBN mostre a lista com somente a obra. Caso contrário mostre uma lista com várias obras, e entre elas a obra desejada.

Caso o usuário apresente alguma dificuldade ou fique "emperrado" em alguma parte, espere alguns segundos para observar suas interações e depois intervenha e ajude-o a encontrar a obra desejada.

#### 4.1.2. Agendamento de empréstimo

O serviço de agendamento de empréstimo possibilita que livros disputados sejam agendados para empréstimo. Essa funcionalidade impossibilita que pessoas "sortudas" peguem o livro antes de você, uma vez que para pegar um livro será preciso entrar em uma lista de espera.

O objetivo dessa atividade é avaliar se o usuário será capaz de agendar um empréstimo.

Essa atividade é uma continuação do fluxo de pesquisa de obra. Dessa maneira, o usuário deve ter conseguido achar o livro detalhado na atividade 4.1.1. Caso não tenha conseguido, ajude-o. 

Essa atividade começa na página de detalhamento do livro descrito na figura 2.

A avaliação deverá ocorrer da seguinte maneira:

1. Peça para que o usuário reserve o livro encontrado na atividade 4.1.1.

Uma vez clicado no botão referente ao agendamento, mostre a tela de autentificação.

2. Peça para o usuário realizar o login

3. Se o usuário falar que não sabe qual senha deve usar, peça para o mesmo recuperar sua senha.

Mostre a tela de recuperação de senha. Quando o usuário completar os detalhes referentes a sua conta (CPF ou Email), mostre o pop-up de envio de senha por email. Após o usuário clicar no botão de fechar o pop-up, mostre a tela de autentificação novamente.

Após autentificação ser realizada, mostre a tela de confirmação do agendamento. Caso o usuário confime, mostre o pop-up de agendamento confimado. Caso contrário mostre o pop-up de agendamento cancelado.

Caso o agendamento seja bem sucedido, mostre a tela de obras agendadas, onde estará presente o livro agendado e a data máxima que o livro estará disponível para empréstimo.

Caso o agendamento não seja bem sucedido, mostre o painel principal do acesso restrito do site da BCE.

4. Peça para o usuário realizar o _logout_

#### 4.1.3. Renovação do prazo de devolução

A renovação de prazo de devolução é um serviço disponível pela BCE que possibilita que pessoas que esteja de posse de uma obra que não tenha lista de espera, possa renovar a data de devolução online, ou seja, sem a necessidade de ir até a biblioteca.

O objetivo dessa atividade é avaliar se o usuário será capaz de renovar o prazo de devolução de um obra em sua posse.

A avaliação deverá ocorrer da seguinte maneira:

Antes de começar essa avaliação, mostre a tela tela do site principal da BCE.

1. Contextualize o usuário, avisando que ele possui a obra em sua posse (obra detalhada na figura 2), e que a data da devolução é hoje e que ele ainda não terminou de usar o livro.

2. Uma vez entendido o contexto, peça para o participante renovar a data de devolução.

Observe as ações do participante. Caso ele não saiba o que fazer observe por alguns instantes e ajude-o. Informe que é preciso realizar a autentificação primeiro.

Caso o usuário clique no botão referente a realização de login, mostre a tela de autentificação. 

3. Peça para o usuário realizar o login

4. Se o usuário falar que não sabe qual senha deve usar, peça para o mesmo recuperar sua senha.

Mostre a tela de recuperação de senha. Quando o usuário completar os detalhes referentes a sua conta (CPF ou Email), mostre o pop-up de envio de senha por email. Após o usuário clicar no botão de fechar o pop-up, mostre a tela de autentificação novamente.

Após autentificação ser realizada, mostre a tela do painel principal do acesso restrito, e nela deverá está presente os livros que estão em posse do participante.

Observe o participante, caso ele não saiba o que fazer, ajude-o. Informe que é preciso identificar o livro, e clicar no botão de renovação de prazo.

Após o usuário clicar no botão da renovação, mostre a tela referente aos detalhes do empréstimo. E mostre o pop-up de confirmação da renovação. 

Caso a renovação confirmada, mostre o pop-up de renovação bem sucedido. 

Caso a renovação não seja confirmada, mostre o pop-up informado que a renovação foi cancelada.

Quando os pop-ups forem fechado volte para o painel principal de acesso restrito.

5. Peça para o usuário realizar o _logout_

### 4.2. Definição dos participante e Recrutamento

O próximo passo é definir quem vai participar da avaliação. É de extrema importância que os participante tenham o mesmo perfil de usuário do usuários da BCE. Esses perfis estão disponíveis no [documento de perfil de usuário](pages/ponto_de_controle_2/perfil_usuario.md).

As atividades definidas nessa avaliação podem ser executadas pelos seguintes perfis de usuários:
- Alunos de Graduação
- Alunos de Pós-Graduação
- Ex-Alunos
- Professores

Qualquer pessoa que se encaixe em algum desses perfis estão aptos de serem recrutados para a atividade de validação.

Procure por pessoas com esse perfil, entre em contato, explique a motivação da avaliação e os detalhes envolvidos. Caso a pessoa confirme o desejo de participar, combine uma data e um horário.

Caso o avaliador consiga recrutar mais de 3 pessoas, escolha a pessoa com a data mais próxima para realizar o teste-piloto. Teste-piloto é uma execução da avaliação com o objetivo de identificar dúvidas que podem surgir durante a avaliação.

### 4.3. Execução do teste piloto

Realize a avaliação com o participante escolhido para o teste piloto. 

Caso apareça problemas ou surja novas ideias de avaliação, anote.

Quando acabar o teste piloto, leia as anotações e realize as modificações necessárias.

### 4.4. Execução das Avaliações

Na data referente a cada participante, crie um link de vídeoconferência no site [jitsi](https://meet.jit.si/), e envie para o participante.

Antes da entrevista converse com o participante, explicando novamente a motivação e os detalhes da avaliação que será realizada.

No começo da avaliação mostre o [termo de compromisso](/pages/ponto_de_controle_5/termo_de_consentimento.md) e pergunte se o participante está de acordo. Caso não esteja a avaliação é cancelada. 

Peça para o participante compartilhas a tela antes da entrevista, e peça para fixar a tela da pessoa com o nome "Computador" no jitsi. A pessoa com o nome "Computador" será um membro do projeto que irá ser responsável por reagir as interações do usuário. É muito importante que a pessoa responsável por ser o computador conheça o fluxo e a sequência das telas.

Após toda a configuração, começe a gravar a vídeoconferência.

Durante a avaliação realize as atividades detalhadas no tópico 4.1.

Sempre que achar importante, realize anotações para que no término da avaliação seja possível lembrar de descobertas importantes.

### 4.5. Relatório das Avaliações e Conclusão

Após cada entrevista o avaliador deve escrever um pequeno relatório identificando os problemas encontrados, os sugestões de melhoria e outros aspectos importantes.

O avaliador deve fazer o upload do vídeo em algum serviço de hospedagem de vídeo e colocar o link junto do relatório. 

Após a produção de todos os pequenos relatórios, o avaliador deverá escrever uma conclusão da atividade de avaliação, onde será listado todos os problema com suas devidas priorização (qual deve ser resolvido primeiro).

## 5. Conclusão

Esse documento visa facilitar a vida do avaliador durante a realização das avaliações. Desse modo, o avaliador está livre para realizar mudanças durante ou previamente a avaliação, mas sempre lembrando de manter a consistência entre os diversos participantes.

## Referências Bibliográficas

BARBOSA, S.D.J.; SILVA, B.S. Interação Humano--Computador. Computador. Editora Campus -- ElsevierElsevier, 2010., 2010.INF 1403 INF 1403 -- Introdução a IHC Introdução a IHC @Prof. Alberto Barbosa Raposo@Prof. Alberto Barbosa Raposo

</div>
