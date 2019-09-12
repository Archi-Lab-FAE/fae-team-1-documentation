# fae-team-1-documentation

In diesem Repository sollen alle Entscheidungen die nur Team 1 betreffen festgehalten werden.


## Benutzung
Um einen neuen Eintrag zu erstellen legt zu aller erst eine Markdown-Datei nach dem folgendnen Template an.

Dateiname: DD-MM-YYYY-TITEL.md
Beispiel: 12-09-2019-Beispiel.md

Achtung: jeder Titel muss einzigartig sein, sodass die Datei immer gefunden wird. 

Nachdem ihr die Datei angelegt habt, braucht der Server noch ein paar Metadaten um den Eintrag richtig zuzuordnen. 
Die Metadaten müssen an oberester Stelle innerhalb der Datei stehen.

### Metadaten
```
---
layout: post
title: Der Titel //Dieser muss nicht der gleiche wie der Dateiname sein!
author: Der jeweilige Name des Autors //optional
categories: team1 //Die Teamspezifische Kategorie
---
```


Folgend auf diese Metadaten kommt nun der eigentliche Inhalt.
Sobald ihr einen Eintrag committed und pushed, wird der Server aktualisiert und stellt den neuen Eintrag bereit.