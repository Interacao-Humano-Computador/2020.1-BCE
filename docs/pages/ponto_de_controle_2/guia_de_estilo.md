# Guia de Estilo

## Histórico de Versões
| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 23/09/2020 | 0.1 | Criação do Documento | Isabella Carneiro |
| 26/09/2020 | 0.2 | Adição do Objetivo e Metodologia do documento | Durval Carvalho |
| 26/09/2020 | 0.2 | Modificação do tópico Tipografia | Durval Carvalho |
| 26/09/2020 | 0.3 | Modificação do tópico Opções de Acessibilidade | Isabella Carneiro |

## 1. Introdução

Este guia de estilo define os padrões visuais sugeridos para serem utilizados no site da BCE.
Com base na avaliação e visando melhorias esse documento apresenta as características do design do site.

## 2. Objetivo

O objetivo desse documento é compreender o estado pré-intervenção do design da interface da BCE. Após o entendimento dos fundamentos da interface, será desenvolvido um novo design de interface procurando não romper com identidade visual original.

## 3. Metodologia

Para entender a identidade visual do site original, foi preciso avaliar as seguintes características da interface:
- Qual tipografia era predominante?
- Quais logos são usados com mais frequência?
- Qual a paleta de cor predominante?
- Existe uma Padronização de Formas? Se sim, qual?
- Existe uma Padronização de Elementos da Interface? Se sim, qual?
- Existe uma Padronização de Simbolos usados? Se sim, qual?
- Existe opções de acessibilidade? Se sim, quais? Elas servem ao seu propósito?
- Como o layout da página (proporções, grids, diposição de elementos) está definido?

Com base nas características identificadas no site original, foi avaliado se a características precisava ser modificada, e quando necessário foi sugerido uma nova alternativa. Desse modo, o design final sugerido nesse documento é uma mescla de características originais do site, com modificações parciais e totais.

## 4. Avaliação da interface original


### 4.1. Tipografia

A fonte utilizada com maior frequência no site da BCE é a `Verdana`. Essa fonte foi criada por Matthew Carter para a Microsoft Corporations, e é da subfamília `Regular`. A fonte `Verdana` é de uso gratuito apenas para uso pessoal, desse modo é preciso autorização quando utilizada para uso comercial. Essa fonte foi criada para oferecer melhor legibilidade possível em monitores de baixa resolução, porém muitos editores de `Web` não recomendam seu uso, pois o tamanho da fonte é incompatível com o tamanho das demais fontes, assim um caractere em `Verdana` 10pt é consideravelmente maior que o mesmo caractere em `Times New Roman` também em 10pt, dificultando assim a leitura quando há mais de uma tipografia na mesma página. [[1]](http://tipografos.net/designers/mathew-carter.html) [[2]](https://pt.wikipedia.org/wiki/Verdana)

Exemplos de Verdana:

<p align='center'>
    <img src='_media/images/verdana_examples.png'>
</p>

No design atual, não há uma padronização de tamanho de fontes. Existem diversos tamanhos de fonte diferentes, para textos de mesma relevância semântica na interface do site. Um problema grave é que existem informações textuais armazenadas em imagens, dificultando assim a acessibilidade de usuários de dispositivos móveis (não é possível redimensionamento) e de usuários de leitores de tela (esses dispositivos não conseguem ler textos gravados em imagens).


<div style='border-style: solid;'>
<p align='center'> Exemplos dos vários tamanhos de fonte distribuidos na interface </p>
<p align='center'>
    <img src='_media/assets/images/print_screen/verdana1.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/verdana2.png' style='margin: 5px;'>
</p>

<p align='center'> Exemplos de informações textuais em armazenadas em imagens </p>
<p align='center'>
    <img src='_media/assets/images/print_screen/text_images1.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/text_images2.png' style='margin: 5px;'>
</p>
</div>

As cores dos textos também não estão padronizadas, em textos de mesma relevância semântica é utilizado cores diferentes (#003366 e #666666). Já em outros elementos textuais, são utilizado as cores #009999, #FF3366, #074260, #297474 e #336C89, além do branco (#FFFFFF) e do preto (#000000). Devido a semelhança entre algumas dessas cores, como por exemplo a #003366 e #074260, acredita-se a intenção original era utilizar somente uma delas. 

<p align='center'>
    <img src='_media/assets/images/print_screen/color_666666.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_009999.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_297474.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_003366.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_074260.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_336C89.png' style='margin: 5px;'>
    <img src='_media/assets/images/print_screen/color_FF3366.png' style='margin: 5px;'>
</p>

### 4.2. Logo

A logo da Biblioteca Central é formada pela logo da Universidade de Brasília adicionada a sigla 'BCE' ao lado ou embaixo como podemos ver a seguir.

<p align='center'>
    <img height="100px" src="_media/assets/images/logos/BCE.png" style='margin: 10px;'>
    <img src="_media/assets/images/logos/logo_branca.png" style='margin: 10px;'>
    <img src="_media/assets/images/logos/logo_preta.png" style='margin: 10px;'>
    <img src="_media/assets/images/logos/logo_grande.png" style='margin: 10px;'>
</p>


  
## Paleta de Cores

* A cor de fundo do site está dividida entre a cor branca (#FFFFFF) e a cor cinza (#F1F3F2).
* A cor do menu é o azul (#3162C6).

<img src="_media/assets/images/logos/cor_Branca.png">
<img src="_media/assets/images/logos/cor_Cinza.png">
<img src="_media/assets/images/logos/cor_Azul.png">


## Padronização de Formas


## Padronização de Elementos da Interface


## Padronização dos Simbolos Usados

Os símbolos utilizados no site são para as seguintes funções:
* Busca
* Ajuda
* Logout
* Ir para página inicial
* Salvar
* Procurar uma data

Os símbolos deverão seguir o seguinte padrão:

<img height="200px" src="_media/assets/images/logos/busca.jpg">
<img height="200px" src="_media/assets/images/logos/home.png">
<img height="200px" src="_media/assets/images/logos/logout.png">
<img height="200px" src="_media/assets/images/logos/ajuda.png">
<img height="200px" src="_media/assets/images/logos/salvar.jpg">
<img height="200px" src="_media/assets/images/logos/calendario.png">

## Opções de Acessibilidade

* Haverá a opção de alto contraste para facilitar a leitura de pessoas com problemas de visão.
* Não haverá informações destacadas apenas por cores para facilitar para pessoas com dificuldade em diferencias as cores.
* Haverá a opção de aumentar o tamanho da fonte para pessoas com problemas de visão.

## Layout

<p>O layout do site é definido por:</p>
<img src="_media/assets/images/logos/layout.png">


## Referências Bibliográficas

[1] Resumo da vida de Matthew Carter. Disponível em: http://tipografos.net/designers/mathew-carter.html. Acessado em 26 de setembro de 2020.

[2] Descrição da fonte Verdana. Disponível em: https://pt.wikipedia.org/wiki/Verdana. Acessado em 26 de setembro de 2020.
