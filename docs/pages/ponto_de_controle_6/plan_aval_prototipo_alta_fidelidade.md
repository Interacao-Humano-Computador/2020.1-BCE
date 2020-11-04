# <center>Planejamento da Avaliação do Protótipo de Alta Fidelidade

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 04.11.2020 |  0.1   | Criação do documento | Durval Carvalho  |
| 04.11.2020 |  0.2   | Adição do tópico WCAG | Durval Carvalho  |

<div align="justify">

## 1. Introdução

A utilização de protótipos durante a atividade de design é fundamental para consolidar ideias e corrigir enganos nas etapas iniciais dos projetos.

Visando a identificação e correção de erros, é essencial que após a elaboração de uma versão estável do protótipo, seja realizado avaliação e validações juntos com os usuários do sistema, para assim verificar se as decisões tomadas fazem sentido ao contexto da aplicação e se satisfaz critérios as [metas de usabilidade do projeto](/pages/ponto_de_controle_3/metas_usabilidade).

Desse modo, este documento visa documentar e planejar como será realizado a avaliação do protótipo de alta fidelidade desenvolvido pela nossa equipe.

## 2. Objetivo

O objetivo desse documento é detalhar o máximo possível os aspectos referentes a avaliação do protótipo de alta fidelidade, de modo que o futuro avaliador não tenha dúvidas durante a avaliação e possa realizar uma avaliação metódica e sistemática com diversos usuários.

## 3. Metodologia

A validação do protótipo de alta fidelidade que será realizada em duas etapas. A primeira etapa será uma avaliação estática, onde será realizado uma inspeção nas telas do protótipo avaliando critérios especificados nas [Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG)](https://guia-wcag.com/). Nessa etapa o avaliador deve percorrer o protótipo a procura de inconsistências definidas no checklist de acessibilidade.

Na segunda etapa, onde ocorrerá as validações com os usuários, o avaliador irá se reunir com potenciais usuários do sistema afim de avaliar a usabilidade do sistema e coletar sugestões de melhoria.

Como esse documento se propõe a planejar a avaliação do protótipo, desse modo, não abordaremos as etapas referentes a concepção do protótipo e começaremos na etapa de preparação da avaliação.

## 4. Etapa Estática - Inspeção

## 4.1. Diretrizes de Acessibilidade para o Conteúdo da Web - WCAG

As Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG, do inglês Web Content Accessibility Guidelines) são parte de uma série de recomendações para acessibilidade para a web publicadas pela Web Accessibility Initiative do W3C, ([3]). 

Elas consistem de um conjunto de recomendações para fazer com que o conteúdo seja acessível, principalmente para utilizadores com deficiência, mas também para todos os agentes de usuários, incluindo dispositivos bastante limitados, tais como os telefones celulares. ([3]).

Os pontos de verificação do WCAG são definidos em 3 níveis (A, AA e AAA), partindo de pontos gerais para pontos especídicos.

No nosso contexto, foi localizado 12 pontos de nível A, 9 pontos de nível AA e 10 pontos de nível AAA. Quanto mais pontos forem atendidos, maior será o grau de usabilidade do sistema avaliado. 

### 4.1.1. Nível A

#### 4.1.1.1. Conteúdo não textual
Todo conteúdo interativo "não textual" deve trazer uma alternativa em texto para identificar o conteúdo. Exemplo de elementos interativos que precisam de informação textual são botões com ícones, imagens clicáveis, ícones de menus, etc.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships)

#### 4.1.1.2. Características sensoriais
Qualquer tipo de instrução não deve depender apenas de forma, tamanho, localização visual ou som.

A intenção deste critério é garantir que todos os usuários possam acessar as instruções de uso do conteúdo, mesmo quando não consigam perceber a forma ou tamanho ou usar informações sobre localização espacial ou orientação. Alguns conteúdos dependem do conhecimento da forma ou posição dos objetos que não estão disponíveis na estrutura do conteúdo (por exemplo, "botão redondo" ou "botão à direita"). Alguns usuários com deficiência não conseguem perceber a forma ou a posição devido à natureza das tecnologias assistivas que utilizam. 

