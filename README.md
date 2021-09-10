# UC7trio

COLABORADOR 1: MECPERES

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio
$ git config --global user.name "mecperes"

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio
$ git config --global user.email "salulumo@hotmail.com"

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio
$ git init
Initialized empty Git repository in D:/Peres/Projeto em trio/.git/

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Projetao dos cria.txt
        README.MD.txt

nothing added to commit but untracked files present (use "git add" to track)

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git add .

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git commit -m "criei o readme e o projetao para fazer o push"
[master (root-commit) 840b3ec] criei o readme e o projetao para fazer o push
 2 files changed, 2 insertions(+)
 create mode 100644 Projetao dos cria.txt
 create mode 100644 README.MD.txt

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git log
commit 840b3ec4d47d840aac0e19018f9cde785f4167be (HEAD -> master)
Author: mecperes <salulumo@hotmail.com>
Date:   Thu Sep 9 21:26:52 2021 -0300

    criei o readme e o projetao para fazer o push

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git remote add origin https://github.com/mecperes/UC7trio.git

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (master)
$ git branch -M main

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 310 bytes | 155.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mecperes/UC7trio.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Aluno@ESN914D1233556 MINGW64 /d/Peres/Projeto em trio (main)

COLABORADOR 2: IGOR CARBONARI SILVA

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$ git config --global user.name "Igor Carbonari Silva"

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$ git config --global user.email "igorcarbosilva@hotmail.com"

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Projetao dos cria.txt

no changes added to commit (use "git add" and/or "git commit -a")

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$ git add .

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$ git commit -m "eu Igor coloquei meu nome na lista"
[main 7a4a806] eu Igor coloquei meu nome na lista
 1 file changed, 2 insertions(+), 1 deletion(-)

CT WEB FULL STACK@ESN914D1233553 MINGW64 /d/Igor Carbonari Silva/Projeto dos cria/UC7trio (main)
$

COLABORADOR 3: EDUARDO CARBONARI SILVA

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git config --global user.name "Eduardo Carbonari Silva"

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git config --global user.email "ducarbosilva@hotmail.com"

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Projetao dos cria.txt

no changes added to commit (use "git add" and/or "git commit -a")

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git add .

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git commit -m "eu Eduardo finalizei o projetao dos cria"
[main 4a2a369] eu Eduardo finalizei o projetao dos cria
 1 file changed, 2 insertions(+), 1 deletion(-)

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$ git log
commit 4a2a3695dfaf7fe1a98b9ed49772c4a878c8b9d2 (HEAD -> main)
Author: Eduardo Carbonari Silva <ducarbosilva@hotmail.com>
Date:   Thu Sep 9 20:48:24 2021 -0300

    eu Eduardo finalizei o projetao dos cria

commit dba4655efd716afec82e02bbbc94ea69ce72842e (origin/main, origin/HEAD)
Author: Igor Carbonari Silva <igorcarbosilva@hotmail.com>
Date:   Thu Sep 9 21:30:48 2021 -0300

    atualizei o readme

commit 7a4a806617e6a5f2beefb6819391e4e223ee8a90
Author: Igor Carbonari Silva <igorcarbosilva@hotmail.com>
Date:   Thu Sep 9 21:29:13 2021 -0300

    eu Igor coloquei meu nome na lista

commit 22375c4f36e68017bb5c5ce426e4e223c78c346c
Author: mecperes <salulumo@hotmail.com>
Date:   Thu Sep 9 21:30:45 2021 -0300

    atualizei o readme

commit 840b3ec4d47d840aac0e19018f9cde785f4167be
Author: mecperes <salulumo@hotmail.com>
Date:   Thu Sep 9 21:26:52 2021 -0300

    criei o readme e o projetao para fazer o push

CT WEB FULL STACK@ESN914D1233557 MINGW64 /f/Eduardo Carbonari Silva/projetin dos cria/UC7trio (main)
$
