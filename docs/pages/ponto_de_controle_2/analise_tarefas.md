# <center>Análise de Tarefas</center>

## Histórico de Versão
| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 26.09.2020 | 0.1 | Realização da Análise de Tarefas | Rafaella Junqueira |

<div align="justify">

## 1. Introdução
A análise de tarefas pode ser realizada em diferentes momentos do desenvolvimento, na fase anterior ao desenvolvimento do produto, analisando a situação atual e contando ou não com apoio de softwares. Após realizada uma intervenção que inclua sistemas computacionais, ou visando o redesenho de um sistema já existente.
O método utilizado para realização de análises de tarefas deste projeto será a Análise Hierárquica de Tarefas (AHT).

## 2. Análise Hierárquica de Tarefas (AHT)
Esta análise parte dos objetivos do usuário para identificar as tarefas que devem ser realizadas a fim de atingir tais objetivos. Um plano configura a sequência de tarefas que deve ser realizada, como caminhos a serem percorridos, para atingir um determinado objetivo. <br>A forma adotada para demonstrar as tarefas serão as notações textual e gráfica propostas por (Preece, Rogers e Sharp, 2005). Na notação textual, os itens de número zero representam os objetivos, os itens subsequentes são as tarefas e seus subitens representam sub tarefas. Já na notação gráfica, os retângulos representam as tarefas, as linhas as relação hierárquica entre elas e os planos são descritos entre as hierarquias.

### 2.1 Representação textual

Representação textual do objetivo de agendamento de empréstimos:

0. Agendar empréstimos
    1. Localize o livro desejado
        <br>1.1 Acesse o catálogo da biblioteca (na "busca integrada")
        <br>1.2 Insira o título buscado
        <br>1.3 Forneça os critérios de pesquisa
        <br>1.4 Identifique na lista o livro desejado
    2. Reserve o livro
        <br>2.1 Selecione o livro desejado
        <br>2.2 Acesse "Ver o registro no catálogo"
        <br>2.3 Clique em "reserva"
        <br>2.4 Insira os dados de cadastro
    3. Faça login
        <br> 3.1 Clique em "minha conta"
        <br> 3.2 Insira CPF e senha
        <br> 3.3 Clique em "login"

Plano 0: faça 1 - 2. Caso o login não tenha sido realizado previamente, faça 3 - 1 - 2.
<br>Plano 1: faça 1.1 - 1.2 - 1.4. Caso esteja na área de catálogo de pesquisa geral, faça 1.1 - 1.2 - 1.3 - 1.4.
<br>Plano 2: faça 2.1 - 2.2 - 2.3 - 2.4. Caso já esteja na área de catálogo de pesquisa geral, faça 2.1 - 2.3 - 2.4.
<br>Plano 3: faça 3.1 e 3.2. Caso já tenha realizado a pesquisa e esteja na área de catálogo de pesquisa geral, faça 3.3 - 3.2


Representação textual do objetivo de renovação do prazo de devolução:

0. Renovar prazo de devolução
    1. Realize login de acesso
        <br> 1.1 Clique em "minha conta"
        <br> 1.2 Insira CPF e senha
    2. Identifique o livro desejado na área "títulos pendentes"
    3. Clique em "Renovar"
    4. Verifique o status de renovação realizada
        <br>4.1 Receba por email o recibo de renovação

Plano 0: faça 1 - 2 - 3 - 4. 
<br>Plano 4: faça 4.1
    
### 2.1 Representação gráfica

Representação gráfica do objetivo de agendamento de empréstimos.

<p align='center'>
    <img src='_media/images/AHT_objetivo1.png'>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------:|:-------------------------:|
