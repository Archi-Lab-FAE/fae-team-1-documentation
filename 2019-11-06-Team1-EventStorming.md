---
layout: post
title: Event Storming
author: Team 1 
categories: team1 
---

#### Anmerkung SB 15.11. (bitte nach Bearbeitung löschen)
Was Sie hier dokumentiert haben, gehört ins Wiki. Das ist keine lokale Entscheidung. 

## Events

|Nummer| Event                                                                                                    |
|------| ---------------------------------------------------------------------------------------------------------|  
|     1| Die Gesellschaft hatte ausreichend finanzielle Mittel, um für Inklusion zu investieren                   |
|     2| Hilfestellung (durch GPS) gesucht                                                                        |
|     3| Pflegeheim ist mit dem Einbau des GPS-Trackers einverstanden und kooperiert mit der Familie und mit Maria|
|     4| Liste von Zuständigen wurde festgelegt                                                                   |
|     5| Maria wird informiert                                                                                    |
|     6| Gespräch mit Maria wird geführt - hierbei werden die "Vorteile" des Senders/Trackers erklärt             |
|     7| Maria war mit dem Einbau des GPS-Trackers einverstanden                                                  |
|     8| Heim stellt ausreichend Personal ein, um Menschen zun suchen                                             |
|     9| Umgang mit GPS-Tracker (Laden, Wartung) wird mit Mitarbeitern besprochen                                 |
|    10| Temporär gefährliche Zone wird identifiziert (Baustelle)                                                 |
|    11| Beteiligte wurden registriert                                                                            |
|    12| Marias Familie wurde im System vernetzt                                                                  |
|    13| Die für Maria wichtigen Orte wurden registiert                                                           |
|    14| GPS-Sender installiert                                                                                   |
|    15| Marias Familie hat die App runtergeladen                                                                 |
|    16| Ein Hilfe-Knopf wurde registriert                                                                        |
|    17| Der GPS-Tracker von Marias Schuhe wurde/konnte registriert werden                                        |
|    18| Wartungszeit der Schuhe ist überprüft                                                                    |
|    19| Maria die GPS-Schuhe gegeben                                                                             |




## Fragen

|Nummer| Frage                                                                                                | Event  |
|------|------------------------------------------------------------------------------------------------------|--------|
|     1| Ab wann hat man einen fairen Zugang?                                                                 |      2 |
|     2| Wer haftet bei Fehlern?                                                                              |      3 |
|     3| Kosten?                                                                                              |      4 |
|     4| Kostenträger?                                                                                        |      4 |
|     5| Welche Verpflichtungen hat eine eingetragene Person?                                                 |      4 |
|     6| Wer legt diese Liste fest?                                                                           |      4 |
|     7| Wer übernimmt die Position der Angehörigen, wenn es keine Angehörige gibt?                           |      4 |
|     8| Darf die Familie über die "Bewachung" Marias entscheiden, wenn sie dazu nicht mehr in der Lage ist?  |      5 |
|     9| Kann das Gebiet bei Ausflügen angepasst werden?                                                      |      10|
|    10| Gibt es Optionen um leere Batterien zu behandeln?                                                    |      10|
|    11| Welche Daten werden bei der Registrierung erfasst?                                                   |      11|
|    12| Wie wird die Zone definiert? Radius?                                                                 |      13|
|    13| Beeinträchtigt der Sender die Schuhe?                                                                |      14|
|    14| Wie viele Schuhe werden gechipt?                                                                     |      15|
|    15| Gibt es für jede Person einen eigenen Hilfe-Knopf? -> Wie wird erkannt, dass Maria Panik hat?        |      16|
|    16| Wie wird sichergestellt, dass Maria die GPS-Schuhe anzieht?                                          |      19|



## Personen

|Nummer| Name                        | Events            |
|------|-----------------------------|-------------------|
|    1 | Gesellschaft                |                  1|
|    2 | Heimleitung                 |         2, 3, 6, 8|
|    3 | Angestellte für das System  |               2, 9|
|    4 | Maria                       | 3, 5, 6, 7, 13, 19|
|    5 | Hilde                       |   3, 4, 11, 12, 15|
|    6 | Fritz                       |   3, 4, 11, 12, 15|
|    7 | Pflegekasse                 |                  3|
|    8 | Mitarbeiter                 |            3, 8, 9|
|    9 | Gesetzliche Betreuer        |                  3|
|    10| Freunde von Maria           |                  4|
|    11| Vertraute Personen          |                  4|
|    12| Schuhhersteller             |                 14|
|    13| Service-Mitarbeiter         |                 16|




## Soziale Aspekte

|Nummer| Aspekt                                                                                            | Event|
|------|---------------------------------------------------------------------------------------------------|------|
|     1| Finanzierung?                                                                                     |     1|
|     2| Aufklärung über Datenschutz und Digitalisierung                                                   |     2|
|     3| Verantwortungsbereiche neu aushandeln                                                             |     2|
|     4| Einverständniserklärung der erkrankten Person immer gegeben? (erinnert sich nicht)                |     2|
|     5| Einsparung des Personals (Pro + Con)                                                              |     3|
|     6| Angehörige sollen geschult werden                                                                 |     4|
|     7| Steigende Kompetenz bei der Betreuung älterer Menschen                                            |     4|
|     8| Mehr direktes Involvement Angehörige                                                              |     4|
|     9| Rechtliche Verantwortung klären! (Fritz, Pflegeheim, Hilde, Polizei...)                           |     5|
|    10| Kontrolliert werden                                                                               |     6|
|    11| Aufgaben der Fachkräfte ändern sich                                                               |     6|
|    12| Möchte Maria das überhaupt?                                                                       |    13|
|    13| Bewusstsein der Gesellschaft ändert sich                                                          |    16|
|    14| Bereitschaft der Gesellschaft für die Übernahme der Verantwortung -> Will ich das?, Mache ich das?|    16|
|    15| Softe Kontrolle vs. Extrementscheidungen                                                          |    17|
|    16| Verletzung von Marias Freiheits- und Persönlichkeitsrechten                                       |    17|
|    17| Machtungleichheit: Machtausübung von Leitung, Personal etc.                                       |    17|
|    18| Gewissheit für Angehörige, dass es Maria gut geht (keine Sorge)                                   |    19|



## Features

|Nummer| Feature                                                   | Event|
|------|-----------------------------------------------------------|------|
|     1| App Entwicklung für Sohle -> Kommunikation mit Angehörigen|     6|  
|     2| Berechtigung auch übertragbar, wenn Maria ins KH kommt?   |    17|


