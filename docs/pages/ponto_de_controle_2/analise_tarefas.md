# <center>Análise de Tarefas</center>

## Histórico de Versão
| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 26.09.2020 | 0.1 | Realização da Análise de Tarefas | Rafaella Junqueira |
| 27.09.2020 | 0.2 | Refinamento do documento | Rafaella Junqueira |

<div align='justify'> 

## 1. Introdução
A análise de tarefas pode ser realizada em diferentes momentos do desenvolvimento, na fase anterior ao desenvolvimento do produto, analisando a situação atual e contando ou não com apoio de softwares. Após realizada uma intervenção que inclua sistemas computacionais, ou visando o redesenho de um sistema já existente.
O método utilizado para realização de análises de tarefas deste projeto será a Análise Hierárquica de Tarefas (AHT).

## 2. Análise Hierárquica de Tarefas (AHT)
Esta análise parte dos objetivos do usuário para identificar as tarefas que devem ser realizadas a fim de atingir tais objetivos. Um plano configura a sequência de tarefas que deve ser realizada, como caminhos a serem percorridos, para atingir um determinado objetivo. <br>A forma adotada para demonstrar as tarefas serão as notações textual e gráfica propostas por (Preece, Rogers e Sharp, 2005). Na notação textual, os itens de número zero representam os objetivos, os itens subsequentes são as tarefas e seus subitens representam sub tarefas. Já na notação gráfica, os retângulos representam as tarefas, as linhas as relação hierárquica entre elas e os planos são descritos entre as hierarquias.


### 2.1 Representação textual

#### 2.1.1 Representação textual do objetivo de agendamento de empréstimos:

**0.** Agendar empréstimos
<br>&emsp;&emsp;**1.** Localize o livro desejado
<br>&emsp;&emsp;&emsp;**1.1** Acesse o catálogo da biblioteca (na 'busca integrada')
<br>&emsp;&emsp;&emsp;**1.2** Insira o título buscado
<br>&emsp;&emsp;&emsp;**1.3** Forneça os critérios de pesquisa
<br>&emsp;&emsp;&emsp;**1.4** Identifique na lista o livro desejado
<br>&emsp;&emsp;**2.** Reserve o livro
<br>&emsp;&emsp;&emsp;**2.1** Selecione o livro desejado
<br>&emsp;&emsp;&emsp;**2.2** Acesse 'Ver o registro no catálogo'
<br>&emsp;&emsp;&emsp;**2.3** Clique em 'reserva'
<br>&emsp;&emsp;&emsp;**2.4** Insira os dados de cadastro
<br>&emsp;&emsp;**3.** Faça login
<br>&emsp;&emsp;&emsp;**3.1** Clique em 'minha conta'
<br>&emsp;&emsp;&emsp;**3.2** Insira CPF e senha
<br>&emsp;&emsp;&emsp;**3.3** Clique em 'login'

Plano 0: faça 1 - 2. Caso o login não tenha sido realizado previamente, faça 3 - 1 - 2.
<br>Plano 1: faça 1.1 - 1.2 - 1.4. Caso esteja na área de catálogo de pesquisa geral, faça 1.1 - 1.2 - 1.3 - 1.4.
<br>Plano 2: faça 2.1 - 2.2 - 2.3 - 2.4. Caso já esteja na área de catálogo de pesquisa geral, faça 2.1 - 2.3 - 2.4.
<br>Plano 3: faça 3.1 e 3.2. Caso já tenha realizado a pesquisa e esteja na área de catálogo de pesquisa geral, faça 3.3 - 3.2

#### 2.1.2 Representação textual do objetivo de renovação do prazo de devolução:

**0.** Renovar prazo de devolução
<br>&emsp;&emsp;**1.** Realize login de acesso
<br>&emsp;&emsp;&emsp;**1.1** Clique em 'minha conta'
<br>&emsp;&emsp;&emsp;**1.2** Insira CPF e senha
<br>&emsp;&emsp;**2.** Identifique o livro desejado na área 'títulos pendentes'
<br>&emsp;&emsp;**3.** Clique em 'Renovar'
<br>&emsp;&emsp;**4.** Verifique o status de renovação realizada
<br>&emsp;&emsp;&emsp;**4.1** Receba por email o recibo de renovação

Plano 0: faça 1 - 2 - 3 - 4.
<br>Plano 1: faça 1.1 - 1.2
<br>Plano 4: faça 4.1
    
### 2.2 Representação gráfica

#### 2.2.1 Representação gráfica do objetivo de agendamento de empréstimos.

<p align='center'>
    <img src='/docs/_media/images/AHT_objetivo1.png'>
</p>

<p text-align='right'>

