# Como inicializar el repositorio remoto
…or create a new repository on the command line
echo "# prueba" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin url
git push -u origin master
…or push an existing repository from the command line
git remote add origin url
git push -u origin master
