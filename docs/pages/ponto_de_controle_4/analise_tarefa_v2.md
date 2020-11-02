# <center> Avaliação da Análise de tarefas

### Histórico de Versão
| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 22.10.2020 | 0.1 | Realização da Análise de Tarefas | Rafaella Junqueira |
| 25.10.2020 | 0.2 | Revisão do documento | Durval Carvalho |
| 26.10.2020 | 0.3 | Revisão do documento | Rafaella Junqueira |

<div align="justify"> 

## 1. Introdução
A análise de tarefas pode ser realizada em 3 momentos do desenvolvimento
- Na fase anterior ao desenvolvimento do produto, analisando a situação atual, podendo contar ou não com o apoio de um software (versões anteriores);
- Após a realização de uma intervenção em um sistemas computacionais;
- Visando o redesenho de um sistema já existente.

A análise de tarefas que é apresentada nesse documento se enquadra no primeiro momento apresentado, na fase anterior do desenvolvimento, contando com o apoio da versão atual do sistema. O intuito dessa atividade é propor melhorias para o design do site baseando-se na análise do comportamento do usuário obtidas em entrevistas com usuários reais do sistema. O método utilizado para realização desta análise é a Análise Hierárquica de Tarefas (AHT), utilizando-se a notação proposta por Preece, Rogers e Sharp (2005).

## 2. Objetivo
A primeira análise de tarefas realizada, através do método de inspeção, possuia o intuito de identifcar como os objetivos de agendamento de empréstimo e renovação de prazo de devolução podiam ser atingidos dada a atual situação de desenho do site. Esta nova análise pretende verificar se o que foi levantado previamente está de acordo com as experiências dos usuários. 

Assim, será possível analisar os caminhos realizados pelos usuários e propor um design que apoie a intuição das pessoas que utilizam o sistema. Com base nessa análise, será possível realizar um design de interface mais efetivo, que melhore características como Memorabildiade, Usabilidade e Aprendizagem.

## 3. Análise e levantamento de dados (Metodologia)

Para que fosse possível validar a análise de tarefa sugerida pelos designers, foi necessário realizar entrevistas estruturadas com usuários reais do sistema, cujos [planejamento](planejamento_1_entrevista.md) e [execução](/pages/ponto_de_controle_4/entrevistas.md) dessas entrevistas podem ser vistas em seus respectivos documentos.

Resumidamente, essas entrevistas consistiam em observar os usuários realizando determinadas ações no sistema da BCE. O elenco de entrevistados contou com usuários novatos, isso é, usuários que nunca tinham realizadas determinadas ações, e usuários experiêntes, isso é, usuários que já conheciam as ações solicitadas.

Com base na observação e análise usuários usando o sistema, foi possível observar caminhos comuns que todos os entrevistados realizavam. Foi possível também analisar a sequência de ações realizadas para alcançar determinado objetivo, fornecendo assim dados que auxiliam na correção do documento de análise de tarefa. Outra conclusão que foi possível concluir, é que todos os usuários consideram o site da BCE pouco intuitivo.

Desta forma, baseado na [primeira análise de tarefas](/pages/ponto_de_controle_2/analise_tarefas.md), nos dados obtidos pela entrevistas, e na análise do designer, foi possível realizar uma nova versão da Análise de Tarefa, incluindo as representações textuais e gráficas das tarefas envolvidas. Essa nova versão poderá ser usada no design de futuras interfaces, pois já condiz com a intuição dos usuários.

## 4. Análise Hierárquica de Tarefas (AHT)
Este tipo de análise parte dos objetivos do usuário para identificar as tarefas que devem ser realizadas a fim de atingir tais objetivos. Um plano configura a sequência de tarefas que deve ser realizada, como caminhos a serem percorridos, para atingir um determinado objetivo. 

A forma adotada para demonstrar as tarefas serão as notações textual e gráfica propostas pelas autoras Preece, Rogers e Sharp (2005). Na notação textual, os itens de número zero representam os objetivos, os itens subsequentes são as tarefas e seus subitens representam sub tarefas.

### 4.1 Representação textual

#### 4.1.1 Representação textual do objetivo de agendamento de empréstimos
**0.** Agendar empréstimos
<br>&emsp;&emsp;**1.** Localize o livro desejado
<br>&emsp;&emsp;&emsp;**1.1** Acesse o catálogo da biblioteca
<br>&emsp;&emsp;&emsp;**1.2** Indique o tipo de pesquisa desejada
<br>&emsp;&emsp;&emsp;**1.3** Indique o item a ser buscado
<br>&emsp;&emsp;&emsp;&emsp;**1.3.1** Indique especificações de busca avançada
<br>&emsp;&emsp;&emsp;**1.4** Identifique na lista o livro desejado
<br>&emsp;&emsp;**2.** Reserve o livro
<br>&emsp;&emsp;&emsp;**2.1** Selecione o livro desejado
<br>&emsp;&emsp;&emsp;**2.2** Selecione "reservar obra"
<br>&emsp;&emsp;&emsp;**2.3** Insira os dados de cadastro
<br>&emsp;&emsp;&emsp;**2.4** Efetive a reserva

