# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)
<<<<<<< HEAD

- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)


- git config --global user.name (Man gibt seinen Namen an)

- git config --global user.email (Man gibt seine Email an)

- git init (Repository wird erstellt)

- git add (Damit wird eine Datei hinzugefügt + mit * werden alle neue Dateien hinzugefügt)

- git commit -m "Titel" (Hiermit wird ein Stand gespeichert inklusive Namen)

- git Branch (Ein Namensschild für einen Commit)

- git log (Zeigt alle getätigten Commits vom Projektverlauf)

- git merge (Setzt zwei oder mehrere commits zusammen)

- git cherry pick (Einzelne commits werden bei einer Referenz ausgewählt und bei dem Head drangehangen)

- git rebase (Das Verschieben oder Kombinieren einer Sequenz von Commits zu einem Commit)

- git checkout (Das Wechseln zwischen Branches oder Commits)

- git clone (Es wird vom Webserver die Git-Datei auf den Lokalen Ordner kopiert)

- git push (Es werden bearbeitete (oder hinzugefügte) Dateien auf den Webserver geschoben)

- git fetch (Es werden veränderte Dateien auf den Lokalen Ordner geholt)

- git pull (Es werden veränderte Dateien auf den Lokalen Ordner geholt und man Mergt diese)

=======
- Repository: Ist eine Arbeitskopie von dir, welches den vollständigen Verlauf der Änderungen enthalt.
- Branch: Ist ein Namensschild für einen commit.
- Head: Beschreibt auf welchem branch du bist. 

- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

<<<<<<< HEAD

-git clone: wird verwendet um ein Repository zu verweisen und 
 unter einem neuen Speicherort einen Klon oder eine Kopie dieses Repositorys zu ersstellen.

-git push: Der Befehl git push wird verwendet, um Inhalte aus einem lokalen Repository in ein Remote-Repository hochzuladen

-git fetch:Mit dem Befehl git fetch werden Commits, Dateien und Verweise
    aus einem Remote-Repository in dein lokales Repository heruntergeladen

-git pull:Der git pull -Befehl wird verwendet, um Inhalte aus einem Remote-Repository herunterzuladen und unverzüglich das lokale
 Repository zu aktualisieren, damit die Inhalte übereinstimmen.




=======
>>>>>>> 
## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen) : Ist da zur bereitstellung einer allgemeinen definition einer Basisklasse, die dann für mehrere kommenden Klassen freigegeben ist.
  - abstract (Methoden) : Abstrakte Methoden legen lediglich die Signatur der Methode fest, ohne sie zu implementieren. Sie sind durch das Schlüsselwort abstract gekennzeichnet und haben keinen Rumpf (Anweisungsblock)
  - virtual : Die virtuelle C#-Methode ist eine Methode, die in abgeleiteten Klassen neu definiert werden kann. In C# hat eine virtuelle Methode sowohl eine Implementierung in einer Basisklasse als auch eine abgeleitete Klasse.
  - override : Mit einem override überschreibt man virtuelle und Methoden einer Basisklasse - Beispiel: public abstragt string Word(); // public override string Word();
  - Polymorphie : Ist eine Liste welches Objekte der Mutter und Kinderklasse hinzufügt, welche bearbeitet werden können. - Beispiel: Class Mother, Class Child, List Mother = new List();
- Wie überschreibt man die Methode `virtual string ToString()`? : public override string ToString(){}



