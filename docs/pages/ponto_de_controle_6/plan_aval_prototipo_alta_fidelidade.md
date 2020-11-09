# <center>Planejamento da Avaliação do Protótipo de Alta Fidelidade - Estática

### Histórico de Versão
| Data       | Versão | Descrição                       | Autor(es)          |
|:----------:|:------:|:-------------------------------:|:------------------:|
| 04.11.2020 | 0.1    | Criação do documento            | Durval Carvalho    |
| 04.11.2020 | 0.2    | Adição do tópico WCAG           | Durval Carvalho    |
| 07.11.2020 | 0.3    | Revisão do documento            | Rafaella Junqueira |
| 09.11.2020 | 0.4    | Correção de erros de digitação  | Durval Carvalho    |

<div align="justify">

## 1. Introdução

A utilização de protótipos durante a atividade de design é fundamental para consolidar ideias e corrigir enganos nas etapas iniciais dos projetos.

Visando a identificação e correção de erros, é essencial que após a elaboração de uma versão estável do protótipo, seja realizado avaliação e validações juntos com os usuários do sistema, para assim verificar se as decisões tomadas fazem sentido ao contexto da aplicação e se satisfazem critérios das [metas de usabilidade do projeto](/pages/ponto_de_controle_3/metas_usabilidade.md).

A avaliação do protótipo de alta fidelidade será dividida em duas etapas, fase de avaliação estática e fase de validação por meio de entrevistas, respectivamente. Desta forma, o planejamento de cada etapa está disponível em dois documentos diferentes.

O documento que evidencia a segunda etapa se encontra disponível no [planejamento das entrevistas](/pages/ponto_de_controle_6/plan_aval_prototipo_alta_fidelidade.md) com usuários. Já o atual documento guarda as informações do planejamento das atividades de avaliação da fase estática. 

## 2. Objetivo

O objetivo desse documento é detalhar o máximo possível os aspectos referentes a avaliação do protótipo de alta fidelidade, de modo que o futuro avaliador não tenha dúvidas durante a avaliação e possa realizar uma avaliação metódica e sistemática. Este documento irá detalhar a primeira etapa da avaliação, intitulada como avaliação estática.

## 3. Metodologia

A primeira etapa deste planejamento é uma avaliação estática, que consiste em realizar uma inspeção nas telas do protótipo avaliando critérios especificados nas [Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG)](https://guia-wcag.com/). Nessa etapa o avaliador deve percorrer o protótipo a procura de inconsistências definidas no checklist de acessibilidade.

Como esse documento se propõe a planejar a avaliação do protótipo, desse modo, não abordaremos as etapas referentes a concepção do protótipo e começaremos na etapa de preparação da avaliação.

## 4. Etapa Estática - Inspeção

Inspeção é um método de avaliação que permite o avaliador tentar identificar problemas que os usuários podem vir a ter quando interagirem com o sistema. Esse método não envolve diretamente os usuários do sistema, e visa, com base em critérios, identificar problemas em soluções de IHC.

### 4.1. Diretrizes de Acessibilidade para o Conteúdo da Web - WCAG

As Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG, do inglês Web Content Accessibility Guidelines) são parte de uma série de recomendações para acessibilidade para a web publicadas pela Web Accessibility Initiative do W3C, ([3]). 

Elas consistem de um conjunto de recomendações para fazer com que o conteúdo seja acessível, principalmente para utilizadores com deficiência, mas também para todos os agentes de usuários, incluindo dispositivos bastante limitados, tais como os telefones celulares. ([3]).

Os pontos de verificação do WCAG são definidos em 3 níveis (A, AA e AAA), partindo de pontos gerais para pontos específicos.

No nosso contexto, foram localizados 12 pontos de nível A, 9 pontos de nível AA e 10 pontos de nível AAA. Quanto mais pontos forem atendidos, maior será o grau de usabilidade do sistema avaliado. 

#### 4.1.1. Nível A

##### 4.1.1.1. Conteúdo não textual
Todo conteúdo interativo "não textual" deve trazer uma alternativa em texto para identificar o conteúdo. Exemplo de elementos interativos que precisam de informação textual são botões com ícones, imagens clicáveis, ícones de menus, etc.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships)