Plano 0: faça 1 - 2; 
<br>Plano 1: faça 1.1 - 1.3 - 1.4. Caso queira filtrar a busca por assunto, título ou autor, faça 1.1 - 1.2 - 1.3 - 1.4; Caso queira especificar a busca com mais informações, faça 1.1 - 1.2 - 1.3 - 1.5 - 1.4;
<br>Plano 2: faça 2.1 - 2.2 - 2.3 - 2.4.

#### 4.1.2 Representação textual do objetivo de renovação do prazo de devolução
A realização das tarefas referentes à renovação do prazo de devolução mostrou-se efetiva e não apresentou problemas por parte dos usuários para alcançar tal objetivo. Desta forma, a análise de tarefas referente ao objetivo de renovação do prazo de devolução das obras mantem-se a mesma, conforme indicada em seguida.

**0.** Renovar prazo de devolução
<br>&emsp;&emsp;**1.** Acesse perfil do usuário
<br>&emsp;&emsp;&emsp;**1.1** Clique em "minha conta"
<br>&emsp;&emsp;&emsp;**1.2** Insira CPF e senha
<br>&emsp;&emsp;**2.** Identifique o livro desejado
<br>&emsp;&emsp;**3.** Renove o prazo
<br>&emsp;&emsp;**4.** Verifique o status de renovação
<br>&emsp;&emsp;&emsp;**4.1** Receba por email o recibo de renovação

Plano 0: faça 1 - 2 - 3 - 4.
<br>Plano 1: faça 1.1 - 1.2
<br>Plano 4: faça 4.1

### 4.2 Representação gráfica
A notação gráfica para a AHT tem como base os autores Preece e Rogers (2005), e possui uma estrutura formada por retângulos, que representam tarefas e subtarefas, e linhas que marcam a relação hierárquica entre as tarefas. Os planos de cada tarefa são descritos junto à linha vertical, logo abaixo do retângulo que contém a tarefa decomposta. As análises gráficas são complementadas por explicações em forma de tabela, equivalentes aos diagramas apresentados, conforme descritos abaixo:<br>

#### 4.2.1 Representação gráfica do objetivo de agendamento de empréstimo
<br>
<p align='center'>
    <img src='_media/images/AHT_2_objetivo1.png'>
    <figcaption align='center'>
        <b>Figura 1: Representação gráfica do objetivo de agendamento de empréstimos.</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------|:-------------------------|
| 0. Agendar empréstimo | |
| 1. Localize o livro desejado |  **Input**: página principal da BCE aberta; |
| 1.1 Acesse o catálogo da biblioteca | **Input**: página principal aberta<br>**Action**: localizar a barra intitulada "busca integrada" ou "catálogo online"|
| 1.2 Indique o tipo de pesquisa desejada | **Input**: localizar a caixa de seleção ao lado esquerdo da barra de "pesquisa integrada" ou "catálogo online", que por padrão estará marcada como "livre";<br>**Action**: caso queira especificar a pesquisa por "assunto", "título" ou "autor", é preciso clicar sobre a caixa de filtro e selecionar a opção desejada; <br>**Feedback**: a opção desejada ficará descrita na caixa de filtro.|
| 1.3 Indique o item a ser buscado | **Input**: barra intitulada "busca integrada" ou "catálogo online"<br>**Action**: digitar o título do livro na barra de busca.<br>**Feedback**: aparecerá uma lista de livros que contenham o título digitado;<br>**Problema**: uma nova aba será aberta no navegador, com padrões estéticos diferentes daqueles utilizados nas telas anteriores;<br>**Recomendação**: modificar o caminho de acesso para que o usuário seja redirecionado para uma tela na mesma aba do navegador. |
| 1.3.1 Indique especificações de busca avançada |**Input**: lista de livros gerada após inserção do título buscado;<br>**Plano**: caso necessário filtrar os livros utilizando informações específicas da obra, selecione a opção "busca avançada" abaixo da barra de busca contendo o título buscado.|
| 1.4 Identifique na lista o livro desejado | **Input**: lista de livros gerada após inserção do título buscado;<br>**Problema**: os livros encontrados não possuem imagem da capa;<br>**Recomendação**: acrescentar a imagem da capa para facilitar a identificação. |
| 2. Reserve o livro | **Input**: lista de livros gerada após inserção do título buscado; |
| 2.1 Selecione o livro desejado | **Input**: livro desejado já identificado na lista;<br>**Action**: clique sobre o título desejado;<br>**Feedback**: será direcionado para uma tela contendo as informações específicas do livro;<br>**Problema**: as informações estão dispostas de maneira não convencional. Além de existirem muitas informações nas laterais da página;<br>**Recomendações**: reformular a disposição das informações para evitar uso excessivo de espaço e dar mais visibilidade às informações de localização e reserva do exemplar. Desta forma, as funcionalidades que atualmente se encontram "escondidas" nas laterais da página também ficarão mais em evidência.|
| 2.2 Selecione "reservar obra" | **Input**: tela contendo as informações específicas do livro desejado;<br>**Action**: clicar sobre o botão de "reservar obra";<br>**Feedback**: uma tela com dados da obra no acervo será aberta;<br>**Problema**: atualmente, a opção de reserva se encontra apenas quando a área "ver registro no catálogo" é clicada, na parte esquerda da tela de dados da obra, dificultando o acesso intuitivo.<br>**Recomendações**: o botão de reserva deve estar presente na tela de informações específicas do livro.|
| 2.3 Insira os dados de cadastro | **Input**: tela com informações de localização e tipo do livro;<br>**Action**: digite o CPF e a senha cadastrados na biblioteca e clique em "confirmar".<br>**Feedback**: caso a reserva não possa ser realizada aparecerá a mensagem "Reserva Cancelada. O usuário não pode reservar este tipo de obra desta biblioteca". Em caso de sucesso, aparecerá uma mensagem confirmando a reserva e o prazo para retirada do exemplar. |

