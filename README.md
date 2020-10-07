# Das wichtigste zuerst

## <a name='projektstruktur'>Projektstruktur</a>

- Im Ordner **\_pages** befinden sich die statischen Seiten (die auch in der Navigationsleiste anwählbar sind).
- Im Ordner **\_posts** befinden sich Ankündigungen und Berichte. 
- Bilder können in den Ordner **bilder** hochgeladen und in den Texten verlinkt werden.
- Andere Dokumente können im den Ordner **docs** abgelegt und zum Download verlinkt werden.

## Markdown

Das Format der Dateien ist Markdown, das dann automatisch in HTML umgewandelt wird. HTML kann aber auch verwendet werden. Wie man Github-Markdown schreibt, kann man hier nachlesen: https://guides.github.com/features/mastering-markdown/

# Änderungen machen

## Für neue Posts

1. Einen GitHub Account erstellen / einloggen
1. Im Repository [ktiu/dig-geo][1] in den Ordner **[posts][2]** wechseln
2. Auf **Create new file** clicken
![Create new file][image-2]
4. Datei benennen. Dabei sollte das Format des Dateinamens (YYY-MM-DD-titel-mit-bindestrichen.md) eingehalten werden.
5. In der Datei ganz oben steht der YAML-Header mit den Metadaten, z.B
```
---
title: Bericht vom Workshop „Praxis und Zukunft der digitalen Kartographie“
zeit: 8.-9. November 2018
ort: Forschungsgruppe Kartographie, TU Wien, Österreich
image: /bilder/2018-wien-vsc.jpg
tags: Berichte Workshops Wien
---
```
6. Darunter folgt der Text in Markdown/HTML
3. Auf **Commit new file** klicken
4. Überprüfen und **Create pull request** wählen
5. Ggf. eine kurze Beschreibung / Erklärung der Änderungen verfassen und Pull request bestätigen
6. Das war's! Der Pull request mit den Änderungen ist für alle sichtbar und kann angenommen werden.

## Für kleine Änderungen und Korrekturen

1. Einen GitHub Account erstellen / einloggen
1. Im Repository [ktiu/dig-geo][1] die betreffende Datei finden (siehe [Projektstruktur][3])
2. Auf der zu ändernden Datei auf den kleinen Stift im Menü oben rechts klicken:
![Fork this project and edit the file][image-1]
3. Änderungen vornehmen und auf **Propose file change** klicken
4. Überprüfen und **Create pull request** wählen
5. Ggf. eine kurze Beschreibung / Erklärung der Änderungen verfassen und Pull request bestätigen
6. Das war's! Der Pull request mit den Änderungen ist für alle sichtbar und kann angenommen werden.

## Für umfassendere Änderungen...

...(z.B. Designänderungen) ist es besser, zuerst an einer eigenen Kopie des gesamten Projekts Änderungen vorzunehmen und sich anzeigen zu lassen. Das geht so:

1. Im Repository [ktiu/dig-geo][1] auf "Fork" klicken. Das kopiert das komplette Projekt in den eigenen Account. (Das passiert übrigens auch bei der schnellen Methode automatisch im Hintergrund.)
1. Die Datei "CNAME" im eingenen Repository löschen (sonst kommt GitHub bei der Vorschau durcheinander).
1. Im *eigenen* Repository (also https://github.com/{eigener-benutzername}/dig-geo) auf "Settings" klicken
2. Im Menüpunkt **GitHub Pages** die Option **Source** auf »master« setzen. Damit werden die Änderungen, die im eigenen Repository vorgenommen werden, live (mit einer kleinen Verzögerung) angezeigt.
3. Die Adresse für die Vorschau lautet: https://{eigener-benutzername}.github.io/dig-geo/
	- Der Markdown-Editor [Prose][4] kann hierbei helfen.
	- Die Profi-Variante ist dann, sich den [GitHub Desktop][5] (oder sogar nur Git) und [Jekyll][6] zu installieren, das Repository lokal zu ›klonen‹ und sich die Änderungen in Echtzeit auf localhost anzeigen zu lassen.
4. Wenn die eigene Kopie soweit ist, dass die Änderungen in die Live-Seite einfließen sollen, muss noch ein ›pull request‹ erstellt werden. Hierzu auf **New pull request** klicken (oder diesem [Link](../../compare/ktiu:master...master) folgen)
5. Dann als **base fork** auswählen: »ktiu/dig-geo«
6. Als **head fork**: »{eigener-benutzername}/dig-geo« 
7. Dann prüft GitHub, ob die Versionen zusammengeführt werden können. Solange nicht in der Zwischenzeit die gleichen Zeilen bearbeitet wurden, sollte das gehen.
8. Auf **Create pull request** klicken und dann nochmal bestätigen. Fertig!

Wenn ihr in weiterer Folge Aktualisierungen von ktiu/dig-geo in euren Fork "nachziehen" wollt, könnt ihr den Pull-Request auch in die andere Richtung machen, d.h. »{eigener-benutzername}/dig-geo« als base fork und »ktiu/dig-geo« als head fork. ([Link](../../compare/master...ktiu:master))


# Zum Weiterlesen

- Das Format der Dateien ist Markdown, welches dann automatisch in HTML umgewandelt wird. https://guides.github.com/features/mastering-markdown/
- Die Seite ist auf GitHub gehostet, wofür es hier eine schöne Einleitung gibt: https://guides.github.com/introduction/flow/

[1]:	https://github.com/ktiu/dig-geo
[2]:	https://github.com/ktiu/dig-geo/tree/master/_posts
[3]:	#projektstruktur
[4]:	https://prose.io
[5]:	https://desktop.github.com/
[6]:	https://jekyllrb.com

[image-1]:	https://raw.githubusercontent.com/ktiu/dig-geo/master/bilder/tutorial/fork_and_edit.png
[image-2]:	https://raw.githubusercontent.com/ktiu/dig-geo/master/bilder/tutorial/create_new_file.png
