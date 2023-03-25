<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

# Tema da Aula

Turma Online 22 - B3 | Back-end | Semana 1 | 2023 | Professora Thiele Nunes

### Instruções
Antes de começar, vamos organizar nosso setup.
* Fork esse repositório 
* Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)
* Entre na pasta do seu repositório (Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`)

### Resumo
O que veremos na aula de hoje?
* [Tema1](#tema1) O que é versionamento de código? Introdução a git/github, conceitos e introdução.
* [Tema2](#tema2) Comandos básicos no terminal usando o GitBash e configurações de autoria no git
* [Tema3](#tema3) Controle de versão e projeto em sala chamado: Perfil da aluna
* [Tema4](#tema4) Meu primeiro commit!

*Finalizaremos com um momento de dúvidas e introdução ao projeto para casa


## Conteúdo
### Tema1 
1. [Tópico 1](#topico1) O que é  versionamento de código?
2. [Tópico 2](#topico2) GIT/GITHUB
### Tema2 
1. [Tópico 3](#topico3) GitBash - primeiros comandos no terminal!
   * [Subtópico 1](#subtopico1) Iniciaremos aprendendo a verificar o caminho onde se encontra, listar o que tem nesse lugar, criar uma nova pasta, navegar pela pasta, criar um arquivo dentro desta pasta, deletar o arquivo e deletar a pasta.
   * [Subtópico 2](#subtopico2) Configuração de autoria no Git 
   
### Tema3
1. [Tópico 4](#topico4) Controle de versão e projeto pratico em aula.

### Tema4
1. [Tópico 5](#topico5) Meu primeiro COMMIT! Como usar o GitHub

<img width="500" alt="Captura de Tela 2023-03-23 às 13 17 57" src="https://user-images.githubusercontent.com/91084243/227267875-ce5d9cd7-e179-4654-b114-909b1b7af927.png">


### Tema1 

#### Topico1

Construir um software ou desenvolver um projeto é também similar a uma linha de montagem: cada peça por vez. Como são processos que envolvem sequências lógicas, é normal que um produto passe por várias versões antes de chegar à forma final, terminada e pronta para uso. Por isso, falamos em versionamento.

O versionamento consiste em estratégias para gerenciar as diferentes versões de um código, de um sistema ou de um modelo. É uma forma de administrar as mudanças que são feitas e de garantir mais segurança na transição de uma versão para outra. 

O versionamento oferece um controle importante para garantir segurança e precisão nos sistemas!


 #### Topico2
 
  Git e Github são utilizados no dia a dia das pessoas que criam software como uma forma fácil de gerenciar o código fonte da aplicação, do sistema, do produto. O Git é um sistema de versionamento que protege os projetos. Um Sistema de Controle de Versão Distribuído que evita que alterações realizadas em um projeto modifiquem o código-fonte. Ja o Github é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. 

O Github vai facilitar o uso do Git, escondendo alguns detalhes mais complicados de setup. É lá que você provavelmente vai ter seu repositório e usar no dia a dia!

 #### Mas o que é ?
<img width="400" alt="Captura de Tela 2023-03-23 às 13 26 41" src="https://user-images.githubusercontent.com/91084243/227270328-3d868974-5bcc-4af8-9af8-4eb7a7cb3c19.png">

  Git é um sistema de controle de versões, criado pelo mesmo desenvolvedor do linux(Linus Torvalds), usado principalmente no desenvolvimento de software para versionar código e registrar o histórico de edições dos arquivos.

  Com ele conseguimos desenvolver projetos colaborativos, no qual muitas pessoas podem trabalhar simultaneamente no mesmo código, adicionando e removendo conteúdos e novos arquivos. Também podemos consultar o histórico do que e quando foi modificado e até restaurar versões anteriores. 

 Para fazer uma comparação com ferramentas que já utilizamos no dia a dia, ele é muito semelhante ao Google Drive/Docs, onde muitas pessoas podem editar arquivos e editar documentos.

**Vantagens**:
 - **Trabalho em equipe**: Diversos desenvolvedores trabalhando no mesmo projeto sem perder o que cada um fez
 - **Organização**: O Git cria uma timeline com todas as modificações contendo detalhado que arquivos foram modificados de versão para versão
 - **Segurança**: Temos nosso repositório online e também conseguimos restaurar versões anteriores caso alguma coisa dê problema.

 #### Instalação
  - Para Linux/Unix: https://git-scm.com/download/linux
  - Para Mac: https://git-scm.com/download/mac
  - Para Windows: https://git-scm.com/download/win
<img width="500" alt="Captura de Tela 2023-03-23 às 13 28 10" src="https://user-images.githubusercontent.com/91084243/227270686-110a9995-8491-4b14-9b4f-d5b58f55ece0.png">



### Tema2
#### Topico3
* [Subtópico 1](#subtopico1) Primeiros comandos no terminal
<img width="300" alt="Captura de Tela 2023-03-23 às 13 04 02" src="https://user-images.githubusercontent.com/91084243/227263838-325ec61f-0c54-4485-a02b-bb501e8a398c.png">

* [Subtópico 2](#Subtopico2) Configuração de autoria no git

<img width="400" alt="Captura de Tela 2023-03-23 às 13 03 35" src="https://user-images.githubusercontent.com/91084243/227263703-c7b18fe8-9e1a-44d2-b49c-3bbec43d982b.png">

#### Git Bash
<img width="300" alt="Captura de Tela 2023-03-23 às 13 30 14" src="https://user-images.githubusercontent.com/91084243/227271222-b97ab44a-e26e-49b0-9a03-01865e5d7785.png">

  É um software para utilizar as linhas de comando do Git além de alguns comandos Unix, necessário principalmente no Windows, já que inicialmente o Git foi desenvolvido para o Linux.

### Linha de comando 
* [O que é ?](#o-que-é-linha-de-comando-?)
* [Comandos básicos](#comandos-básicos-do-terminal)

#### O que é linha de comando ?
<img width="300" alt="Captura de Tela 2023-03-23 às 13 30 43" src="https://user-images.githubusercontent.com/91084243/227271366-e85485e1-0c60-40a3-8760-c6475afde74b.png">

  É aquela tela preta que aparece nos filmes, normalmente com alguém hackeando algum sistema. Mexer com o terminal assusta um pouco porque ele não é nem um pouco visual. Mas é muito simples mexer nele. Sabe quando a gente arrasta arquivos para uma pasta ou cria uma pasta nova? No terminal você faz tudo isso também, mas sem interface gráfica. A gente insere comandos, e ele executa.
  
  Na linha de comando você controla melhor o que está rolando com o seu computador - inclusive o versionamento. O git é sempre usado através de linha de comando. (Existem outras ferramentas visuais para uso do Git, mas é importante saber se virar pela linha de comando no dia-a-dia)


```
ls - Listar (ele traz uma lista de tudo o que está naquela pasta - documentos, outras pastas, etc)
pwd - Present working directory (onde estou?) Ele traz todo o caminho onde você está (em que pasta e onde essa pasta fica)
mkdir nome-da-pasta - cria uma pasta
cd - change directory (use para se locomover entre as pastas)
cd ~ - volta para a pasta raiz
cd .. - volta uma pasta
cd nome-da-pasta - para entrar em uma pasta específica (você precisa conseguir enxergar ela quando listar os arquivos)
rm arquivo - remove, deleta um arquivo.
rm -f ou rm --recursive pasta: deleta uma pasta
whoami - "quem sou eu?" identifica o usuário que está mexendo no sistema.
```

#### Github
GitHub é uma plataforma de hospedagem de código-fonte com controle de versão usando o Git. Ele permite que programadores ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. É a partir dele que hospedaremos nosso repositório local para um online.
GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com projetos.

Vamos nos cadastrar para conseguirmos subir nossos códigos para um repositório online.

Após o cadastro configuraremos nosso usuário no gitbash para definir a autoria das nossas modificações:
Para adicionar usuário:

```
git config --global user.name "NOME USUARIO"
git config --global user.email “nomeusuario@hotmail.com” 
```

```
git config --list
```

Para remover usuário:

```
git config --global --unset user.name "NOME USUARIO"
git config --global --unset user.email “nomeusuario@hotmail.com” 
```

### Tema3
#### Topico4
O controle de versão, também conhecido como controle de fonte, é a prática de rastrear e gerenciar as alterações em um código de software. Os sistemas de controle de versão são ferramentas de software que ajudam as equipes de software a gerenciar as alterações ao código-fonte ao longo do tempo.

<img width="500" alt="Captura de Tela 2023-03-23 às 13 01 49" src="https://user-images.githubusercontent.com/91084243/227263202-963bd960-0b70-4ed6-90b9-0217dabd03f5.png">
<img width="500" alt="Captura de Tela 2023-03-23 às 13 02 01" src="https://user-images.githubusercontent.com/91084243/227263257-df379b68-42c1-4630-ac07-c725e6ac97f9.png">
<img width="500" alt="Captura de Tela 2023-03-23 às 13 02 12" src="https://user-images.githubusercontent.com/91084243/227263310-07c248e5-1e49-4ac6-870f-321658dbfc37.png">





### Tema4
#### Topico5
#### Começando com o Git

Algumas palavras novas que vamos usar com o Git/GitHub

* Repositório: É um espaço digital aonde o seu projeto vai ser salvo. No seu computador ele é a pasta aonde o seu projeto está salvo.

* Controle de versão: É a proposta básica do Git, um histórico de tudo o que aconteceu com o(s) arquivo(s) que você está trabalhando. Por exemplo, quando você salva um arquivo do Word no seu computador, você perde todas as versões anteriores, ficando somente com o conteúdo atual. Com o Git você tem todas as versões antigas dos arquivos.

* Commit: Quando você faz um commit com o Git, você está criando um controle de versão (histórico) daquele arquivo e criando uma etiqueta para facilitar o entendimento do que foi salvo naquele momento.

* Pull: O pull serve para se comunicar entre a sua máquina e o repositório remoto. Esse comando faz uma cópia do repositório remoto e baixa ele para a sua máquina.

* Push: O push também serve para se comunicar entre a sua máquina e o repositório remoto. Esse comando faz uma cópia do repositório local e envia ele para o repositório remoto.

* Clone: O comando clone faz exatamente o que ele sugere: uma cópia exata do arquivo, que você vai baixar do repositório remoto para a sua máquina.

***
### Fluxo do git
<img width="600" alt="Captura de Tela 2023-03-23 às 13 40 23" src="https://user-images.githubusercontent.com/91084243/227273860-e6ab780e-a78d-410c-b671-d581e066cab0.png">

Tudo isso está acontecendo apenas localmente no seu computador!

Cada etiqueta vai gerando um ponto na nossa timeline. Essa etiqueta se chama commit, e com essa pequena descrição fica mais fácil se achar entre as versões.

<img width="600" alt="Captura de Tela 2023-03-23 às 13 40 52" src="https://user-images.githubusercontent.com/91084243/227273992-8b4d8445-917a-4645-8d4a-57ab2e57f4db.png">

***

### Pull request

Quando você faz um fork de um projeto, ou quando você trabalha em uma empresa com mais desenvolvedores, é normal que as demais pessoas envolvidas no projeto façam um review do seu código antes de ele ir pro main, afinal você pode ter cometido algum erro no desenvolvimento, ou alguma parte do seu código pode ser melhorada.

Um pull request é quando você quer fazer merge do seu código em outro branch, mas você precisa da autorização das outras pessoas envolvidas no projeto.

***


***
### Exercícios 
* [Exercicio para sala](https://github.com/reprograma/-on23-b3-s1-git-github/blob/main/exercicios/para-sala/README.md)
* [Exercicio para casa](https://github.com/reprograma/-on23-b3-s1-git-github/tree/main/exercicios/para-casa)

### Material da aula 

### Links Úteis
Esse conteúdo foi feito com referência e cópia nos seguintes materiais:
 - [Turma Online 1 - Github](https://github.com/reprograma/CursoOnline-Aula3-Git-and-Github)
 - [Turma Online 2 - Github](https://github.com/reprograma/On2-git-e-github)
 - [Turma Online 3 - Github](https://github.com/reprograma/On3-git-e-github)
 - [Turma Online 4 - Github](https://github.com/reprograma/On4-git-e-github)
 - [Turma Online 5 - Github](https://github.com/reprograma/On5-git-e-github)
 - [Turma 6 - Github](https://github.com/reprograma/github)
 - [Ramificação git](https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-O-que-%C3%A9-um-Branch)

<p align="center">
Desenvolvido com :purple_heart:  
</p>

