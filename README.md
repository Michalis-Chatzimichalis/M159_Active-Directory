README for AD-PowerShell Tool
------------------------------
Author: Michalis Chatzimichalis
Date: 01.11.2020
Version: 1.0
------------------------------

## Beschreibung und Erste Schritte

Das Programm dient zur Abfragen, Erstellen und Löschen von ActiveDirectory Objekten.
Um das Programm zu starten, müssen Sie die main_0.ps1-Datei starten. Das GUI sowie dieses ReadMe erscheint.

----------
## Inhaltsverzeichnis
[1 - Hauptmenü](#1---hauptmenü)\
[2 - Neuen User hinzufügen](#2---neuen-user-hinzufügen)\
[3 - Bestehender User löschen](#3---bestehender-user-löschen)\
[4 - OUs anzeigen](#4---ous-anzeigen)
[5 - Gruppen anzeigen](#5---gruppen-anzeigen)


-------------
### 1 - Hauptmenü

In diesem Hauptmenü habt ihr lediglich 4 Optionen 
* Einen neuen User zu erstellen samt Username, Passwort, Telefonnummer und zugehörige OU
* Einen bestehenden User gemäss Dropdown endgültig zu löschen
* Alle Organisationseinheiten der Domäne anzuschauen und ein Feld für das Objekteanzeige
* 1.4 Alle Sicherheitsgruppen der Domäne anzuschauen und ein Feld für das Objekteanzeige

------------
### 2 - Neuen User hinzufügen

Um einen neuen User hinzufügen müsst Ihr alle Felder ausfüllen, sowie eine OU in der Domäne raussuchen.

Die Checkboxes betr. das Passwort sind optional.

-------------
### 3 - Bestehender User löschen

Aus dem Dropdown seht ihr allen bestehenden User, die mit einem Klick aufs User endgültig löschen-Button, gelöscht werden


---------------
### 4 - OUs anzeigen

Im linken Dropdown werden alle OUs in der Domäne angezeigt. Mit einem Klick auf Get User werden alle User Objekte mit Ihrem SamAccountName im rechten Box angezeigt.
OUs, die keine Objekte beinhalten, werden mit einer Fehlermeldung konfrontiert.

---------------
### 5 - Gruppen anzeigen

Im linken Dropdown werden alle Sicherheitsgruppen in der Domäne angezeigt. Mit einem Klick auf Get User werden alle User Objekte mit Ihrem SamAccountName im rechten Box angezeigt.
Sicherheitsgruppen, die keine Objekte beinhalten, werden mit einer Fehlermeldung konfrontiert.