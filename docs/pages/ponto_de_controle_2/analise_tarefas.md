# <center>Análise de Tarefas

## Histórico de Versão
| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 26.09.2020 | 0.1 | Realização da Análise de Tarefas | Rafaella Junqueira |
| 27.09.2020 | 0.2 | Refinamento do documento | Rafaella Junqueira |
| 28.09.2020 | 0.3 | Adição de legendas nas imagens | Durval Carvalho |

<div align="justify"> 

## 1. Introdução
A análise de tarefas pode ser realizada em diferentes momentos do desenvolvimento, na fase anterior ao desenvolvimento do produto, analisando a situação atual e contando ou não com apoio de softwares. Após realizada uma intervenção que inclua sistemas computacionais, ou visando o redesenho de um sistema já existente.
O método utilizado para realização de análises de tarefas deste projeto será a Análise Hierárquica de Tarefas (AHT).

## 2. Análise Hierárquica de Tarefas (AHT)
Esta análise parte dos objetivos do usuário para identificar as tarefas que devem ser realizadas a fim de atingir tais objetivos. Um plano configura a sequência de tarefas que deve ser realizada, como caminhos a serem percorridos, para atingir um determinado objetivo. <br>A forma adotada para demonstrar as tarefas serão as notações textual e gráfica propostas por (Preece, Rogers e Sharp, 2005). Na notação textual, os itens de número zero representam os objetivos, os itens subsequentes são as tarefas e seus subitens representam sub tarefas. Já na notação gráfica, os retângulos representam as tarefas, as linhas as relação hierárquica entre elas e os planos são descritos entre as hierarquias.


### 2.1 Representação textual

#### 2.1.1 Representação textual do objetivo de agendamento de empréstimos:

**0.** Agendar empréstimos
<br>&emsp;&emsp;**1.** Localize o livro desejado
<br>&emsp;&emsp;&emsp;**1.1** Acesse o catálogo da biblioteca (na "busca integrada")
<br>&emsp;&emsp;&emsp;**1.2** Insira o título buscado
<br>&emsp;&emsp;&emsp;**1.3** Forneça os critérios de pesquisa
<br>&emsp;&emsp;&emsp;**1.4** Identifique na lista o livro desejado
<br>&emsp;&emsp;**2.** Reserve o livro
<br>&emsp;&emsp;&emsp;**2.1** Selecione o livro desejado
<br>&emsp;&emsp;&emsp;**2.2** Acesse "Ver o registro no catálogo"
<br>&emsp;&emsp;&emsp;**2.3** Efetive a reserva
<br>&emsp;&emsp;&emsp;**2.4** Insira os dados de cadastro
<br>&emsp;&emsp;**3.** Faça login
<br>&emsp;&emsp;&emsp;**3.1** Acesse perfil do usuário
<br>&emsp;&emsp;&emsp;**3.2** Insira CPF e senha

Plano 0: faça 1 - 2. Caso o login não tenha sido realizado previamente, faça 3 - 1 - 2.
<br>Plano 1: faça 1.1 - 1.2 - 1.4. Caso esteja na área de catálogo de pesquisa geral, faça 1.1 - 1.2 - 1.3 - 1.4.
<br>Plano 2: faça 2.1 - 2.2 - 2.3 - 2.4. Caso já esteja na área de catálogo de pesquisa geral, faça 2.1 - 2.3 - 2.4.
<br>Plano 3: faça 3.1 e 3.2. Caso já tenha realizado a pesquisa e esteja na área de catálogo de pesquisa geral, faça 3.3 - 3.2

#### 2.1.2 Representação textual do objetivo de renovação do prazo de devolução:

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
    
### 2.2 Representação gráfica

<p align='center'>
    <img src='_media/images/AHT_objetivo1.png'>
    <figcaption align='center'>
        <b>Figura 1: Representação gráfica do objetivo de agendamento de empréstimos.</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