**Exemplo**: Evitar "clique no botão verde", "clique no botao abaixo" ou "ao ouvir o bip, selecione uma opção".

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/sensory-characteristics)

#### 4.1.1.3. Utilização de cores
Cores não devem ser utilizadas como única maneira de transmitir conteúdo ou distinguir elementos visuais.

**Exemplo**: uma mensagem de erro em formulário deve trazer indicações visuais, textos e também mudança de cor do formulário (e não apenas a mudança de cor).

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)

#### 4.1.1.4. Três flashes ou abaixo do limite 
Nenhum conteúdo da página deve piscar mais do que 3 vezes por segundo, a não ser que os flashes estejam em baixo contraste ou possuam pouco vermelho.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold)

#### 4.1.1.5. Página com título 
Páginas ou telas devem possuir um título que descreva claramente a sua finalidade.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/page-titled)

#### 4.1.1.6. Ordem do foco
A navegação (através de um teclado) por elementos focáveis em tela deve ser sequencial e lógica de acordo com o conteúdo apresentado.

**Exemplo**: Em um formulário, quando a tecla tab é apertada, o foco deve ir do primeiro elemento mais acima, para o último elemento, o botão de envio.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/focus-order)

#### 4.1.1.7. Finalidade do link (em contexto)
A finalidade de cada link deve ser determinada a partir do texto do próprio link ou a partir do contexto no entorno.

**Exemplo**: Não utilizar o texto "link" para links. O texto do link deve ser informativo

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context)

#### 4.1.1.8. Cancelamento de acionamento
Deve ser possível cancelar ou reverter qualquer ação que envolva clique ou toque simples. Algumas condições precisam ser atendidas

**Exemplo**: Nenhuma ação deve ser executável com somente 1 clique. Sempre deve ser perguntado se o usuário realmente deseja realizar aquela ação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation

#### 4.1.1.9. Identificação do erro
Erros durante e após o preenchimento de dados em formulários, devem ser identificados de forma específica e clara para o usuário. O acesso aos campos com erros também deve ser simplificado.

**Exemplo**: Uma vez que for submetido um formulário inválido, o campo com erro deve ser sinalizado e o erro deve ser descrito.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-identification)

#### 4.1.1.10. Rótulos e instruções
Rótulos (labels) devem identificar os respectivos campos de formulários de forma clara e correta. Forneça instruções de tela ou dicas de preenchimento dos campos sempre que possível.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions)

#### 4.1.1.11. Autenticação acessível
Sempre que um processo de login exigir um mecanismo de função cognitiva (memorização/digitação de algo), deve-se fornecer uma alternativa também (exemplo: autenticação de 2 fatores onde o usuário não precise memorizar uma senha).

[Link para descrição completa](https://w3c.github.io/wcag/understanding/accessible-authentication)

#### 4.1.1.12. Entrada redundante
Sempre que houver o preenchimento de etapas em uma processo, qualquer tipo de informação inserida previamente não deverá ser solicitada novamente a não ser que seja essencial (exemplo: reinserção de senha de confirmação).

[Link para descrição completa](https://w3c.github.io/wcag/understanding/redundant-entry)

**Exemplo**: Uma vez que um formulário for rejeitado por conta de um campo inválido, as informações válidas do formulário não devem ser perdidas.

### 4.1.2. Nível AA

#### 4.1.2.1. Contraste (mínimo)
Textos devem ter uma relação de contraste* entre primeiro e segundo plano de ao menos 4.5:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum)

**Exemplo**: Não deve utilizar textos com cores muito próximas do fundo, pois isso dificulta a leitura.

#### 4.1.2.2. Redimensionar texto
O conteúdo em texto deve ser legível e funcional mesmo quando a tela for ampliada em até 200% do seu tamanho padrão.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/resize-text)

#### 4.1.2.2. Imagens de texto
Evitar o uso de textos em imagens a não ser que sejam essenciais (exemplo: marcas e logos) ou que possam ser personalizadas pelo usuário.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/images-of-text)

