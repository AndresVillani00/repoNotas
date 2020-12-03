# Musica Maestro
253 git config --global user.name AndresVillani00     
254 git config --global user.email andres24villani08@gmail.com
 256  mkdir repoNotas  
  257  cd repoNotas
  258  git init
  259  git clone https://github.com/AndresVillani00/repoNotas.git
  260  git add -A
  261  git status
  262  git commit -m "Repo clonado"
  263  git add -A
  264  git status
  265  git commit -m "Añadimos Notas Musicales"
  266  git tag notasMusicales
  267  git tag
  268  git log --graph --decorate --pretty=oneline
  269  git remote add origin https://github.com/AndresVillani00/repoNotas.git
  270  git push -u origin master
  271  git branch claveSol
  272  git branch claveFa
  273  git branch sostenido
  274  git branch
  275  git checkout claveSol
  276  git status
  277  git add -A
  278  git status
  279  git commit -m "Añadimos archivos a la rama claveSol"
  280  git checkout master
  281  git merge claveSol
  282  git branch -D claveFa
  283  git checkout claveFa
  284  git checkout sostenido
  285  git branch -m claveDo
  286  git checkout master
  287  git branch
  288  git push -u origin master
  289  history
