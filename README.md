# Stundenblog-II

## 27.11.2018

Um ein neues Projekt anzufangen, brauchten wir zuerst neue Ideen. In dieser Stunde sammelten wir also Ideen für anspruchsvolle Projekte, die man kreieren könnte.
Wir hatten verschiedene Ansätze. Zum einen überlegten wir ein neues Programm auszuprobierem (Link: Appinventor), um eine App zu programmieren und zum anderen waren wir unentschlossen, ob wir eine App, Animation oder ein weiteres Spiel programmieren wollen.

Hier die Liste unserer Ideen:

  -Physikalische Versuche (Animationen)
  
  -Rechenprogramm (Online Rechner)

  -primitives AI (Arduino)
  
  -Apps:
      --> Selbsttest - daraus ergibt : Persönlichkeit + z.B. passendes Reiseziel
      --> Kinderprognose (das Aussehen aufgrund der Mendel'schen Regeln, DNA, Allele)
      
 
## 03.12.2018

Heute probierten wir das Programm AppInventor aus. Allerdings war dieses Programm völlig anders als Snap! aufgebaut, mit welchem wir zuvor arbeiteten, so dass wir nahezu bei 0 hätten starten müssen.
Da wir unsere Progammierfähigkeiten aber weiter steigern wollten, entschlossen wir uns mit Snap! weiter zu machen.

## 11.12.2018

heute haben wir aus Scatch nach Ideen gesucht, die wir programmieren können. Wir kamen zu dem Schluss, dass ein Spiel kombiniert mit Animationen das Spielerlebnis interessanter gestalten würden. Zudem erfordert diese Kombination eine höhere Fachkompetenz. Dafür schauten wir uns einige Tutorials an, um einen ersten Überblick zu bekommen.

## 17.12.2018

Wir haben einen Steckbrief für unser Spiel entwickelt. Es soll ein interaktives Discovery-Spiel sein, wo der Spieler eine Figur (Kuh) durch verschiedene Situationen bringen muss. Dazu kann man Belohnungen sammeln und lernt zusätzlich allgemeine Information. Als Beispiel haben wir eine Situation in einem Gewitter, in der der Spieler entscheiden muss wie er die Kuh rettet. Als Belohnung bekommt er zum Beispiel einen Regenschirm. Wird das Quiz falsch beantwortet, folgt ein Mini-Spiel wodurch der Spieler die Figur trotzdem retten kann. 

## 18.12.2018
 
"Die Geschichte einer Kuh - Das Grundkonzept unseres Spiels. Heute haben wir die Startseite unseres Spiels programmiert. 

![startseite](https://user-images.githubusercontent.com/42734752/51918958-c79c4880-23e2-11e9-99ce-89e971faf95d.jpg)
![startseite2](https://user-images.githubusercontent.com/42734752/51919039-f61a2380-23e2-11e9-94ad-f50687ee87ac.jpg)

Dazu haben wir einen Button eingefügt, der zur nächsten Situation/Herausforderung wechselt("NEXT"). Es ändert sich der Hintergrund.

![next button](https://user-images.githubusercontent.com/42734752/52200584-75877700-2869-11e9-83ff-8c17b38b096f.png)

Es erscheint die Aufforderung "Klicke 1".

## 08.01.2019

Wenn man nun die Taste 1 klickt, erscheint die Spielfigur.

![unbenannt](https://user-images.githubusercontent.com/42734752/52200786-f181bf00-2869-11e9-84d7-d8f819ac484a.png)

Klickt man diese, erscheinen 4 Antwortsmöglichkeiten zu der Frage, wie man die Kuh (Spielfigur) retten kann. Unser erstes Szenario ist ein Gewitter und soll zeigen, wie man sich dabei verhält.  
Da es Die Antwortmöglichkeiten A, B, C, D gibt, kann man die entsprechende Buchstaben-Taste drücken, um seine Antwort auszuwählen. D.h. wir erstellen zu den jeweiligen Buchstaben ein Szenario in Form einer Animation, die den weiteren Verlauf des Spieles bestimmt.

Daraufhin erscheint ein Text wieso die Entscheidung richtig oder falsch ist.

## 14.01.2019

Wenn die Antwort falsch ist, kann man die Kuh noch mit einem Mini-Spiel retten. 
Heute haben wir zu Antwort A das erste Spiel programmiert.

![mini-spiel a](https://user-images.githubusercontent.com/42734752/52201604-48889380-286c-11e9-9101-49d3dc16994b.png)

Man muss Blitzen mit Hilfe der Pfeiltasten ausweichen.
Die Blitze kommen zufällig vom "Himmel":

![blitze antwort a](https://user-images.githubusercontent.com/42734752/52201724-a026ff00-286c-11e9-81ef-a52030e9a7a1.png)


## 15.01.2019
Heute haben wir die Animation für die Antwort B programmiert. Dafür brauchten wir etwas länger, da stets ein fehler auftrat. Wir wollten dass sich ein blauer Kreis auf einer bestimmten Höhe der y-Achse vergrößert (ausbreitet). Denn elektrische Felder breiten sich kreisförmig aus. Dies wollten wir damit verdeutlichen (für den Spieler). Allerdings schob sich der blaue Kreis immer auf der y-Achse nach oben. Da wir nicht wussten, wieso dies passierte, haben wir dem entgegen gewirkt, indem wir den Befehl hinzufügten, dass sich die Position des blauen Kreises auf der y-Achse negativ verändert, sodass es parallel zu der Vergrößerung wirkt. So blieb das Zentrum des Kreis auf der selben Position.

![kreis antwort b](https://user-images.githubusercontent.com/42734752/52202106-d1ec9580-286d-11e9-8de3-a1d7b6b56d8d.png)


## 21.01.2019
 Heute wollen wir die "Rettungsaktion für die Antwort **B** programmieren. Diese wird eine weitere Frage zum Thema *Elektrische Feldern*. Wir haben uns entschieden einen einzigen Sprite für die Rettungsfragen zu erstellen.Mit diesem Sprite werden alle Zusatzfragen erscheinen, die im Verlauf des Spieles auftreten.
 Dazu haben wir Soundeffekts eingefügt. Und ein Konzept für eine Variable, die das Programmieren einfacher machen soll. Dies haben wir bis zum Ende der Stunde gemacht und werden es die folgenden Stunden weiter machen.
 
## 22.01.2019
Heute haben wir das Szenario für die Antwort c programmiert. Diese Antwort ist ebenfalls falsch. Deswegen erscheint wenn man c drückt die Kuh in einem See, wo ein Blitz eintrifft.
![c antwort](https://user-images.githubusercontent.com/42734752/53418781-dcb3c980-39d8-11e9-81b9-0103d9d16a73.jpg)

Dazu haben wir auch das Szenario für Antwort D, also eine Grube erstellt.
![d antwort](https://user-images.githubusercontent.com/42734752/53419163-9dd24380-39d9-11e9-9889-7a48e2ec76d6.jpg)

## 29.01.2019
Diese Stunde haben wir das Szenario der Antwortsmöglichkeit A weiterentwickelt, indem wir eine Animation (Feuer)zusätzlich programmiert haben. 
![feuer](https://user-images.githubusercontent.com/42734752/53419487-4680a300-39da-11e9-81ea-19e0e733f6dd.jpg)

## 04.02.2019
Heute haben wir die Antwortmöglichkeit B optimiert, indem wir programmiert haben, dass unsere einen Stromschlag bekommt (Animation). 

![b blitz](https://user-images.githubusercontent.com/42734752/53419891-f8b86a80-39da-11e9-8549-354b2ad47891.jpg)

Danach erscheint ein Informationskasten, der erklärt wieso die Antwort falsch ist. 
![b falsch](https://user-images.githubusercontent.com/42734752/53420721-95c7d300-39dc-11e9-9b73-c4c7cc3529b8.jpg)


## 12.02.2019

Diese Stunde haben wir eine Variable *Score Belohnungen* erstellt. Diese erhöht sich immer wenn die Kuh eine Belohnung bekommt. man bekommt immer eine Belohnung, wenn man eine richtige Antwort angibt. Diese Belohnungen sammelt man und kann in einer Trophäenliste ansehen. Der Score gibt dann dementsprechend die Information weiter, welche Belohnungen bereits gesammelt wurden.

![belohnungen](https://user-images.githubusercontent.com/42734752/53423960-982d2b80-39e2-11e9-98aa-19120ce2bab5.png)

## 19.02.2019
## 25.02.2019
## 26.02.2019
