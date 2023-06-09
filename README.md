<!-- Icones dos países. Ao clicar, direciona para nova página ou para o ponto em que a nova linguagem começa
:us:
:es:
:fr:
:it:
:jp: -->
:brazil:
# BEM VINDO PROGRAMADOR(A)!

Use esse `README.md` para tirar dúvidas sobre todos os comandos e funcionalidades do GIT e GITHUB. Fique a vontade para enviar contribuições para a comunidade.
<br>
<hr>

##### README criado a partir das explicações do [Professor Pietro](https://github.com/pietromartinso). Acesse a [playlist](https://youtube.com/playlist?list=PLpaKFn4Q4GMOhOuffvi7VagNib0P325AV) para ver o conteúdo completo.
<hr>

> Programadores, para facilitar o acesso a informação, favor contribuir como se estivesse explicando para alguém do absoluto zero. Simplificar termos técnicos ao ponto que qualquer pessoa possa entender sem ter muitos questionamentos. Esse é o desafio! **Que comecem os jogos**.
<br>

## ESTRUTURA

1.  **DICIONÁRIO DE TERMOS** <!-- Aqui você encontrará uma lista com os principais termos usados durante o uso do GIT e GITHUB e suas respectivas definições.-->
2.  **COMANDOS DO TERMINAL** <!-- Aqui você verá os principais comandos para ajudar você a navegar pelo terminal. --> 
3.  **COMO FAZER (TUTORIAL)** <!-- Aqui você verá exemplos práticos de como executar vários comandos no GIT e no GITHUB. -->

<hr>

### 1. DICIONÁRIO DE TERMOS

TERMO | EXPLICAÇÃO |
:---------- | :------------------------------
*commit* | teste
*deploy* | teste
*VSCode* | teste

<hr>
<h3>2. COMANDOS DO TERMINAL</h3>

**GIT**
COMANDO | EXPLICAÇÃO
:---------- | :------------------------------ 
`git init` | Cria a pasta oculta `.git` dentro da pasta criada
`git status` | Verifica se os arquivos adicionados, enviados, modificados, etc (use em qualquer momento)
`git add` nome-do-seu-arquivo | Adiciona o arquivo/pasta nomeado à fila para envio
`git add .` | Adiciona todos os arquivos/pastas à fila para envio
`git commit -m "Sua mensagem aqui"` | Confirma as modificações/exclusões feitas e adiciona uma mensagem de identificação
`git config --global user.name "seu-nome-de-usuário-no-github"` | Comando usado para vincular seu nome de usuário no GITHUB ao VSCode. Geralmente feito no envio do primeiro repositório
`git config --global user.email "seu-email-no-github"` | Comando usado para vincular seu e-mail no GITHUB ao VSCode. Geralmente feito no envio do primeiro repositório
`git log` | Mostra os registros de *commits* feitos antes do `push` 
`git branch` | Mostra o nome principal da `branch`
`git branch -M main` | Modifica o nome da `branch`
`git push -u origin main` | Usado somente nos envios dos primeiros `commit` de cada repositório para o GITHUB
`git push` | Faz o envio das alterações `commit` para o GITHUB
`em breve` | Em breve

<br>

**WINDOWS**
COMANDO | EXPLICAÇÃO
:---------- | :------------------------------ 
`/exit` | Fecha o terminal
`/.cd` | Volta para a pasta anterior
`/..cd` | Volta duas pastas anteriores
`/cls` | Limpa a tela do terminal
`/dir` | Mostra todos os arquivos da pasta
`/help` | Mostra alguns dos comandos disponiveis no terminal 
`/em breve` | Em breve
<br>

**MAC**
COMANDO | EXPLICAÇÃO
:---------- | :------------------------------ 
`/em breve` | Em breve
<br>

**LINUX**
COMANDO | EXPLICAÇÃO
:---------- | :------------------------------ 
`/em breve` | Em breve

<hr>

### 3. COMO FAZER (TUTORIAL)

**INSTALANDO E CONFIGURANDO VSCODE, GIT E GITHUB**

Em breve.

**ENVIANDO ESTE ARQUIVO (README.MD) PARA O GITHUB PELO VSCODE**

1.  No GITHUB, criar novo repositório (nome, privado ou público, etc);
2.  Criar no computador a pasta que será enviada para o GITHUB;
3.  Abrir a pasta criada no VSCode;
4.  Criar no VSCode o arquivo ou demais pastas que serão enviadas para o GITHUB (crie um arquivo README.MD, por exemplo);
5.  Abrir o terminal pelo VSCode (verificar se iniciou diretamente na pasta criada);
6.  Digitar os seguintes comandos no terminal, dando enter ao final para confirmar: <br>
   \ `git init`<br>
   \ `git status`<br>
   \ `git add nome-do-seu-arquivo`<br>
   \ `git commit -m "Sua mensagem aqui"`<br>
   \ `git config --global user.name "seu-nome-de-usuário-no-github"`<br>
   \ `git config --global user.email "seu-email-no-github"`<br>
   \ `git log`<br>
   \ `git branch`<br>
   \ `git branch -M main`<br>
7.  No GITHUB, copie o código e cole no terminal do VSCode:
   \ `git remote add origin 'https://github.com/seu-nome-de-usuario/nome-da-sua-pasta'`  
8.  Digite no terminal para enviar seu `commit` para seu repositório GITHUB:<br>
   \ `git push -u origin main`<br>
   \ `git push`
9.  Atualize sua página no GITHUB (pressione `F5` no teclado, por exemplo)
10. Ao realizar novas alterações neste repositório, repita os comandos: <br>
   \ `git status`<br> 
   \ `git add .`<br>
   \ `git commit -m "Sua mensagem aqui"`<br>
   \ `git push`<br>

<hr>
<br>

> Obrigado por acompanhar. Considere apoiar adicionando novos conteúdos ao material. Consulte a playlist no começo do README e os demais tutoriais para aprender atalhos e novos comandos e recursos relacionados ao GIT e GITHUB.