# Command-List
git commands:

pwd					-> aktueller Directory
cd "C:\Users\Critex\Documents\"		-> Directory ändern
git init				-> initialisiert ein lokales Repository. Erzeugt .git Datei
git status				-> zeigt aktuellen Status an
git add [dateiname]			-> added eine veränderte oder neue Datei
git add * oder .			-> added alle veränderten oder neuen Dateien
git reset HEAD [dateiname]		-> macht "add" wieder rückgänging
git commit -m "commit nachricht"	-> commit erzeugen
git branch
git clone "addresse"			-> Holt eine Kopie des Repositorys
git log					-> Zeigt alle commits
git remote add origin [github addresse]	-> verbindet das lokale repository mit gibhub
git push -u origin master		-> origin ist der remote name und master der branch name

git tag -a v1.0 -m "first version"	-> erzeugt ein versions Tags
git tag					-> zeigt alle vorhandenen Tags


Neues File hinzufügen:
git add log.txt
git commit -m "log.txt hinzugefügt"
git push -u origin master

Reihenfolge bei einem neuen Projekt:

Repository auf Github erzeugen
.gitignore dateien im lokalen Ordner packen
git init
echo "# test" >> README.md			-> erzeugt die README Datei
git add *
git commit -m "Initial commit"
git remote add origin [github addresse]		-> Muss man nur einmal machen
git push -u origin master
