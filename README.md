#<strong>BEM VINDO PROGRAMADOR(A)!</strong>#

Use esse README para tirar dúvidas sobre todos os comandos e funcionalidades do GIT e GITHUB. Fique a vontade para enviar contribuições para a comunidade.

README criado a partir das explicações do Professor Prieto (https://github.com/pietromartinso). Acesse a playlist para ter o conteúdo completo: https://youtube.com/playlist?list=PLpaKFn4Q4GMOhOuffvi7VagNib0P325AV

###<strong>ESTRUTURA</strong>###
1 - DICIONÁRIO DE TERMOS
2 - COMANDOS DO TERMINAL
3 - COMO FAZER (TUTORIAL)

--------------------------------------------------
<em>PS.: Para facilitar o acesso a informação, favor contribuir como se estivesse explicando para alguem do absoluto zero. Simplificar termos técnicos ao ponto que qualquer pessoa possa entender sem ter muitos questionamentos. Esse é o desafio! Que comecem os jogos.</em>
--------------------------------------------------

##1 - DICIONÁRIO DE TERMOS##
commit - 
deploy - 
VSCode - 

----------
##2 - COMANDOS DO TERMINAL##
###WINDOWS###
/exit - sai do terminal
/.cd - volta para a pasta anterior
/..cd - volta duas pastas anteriores
/cls - limpa a tela
/dir - Mostra os arquivos da pasta
/help - mostra alguns dos comandos disponiveis no terminal 

###MAC###

###LINUX###

----------
##3 - COMO FAZER (TUTORIAL)##
###ENVIANDO ESTE ARQUIVO (README.MD) PARA O GITHUB PELO VSCODE###
    1 - No GITHUB, Criar novo repositório (nome, privado ou público, etc);
    2 - Criar no computador a pasta que será enviada para o GITHUB;
    3 - Abrir a pasta criada no VSCode
    4 - Criar no VSCode o arquivo ou demais pastas que serão enviadas para o GITHUB (crie um arquivo README.MD, por exemplo)
    5 - Abrir o terminal pelo VSCode (verificar se iniciou diretamente na pasta criada)
    6 - Digitar os seguintes comandos no terminal, dando enter ao final para confirmar:
        git init                             -> Cria a pasta .git na sua pasta criada
        git status                           -> Verifica se os arquivos adicionados, enviados, modificados, etc (use em qualquer momento)
        cls                                  -> limpa a tela do terminal (use em qualquer momento)
        git add nome-do-seu-arquivo          -> Adiciona o arquivo/pasta à fila para envio
        git commit -m "Sua mensagem aqui"    -> Confirma as modificações/exclusões feitas
        git config --global user.name "seu-nome-de-usuário-no-github"   ->Digitar SOMENTE se o VSCode não estiver configurado
        git config --global user.email "seu-email-no-github"            ->Digitar SOMENTE se o VSCode não estiver configurado
        git log                              -> Verifica os commits feitos
        git branch                           -> Verificar nome da branch (estrutura da pasta)
        git branch -M main                   -> Modifica nome da branch (estrutura da pasta)
        cls                                  -> limpa a tela do terminal (use em qualquer momento)
    7 - No GITHUB, copie o código git remote add origin https://github.com/seu-nome-de-usuario/nome-da-sua-pasta e cole no terminal
    8 - Digite no terminal para enviar seu commit para seu repositório GITHUB:
        git push -u origin main     -> Caso seja o primeiro envio
        git push    -> Caso já tenha feito o envio
    9 - Atualize sua página no GITHUB (pressione F5 no teclado, por exemplo)
    10 - Ao realizar novas alterações neste repositório, repita os comandos:
        git status 
        git add .
        git commit -m "Sua mensagem aqui"
        git push
    
    PS.: Consulte a playlist no começo do README e os demais tutoriais para aprender atalhos e novos comandos.

----------


