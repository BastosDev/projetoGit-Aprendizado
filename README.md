# Meu Projeto
Este é meu primeiro projeto usando Git!


### ----- Resumo -----


# Curso Digital: Git
-Registro de mudanças em arquivos, que possibilita recuperar ou acesso a versões anteriores.\
-Desenvolvimneto de código em colaboração com outros integrantes.
## o que é git?
Snapshots do estado do projeto\
-git cmd\
-git desktop\
-git vscode
## Comandos
-git clone http #clone repositorio\
-git init #inicia o git\é possível abrir o git pela pasta tambem
-git status # status do projeto # Git status\  

    -Os status do git são divididos em(use {git status} para verificar):
        -Unmodified{ja mapeado e jogado na area do Stage}
        -Modified{quando é modificado}
        -Staged{area antes de dar commit no projeto}
            -git add {file} -- para adicionar o arquivo na area de Staged e dar commit/registrar
        -Untracker {quando é adicionado um novo arquivo externo}

-git diff # mostra as linhas que foram modificadas no projeto\
-git diff --staged #arquivos modificados no staged\
-git commit -m "add new title"\
-git log #lista ultimos commits\
-git restore  File #Retornar modificacoes no arquivo\
-git restore --staged File #Retornar um arquivo do staged antes do commit\

    -apos usar o {git restore --stage file} usamos o {git restore file} para que seja retornado o comando
    
-git push\
-git pull\
-git fetch\
-git diff origin/branch\
-git branch new_name
-git log --oneline --decorate
-git config --global user.name "{name}"
-git config --global user.email {email}