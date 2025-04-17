git init
git remote add origin http://github.com/Mistigun/giteval
cd Documents
git config user.name "ARCCSIN"
git config user.mail "blenetguilhem@gmail.com"
git clone git clone "https://github.com/Mistigun/giteval"
cd giteval
git branch form
git checkout form
git pull origin master
 touch form.html
 mkdir html
 mv form.html html
$ cd html
nano form.html
$ git config user.email "blenetguilhem@gmail.com"
$ git config user.name "ARCCSIN"
$ git add html/form.html
$ git commit -m "formulaire guilhem"
$ git push -u origin form
git pull origin aymene --allow-unrelated-histories
 cd css
 nano style.css
$ git add *
$ git commit -m "css guilhem"
$ git push -u origin form
$ git commit -m "css guilhem"
$ git push -u origin form
$ nano form.html
$ git add form.html
$ git add *
$ git commit -m "nav guilhem formulaire"
$ git push -u origin form
$ git branch form2
$ git checkout form2
$ git branch -a
$ git pull origin aymene
$ nano form.html
$ git add *
$ git push -u origin form2
$ nano index.html
$ git add *
$ git commit -m "modifier l'ordre dans la nav - Guilhem"
$ git push -u origin form2
$ git branch guilhemv4
$ git pull origin charlesv3
$ touch guilhem.md
$ nano guilhem.md
$ git add *
$ git commit -m "ajout du fichier md"
$ git push -u origin guilhemv4
