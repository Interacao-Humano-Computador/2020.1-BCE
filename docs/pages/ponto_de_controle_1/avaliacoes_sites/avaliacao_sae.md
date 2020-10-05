# <center>Relatório da avaliação - SAE

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 02.09.2020 |  0.1   | Criação do documento | Geraldo Victor |

<div align="justify">

## 1. Objetivo
Como proposto pelo planejamento de avaliação nesta atividade irei usar cada uma das heurísticas propostas por Nielsen em cada tela do módulo de questões do site do SAE. O site apenas permite acesso às pessoas previamente autorizadas, portanto prints da tela serão disponibilizados para que assim sejam exemplificados os casos em que o sistema  possuir ou não as heurísticas necessárias.

## 2. Método
O método escolhido para realizar a avaliação é o método de inspeção por meio das avaliações heurísticas. Segundo Nielsen (2000), existem dez heurísticas principais e serão elas as exploradas:
1. Visibilidade e reconhecimento do estado ou contexto atual do sistema
2. Compatibilidade com o mundo real
3. Controle e Liberdade do usuário
4. Consistência e padrões
5. Prevenção de erros
6. Reconhecimento ao invés de memorização
7. Flexibilidade e eficiência
8. Projeto estético e minimalista
9. Diagnosticar e corrigir erros
10. Ajuda e Documentação
Esses serão os aspectos presentes na avaliação do site a fim de identificar oportunidades de
melhoria e compreender se o mesmo atende aos usuários em termos práticos de uso.

## 3. Heurísticas
A tela de questões foi escolhida para a avaliação onde será feito uma avaliação da primeira heurística: Visibilidade e reconhecimento do estado ou contexto atual do sistema.

<p align='center'>
    <img src='_media/images/H1_sae.png'>
    <figcaption align='center'>
        <b>Figura 1: Análise do problema 1</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: O sistema informa ao usuário com o título “Pessoa” o que aparece em 2 lugares no canto superior direito (onde abaixo tem a palavra “inicio”) e outra centralizada na tela,além disso tem-se no canto superior uma mensagem de boas vindas onde aparentemente tem a função de dizer também as possibilidades que a tela possui, leva-se a crer que as palavras “Pessoa” na tela identificam onde o usuário se encontra. A duplicidade dessa informação pode deixar o usuário confuso em qual lugar ele deve olhar para que saiba onde está e possívelmente saber como chegar a cada parte do site.

- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.

<p align='center'>
    <img src='_media/images/H2_sae.png'>
    <figcaption align='center'>
        <b>Figura 2: Análise do problema 2</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Após o login suponhamos que o usuário queira responder as questões ele tem duas palavras que levam ele a crer que ele será direcionado para a tela de questões, a primeira na parte superior da tela e a segunda na parte central da tela.As duas levam para a mesma tela, o fato de terem dois lugares pode levar o usuário a crer que essas duas interações façam coisas diferentes e se sentir motivado a clicar nos dois para ter certeza do que se trata deixando assim confuso ao perceber que fazem a mesma coisa, causando um desconforto desnecessário. 
 
    A palavra “Questões” aparece destacada na esfera, centro da tela e também no canto esquerdo, a mensagem mudou na parte superior, e no canto superior direito aparece “BQD” logo embaixo “inicio”, tanta informação visual e fora de padrão não permite ao usuário saber em qual local ele deve olhar para saber qual caminho ele teve que tomar para chegar a tal tela, tamém o confunde, pois após clicar em quetões foi direcionado para uma página que tem partes com o nome “questões” clicáveis em 3 lugares distintos, dessa forma por mais que hajam informações na tela dizendo onde ele se encontra e quais são suas possibilidades os fatores supracitados deixam a desejar e causam desconforto ao usuário.

- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.

<p align='center'>
    <img src='_media/images/H3_sae.png'>
    <figcaption align='center'>
        <b>Figura 3: Análise do problema 3</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Após chegarmos na tela de questões, suponhamos que o usuário quisesse resolver as questões e já tivesse clicado na parte superior e/ou na esfera das questões e clique no
