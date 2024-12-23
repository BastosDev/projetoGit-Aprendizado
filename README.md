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
-git commit -m "add new {modification}"\
-git log #lista ultimos commits\
-git restore  File #Retornar modificacoes no arquivo\
-git restore --staged File #Retornar um arquivo do staged antes do commit\

    -apos usar o {git restore --stage file} usamos o {git restore file} para que seja retornado o comando
    
-git push\

    -manda para o rep(tem como alternativa o github desktop)

-git pull\

    -da um merge com o repositorio remoto{o do site do github}

-git fetch\

    -pega as alterações do rep remoto antes de passar pro local

-git diff origin/branch\

    -mostra as alterações do git fetch

-git branch new_name

    -cria um novo local para codigo independente(como se fosse um segundo repositorio)
    -permite ramificação de codigos

-git log --oneline --decorate

    -mostra em que branch estamos

-git checkout {new_name}

    -nos permite transitar entre o branchs

-git merge {branch_name}

    -da merge de duas branchs
    -junta os dois arquivos, podendo sobrepor outros codigos

-git config --global user.name "{name}"\

-git config --global user.email {email}\