<figcaption align='center'>
    <b>Tabela 1: Problemas e recomendações do objetivo de agendamento de empréstimos</b>
    <br> 
    Fonte: Elaboração própria.
</figcaption>
<hr>

#### 4.2.2 Representação gráfica do objetivo de renovação do prazo de devolução
<br>
<p align='center'>
    <img src='_media/images/AHT_objetivo2.png'>
    <figcaption align='center'>
        <b>Figura 2: Representação gráfica do objetivo de renovação do prazo de devolução</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------|:-------------------------|
| 0. Renovar prazo de devolução |  |
| 1. Acesse perfil do usuário |  **Input**: página inicial da BCE;<br>**Action**: clique em "minha conta" localizada no canto superior direito;<br>**Feedback**: será redirecionado para a área de autenticação da CPF e senha. |
| 1.1 Insira CPF e senha | **Input**: página de autenticação;<br>**Feedback**: ao logar, será redirecionado para a área de perfil do usuário.|
| 2. Identifique o livro desejado | **Input**: página de perfil do usuário aberta;<br>**Action**: clique sobre a área "títulos pendentes" ou sobre a área de "renovação" na lateral esquerda;<br>**Feedback**: haverá uma lista com informações sobre livros emprestados e ainda não devolvidos. Ao lado de cada título haverá o botão "renovar".</p>|
| 3. Renove o prazo |  **Input**: livro identificado na lista "Títulos pendentes";<br>**Action**: clique sobre o botão "renovar";<br>**Feedback**: aparecerá um *pop-up* informando o status de renovação, aprovada ou não. </p>| 
| 4. Verifique o status de renovação | **Feedback**: aparecerá uma mensagem indicando renovação efetivada ou não do livro e a opção "enviar comprovante por email";<br>**Plano**: caso queira receber por email a confirmação de renovação, clique na opção "receber por email"</p>|

<figcaption align='center'>
    <b>Tabela 2: Problemas e recomendações do objetivo de renovação do prazo de devolução</b>
    <br> 
    Fonte: Elaboração própria
</figcaption>

## 5. Conclusão

Com base nas entrevistias e na análise dos passos efetuados pelos usuários, foi possível aferir que todos os entrevistados tinham expectativas em comunm sobre onde deveriam estar dispostos certos elementos na página. Vale lembra que essas expectativas são de usuários novatos e experientes no sistema, corroborando a ideia de que a não disposição desses elementos nos locais procurados se trata de uma falha de design.

Desse modo, foi criada uma nova Análise de Tarefas que especifica os objetivos, os passos, e as tarefas que devem ser executadas para realizar determinada ação no site. A principal mudança foi na atividade de Agendamento de Empréstimo, onde o elemento responsável por efetuar o agendamento passou a estar disposto logo após a identificação da obra no catálogo. As demais atividades foram validadas e não apresentaram mudanças significativas na ordem de execução, somente em seu detalhamento.

</div>

## Bibliografia
BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.

Preece, J.; Rogers, Y,; Sharp, H. **Design de Interação**. Porto ALegre: Bookman, 2005.

CAIADO, Márcio S. **Análise Hierárquica de Tarefas**. Disponível em https://docplayer.com.br/13376795-Analise-de-tarefas-analise-hierarquica-de-tarefas.html Acesso em 26 de setembro de 2020. 
