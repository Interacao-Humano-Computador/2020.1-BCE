# <center>Avaliação Protótipo de Alta Fidelidade - Estática

### Histórico de Versão
| Data       | Versão | Descrição                       | Autor(es)          |
|:----------:|:------:|:-------------------------------:|:------------------:|
| 16.11.2020 | 0.1    | Criação do documento            | Rafaella Junqueira |
| 17.11.2020 | 0.2    |Adição nível AA            | Isabella Carneiro |

<div align="justify">

## 1. Introdução
A utilização de protótipos durante a atividade de design é fundamental para consolidar ideias e corrigir enganos nas etapas iniciais dos projetos. A avaliação do protótipo de alta fidelidade visa identificar e corrigir erros de design e, assim, embasar as tomadas de decisão ao longo do projeto. Este documento consiste na primeira etapa de validação do protótipo de alta fidelidade intitulada etapa estática, onde serão avaliadas as interfaces durante uma experiência de interação com o protótipo.

## 2. Objetivo
O objetivo desta etapa de avaliação é realizar uma inspeção nas telas do protótipo avaliando critérios especificados nas [Diretrizes de Acessibilidade para o Conteúdo da Web (WCAG)](https://guia-wcag.com/). Inspeção é um método de avaliação que permite o avaliador tentar identificar problemas que os usuários podem vir a ter quando interagirem com o sistema. 

Os resultados coletados nesta fase, juntamente com os resultados da [segunda etapa de avaliação](), vão compor as conclusões finais acerca do protótipo de alta fidelidade criado, possibilitando a proposição de melhorias para o design final do site da Biblioteca Central da UnB. 

## 3. Metodologia
Os princípios que serão inspecionados durante esta avaliação estática estão dispostos e detalhados no [planejamento da primeira etapa](/pages/ponto_de_controle_6/plan_aval_prototipo_alta_fidelidade.md) de avaliação do protótipo de alta fidelidade. 

A avaliação da etapa estática é dividida em 3 níveis: A, AA e AAA. Para fim de melhor visualização, foi criado um checklist separado por nível e seus respectivos critérios. O protótipo de alta fidelidade será avaliado de acordo com os pontos definidos em cada nível e, caso o critério seja atendido, será assinalado 🟢; caso não seja atendido, será assinalado 🔴; e caso seja atendido de forma parcial, será assinalado 🟡.

## 4. Avaliação

| <center>Nível A             |   |<center> Nível AA              |   | <center>Nível AAA      |   |
|:----------------------------|:-:|:------------------------------|:-:|:-----------------------|:-:|
| Conteúdo não textual        | 🟢 | Contraste (mínimo)           | 🔴 | Contraste (melhorado) | 🔴 |
| Características sensoriais  | 🟢 | Redimensionar texto          | 🟡 | Teclado (sem exceção) | 🔴 |
| Utilização de cores         | 🟢 | Imagens de texto             | 🟢 | Sem limite de tempo   | 🟢 |
| Três flashes                | 🟢 | Refluxo                      |  | Nova autenticação     | 🟢 |
| Página com título           | 🟢 | Contraste Não-Textual        |  | Limites de tempo      | 🟢 |
| Ordem do foco               | 🟡 | Cabeçalhos e rótulos         |  | Cabeçalhos da seção   | 🟢 |
| Finalidade do link          | 🟢 | Espaçamento da área clicável |  | Palavras incomuns     | 🟢 |
| Cancelamento de acionamento | 🟡 | Controles ocultos            |  | Abreviações           | 🟢 |
| Identificação do erro       | 🟡 | Sugestão de erro             | 🟢 | Pronúncia             | 🟢 |
| Rótulos e instruções        | 🟡 | Mensagens de status          | 🟢 | Ajuda                 | 🟢 |
| Autenticação acessível      | 🟢 |                              |  | Prevenção de erro     | 🟡 |
| Entrada redundante          | 🟢 |                              |  |                       |  |

## 5. Observações
Foram identificados alguns pontos do protótipo que não estão de total acordo com os critérios avaliados, como:
* A funcionalidade para recuperação de senha só é possível ser consultada caso tente-se realizar o login antes de buscar um livro, a funcionalidade não está disponível para utilização no momento em que o usuário tenta se autenticar para reservar um livro; 
* Durante a tentativa de login para realizar a reserva de um livro, não há a opção de cancelar a ação nem de retornar à tela anterior;
* Durante a tentativa de login para realizar a reserva de um livro, caso clicado em "entrar" sem insrção das credenciais, não há mensagem de erro;
* Durante a tentativa de login para realizar a reserva de um livro, a opção "esqueceu sua senha?" não está disponível;
* Quando selecionada a opção "reservar o livro", é direcionado para a página de acesso restrito do usuário e recebido o alerta de "renovação do prazo de devolução", não de reserva de livro. 
* Quando acessado o painel de acesso restrito, não há opção de retornar para a lista de livros que estava sendo buscado;
* Quando acessado o painel de acesso restrito, o retorno para a tela inciail da biblioteca não está claro, dá-se apenas pela logo da UnB;
* Os campos de login não indicam como deve ser o preenchimento (Exemplo: "exemplo@gmail.com", ou "senha de 6 dígitos");
* A tela 41, referente à inserção de senha para o login para a área de acesso restrito, não possui mensagem de erro caso tente-se logar sem inserir a senha;
* A tela 35, referente à recuperação de senha, não apresenta mensagem de erro caso clicado em "enviar link" sem antes inserir o email;
* As telas de 31 a 35 possuem a tecla de voltar em um local que não segue o padrão das outras telas;
* A tela 33, referente à confirmação de link enviado por email, não possui o botão "voltar" habilitado, nem um outro link de retorno para a página de login;
* A tela 32, referente à recuperação de senha, não possui mensagem de erro caso clicado em "confirmar recuperação de senha" sem antes preencher as senhas;
* A tela 19, referente à consulta de livros, não possui a logo da UnB como forma de retorno à página principal; 
* A ordem dos elementos é sequencial e lógica, porém não permite navegação utilizando o teclado;
* As telas de login não possuem opção de contraste nem de redimensionar texto;
* Não foi identificado nenhuma imagem que não possui um texto que explique-a;
* Quando ocorre um erro há uma mensagem explicando e também há mensagem que explica o status se for feita a operação sem erro;



<!-- ### 4.2 Nível AA

| Tela| Contraste (mínimo) |Redimensionar texto | Imagens de texto | Refluxo | Contraste Não-Textual | Cabeçalhos e rótulos | Espaçamento da área clicável | Controles ocultos | Sugestão de erro | Mensagens de status |
:----:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
 **1**  | ✅ | ✅ | ✅ | ? | ? | ? | ? | ? | ✅ | ✅ |
 **2**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **3**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **4**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **5**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **6**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **7**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **8**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **9**  | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **10** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **11** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **12** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **13** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **14** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **15** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **16** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **17** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **18** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **19** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **20** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **21** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **22** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **23** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **24** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **25** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **26** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **27** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **28** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **29** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **30** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **31** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **32** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **33** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **34** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **35** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **36** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **37** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **38** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **39** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **40** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **41** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **42** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **43** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **44** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **45** | ❌ | ❌ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **46** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **47** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **48** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **49** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ |
 **50** | ✅ | ✅ | ✅ |   |   |   |   |   | ✅ | ✅ | -->


## 5. Conclusão
A análise do protótipo nesta primeira etapa da avaliação gerou pontos de observação baseados nos critérios definidos por cada nível das diretrizes de acessibilidade para o conteúdo web (WCAG). Esses pontos serão priorizados e, juntamente com os resultados da segunda etapa da avaliação, referente às entrevistas com usuários, serão adotadas algumas medidas de melhoria para o protótipo existente a fim de validar e consolidar a proposta de design feita pela equipe.

</div>

## Bibliografia
PREECE, J.; ROGERS, Y; SHARP, H. **Design de Interação: Além da interação homem-computador.** John Wiley e Sons. São Paulo - SP. 1ª Edição. Editora Erica, 2005.

BARBOSA, Simone; DINIZ, Bruno. **Interação Humano-Computador**, Editora Elsevier, Rio de Janeiro, 2010.


