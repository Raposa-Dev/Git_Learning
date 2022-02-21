# Git & GitHub

$: git help  ( Mostra os comandos git )

$: git init  ( Inicia um repositório git )

$: git add ( Adiciona para area stage)

$: git status ( ver status dos commits)

$: git config [user.name](http://user.name)  <"nome do usuário">  ( Configuração de usuário git)

$: git config [user.email](http://user.email) <"email do GitHub"> ( Configuração do email )

$: git config -l | grep alias  ( Apelidos dos comandos/ atalhos do git)

$: git commit -m "mensagem objetiva sobre o commit" ( Faz o commit )

$: git log  ( O que foi commitado )

$: git checkout -b <Nome da branch>  ( Cria e se move para a branch criada)

$: git switch -c ( idem checkout )

$: git Merge master ( atualização das modificações nas branch )

$: git rebase   ( Reescreve a estrutura da árvore, movendo o galho para frente )

$:git branch -M main

$:git remote add origin [https://github.com/Raposa-Dev/bug-free-octo-pancake.git](https://github.com/Raposa-Dev/bug-free-octo-pancake.git)

$:git push -u origin main

---

Configurações rápida 
Se você já fez isso antes...

---

Comece criando um novo arquivo ou carregando um arquivo existente. Recomendamos que cada repositório inclua um README, LICENSE e .gitignore.

---

…Ou crie um novo repositório na linha de comando

Atenção não dar push direto na main esse é apenas um exemplo!

echo "# bug-free-octo-pancake" >> [README.md](http://readme.md/)   (windows)

$:touch [README.md](http://readme.md)   (Linux)

$:git init

$:git add [README.md](http://readme.md/)

$:git commit -m "first commit"

$:git branch -M main

$:git remote add origin [https://github.com/Raposa-Dev/bug-free-octo-pancake.git](https://github.com/Raposa-Dev/bug-free-octo-pancake.git)

$:git push -u origin main

---

… Ou envie um repositório existente a partir da linha de comando

$:git remote add origin [https://github.com/Raposa-Dev/bug-free-octo-pancake.git](https://github.com/Raposa-Dev/bug-free-octo-pancake.git)

$:git branch -M main

$:git push -u origin main

---