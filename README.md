##  Comandos Para Criar um Repo no Git



### or create a new repository on the command line
echo "# desafio-git-dio" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/PatriciaNFreitas/desafio-git-dio.git
git push -u origin main
### …or push an existing repository from the command line
git remote add origin https://github.com/link do repo
git branch -M main
git push -u origin main
