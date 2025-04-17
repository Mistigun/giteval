git init

git remote add origin http://github.com/Mistigun/giteval

git clone https://github.com/Mistigun/giteval


 git config user.name "Mistigun"

 git config user.email "ch.courcol@outlook.fr"

 cd giteval 

  git branch page
  git branch -a
  git checkout branch
  git pull origin master

  git add *
  git commit -m "page charles bisbis"
  git push -u origin page
  git pull origin aymene

  modification css de ma page sur ma branche

  git add * 
  git commit -m "page v2 charles"
  git push -u origin page

  La V1 est faite, chacun à créer sa page, l'a partagé (push/pull)
  On crée une v2 où chacun créer une sous branche

  git branch page2 
  git checkout page2

  modification de ma page page.html
  rajout d'une image et de son texte
  déplacement du footer

  modification du css

git add *
git commit -m "page V2 charles"
git push -u page2

git pull origin form2

modification du css
git add *
git commit -m "page css charles"
git push -u page2

reprise de la nouvelle version avec du css adapté et des changements
git pull aymene3

adaptation pour mobile (code dans le css)

création de la branche charlesv3 pour la version finale
git branch charlesv3
git checkout charlesv3

git add *
git commit -m "modification css mobile pour version finale"
git push -u origin charlesv3

git pull origin guilhemv4
ajout de mon charles.md

git add *
git commit -m "ajout charles md"
git push -u guilhemv4