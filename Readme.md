Olá esse projeto ensina a usar o Git

#comandos

git init - inciar repositorio vazio
quando aparecer master é já estão na branch master - branch principal - pode ser main

pasta .git criada - onde acontece tudo do git - não apagar

commit - versões

git add - manda os arquivos pra área de staging - como se fosse um backstage
git add . - manda todos os arquivos que sofreram alteração pro staging

git status - pra ver o status do git ..

git commit -m "titulo do commit" - para comitar de fato

git branch -M "main" - renomear a branch

git remote add origin https://github.com/rafalelas/TestandoGit.git
meio q linka o repositorio que criamos manualmente no basch com o repositorio do github. origin é o nome do repositorio
apenas uma vez na primeira vez precisa do remote pois está estabelecendo a conexão remota.

git push -U origin main - adiciona arquivos no repositorio do github. envia os commits do local para o 'remoto'.
também não precisa mais do -u depois da primeira vez usada. pode utilizar apenas git push origin main para os próximos commits

*Projeto desenvolvido na faculdade de Eng. de Software onde o usuário pode criar equipes *

até aqui foi alterado