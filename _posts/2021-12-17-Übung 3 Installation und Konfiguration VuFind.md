---
title: "Übung 3: Vufind Konfiguration Suche und Facetten"
date: 2021-12-17
---

### Installation Vufind

Leider konnte ich nach der Installation die Seite von Vufind nicht aufrufen, es kam nur eine leere Seite «404 not found». 
Deshalb habe ich Herrn Lohmeier eine Mail geschrieben. Mir wurde geraten die Installation nochmals vorzunehmen. 
Beim zweiten Durchlauf habe ich mich sehr auf Fehlermeldungen geachtet und bemerkt, dass eine Fehlermeldung beim Befehl «sudo apt-get install -f» erschien,  mit der Meldung, dass die Pakete nicht gefunden werden konnten. 
Das Problem konnte ich lösen, indem ich «sudo apt-get update» eingegeben habe. Danach hat die Neuinstallation mit Hilfe des Screencasts gut geklappt.Ich fand es toll, dass ein Screencast erstellt wurde – dies hat mir sehr geholfen. 

### Konfiguration

Mit dem [Video](https://www.youtube.com/watch?v=qFbW8u9UQyM&list=PL5_8_wT3JpgE5rv38PwE2ulKlgzBY389y&index=5) zu Vufind hatte ich Mühe, da ich nicht wusste, wie ich zu dieser Konfigurationsseite genau komme. Mit dem Befehl "sudo gedit /usr/local/vufind/local/config/vufind/config.ini" habe ich zumindest die Konfigurationsdatei gefunden aber wie ich von dort zu "searches.ini" gelangen sollte bleibt mir schleierhaft.

![Konfiguration](https://raw.githubusercontent.com/slunz/Lerntagebuch-BAIN/master/pictures/searches.png)

Trotzdem habe ich mir das Video angeschaut und konnte die einzelnen Schritte gut nachvollziehen. Es wurde erklärt, wie man die Anzahl Suchresultate und Suchfacetten anpassen kann. Beim Dropdown Menu zum Beispiel kann man die Reihenfolge und die Bezeichnungen ändern. Zu dem kann man im Verzeichnis *facets.ini* den Standort und die Anzahl der Facetten ändern. Im Verzeichnis *searchspecs.yaml* könnte man auch anpassen, wie Vufind die Relevanz der Suchtreffer rankt.
Allgemein kann man Vufind ganz nach seinen Wünschen konfigurieren, was für den Einsatz in verschiednen Institutionen sehr nützlich ist. 


Zeichen: 1865
