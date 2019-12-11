---
layout: post
title: Team 1 Feature Branch Verwendung
author: TillHein
categories: team1
---

#### Feature Branch Verwendung
Für die Entwicklung neuer Funktionen ist grundsätzlich ein Feature Branch zu erstellen.
Das hat den Vorteil das eine neue Funktion unabhängig vom Master entwickelt und getetstet werden können.
Sobald ein Feature vollständig entwickelt und alle nötigen Tests bestanden hat kann der entsprechende Branch in den Master gemerged werden.
Bei kleineren Änderungen kann auf einem lokalen branch gearbeitet werden, sobald die Entwicklung jedoch länger als einen Tag dauert ist der Branch ins Repository  zu pushen, 
um für eine bessere Übersicht zu sorgen.

git checkout master
git checkout -b feature_xy
(git push -u origin feature_xy) --- Erstellung remote Branch
git commit ...
git commit ...
git commit ...
git checkout master
git merge --squash feature_xy
git commit -m 'Feature xy'

git branch -d feature_xy --- Lokalen Branch löschen
git push origin --delete feature_xy --- Remote Branch löschen