| 0. Agendar empréstimo | - |
| 1. Localize o livro desejado | **input**: entre na página principal da BCE |
| 1.1 Acesse o catálogo da biblioteca | **input**: clique na barra de pesquisa da área intitulada "pesquisa integrada" ou "catálogo online". |
| 1.2 Insira o título buscado | **input**: insira o nome do título buscado na barra de pesquisa <br>**feedback**: aparecerá uma lista de livros que contenham o título digitado. <br>**problema**: uma nova aba será aberta no navegador. |
| 1.3 Identifique na lista o livro desejado | **plano**: caso esteja no catálogo de pesquisa geral, preencha os campos existentes com critérios de busca mais específicos. |
| 2. Reserve o livro | - |
| 2.1 Selecione o livro desejado | **input**: clique no título desejado. <br>**feedback**: aparecerão as informações gerais do livro. |
| 2.2 Acesse "Ver o registro no catálogo" | **feedback**: abrirá um *pop-up* com dados do acervo. <br>**recomendações**: os itens da barra inferior devem estar mais em evidência para o usuário. <br>A opção de reserva deveria estar presente sem a necessidade de acessar via "registro no catálogo".<br>**problema**: uma terceira aba é aberta no navegador.|
| 2.3 Clique em "reserva" | **feedback**: aparecerá um *pop-up* com informações de localização e tipo do livro. |
| 2.4 Insira os dados de cadastro | **input**: digite o CPF e a senha cadastrados na biblioteca. Em seguida, aperte em "confirmar". <br>**feedback**: caso o login não tenha sido feito previamente, aparecerá a mensagem "Reserva Cancelada. O usuário não pode reservar este tipo de obra desta biblioteca". |
| 3. Faça o login | - |
| 3.1 Clique em "minha conta" | **feedback**: caso queira realizar o login antes de pesquisar um livro, clique em "minha conta" e será redirecionado para a será redirecionado para uma página de autenticação contendo espaços para CPF e senha |
| 3.2 Insira CPF e senha | **feedback**: após confirmar, será redirecionado para a área de perfil do usuário. <br> **problema**: quando direcionado para a área de perfil após fazer login, não existem meios de retornar à busca, é preciso retornar para a página principal do site direto pela barra URL.<br>**recomendações**: a logo da UnB à esquerda poderia redirecionar o usuário para a página incial, onde é possível realizar a busca por materiais.|
| 3.3 Clique em "login" | **input**: caso tenha realizado a pesquisa e queira reservar um livro mas não tenha realizado login, clique sobre o botão "fechar" do *pop-up* com as informações de localização e tipo do livro que estará aberta. Em seguida clique no botão "login" no canto superior direito. <br>**feedback**: aparecerá um *pop-up* solicitando informações cadastrais. Após confirmação, aparecerá o nome do usuário no canto superior direito em uma barra verde.|

Representação gráfica do objetivo de renovação do prazo de devolução.

<p align='center'>
    <img src='_media/images/AHT_objetivo2.png'>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------:|:-------------------------:|
| 0. Renovar prazo de devolução | - |
| 1. Realize login de acesso | **input**: acesse a página inicial da BCE. |
| 1.1 Clique em "minha conta" | **feedback**: será redirecionado para a área de autenticação da CPF e senha.|
| 1.2 Insira CPF e senha | **feedback**: será redirecionado para a área de perfil do usuário. |
| Identifique o livro desejado na área "títulos pendentes". | **feedback**: assim que entrar na área de perfil do usuário haverá as informações sobre livros emprestados e ainda não devolvidos. Ao lado de todos haverá o botão "renovar".|
| 3. Clique em "Renovar" | **feedback**: aparecerá um *pop-up* informando o status de renovação, aprovada ou não.| 
| 4. Verifique o status de renovação realizada | **feedback**: aparecerá uma mensagem indicando renovação ou não do livro e a opção de enviar comprovante por email.|

<br>

## Bibliografia
BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.

CAETANO, Cíntia. **Projeto de Interface**. Disponível em http://www.ic.uff.br/~ccaetano/aulas/IHC_Aula_7_Projeto_de_Interface_Analise_Ususario_e_Tarefa.pdf Acesso em 26 de setembro de 2020.

</div>