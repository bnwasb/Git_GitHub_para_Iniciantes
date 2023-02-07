# Projeto criado para aprender a utilizar o Git:

## Salvando alterações e enviando para o repositório no GitHub:
*  (após utilizar `git init` para iniciar um repositório)

* 1º `git add .` (mandar para *staging*)

* 2º `git commit -m "coment"` (adicionar *commit* com mensagem)

* 3º `git push origin master`(Empurrar para o repositório no GitHub)


## Comandos básicos do Git:


* `Ctrl + Insert` = Ctrl + C (copy)
* `Shift + Ins`   = Ctrl + V (paste)

* `git version` = Verificar a versão do Git (se há erros de instalação);

* `git init` = Iniciar um novo repositório;

* `clear` = Limpar códigos do console;

* `git add .` = Adicionar todos os arquivos ao *stage*.
* `git add` +`'arquivo.tipo'` = Adiciona arquivo expecífico ao *stage* para fazer *commit* quando necessário.

* `git status` = Verificar mudanças à receber *commit*.

* `git comit -m` `"coment"`= Fazer o *commit* com comentário entre `""`.

* `git remote add origin` +`url-do-repositório` = Adicionar repositório local da máquina no GitHub.

* `git push origin main`(ou *master*) = Enviar arquivo para o repositório no GitHub.

* `git branch -M "main"` = Renomear a *branch* para *main*(ou outro nome).

* `git checkout -b "nome-nova-branch"` = Sair da *branch* atual(checkout), criar/entrar em uma nova *branch*.

* `git checkout master` (ou *main* / '*branch* principal') = Retorna para *branch* principal.

* `git merge "nome-da-branch"` = Adicionar a *branch* referida ao master/main (*branch* principal).

* `git clone 'url-do-repositório'` = Para clonar um repositório, basta criar uma pasta local, abrir o Git Bash dentro da pasta e utilizar o comando com a url do repositório a ser clonado.

* `git pull` = Utilizado para 'puxar' as atualizações/mudanças do repositório do GitHub para o repositório local.