OBS.: [Representação do objetivo 1 de forma expandida](https://github.com/Interacao-Humano-Computador/2020.1-BCE/blob/master/docs/_media/images/AHT_objetivo1.png)

<hr>

<p text-align="right">

| Objetivos/ operações | Problemas e recomendações |
|:--------------------:|:-------------------------:|
| 0. Agendar empréstimo | |
| 1. Localize o livro desejado | <p align="left"> **Input**: página principal da BCE aberta </p>|
| 1.1 Acesse o catálogo da biblioteca |<p align="left"> **Input**: área intitulada "pesquisa integrada" ou "catálogo online"; <br> **Action**: clicar em uma das duas áreas disponíveis e clicar sobre a barra de pesquisa logo abaixo do nome da área.</p>|
| 1.2 Insira o título buscado | <p align="left"> **Input**: barra de pesquisa; <br> **Action**: insira o nome do título buscado na barra de pesquisa; <br>**Feedback**: aparecerá uma lista de livros que contenham o título digitado; <br>**Problema**: uma nova aba será aberta no navegador;<br> **Recomendação**: modificar o caminho de acesso para que o usuário seja redirecionado para uma tela na mesma aba do navegador. </p>|
| 1.3 Identifique na lista o livro desejado | <p align="left"> **Input**: lista de livros buscados;<br> **Plano**: caso esteja no catálogo de pesquisa geral, preencha os campos existentes com critérios de busca mais específicos;<br> **Problema**: os livros encontrados não possuem imagem da capa; <br> **Recomendação**: acrescentar a imagem da capa para facilitar a identificação.</p>|
| 2. Reserve o livro | <p align="left"> **Input**: lista de livros buscados.</p> |
| 2.1 Selecione o livro desejado | <p align="left"> **Input**: livro desejado já identificado na lista; <br> **Action**: clique sobre o título desejado;<br>**Feedback**: será direcionado para uma tela contendo as informações gerais do livro.<br> **Problema**: as informações estão dispostas de maneira pouco visual;<br> **Recomendação**: dispor as informações de forma mais visual, evitando assim, uso excessivo de espaço e dando mais visibilidade às informações de localização do exemplar.</p>|
| 2.2 Acesse "Ver o registro no catálogo" | <p align="left"> **Input**: tela contendo as informações do livro desejado;<br> **Action**: clique em "ver registro no catálogo" localizado no canto superior esquerdo; <br>**Feedback**: abrirá uma tela com dados do acervo; <br> **Problema**: os itens da barra inferior deveriam estar mais em evidência para o usuário. Uma terceira aba é aberta no navegador; <br>**Recomendações**: evidenciar a opção de "reserva" quando abertas as informações do livro e disponibilizar esta opção na tela anterior, após seleção do livro desejado. Assim, não haverá necessidade de acessar a área "registro no catálogo".</p>|
| 2.3 Efetive a     reserva | <p align="left"> **Input**: tela de dados do acervo aberta;<br>**Action**: clique em "Reserva";<br> **Feedback**: aparecerá uma tela com informações de localização e tipo do livro. </p>|
| 2.4 Insira os dados de cadastro | <p align="left"> **Input**: tela com informações de localização e tipo do livro; <br>**Action**: digite o CPF e a senha cadastrados na biblioteca. Em seguida, aperte em "confirmar". <br>**Feedback**: caso o login não tenha sido feito previamente, aparecerá a mensagem "Reserva Cancelada. O usuário não pode reservar este tipo de obra desta biblioteca". Em caso de sucesso, aparecerá uma mensagem confirmando a reserva e o prazo para retirada do exemplar.</p>|
| 3. Faça o login |  | 
| 3.1 Acesse perfil do usuário | <p align="left"> **Input**: página principal da BCE ou área de "Pesquisa Geral";<br> **Plano**: caso esteja na página principal da BCE, clique em "minha conta" localizada no canto superior direito. Caso esteja na área de "Pesquisa Geral", clique na tecla "login" localizada no canto superior direito;<br>**Feedback**: em caso de login realizado a partir da tela principal, será redirecionado para uma página de autenticação contendo espaços para CPF e senha. Em caso de login realizado pela tela de "Pesquisa geral" (após buscado o livro), aparecerá um *pop-up* com espaço para CPF e senha.</p>|
| 3.2 Insira CPF e senha | <p align="left"> **Input**: página redireciona a partir da principal da BCE ou *pop-up* da área de "Pesquisa Geral; <br>**Feedback**: após confirmar, será redirecionado para a área de perfil do usuário. A confirmação é indicada ao surgir o nome do usuário no canto superior direito em uma barra verde.**Problema**: quando direcionado após fazer login, não existem meios de retornar à busca, é preciso retornar para a página principal da BCE direto pela barra URL;**Recomendações**: a logo da UnB localizada na parte esquerda esquerda poderia redirecionar o usuário para a página incial, onde é possível realizar a busca por materiais.</p>|

<figcaption align='center'>
    <b>Tabela 1: Problemas e recomendações do objetivo de agendamento de empréstimos</b>
    <br> 
    Fonte: Elaboração própria
</figcaption>
</p>

<hr>

<p align='center'>
    <img src='_media/images/AHT_objetivo2.png'>
    <figcaption align='center'>
        <b>Figura 2: Representação gráfica do objetivo de renovação do prazo de devolução</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------:|:-------------------------:|
| 0. Renovar prazo de devolução |  |
| 1. Acesse perfil do usuário | <p align="left"> **Input**: página inicial da BCE;<br>**Action**: clique em "minha conta" localizada no canto superior direito;<br>**Feedback**: será redirecionado para a área de autenticação da CPF e senha. </p> |
| 1.1 Insira CPF e senha | <p align="left"> **Input**: página redireciona a partir da principal da BCE;<br>**Feedback**: ao logar, será redirecionado para a área de perfil do usuário. </p>|
| 2. Identifique o livro desejado | <p align="left"> **Input**: página de perfil do usuário aberta;<br>**Action**: clique sobre a área "títulos pendentes"; **Feedback**: haverá uma lista com informações sobre livros emprestados e ainda não devolvidos. Ao lado de cada título haverá o botão "renovar".</p>|
| 3. Renove o prazo | <p align="left"> **Input**: livro identificado na lista "Títulos pendentes";<br>**Feedback**: aparecerá um *pop-up* informando o status de renovação, aprovada ou não. </p>| 
| 4. Verifique o status de renovação | <p align="left"> <br>**Feedback**: aparecerá uma mensagem indicando renovação ou não do livro e a opção de enviar comprovante por email;<br>**Plano**: caso queira receber por email a confirmação de renovação, clique na opção "receber por email"</p>|
<figcaption align='center'>
    <b>Tabela 2: Problemas e recomendações do objetivo de renovação do prazo de devolução</b>
    <br> 
    Fonte: Elaboração própria
</figcaption>

<br>

## Bibliografia
BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.

CAETANO, Cíntia. **Projeto de Interface**. Disponível em http://www.ic.uff.br/~ccaetano/aulas/IHC_Aula_7_Projeto_de_Interface_Analise_Ususario_e_Tarefa.pdf Acesso em 26 de setembro de 2020.

</div>