#### 4.1.2.3. Refluxo
Ao se aplicar zoom de até 400% na tela, não deverá ocorrer rolagem (scroll) vertical e horizontal ao mesmo tempo.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/reflow)

#### 4.1.2.4. Contraste Não-Textual
Componentes de interface (exemplo: botões) e imagens essenciais para o entendimento do conteúdo devem ter uma relação de contraste entre primeiro e segundo plano de ao menos 3:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast)

#### 4.1.2.5. Cabeçalhos e rótulos
Títulos e sub-títulos de conteúdos e rótulos (labels) de formulários devem descrever claramente a finalidade dos elementos ou agrupamentos sem que haja ambiguidade em seu entendimento.

**Exemplo**: Um campo de login deve especificar se o usuário deve digitar email ou CPF.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/headings-and-labels)

#### 4.1.2.6. Espaçamento da área clicável 
A distância das áreas clicáveis precisam ter no mínimo 44 pixels na altura e na largura entre elementos adjacentes, isso inclui a soma do elemento em si (alvo) e o espaçamento entre cada um dos elementos clicáveis.

**Exemplo**: Um campo de login deve especificar se o usuário deve digitar email ou CPF.

[Link para descrição completa](https://w3c.github.io/wcag/understanding/pointer-target-spacing)

#### 4.1.2.7. Controles ocultos 
Nenhum controle necessário para seguir em frente ou retornar em um determinado fluxo deve permanecer oculto na tela exigindo a passagem do mouse (mouse-over) pelo elemento em si. Os controles devem estar visíveis ou deve ser fornecido um mecanismo que permita ao usuário deixá-los visíveis.

**Exemplo**: Em um fluxo de finalizar compra, deve-se sempre está visível o controle para avançar para a próxima etapa da compra.

[Link para descrição completa](https://w3c.github.io/wcag/understanding/hidden-controls)

#### 4.1.2.8. Sugestão de erro
Forneça sugestões simples para que o usuário consiga corrigir facilmente os erros de preenchimento.

**Exemplo**: Se o usuário digitar um CPF inválido, sinalize no momento que o campo perder o foco, antes mesmo do formulário ser enviado.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-suggestion)

#### 4.1.2.9. Mensagens de status
Qualquer tipo de mensagem informacional e relevante ao usuário após executar uma ação deve ser transmitida sem que haja mudança de foco no elemento que originou a informação.

**Exemplo**: Após um formulário ser enviado com sucesso, mostre uma notificação avisando que o envio das informações foi bem sucedido.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/status-messages)

### 4.1.3. Nível AAA

#### 4.1.3.1. Contraste (melhorado)
Textos devem ter uma relação de contraste* entre primeiro e segundo plano de ao menos 7:1. Textos em tamanhos de fontes maiores (a partir de 18pt ou 14pt bold) podem ter uma relação de contraste de 4.5:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced)

#### 4.1.3.2. Teclado (sem exceção)
Toda funcionalidade deve estar disponível para utilização com teclado. O sistema deve ser 100% operável com somente uso do teclado.

**Exemplo**: Todas as ações e navegações entre páginas deve está mapeada para atalhos no teclado.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/keyboard-no-exception)

#### 4.1.3.3. Sem limite de tempo
Nenhuma funcionalidade deve possuir limite de tempo para que uma ação seja executada.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/no-timing)

#### 4.1.3.4. Nova autenticação
Caso uma sessão autenticada expire, qualquer usuário logado deve ser capaz de continuar sua atividade sem qualquer perda de dados, ao se efetuar uma nova autenticação no ambiente.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/re-authenticating)

#### 4.1.3.5. Limites de tempo
Caso a inatividade do usuário resulte em perda de dados preenchidos anteriormente, ele deverá saber qual é o tempo limite (e restante) antes que ocorra a perda automática de dados. A menos que esse limite seja superior a 20 horas.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/timeouts)

#### 4.1.3.5. Cabeçalhos da seção
Sempre que possível, deve-se fornecer títulos em diferentes sessões e níveis, permitindo que o usuário identifique facilmente a hierarquia das informações em um determinado conteúdo