##### 4.1.1.2. Características sensoriais
Qualquer tipo de instrução não deve depender apenas de forma, tamanho, localização visual ou som.

A intenção deste critério é garantir que todos os usuários possam acessar as instruções de uso do conteúdo, mesmo quando não consigam perceber a forma ou tamanho ou usar informações sobre localização espacial ou orientação. Alguns conteúdos dependem do conhecimento da forma ou posição dos objetos que não estão disponíveis na estrutura do conteúdo (por exemplo, "botão redondo" ou "botão à direita"). Alguns usuários portadores de deficiência não conseguem perceber a forma ou a posição devido à natureza das tecnologias assistivas que utilizam. 

**Exemplo**: Evitar "clique no botão verde", "clique no botao abaixo" ou "ao ouvir o bip, selecione uma opção".

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/sensory-characteristics)

##### 4.1.1.3. Utilização de cores
Cores não devem ser utilizadas como única maneira de transmitir conteúdo ou distinguir elementos visuais.

**Exemplo**: uma mensagem de erro em formulário deve trazer indicações visuais, textos e também mudança de cor do formulário (e não apenas a mudança de cor).

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)

##### 4.1.1.4. Três flashes ou abaixo do limite 
Nenhum conteúdo da página deve piscar mais do que 3 vezes por segundo, a não ser que os flashes estejam em baixo contraste ou possuam pouco vermelho.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold)

##### 4.1.1.5. Página com título 
Páginas ou telas devem possuir um título que descreva claramente a sua finalidade.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/page-titled)

##### 4.1.1.6. Ordem do foco
A navegação (através de um teclado) por elementos focáveis em tela deve ser sequencial e lógica de acordo com o conteúdo apresentado.

**Exemplo**: Em um formulário, quando a tecla tab é apertada, o foco deve ir do primeiro elemento mais acima, para o último elemento, o botão de envio.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/focus-order)

##### 4.1.1.7. Finalidade do link (em contexto)
A finalidade de cada link deve ser determinada a partir do texto do próprio link ou a partir do contexto no entorno.

**Exemplo**: Não utilizar o texto "link" para links. O texto do link deve ser informativo

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context)

##### 4.1.1.8. Cancelamento de acionamento
Deve ser possível cancelar ou reverter qualquer ação que envolva clique ou toque simples. Algumas condições precisam ser atendidas

**Exemplo**: Nenhuma ação deve ser executável com somente 1 clique. Sempre deve ser perguntado se o usuário realmente deseja realizar aquela ação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation

##### 4.1.1.9. Identificação do erro
Erros durante e após o preenchimento de dados em formulários, devem ser identificados de forma específica e clara para o usuário. O acesso aos campos com erros também deve ser simplificado.

**Exemplo**: Uma vez que for submetido um formulário inválido, o campo com erro deve ser sinalizado e o erro deve ser descrito.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-identification)

##### 4.1.1.10. Rótulos e instruções
Rótulos (labels) devem identificar os respectivos campos de formulários de forma clara e correta. Forneça instruções de tela ou dicas de preenchimento dos campos sempre que possível.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions)

##### 4.1.1.11. Autenticação acessível
Sempre que um processo de login exigir um mecanismo de função cognitiva (memorização/digitação de algo), deve-se fornecer uma alternativa também (exemplo: autenticação de 2 fatores onde o usuário não precise memorizar uma senha).

[Link para descrição completa](https://w3c.github.io/wcag/understanding/accessible-authentication)

##### 4.1.1.12. Entrada redundante
Sempre que houver o preenchimento de etapas em uma processo, qualquer tipo de informação inserida previamente não deverá ser solicitada novamente a não ser que seja essencial (exemplo: reinserção de senha de confirmação).

[Link para descrição completa](https://w3c.github.io/wcag/understanding/redundant-entry)

**Exemplo**: Uma vez que um formulário for rejeitado por conta de um campo inválido, as informações válidas do formulário não devem ser perdidas.

#### 4.1.2. Nível AA

##### 4.1.2.1. Contraste (mínimo)
Textos devem ter uma relação de contraste entre primeiro e segundo plano de ao menos 4.5:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum)

**Exemplo**: Não deve-se utilizar textos com cores muito próximas às cores de fundo, pois isso dificulta a leitura.

##### 4.1.2.2. Redimensionar texto
O conteúdo em texto deve ser legível e funcional mesmo quando a tela for ampliada em até 200% do seu tamanho padrão.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/resize-text)