|        Objetivos/ operações       | Problemas e recomendações |
|:---------------------------------:|:-------------------------:|
| 0. Agendar empréstimo | - |
| 1. Localize o livro desejado | <p align='left'> **Input**: entre na página principal da BCE </p>|
| 1.1 Acesse o catálogo da biblioteca |<p align='left'> **Input**: clique na barra de pesquisa da área intitulada 'pesquisa integrada' ou 'catálogo online'. </p>|
| 1.2 Insira o título buscado | <p align='left'> **input**: insira o nome do título buscado na barra de pesquisa <br>**Feedback**: aparecerá uma lista de livros que contenham o título digitado. <br>**Problema**: uma nova aba será aberta no navegador. </p>|
| 1.3 Identifique na lista o livro desejado | <p align='left'> **Plano**: caso esteja no catálogo de pesquisa geral, preencha os campos existentes com critérios de busca mais específicos. </p>|
| 2. Reserve o livro | - |
| 2.1 Selecione o livro desejado | <p align='left'> **Input**: clique no título desejado. <br>**Feedback**: aparecerão as informações gerais do livro. </p>|
| 2.2 Acesse 'Ver o registro no catálogo' | <p align='left'> **Feedback**: abrirá um *pop-up* com dados do acervo. <br>**Recomendações**: os itens da barra inferior devem estar mais em evidência para o usuário. <br>A opção de reserva deveria estar presente sem a necessidade de acessar via 'registro no catálogo'.<br>**Problema**: uma terceira aba é aberta no navegador.</p>|
| 2.3 Clique em 'reserva' | <p align='left'> **Feedback**: aparecerá um *pop-up* com informações de localização e tipo do livro. </p>|
| 2.4 Insira os dados de cadastro | <p align='left'> **Input**: digite o CPF e a senha cadastrados na biblioteca. Em seguida, aperte em 'confirmar'. <br>**Feedback**: caso o login não tenha sido feito previamente, aparecerá a mensagem 'Reserva Cancelada. O usuário não pode reservar este tipo de obra desta biblioteca'. </p>|
| 3. Faça o login | - | 
| 3.1 Clique em 'minha conta' | <p align='left'> **Feedback**: caso queira realizar o login antes de pesquisar um livro, clique em 'minha conta' e será redirecionado para a será redirecionado para uma página de autenticação contendo espaços para CPF e senha </p>|
| 3.2 Insira CPF e senha | <p align='left'> **Feedback**: após confirmar, será redirecionado para a área de perfil do usuário.**Problema**: quando direcionado para a área de perfil após fazer login, não existem meios de retornar à busca, é preciso retornar para a página principal do site direto pela barra URL.**Recomendações**: a logo da UnB à esquerda poderia redirecionar o usuário para a página incial, onde é possível realizar a busca por materiais. </p>|
| 3.3 Clique em 'login' | <p align='left'> **Input**: caso tenha realizado a pesquisa e queira reservar um livro mas não tenha realizado login, clique sobre o botão 'fechar' do *pop-up* com as informações de localização e tipo do livro que estará aberta. Em seguida clique no botão 'login' no canto superior direito. <br>**Feedback**: aparecerá um *pop-up* solicitando informações cadastrais. Após confirmação, aparecerá o nome do usuário no canto superior direito em uma barra verde. </p>|

</p>

Representação gráfica do objetivo de renovação do prazo de devolução.

<p align='center'>
    <img src='/docs/_media/images/AHT_objetivo2.png'>
</p>

| Objetivos/ operações | Problemas e recomendações |
|:--------------------:|:-------------------------:|
| 0. Renovar prazo de devolução | - |
| 1. Realize login de acesso | <p align='left'> **Input**: acesse a página inicial da BCE. </p> |
| 1.1 Clique em 'minha conta' | <p align='left'> **Feedback**: será redirecionado para a área de autenticação da CPF e senha. </p>|
| 1.2 Insira CPF e senha | <p align='left'> **Feedback**: será redirecionado para a área de perfil do usuário. </p>|
| Identifique o livro desejado na área 'títulos pendentes'. | <p align='left'> **Feedback**: assim que entrar na área de perfil do usuário haverá as informações sobre livros emprestados e ainda não devolvidos. Ao lado de todos haverá o botão 'renovar'. </p>|
| 3. Clique em 'Renovar' | <p align='left'> **Feedback**: aparecerá um *pop-up* informando o status de renovação, aprovada ou não. </p>| 
| 4. Verifique o status de renovação realizada | <p align='left'> **Feedback**: aparecerá uma mensagem indicando renovação ou não do livro e a opção de enviar comprovante por email.</p>|

<br>

## Bibliografia
BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.

CAETANO, Cíntia. **Projeto de Interface**. Disponível em http://www.ic.uff.br/~ccaetano/aulas/IHC_Aula_7_Projeto_de_Interface_Analise_Ususario_e_Tarefa.pdf Acesso em 26 de setembro de 2020.

</div>
