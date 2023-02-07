Projeto criado para aprender a utilizar o Git 
----------------------------------------------

Salvando alterações e enviando para o repositório no GitHub:
---------------------------------------------------------------
1º git add . (mandar para stage)
---------------------------------
2º git commit -m "new" (adicionar commit)
------------------------------------------
3º git push origin master (Empurrar para o repositório no GitHub)
------------------------------------------------------------------

Comandos básicos:
-----------------
git version = Verificar a versão do Git (se há erros de instalação);
---------------------------------------------------------------------
git init = Iniciar um novo repositório;
---------------------------------------
clear = limpar o console;
--------------------------
git add. = adicionar todos os arquivos ao stage.
git add +'arquivo.tipo' = Adiciona arquivo expecífico ao stage para fazer commit quando necessário.
----------------------------------------------------------------------------------------------------
git status = verificar mudanças à receber commit.
-------------------------------------------------
git comit -m "mensagem do commit"= Fazer o commit.
--------------------------------------------------
git remote add origin +linkDoRepositório = Adicionar repositório local da máquina no GITHUB.
---------------------------------------------------------------------------
shift+insert = ctrl+V
----------------------
git push origin main(ou master) = enviar arquivo para o GITHUB.
---------------------------------------------------------------
git branch -M "main"= Renomear a branch para "main".
----------------------------------------------------
git checkout -b "nomeNovaBranch" = sair da Branch atual, criar e entrar em uma nova Branch.
-------------------------------------------------------------------------------------------
git checkout master (ou main) = retorna pra branch principal.
---------------------------------------------------------------
git merge "nome-da-branch" = adicionar a branch ao master/main.
--------------------------------------------------------------
git clone 'url-do-repositório' = Para clonar um repositório, basta criar uma pasta local, abrir o Git Bash dentro da pasta e utilizar o comando com a url do repositório a ser clonado. 