##### 4.1.2.2. Imagens de texto
Evitar o uso de textos em imagens a não ser que sejam essenciais (exemplo: marcas e logos) ou que possam ser personalizadas pelo usuário.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/images-of-text)

##### 4.1.2.3. Refluxo
Ao se aplicar zoom de até 400% na tela, não deverá ocorrer rolagem (scroll) vertical e horizontal ao mesmo tempo.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/reflow)

##### 4.1.2.4. Contraste Não-Textual
Componentes de interface (exemplo: botões) e imagens essenciais para o entendimento do conteúdo devem ter uma relação de contraste entre primeiro e segundo plano de ao menos 3:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast)

##### 4.1.2.5. Cabeçalhos e rótulos
Títulos e sub-títulos de conteúdos e rótulos (labels) de formulários devem descrever claramente a finalidade dos elementos ou agrupamentos sem que haja ambiguidade em seu entendimento.

**Exemplo**: Um campo de login deve especificar se o usuário deve digitar email ou CPF.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/headings-and-labels)

##### 4.1.2.6. Espaçamento da área clicável 
A distância das áreas clicáveis precisam ter no mínimo 44 pixels na altura e na largura entre elementos adjacentes, isso inclui a soma do elemento em si (alvo) e o espaçamento entre cada um dos elementos clicáveis.

**Exemplo**: Um campo de login deve especificar se o usuário deve digitar email ou CPF.

[Link para descrição completa](https://w3c.github.io/wcag/understanding/pointer-target-spacing)

##### 4.1.2.7. Controles ocultos 
Nenhum controle necessário para seguir em frente ou retornar em um determinado fluxo deve permanecer oculto na tela exigindo a passagem do mouse (mouse-over) pelo elemento em si. Os controles devem estar visíveis ou deve ser fornecido um mecanismo que permita ao usuário deixá-los visíveis.

**Exemplo**: Em um fluxo de finalizar compra, deve-se sempre está visível o controle para avançar para a próxima etapa da compra.

[Link para descrição completa](https://w3c.github.io/wcag/understanding/hidden-controls)

##### 4.1.2.8. Sugestão de erro
Forneça sugestões simples para que o usuário consiga corrigir facilmente os erros de preenchimento.

**Exemplo**: Se o usuário digitar um CPF inválido, sinalize no momento que o campo perder o foco, antes mesmo do formulário ser enviado.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-suggestion)

##### 4.1.2.9. Mensagens de status
Qualquer tipo de mensagem informacional e relevante ao usuário após executar uma ação deve ser transmitida sem que haja mudança de foco no elemento que originou a informação.

**Exemplo**: Após um formulário ser enviado com sucesso, mostre uma notificação avisando que o envio das informações foi bem sucedido.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/status-messages)

#### 4.1.3. Nível AAA

##### 4.1.3.1. Contraste (melhorado)
Textos devem ter uma relação de contraste* entre primeiro e segundo plano de ao menos 7:1. Textos em tamanhos de fontes maiores (a partir de 18pt ou 14pt bold) podem ter uma relação de contraste de 4.5:1.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/contrast-enhanced)

##### 4.1.3.2. Teclado (sem exceção)
Toda funcionalidade deve estar disponível para utilização com teclado. O sistema deve ser 100% operável com somente uso do teclado.

**Exemplo**: Todas as ações e navegações entre páginas deve está mapeada para atalhos no teclado.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/keyboard-no-exception)

##### 4.1.3.3. Sem limite de tempo
Nenhuma funcionalidade deve possuir limite de tempo para que uma ação seja executada.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/no-timing)

##### 4.1.3.4. Nova autenticação
Caso uma sessão autenticada expire, qualquer usuário logado deve ser capaz de continuar sua atividade sem qualquer perda de dados, ao se efetuar uma nova autenticação no ambiente.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/re-authenticating)

##### 4.1.3.5. Limites de tempo
Caso a inatividade do usuário resulte em perda de dados preenchidos anteriormente, ele deverá saber qual é o tempo limite (e restante) antes que ocorra a perda automática de dados. A menos que esse limite seja superior a 20 horas.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/timeouts)

