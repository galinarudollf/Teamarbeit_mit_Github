# Teamarbeit mit GitHub

> Haben Sie bereits einen Github-Account? Falls noch nicht wird es an der Zeit einen zu erstellen :-)

## Aufgabe

Das Githup-Repository ... soll eine kurze Beschreibung der wichtigsten Begriffe bzw. Features von Github in der Datei  `Github_Features.md`enthalten. Bearbeiten Sie die Datei in dem Sie die fehlenden Inhalte einfügen. Arbeiten Sie in den Gruppen von jeweils 2-3 Personen, wobei eine(r) aus der Gruppe als Maintainer des Projekts fungieren soll, während die anderen als Entwickler tätig sein sollen. 

Folgende Schritte sind dabei durchzuführen:

1. Forken des Repositorys durch den **Maintainer**, um eine Kopie des Projekts unter eigenem GitHub-Konto zu erhalten.

    Hinweis: Klicken Sie auf der Repository-Seite auf die Schaltfläche "Fork", um eine Kopie des Repositorys unter Ihrem eigenen Konto zu erstellen.

2. Hinzufügen von Entwicklern durch den **Maintainer**, um ihnen den Zugriff auf das geforkte Repository zu gewähren.

    Hinweis: Klicken Sie auf die Einstellungen Ihres Repositorys im Browser, navigieren Sie zu "Collaborators" und fügen Sie die Entwickler hinzu.

3. Erstellen von Issues durch den **Maintainer** um Aufgaben zu verteilen.

    Hinweis: Gehen Sie auf die Seite des Repositorys im Browser, klicken Sie auf "Issues" und dann auf "New Issue", um ein neues Issue zu erstellen.

4. Erstellen lokaler Kopien des geforkten Repositorys durch die **Entwickler**.

    Zum Erstellen von Kopien auf den lokalen Rechnern kann ein Client verwendet werden. z.B. `git-scm` (zu finden unter https://git-scm.com/download/). 
    Nach der Installation kann der Client über Kontextmenü des Explorers aufgerufen werden (über `Open Git Bash here`). 
    
    Hinweis: Geben Sie den Befehl `git clone <fork-url>` auf der Befehlszeile des Bash-Fensters, um das geforkte Repository zu klonen.

5.  Bearbeiten der Datei in Branches durch die **Entwickler**.

    Hinweis: Verwenden Sie die Befehle `git branch <branch-name>` und `git checkout <branch-name>` auf der Befehlszeile, um einen neuen Branch zu erstellen und darauf zu wechseln.

6.  Commiten und Pushen der Branches durch die **Entwickler**.

    Nach dem Bearbeiten der Datei in einem (beliebigen) Editor sind die Änderungen zu **committen** und auf den Server zu übertragen (**pushen**), um sie mit dem Rest des Teams zu teilen.

    Hinweis: Verwenden dazu die Befehle `git commit -a -m "Commit-Beschreibung"` und `git push origin <branch-name>` auf der Kommandozeile.

7.  Erstellen eines Pull requests durch die **Entwickler**.

    Über den Schalter  "Pull requests" im Browser besteht die Möglichkeit die Pull requests zu erstellen um die Branches in die main-Branch einzupflegen. 
    
    Hinweis: Klicken Sie auf die Schaltfläche "Pull requests", dann "Compare & pull request" und zum Schluss "Create pull request"

8.  Zusammenführen der Branches in den Haupt-Branch durch den **Maintainer**.

    Durch den Klick auf Pull requests erhalten Sie alle vorhandenen Pull requests. Falls die Entwickler-Branches keine Konflikte mit dem main-Branch verursachen, können sie über "Merge pull request" eingepflegt und anschließend gelöscht werden. Die Issues können geschlossen werden.  

## Links

https://git-scm.com/doc

https://docs.github.com/de