**Exemplo**: Várias páginas não devem ter o mesmo título, por mais que todas possam está relacionadas.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/section-headings)

#### 4.1.3.6. Palavras incomuns
Caso use palavras técnicas ou jargões, forneça um glossário ou explicações que informem ao usuário seu significado.

**Exemplo**: Caso o site possua uma termo específico, deve-se oferecer um dicionário léxico explicado o significado daquele termo no contexto da aplicação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/unusual-words)

#### 4.1.3.7. Abreviações
Abreviações e/ou acrônimos devem ser identificados diretamente no conteúdo ou por meio de uma forma que possibilite a apresentação de sua definição por extenso.

**Exemplo**: Caso o site possua uma termo específico, deve-se oferecer um dicionário léxico explicado o significado daquele termo no contexto da aplicação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/abbreviations)

#### 4.1.3.8. Pronúncia
Deve-se fornecer um mecanismo que identifique a pronúncia correta de determinadas palavras que possam gerar ambiguidade fora do contexto.

**Exemplo**: Muitos brasileiros pronunciam a ferramenta MySQL como "MAI-S-Q-L", porém falantes de inglês nativos pronunciam "MAY-SI-QUEL", essa diferença de pronúncia dificulta o entendimento fora do contexto escrito.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/pronunciation)

#### 4.1.3.9. Ajuda
Caso um rótulo (label) não seja suficiente para explicar o preenchimento de um determinado campo, uma ajuda contextualizada deve ser fornecida.

**Exemplo**: Caso o usuário não entenda os erros específicos do formulário que está tentando enviar, deve existir um documentação específica que define os valores aceitos em cada campo.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/help)

#### 4.1.3.10. Prevenção de erro
Sempre que o usuário puder acrescentar qualquer informação via formulário, deve-se possibilitar o cancelamento do envio ou a verificação e/ou confirmação dos dados.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-prevention-all)
 
## 5. Etapa de Validação - Entrevistas

A utilização de entrevistas na etapa de validação possibilita uma alta apropriação da tecnologia, no nosso caso o protótipo, por parte dos entrevistados, que são potenciais usuários do sistema, ([1]). O objetivo das entrevistas é coletar informações detalhadas e profundas de usuários individuais a respeito da usabildidade do sistema e potenciais pontos de melhoria.

### 5.1. Recrutamento dos participantes
O primeiro passo é definir quem vai participar da avaliação. É de extrema importância que os participante tenham o mesmo perfil de usuário do usuários da BCE. Esses perfis estão disponíveis no [documento de perfil de usuário](pages/ponto_de_controle_2/perfil_usuario.md).

As atividades definidas nessa avaliação podem ser executadas pelos seguintes perfis de usuários:
- Alunos de Graduação
- Alunos de Pós-Graduação
- Ex-Alunos
- Professores

Qualquer pessoa que se encaixe em algum desses perfis estão aptos de serem recrutados para a atividade de validação. É desejável que os participantes dessa entrevista não tenham participado de entrevistas anteriores.

Procure por pessoas com esse perfil, entre em contato, explique a motivação da avaliação e os detalhes envolvidos. Caso a pessoa confirme o desejo de participar, combine uma data e um horário.

Caso o avaliador consiga recrutar mais de 3 pessoas, escolha a pessoa com a data mais próxima para realizar o teste-piloto. Teste-piloto é uma execução da avaliação com o objetivo de identificar dúvidas que podem surgir durante a avaliação.

### 5.2. Definição das tarefas

O primeiro passo para validar um protótipo, independente de seu nível de fidelidade, é definir quais tarefas serão executadas pelos participantes.

As atividades que os usuários devem realizar são as mesmas que o protótipo de alta fidelidade dá suporte:
- Busca de obras no acervo;
- Autentificação do usuário;
- Agendamento de empréstimo;
- Renovação de prazo de devolução;

#### 5.2.1. Busca de obras no acervo
#### 5.2.2. Autentificação do usuário
#### 5.2.3. Agendamento de empréstimo
#### 5.2.4. Renovação de prazo de devolução

