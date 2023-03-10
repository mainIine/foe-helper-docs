---
description: Wie funktioniert die Merger Game Info?
---

# Merger Game Info

Dieses Modul zeigt dir beim Betreten des Merger Games des Geburtstagsevents Informationen über dein Spielbrett an.

## Aufbau

![Aufbau](./.images/mergergameinfo.png)

Es werden die folgenden Informationen angezeigt:

* Wieviel Fortschritt auf dem aktuellen Spielfeld gemacht werden kann und wieviel Fortschritt bereits erzielt wurde (durch das Befreien der Schlüsselteile)
* Wieviel Energie bereits verbraucht wurde (inklusive evtl. Kosten für Reset)
    * wenn auf die Energie gezeigt wird, wird in einem Tooltip ausgegeben, wieviel Fortschritt für die aktuell ausgegebene Enrgie auf dem Brett gemacht werden sollte, um den Zielfortschritt zu erreichen
* Wieviele Schlüssel erspielt wurden (auf dem Brett und umgewandelt)
* Eine Effizienz (Fortschritt dividiert durch Energie)
    * der Fortschritt beinhaltet hierbei den Fortschritt durch das Befreien der Schlüsselteile als auch den Fortschritt der später durch die erspielten Schlüssel theoretisch erreicht werden kann
    * über die Eintellungen kann ein Zielwert eingestellt werden - die Farbe der Effizienz ändert sich in Relation zum Zielwert:
        * Die Effizienz wird rot, wenn 5% unterhalb des Zielwerts
		* Die Effizienz ist grün 15% oberhalb des Zielwerts
		* Die Effizienz ist also gelb, wenn gerade gut genug, um Ziel zu erreichen
	* wenn auf die Effizienz gezeigt wird, wird in einem Tooltip ausgegeben, wieviel Fortschritt mit dieser Effizienz erreicht werden kann

Weiterhin wird ein Blocker eingeblendet solange noch Schlüssel auf dem Brett sind, um einen versehentichen Reset zu vermeiden.	

## Einstellungen

In den Einstellungen der Erweiterung (Boxen - Eventassistenten) kann das Modul (de)aktiviert werden.

![Einstellungen](./.images/mergergamesettings.png)

* Fortschritt je Schlüssel: Soviel Fortschritt ist ein Schlüssel etwa wert (Kistenkauf - Standard:1,3)
* Zielfortschritt: soweit willst du kommen in den Hauptpreisen (Standard: 3750 für goldenes Kit)
* vorhandene Währung: soviel Energie steht zur Verfügung (Standard: 11000 - 10500 von Quests und geschätzte 500 von Ereignissen)
    * gekaufte Währung sollte entsprechend aufaddiert werden
* wenn der Reset-Blocker (nicht) verschwinden soll, kann das hier eingestellt werden