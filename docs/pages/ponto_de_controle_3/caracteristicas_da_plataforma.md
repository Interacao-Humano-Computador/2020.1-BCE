# Características da plataforma

## Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 25.09.2020 |  0.1   | Criação do documento de características da plataforma | João Victor  |
| 28.09.2020 |  0.2   | Modificação nos objetivos do documento | Durval Carvalho  |
| 28.09.2020 |  0.3   | Remoção dos tópicos disconexos do documento | Durval Carvalho |
| 02.10.2020 |  0.4   | Adição de conteudo | João Victor |
| 05.10.2020 |  0.5   | Modificações nos tópicos: Introdução, Objetivos | Durval Carvalho |
| 05.10.2020 |  0.6   | Adição do tópicos: Características das Plataformas | Durval Carvalho |
| 05.10.2020 |  0.7   | Adição do tópicos: Conclusão | Durval Carvalho |


<div align="justify">

## 1. Introdução

A análise das capacidades e restrições da plataforma é um das tarefas propostas pelo ciclo de vida de Mayhew, onde será examinado as possibilidades e restrições em termos de equipamentos, sistemas operacionais, ambientes gráficos, recursos de rede e outras peculiares da plataforma onde o sistema irá ser instalado e utilizado.

## 2. Objetivos

Esse documento visa identificar e detalhar as características da plataforma onde será consumida e/ou disponibilizada o sistema de empréstimo de obras da BCE. Uma vez compreendido suas características, será possível produzir um design personalizado que leva em consideração características peculiares de cada plataforma, como por exemplo tamanho de tela, capacidade média de processamento, memória disponível etc.

## 3. Características das Plataformas

Ao projetar uma interface de usuário, você deve entender como a interface irá se comportar na plataforma onde será utilizada, ainda mais quando o sistema pode ser utilizado em mais de uma plataforma, como é o nosso caso. Se o sistema irá funcionar em várias plataformas diferentes, como o Google Chrome, Firefox e Internet Explorer, o design deve estar ciente das diferenças e semelhanças, para assim desenvolver um design que funcione em todas elas sem impor restrições.

O sistema da BCE é um sistema projetado para utilização através de navegadores, depedente de internet e desenvolvido com tecnologias web como HTML, JavaScript e CSS. Ou seja, o sistema da BCE é uma aplicação Web. O sistema pode ser disponibilizado através de um servidor HTTP ou por uma rede local.

### 3.1. Vantagens e Desvantagens de Aplicações Web

Durante muito tempo as aplicações desktop supriram todas as necessidades dos usuários de software nas mais diversas áreas. Porém, nos últimos anos o desenvolvimento web tem crescido vertiginosamente. Sistemas web possui um conjunto de particularidades que podem ser vistas como vantajosas ou desvantajosas, depedente da situação. [1]

#### 3.1.1. Segurança de Dados

Em geral, aplicações web tendem a ser um pouco mais seguras para o usuário, em relação a segurança de dados, devido a limitação de funcionar na plataforma do navegador. Essa limitação, impossibilita que uma aplicação maliciosa tente acessar dados do computador do usuário, pois existe um navegador intermediando a aplicação e o computador do usuário. [1]

Porém, essa características também pode interferir na usabilidade do sistema, pois o sistema necessariamente precisa pedir autorização do usuário em toda interação com os dados do computador. [1]

#### 3.1.2. Confiabilidade do sistema

Confiabilidade é um termo definido na ISO/IEC 25010 que define as condições de funcionamento de um sistema sob condições determinadas em um dado perído de tempo, de forma confiável, controlando e revertendo situação de erros no sistema. [2]

Com a definição desse termo em mente, pode-se dizer que sistemas web geralmente são menos confiáveis do que sistemas desktop, pois seu bom funcionamento depende de mais variáveis como: versão do navegador utilizado, estabilidade de rede, presença de plugins de navegadores que interferem no sistema etc. [1]