### 5.3. Avaliação da Entrevista - Teste Piloto

Muitas pessoas deixam de realizar o teste piloto, por conta de prazos apertados e pela falsa percepção de que o protótipo e planejamento da avaliação está perfeito, porém é essencial que seja realizado no mínimo 1 teste piloto caso o grupo consiga agendar mais de 3 entrevistas.

O objetivo desse teste é identificar falhas no planejamento da avaliação. Com base nessa entrevista inicial será possível avaliar e corrigir problemas na entrevistas que podem prejudicar a validação do protótipo.

O teste piloto visa responder às seguintes perguntas, ([2]):
- A dinâmica da entrevista está boa?
- As tarefas que devem ser executadas estão claras e fáceis de entender?
- Alguma coisa durante a entrevista ficou ambígua para o participante?
- O tempo da entrevista está dentro do previsto?
- A sequência das tarefas fazem sentido para avaliação?

Após o devido preparo para a avaliação, descrito no tópico XYZ, realize o teste piloto. Explique para o participante que o objetivo dessa entrevista é avaliar a entrevista e não o protótipo.

Caso apareça problemas ou surja novas ideias de avaliação, anote.

Quando acabar o teste piloto, leia as anotações e realize as modificações necessárias.

### 5.4. Execução das Avaliações

Na data referente a cada participante, crie um link de vídeoconferência no site [jitsi](https://meet.jit.si/), e envie para o participante e para o co-piloto da entrevista (membro do grupo).

Antes da entrevista converse com o participante, explicando novamente a motivação e os detalhes da avaliação que será realizada.

No começo da avaliação mostre o [termo de compromisso](/pages/ponto_de_controle_6/termo_de_consentimento.md) e pergunte se o participante está de acordo. Caso não esteja a avaliação é cancelada. 

Envie o link do protótipo para o participante da entrevista, e peça para ele deixar aberto nas abas do navegador o protótipo e o termo de compromisso.

Após toda a configuração, começe a gravar a vídeoconferência. Pergunte novamente se o participante concorda com o termo de compromisso, para assim ter o registro gravado.

Durante a avaliação realize as atividades detalhadas no tópico 5.2.

O papel do co-piloto é realizar anotações e observações durante a entrevista. Uma vez que o entrevistador vai está interagindo com o participante, é função do co-piloto documentar observações para futuras análises.

### 5.5. Relatório das Avaliações e Conclusão

Após cada entrevista o avaliador deve escrever um pequeno relatório identificando os problemas encontrados, os sugestões de melhoria e outros aspectos importantes.

O avaliador deve fazer o upload do vídeo em algum serviço de hospedagem de vídeo e colocar o link junto do relatório. 

Após a produção de todos os pequenos relatórios, o avaliador deverá escrever uma conclusão da atividade de avaliação, onde será listado todos os problema com suas devidas priorização (qual deve ser resolvido primeiro).


## 6. Conclusão

Esse documento visa facilitar a vida do avaliador durante a realização das avaliações. Desse modo, o avaliador está livre para realizar mudanças durante ou previamente a avaliação, mas sempre lembrando de manter a consistência entre os diversos participantes.

## Referências Bibliográficas

- [1] BARBOSA, S.D.J.; SILVA, B.S. Interação Humano--Computador. Computador. Editora Campus -- ElsevierElsevier, 2010., 2010.INF 1403 INF 1403 -- Introdução a IHC Introdução a IHC @Prof. Alberto Barbosa Raposo@Prof. Alberto Barbosa Raposo

- [2] Elisa Volpato. 2016. Antes de começar um teste de usabilidade, faça um teste piloto. Disponível em: https://medium.com/testr/antes-de-come%C3%A7ar-um-teste-de-usabilidade-fa%C3%A7a-um-teste-piloto-eadf45c474a2 . Acessado em 04 de novembro de 2020.

- [3] Wikipedia contributors. (2020). Web Content Accessibility Guidelines –- Wikipedia, The Free Encyclopedia.
. Disponível em: https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines . Acessado em 04 de novembro de 2020.


</div>
