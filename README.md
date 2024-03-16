# Software Engineering, Aufgabe 2 (USE CASE)
## Name und Identifikationsnummer
UC 1.03 (Alarm bei zu Hoher Herzfrequenz)

## Beschreibung
Wird eine zu hohe Herzfrequenz festgestellt (über 180), wird ein Warnsignal abgegeben.

## Beteiligte Akteure
Diagnostiker: in, Probandin: in

## Status
Ausstehend

## Verwendete
Anlegen Proband: in, Leistungstest anlegen

## Aulöser
Sicherheit für Patient: innen (Überanstrengung, Vorbeugen von Nachfolgen)

## Vorbedingungen 
Eine Herzfrequenz muss wärend des Leistungstests aufgezeichent werden.
Die Herzfrequnez muss dann den Schwellenwert von 180 überschreiten.

## Invarianten 
Daten müssen stetig erhoben werden auch nach Arlam bei zu hoher Herzfrequenz, der Proband muss durchgängig Leistung bringen.

## Nachbedingung/ Ergebnis
Wir erwarten einen Alarm durch zu hohe Herzfrequenz um somit die maximale Leistung des Probanden zu identifizieren.
Die Anstengung soll bewertet werden (Use Case 1.06), Abbruch des Leistungstests (Use Case 1.07)

## Standard Ablauf
Das es nicht zur Überanstrengung kommt und der gesammte Test ohne Abbruch durch Alarm durchgeführt werden kann. 

## Alternative Ablaufschritte
Der Leistungstest sagt dem Probanden langsamer zu treten und Intensität zu verringern.

# Hinweise
keine

# Änderungsgeschichte
0.01; Pauline Voigtsberger/ Felicitas Thierbach; 16.03.2024