Os desenvolvedores de sistemas web tem muito pouco ou nenhum controle sobre a plataforma que os usuários iram consumir a aplicação. Essa características faz com que frequentemente surja problemas na utilização do sistema em cenários imprevistos, como o uso em um navegador não testado pelos desenvolvedores (tipo o [Opera](https://www.opera.com/pt-br)). [1]

Uma tendência comum que se vem sendo utilizada por sistemas web complexos é o suporte exclusivo a um grupo exclusivo de navegadores, o Google Chrome por exemplo. Essa abordagem impõe ao usuário a utilização da plataforma definida pelos desenvolvedores, porém maximiza as possibilidades da aplicação, uma vez que o sistema será desenvolvido utilizado recursos específicos da API (Application Programming Interface) do navegador em questão. [1]


#### 3.1.3. Portabilidade

Portabilidade é um termo definido na ISO/IEC 25010 que as condições de funcionamento em diversos cenários de uso. [2]

A utilização de sistemas web frequentemente está associada a sua flexibilidade de uso. Normalmente não é preciso instalar softwares nem configurações prévias dos computador para acessar um sistema web. Essa característica faz com que sua utilização não imponha dificuldades de acesso, bastando acessar o link onde a aplicação está disponível, em qualquer dispositivo que suporte um navegador.

#### 3.1.4. Eficiência de desempenho

Eficiência de desempenho é um termo definido na ISO/IEC 25010 que define o desempenho que um sistema computacional deve apresentar quando disponibilizado sua condição mínima de funcionamento (memória, capacidade, presença de GPU etc.) [2]

Normalmente, aplicações web não executam o processamento pesado no lado do usuário (conexão com banco de dados, processamento de imagem etc.), cabendo ao servidor da aplicação, que geralmente são máquinas com maior capacidade computacional a responsabilidade de processamento presado.

Essa característica faz com que os usuários não precisem de hardware de alto desempenho para utilizar serviços que demandem alto desempenho de hardware. Essa centralização do processamento de dados no lado do servidor possibilita que o usuário possam utilizar diversos dispositivo como terminal de acesso, somente definindo as operações que deseja realizar.

Com o avanço das tecnologias web, surgiu uma nova categoria de aplicação web, as aplicações do lado do cliente (Clientside). Nesse tipo de aplicação, o servidor logo na primeira interação irá enviar todos os dados necessários para o funcionamento do sistema, desse modo todo processamento que não exige armazenagem e consulta de bancos de dados serão realizados no dispositivo do usuário. Essas aplicações costumam exigir mais do dispositivo que acessa o sistema.

#### 3.1.5. Instalabilidade

Instalabilidade é um termo definido na ISO/IEC 25010 que o sistema deve ser instalado e/ou desistalado de forma eficaz e eficiênte em um determinado ambiente. [2]

Os sistema web precisam ser instalados somente do lado do servidor, removendo a responsabilidade do usuário de instalar e desinstalar a aplicação. Essa mesma característica faz com que todos os usuários utilizem a mesma versão do sistema, diminuindo assim as dificuldades de gerenciamento de configuração de software.


### 3.2. Navegadores Suportados

Na pesquisa de mercado realizada pelo site Statcounter referente ao mês de outubro de 2020, foi identificado que o navegador mais utilizado é o Google Chrome com 82.15% do mercado. Seguido pelo navegador Safari com 5.49%. Fica evidente que caso o designer precise escolher somente um dos navegadores para dar suporte, o Google Chrome deve ser escolhido.

<p align='center'>
    <img src='_media/assets/images/print_screen/market-share-browser.png'>
    <figcaption align='center'>
        <b>Figura 1: Composição do mercado de navegadores</b>
        <br>
        Fonte: Site da Statcounter
    </figcaption>
</p>

Nessa mesma pesquisa é apresentado a composição do mercado de acordo com a versão dos navegadores utilizado. É importante conhecer essas versões devido o fato de que os navegadores mais antigos não suportam as novas versões das tecnologias web comumente usadas em sistemas web (novas tags de HTML, novos recursos da API do JavaScript, novas maneiras de estilização do CSS). Como pode ser visto na figura abaixo, a o Google Chrome 85.0 é a versão mais utilizada do navegador com 56.6%, seguido pelo Chrome for Android (versão 85.0) com 22.13%, seguido pelo Safari Iphone (versão 13.1) com 3.76%.

<p align='center'>
    <img src='_media/assets/images/print_screen/market-share-browser-version.png'>
    <figcaption align='center'>
        <b>Figura 2: Composição do mercado de navegadores de acordo com a versão</b>
        <br>
        Fonte: Site da Statcounter
    </figcaption>
</p>

Com essas estatísticas em mente, é possível pressumir que os usuários da nossa aplicação potencialmente irão utilizar esses navegadores nessas versões. Com isso em mente, foi avaliado as APIs dos navegadores mais usados em suas respectivas versões, para identificar quais recursos estavam ou não disponíveis para uso do designer. Os recursos identificados foram:

<p align='center'>
    <img src='_media/assets/images/print_screen/browser-support-1.png'>
    <figcaption align='center'>
        <b>Figura 3: Recursos de tecnologias web (HTML, JS e CSS) suportados pelos navegadores mais utilizados</b>
        <br>
        Fonte: Site Caniuse
    </figcaption>
</p>

<p align='center'>
    <img src='_media/assets/images/print_screen/browser-support-2.png'>
    <figcaption align='center'>
        <b>Figura 4: Recursos de tecnologias web (HTML, JS e CSS) suportados pelos navegadores mais utilizados</b>
        <br>
        Fonte: Site Caniuse
    </figcaption>
</p>

Para uma análise completa de todos os recusos suportados pelo navegadores mais utilizados mostrado na pesquisa, é recomendado o acesso ao [relatório gerado site caniuse](https://caniuse.com/?compare=chrome+85,safari+13.1,and_chr+85&compareCats=all).

### 3.3. Hardware utilizado

Além de conhecer a plataforma de software que o sistema da BCE depende, é preciso conhecer a plataforma de harware. A plataforma de harware faz alusão aos equipamentos físicos presentes no dispositivo utilizado para acessar o sistema. Esses equipamentos informar comportamentos e característica que o design deve conhecer durante a elaboração da interface. Essas característica são tempo de processamento, tamanho da tela, memória disponível etc.

#### 3.3.1. Computadores da Biblioteca

A Comissão Permanente de Aquisição de Recursos de Tecnologias da Informação e Comunicação define um documento chamado "Padronização de Computadores na FUB" onde é defido as característica de hardware dos computadores que são exigidos em editais de aquisição. Os computadores nesses documentos são classifcados de acordo com o seu uso, começando pelo uso mais casual, onde não muito do hardware, até computadores de uso específico, onde é exigido processamentos específicos. Essas classificações são: [5]

* **Microcomputador perfil I**: Computador para usuários que necessitem acesso à internet, utiliza pacotes de escritório, fazem uso de programas convencionais com demanda moderada de processamento, armazenamento e memória. [5]
  
* **Microcomputador perfil II**: Usuários que não são atendidos pelo Microcomputador perfil I e que necessitam de mais armazenamento para manipular informações localmente, bem como programas que demandam mais memória RAM. [5]

* **Microcomputador perfil III**: Usuários que não são atendidos pelo Microcomputador perfil II e que demandam alta capacidade de processamento, de armazenamento e uma quantidade maior de memória RAM. [5]

Referente as peças internas das classificações de computadores podem ser observadas na tabela a seguir: 


<p align='center'>
    <img src='_media/assets/images/print_screen/hardware-comp-bce-pcs.png'>
    <figcaption align='center'>
        <b>Figura 5: Descrição resumida dos componentes dos computadores da FUB</b>
        <br>
        Fonte: Documento de Padronização de Computadores da FUB
    </figcaption>
</p>

Como pode ser observado na figura acima, todos os computadores possuem monitores LED de 21.5 polegadas e contam com teclados no padrão ABNT2. Com base nessas informações, o design poderá definir o layout da aplicação partindo desse tamanho de tela como referencial e poderá definir teclas de atalho de acordo com o teclado presente nos computadores. [5]

<p align='center'>
    <img src='_media/assets/images/print_screen/kb_abtn2.png'>
    <figcaption align='center'>
        <b>Figura 6: Teclas presentes no teclado utilizado nos computadores da FUB</b>
        <br>
        Fonte: Site da TechTudo
    </figcaption>
</p>

#### 3.3.2. Servidores da BCE

Com base no Plano Anual de Contratações (PAC) referente ao ano de 2020, foi observado os servidores adquiridos para hospedagem dos sistemas da FUB tinham as seguintes especificações: [6]
* Processador 4 Xeon Quad Core 2.4 Ghz, Memória Cache L2 - 12mb
* 146 Gb SSD;
* Placa Rede 4 Ethernet Ieee 802.3, 10/100/1000
* Placa Mãe 2 Slots Pci-express X4
* Placa Vídeo Svga De 16 Mb, 
* Memória Ram 32 Gb Ddr2/667, Com 64 Gb Extensão
* Softwares Instalados Windows 2003/2008

Somente com pesquisa bibliográficas, não foi possivel saber se a BCE conta com um servidor exclusivo ou se utiliza um servidor compartilhado com outros sistemas. Para efeitos de comparação, foi escolhido o servidor da DELL PowerEdge 2950 III, que possui as mesmas especificações definidas pelo PAC de 2020 da FUB. [6]

<p align='center'>
    <img src='_media/assets/images/dell-server.png' width='50%'>
    <figcaption align='center'>
        <b>Figura 7: Servidor DELL PowerEdge 2950 III utilizado como comparação</b>
        <br>
        Fonte: Site da DELL
    </figcaption>
</p>

O servidor DELL PowerEdge 2950 III é um servidor de entrada da linha de servidores da DELL. Possui compatibilidade com processadores da linha Intel Xeon®. Possui suporte para diversos sistemas operacionais (Microsoft Windows Server®, Red Hat Linux, SUSE Linux Server, VMWare ESX 3.5® etc.). Possui Hipervisor em hardware e conta com 8 slots de memória. Possui capacidade 4 slots com entrada SAS e 1 com entrada SATA, com capacidade máxima de armazenamento de 1.7 Terabytes. A especificação completa desse servidor pode ser vista no [site da DELL](https://www1.la.dell.com/br/pt/gen/Empresa/pedge_2950_3/pd.aspx?refid=pedge_2950_3&s=gen). [7]


Uma vez que o sistema de empréstimo da BCE foi desenvolvido utilizando o software _Meu Pergamum_, foi analisado as espeficiações mínimas desse software para verificar se as espeficiações do servidor descrito pela PAC de 2020 suportava a aplicação.

No [site da PUCPR](https://www.pergamum.pucpr.br/redepergamum/pergamum_caracteristicas_tecnicas.php?ind=2), organização que mantêm o software _Meu Pergamum_ defini os seguintes requisitos de hardware para instalar o software em sevidores: [8]

* Pré-requisitos: Banco de dados SQL Server ou Banco de dados Oracle Instalados
* Processador: Intel Pentium IV Dual Core 2Ghz
* Armazenamento: 40GB disponíveis
* Memória: 4GB disponíveis
* Sistema Operacional: Windows Server ou Linux

Já para software clientes (plataformas que irão utilizar o sistema web), os seguintes requisitos mínimos são definidos: [8]

* Processador: Intel Pentium IV 3Ghz
* Navegador: Internet Explorer >=10.0, Firefox >=16.0, Chrome >=26.0
* Memória: 2GB

## 4. Conclusão

O serviço de empréstimo da BCE é um sistema web baseado no software _Meu Pergamum_. As especificações mínimas de hardware desse software são atendidas pelos computadores e servidores da BCE, desse modo, caso o designer deseje modificar as estilização do software _Meu Pergamum_ não será gerado impacto no serviço. 

Porém, caso seja necessário desenvolver ou utilizar um novo software para dar suporte ao serviço de empréstimo da BCE, será necessário que os requisitos mínimos de hardware desse novo sistema seja no máximo a capacidade computacional já adquirida pela BCE, não sendo necessário a aquisição de novos componentes.

</div>

## Referências Bibliográficas

- [1] [Quais são as diferenças entre aplicações Web e aplicações Desktop](https://pt.stackoverflow.com/questions/187344/quais-s%C3%A3o-as-diferen%C3%A7as-entre-aplica%C3%A7%C3%A3o-web-e-aplica%C3%A7%C3%A3o-desktop)

- [2] [ISO/IEC 25010:2011](https://www.iso.org/standard/35733.html)
  
- [3] [Análise dos recursos suportados pelos navegadores](https://caniuse.com/?compare=chrome+85,safari+13.1,and_chr+85&compareCats=all)
  
- [4] [Navegadores mais utilzados](https://gs.statcounter.com/browser-version-market-share/all/brazil/#monthly-202010-202010-bar)

- [5] [Especificações dos Computadores da FUB](https://daf.unb.br/index.php?option=com_phocadownload&view=category&download=97:padronizao-de-computadores&id=18:guia-de-compras-grupo-3-equipamentos-e-insumos-de-informatica-cparti&Itemid=763)

- [6] [Plano Anual de Contratações de 2020 da FUB](http://www.daf.unb.br/index.php?option=com_phocadownload&view=category&download=1174:pac-2020-consolidado&id=376:plano-anual-de-contratacoes&Itemid=833)
  
- [7] [Especificação do servidor PowerEdge 2950 III](https://www1.la.dell.com/br/pt/gen/Empresa/pedge_2950_3/pd.aspx?refid=pedge_2950_3&s=gen)
  
- [8] [Requisitos mínimos de hardware do software Meu Pergamum](https://www.pergamum.pucpr.br/redepergamum/pergamum_caracteristicas_tecnicas.php?ind=2)