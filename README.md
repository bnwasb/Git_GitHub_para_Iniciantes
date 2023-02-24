# (INICIANTE) Como adicionar repositório no GitHub com Git: 

## Preparativos:

* 1º Faça o download do Git através do [link](https://git-scm.com/downloads)

* 2º Instale a ferramenta: instalação padrão, next, next... install.
* (não se preocupe com as diversas configurações de instalação nesse momento)
  
* 3º Depois de instalado, crie uma pasta no seu computador, ela será o repositório local (você a enviará para o GitHub posteriormente). 
Clique com o botão direito do mouse dentro da pasta e clique em *Git GUI Here*. Esse comando abrirá o terminal já dentro do seu diretório/pasta(local).

* 4º Vamos aos primeiros comandos! Dentro do terminal, digite `git version` para exibir a versão do Git. Caso houver erro de instalção, também exibirá no console.

* 5° Digite `git init` para iniciar o repositório.

## Adicionando arquivos e enviando para o repositório no GitHub:

* 1º `git add .` (mandar para *staging*);

* 2º `git commit -m "coment"` (adicionar *commit* com mensagem);

* 3º `git push origin master`(Empurrar para o repositório no GitHub).


## Comandos básicos do Git:

* `Ctrl + Ins`  = Ctrl + C (copy);
* `Shift + Ins` = Ctrl + V (paste);

* `git version` = Verificar a versão do Git (se há erros de instalação);

* `git init` = Iniciar um novo repositório;

* `clear` = Limpar códigos do console;

* `git add .` = Adicionar todos os arquivos ao *stage*;

* `git add` +`'arquivo.tipo'` = Adiciona arquivo expecífico ao *stage* para fazer *commit* quando necessário;

* `git status` = Verificar mudanças à receber *commit*;

* `git comit -m` `"coment"`= Fazer o *commit* com comentário entre `""`;

* `git remote add origin` +`url-do-repositório` = Adicionar repositório local da máquina no GitHub;

* `git push origin main`(ou *master*) = Enviar arquivo para o repositório no GitHub;

* `git branch -M "main"` = Renomear a *branch* para *main*(ou outro nome);

* `git checkout -b "nome-nova-branch"` = Sair da *branch* atual(checkout), criar/entrar em uma nova *branch*;

* `git checkout master` (ou *main* / '*branch* principal') = Retorna para *branch* principal;

* `git merge "nome-da-branch"` = Adicionar a *branch* referida ao master/main (*branch* principal);

* `git clone 'url-do-repositório'` = Para clonar um repositório, basta criar uma pasta local, abrir o Git Bash dentro da pasta e utilizar o comando com a url do repositório a ser clonado;

* `git pull` = Utilizado para 'puxar' as atualizações/mudanças do repositório do GitHub para o repositório local.