canto esquerdo. Quando isso ocorre, é aberta uma tela onde temos que a mensagem superior não mudou o que a torna ela sem utilidade para se situar quanto as possibilidades da tela. 

    No canto superior direito temos a o mesmo box que contém a palavra “Questao” e abaixo responder, no centro temos a frase “Responder Questões”, fica claro onde o usuário está, mas como ele chegou lá não,nada que mostre ao usuário qual caminho ele tomou pra chegar na tela é colocado na tela fazendo com que o usuário tenha que memorizar as etapas, dessa forma o usuário tem a sensação de desconforto e se sente desmotivado a fazer questões na plataforma.
- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.


<p align='center'>
    <img src='_media/images/H4_sae.png'>
    <figcaption align='center'>
        <b>Figura 4: Análise do problema 4</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Após todo esse processo seria esperado que houvesse em algum lugar uma descrição melhor da função dos campos que aparecem, porém, não fica claro qual a próxima etapa para
responder as questões. Induz o usuário a crer que é só clicar em "continuar", mas o clique apenas faz surgir a mensagem “Informe a disciplina” em vermelho ao lado da lupa. O usuário pode errar caso não saiba que o campo é obrigatório,além disso o campo disciplina não é editável, o que causa a sensação de confusão ao usuário.
- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Descrição no box branco melhor das possibilidades, marcação no campo da disciplina que indique que é um campo obrigatório, formatação no campo ou no cursor que indique que está aquele campo está desabilitado.

<p align='center'>
    <img src='_media/images/H5_sae.png'>
    <figcaption align='center'>
        <b>Figura 5: Análise do problema 5</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Após clicar na lupa, uma nova janela é exibida e um box no canto superior direito é exibido e da mesma forma que o anterior não serve para orientar o usuário já que essa nova janela se trata de adicionar uma matéria e não de
responder alguma questão, mas o box branco na parte superior explica dessa vez qual a possibilidade daquela janela.
- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.


<p align='center'>
    <img src='_media/images/H6_sae.png'>
    <figcaption align='center'>
        <b>Figura 6: Análise do problema 6</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Após adicionar a questão nenhuma mensagem é exibida apenas o nome é adicionado, surge em seguida um campo com a label “Conteúdo” e não fica claro se é um campo obrigatório, a mensagem de erro continua, causando a impressão de que não foi adicionado ainda a disciplina.
- **Efeito sobre a tarefa**: Possibilidade de erro na navegação.
- **Correção possível**: Mensagem de feedback dizendo que a disciplina foi adicionada e dizendo para adicionar conteúdo caso seja desejado.

<p align='center'>
    <img src='_media/images/H7_sae.png'>
    <figcaption align='center'>
        <b>Figura 7: Análise do problema 7</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Ao clicar na lupa da label de conteúdo surge outra janela com os mesmos problemas da
anterior. Após esses passos existem duas possibilidades ao clicar em continuar:
    - O usuário não informa o conteúdo e a tela com as questões contendo todos os conteúdos é exibida, mas não é emitido nenhum alerta pedindo pra ele confirmar que deseja responder uma lista com todos os conteúdos.
    - O usuário informa um conteúdo específico e a tela com questões específicas do
conteúdo é exibida.
- **Efeito sobre a tarefa**: Muitas questões aleatórias sem contexto.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.

<p align='center'>
    <img src='_media/images/H8_sae.png'>
    <figcaption align='center'>
        <b>Figura 8: Análise do problema 8</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: Em ambos os casos citados acima, o usuário é redirecionado a uma tela onde pode-se responder várias perguntas, e o usuário enfim consegue chegar ao objetivo de responder as perguntas. Ao clicar em responder a tela mostra se ele acertou ou errou imediatamente, ao clicar em próxima ele vai pra proxima pergunta, o usuário consegue saber onde ele está, porém não há nenhuma rastreabilidade de como chegar onde ele chegou dessa forma o usuário deve memorizar o caminho que fez para que assim possa responder as questões.
- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir apenas um lugar que seria responsável pela rastreabilidade da página.

<p align='center'>
    <img src='_media/images/H9_sae.png'>
    <figcaption align='center'>
        <b>Figura 9: Análise do problema 9</b>
        <br> 
        Fonte: Elaboração própria
    </figcaption>
</p>

- **Descrição do problema**: O botão cancelar da ultima tela leva pra uma tela sem nenhuma conexão com a anterior e causa confusão ao usuário.
- **Efeito sobre a tarefa**: Aprendizagem de manuseio do site reduzida.
- **Correção possível**: Definir a página anterior como padrão caso seja clicado em cancelar.



</div>