##### 4.1.3.5. Cabeçalhos da seção
Sempre que possível, deve-se fornecer títulos em diferentes sessões e níveis, permitindo que o usuário identifique facilmente a hierarquia das informações em um determinado conteúdo

**Exemplo**: Várias páginas não devem ter o mesmo título, por mais que todas possam está relacionadas.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/section-headings)

##### 4.1.3.6. Palavras incomuns
Caso use palavras técnicas ou jargões, forneça um glossário ou explicações que informem ao usuário seu significado.

**Exemplo**: Caso o site possua uma termo específico, deve-se oferecer um dicionário léxico explicado o significado daquele termo no contexto da aplicação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/unusual-words)

##### 4.1.3.7. Abreviações
Abreviações e/ou acrônimos devem ser identificados diretamente no conteúdo ou por meio de uma forma que possibilite a apresentação de sua definição por extenso.

**Exemplo**: Caso o site possua uma termo específico, deve-se oferecer um dicionário léxico explicado o significado daquele termo no contexto da aplicação.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/abbreviations)

##### 4.1.3.8. Pronúncia
Deve-se fornecer um mecanismo que identifique a pronúncia correta de determinadas palavras que possam gerar ambiguidade fora do contexto.

**Exemplo**: Muitos brasileiros pronunciam a ferramenta MySQL como "MAI-S-Q-L", porém falantes de inglês nativos pronunciam "MAY-SI-QUEL", essa diferença de pronúncia dificulta o entendimento fora do contexto escrito.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/pronunciation)

##### 4.1.3.9. Ajuda
Caso um rótulo (label) não seja suficiente para explicar o preenchimento de um determinado campo, uma ajuda contextualizada deve ser fornecida.

**Exemplo**: Caso o usuário não entenda os erros específicos do formulário que está tentando enviar, deve existir um documentação específica que define os valores aceitos em cada campo.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/help)

##### 4.1.3.10. Prevenção de erro
Sempre que o usuário puder acrescentar qualquer informação via formulário, deve-se possibilitar o cancelamento do envio ou a verificação e/ou confirmação dos dados.

[Link para descrição completa](https://www.w3.org/WAI/WCAG21/Understanding/error-prevention-all)

### 4.2. Verificação da Consistência e Padronização

O objetivo dessa verificação é analisar as telas do protótipo, afim de identificar falhas no guia de estilo. Esse objetivo é desmembrado em subobjetivos que guiar o processo de verificação, esses objetivos são:
- Verificar o layout das telas
    - Verificar as proporções das telas, e dos componentes presentes.
    - Verificar a disposição dos componentes na tela
- Verificar a tipografia utilizada
    - Verificar a fonte utilizada
    - Verificar o tamanho da fonte utilizada
    - Verificar as cores utilizadas na fonte
- Verificar o simbolismo utilizado
    - Verificar se todo elemento simbólico possui um texto associado
    - Verificar se o uso dos símbolos é consistente
- Verificar as cores utilizadas
    - Verificar se o uso das cores é consistente
    - Verificar se há excesso no uso de cores em alguma tela
    - Verificar se há falta de uso de cores em alguma tela
    - Verificar se as cores utilizadas estão presente na paleta de cores
    
## 5. Conclusão

Este documento auxiliará o avaliador durante a realização das inspeções, de forma a gerar um relatório onde as inspeções deverão ser documentadas, a fim de identificar inconsistências no design do protótipo e possibilitar sugestões de melhorias. 

</div>

## Bibliografia

[1] BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.INF 1403 INF 1403 -- Introdução a IHC Introdução a IHC @Prof. Alberto Barbosa Raposo@Prof. Alberto Barbosa Raposo

[2] Elisa Volpato. 2016. **Antes de começar um teste de usabilidade, faça um teste piloto.** Disponível em: https://medium.com/testr/antes-de-come%C3%A7ar-um-teste-de-usabilidade-fa%C3%A7a-um-teste-piloto-eadf45c474a2. Acesso em 04 de novembro de 2020.

[3] Wikipedia contributors (2020). **Web Content Accessibility Guidelines-** Wikipedia, The Free Encyclopedia. Disponível em: https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines. Acesso em 04 de novembro de 2020.