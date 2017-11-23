---
layout: post
title:  "Tutorial Post"
date:   2017-11-23 15:04:51 -0200
authors: [FelipeDeAngelis]
tags: [Tutorial, Post, Site]
---

O presente tutorial tem por objetivo apresentar o passo a passo para se colocar um artigo no site do UIoT.

<b>Parte feita no GitHub</b>

1- Acesse o GitHub no repositório do UIoT e faça um Fork. Acesse o Fork feito e clone o repositório. (O Fork ficara com a cara mais ou menos assim: IDGitHub/uiot.github.io)

![image-title-here](/assets/img/fork.png){:class="img-responsive"}

2- Para clonar repositório é preciso copiar o link que se encontra em Clone or Download.

![image-title-here](/assets/img/clone.png){:class="img-responsive"}

<b>Parte feita no computador local</b>

3- Após copiar o Link, abra o terminal e execute o comando git clone “Link Copiado”, com isso o repositório já será clonado.

![image-title-here](/assets/img/git_clone.png){:class="img-responsive"}

a) É preciso tem o Git instalado, caso não tenha execute o comando sudo apt-get install git.

4- Crie uma Branch para git checkout –b “Nome da Branch”.

![image-title-here](/assets/img/git_branch.png){:class="img-responsive"}

5- Para entrar na Branch criada, utilize o comando git branch “Nome da Branch”.

a) Para verificar a Branch que está, utilize o comando "git branch".

6- Após clonar o repositório é preciso entrar no arquivo clonado para o computador e executar o server com o comando: "bundle exec jekyll server".

![image-title-here](/assets/img/server.png){:class="img-responsive"}

a) Se precisar o GitHub do UIoT temos as explicações de como se instalar os requisitos necessários para se rodar o server.

<b>Parte feita no código</b>

7- Abra o codigo no editor de sua preferencia.

8- Abra a pasta '_post' e crie um arquivo que será o artigo que você irá postar no site, para isso, clique com o botão direito do mouse na pasta '_post' -> 'New' -> 'File'.

![image-title-here](/assets/img/add.png){:class="img-responsive"}

a) O nome do arquivo seguirá o seguinte padrão: “aaaa/mm/dd-Nome-do-artigo.md”

9- Colocar as seguintes informações:

a) layout: post (usar esse layout: post como padrão)

b) title:  "Tutorial Post" (Titulo do post)

c) date:   2017-11-23 15:04:51 -0200 (colocar data e hora)

d) authors: [User Github] (colocar autor)

e) tags: [Tags, Tag] (colocar as tags)

![image-title-here](/assets/img/cabecalho.png){:class="img-responsive"}

10-  Escrever o conteúdo do Post da maneira mostrada na foto.

![image-title-here](/assets/img/paragrafo.png){:class="img-responsive"}

a) Para colocar uma imagem, seguir os seguintes passos:

(i) devemos colocar a imagem na pasta "/assets/img/"

![image-title-here](/assets/img/img.png){:class="img-responsive"}

(ii) inserir imagem:

![image-title-here](/assets/img/imagem.png){:class="img-responsive"}

11- Despois das modificações feitas e salvas, acesse o link: http://localhost:4000/blog/ , com esse link é possível você verificar o post criado e como está ficando.

![image-title-here](/assets/img/localhost.png){:class="img-responsive"}

![image-title-here](/assets/img/codigo.png){:class="img-responsive"}

<b>Parte feita no computador local</b>

12- Após fazer todas as modificações, desligue o servido apertando ctrl-c.

![image-title-here](/assets/img/ctrl-c.png){:class="img-responsive"}

13- Com o comando “git status” é possível verificar as pastas que foram modificadas. Caso esteja com a letra na cor verde, já estão selecionadas para subir para o Github. Caso esteja da cor vermelha, ainda não estão e é preciso dar o comando “git add Nome_Do_Arquivo”, com isso o arquivo será selecionado.

![image-title-here](/assets/img/git_status.png){:class="img-responsive"}

a) Importante estar na repositorio que sera colocado no GitHub.

b) Apenas colocar no Github repositorios que você tenha certeza que modificou e estao certos para subir para o site.

14- Após arquivos selecionados, precisamos dar o comando “git pull”.

15- Por fim, usar o comando ‘git commit -m “Mensagem sobre o que foi feito!”’

<b>Parte feita no GitHub</b>

16- De o Pull request, indique a branch que você gostaria de mandar e a branch que você criou para fazer o post, escreva a mensagem e View Pull Request.

![image-title-here](/assets/img/pull_request.png){:class="img-responsive"}

<b>Caso você já tenha clonado do Git</b>

-Entre no repositorio clonado e de o comando “git push” para verificar atualizações.

<b>Caso seu Fork esteja desatualizado faça o seguinte:</b>

- Entre no repositorio pelo terminal e dê o comando "gedit .git/config".

![image-title-here](/assets/img/branch.png){:class="img-responsive"}

- Veja qual a Branch atualizada e de o comando para atualizar a sua "git pull Branch_atualizada Sua_Branch"

![image-title-here](/assets/img/comando_branch.png){:class="img-responsive"}