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
Die Anstrengungsbewertung soll anfallen (Use Case 1.06), Abbruch des Leistungstests(Use Case 1.07)
