Benutzeroberfläche
==================

Einleitung
----------

Hat man die grundlegenden Prinzipien der goalio-Benutzeroberfläche einmal verstanden, so können selbst komplexe Operationen problemlos durchgeführt werden. Um also sicherzustellen, dass Sie bei der Benutzung von goalio keine Probleme haben, möchten wir Sie mit diesem Leitfaden in die wesentlichen Bedienelemente einführen.

Navigation
--------------

Das zentrale Steuerelement in goalio ist die gelbe/graue Menüleiste, welche sich über dem Seiteninhalt befindet. Bewegen Sie Ihren Mauszeiger auf einen der Einträge, um die verfügbaren Unterseiten angezeigt zu bekommen. Die momentan geöffnete Seite wird dabei blau hinterlegt.

.. image:: ../images/gui/menuleiste.png

.. note ::
	Sollte das Menü nicht oder nicht richtig dargestellt werden, so stellen Sie bitte sicher, dass Javascript in Ihrem Browser aktiviert ist.  Eine Anleitung dazu finden Sie hier_.
	
.. _hier: http://www.enable-javascript.com/de/

Komponenten
------------

In goalio werden unterschiedliche Techniken angewandt, um Daten intuitiv und übersichtlich darzustellen. Folgende Komponenten stellen dabei die wichtigsten dar:

**Fenster**

Ein Fenster (bzw. Formular oder Dialog) öffnet sich in der Regel bei einem Doppelklick auf einen Datensatz (also beispielsweise ein Mitglied in der Mitgliederliste), welcher daraufhin in der Regel bearbeitet werden kann.

**Reiter**

Ist ein Fenster durch ein horizontales Menü in unterschiedliche Abschnitte gegliedert, so spricht man von Reitern (oder Tabs). Betrachtet man also die Mitgliederliste, so handelt es sich bei einem Mitglied um einen Datensatz, beim Bearbeiten-Formular um ein Fenster, und bei den dortigen Abschnitten *Adresse*, *Zahlung* oder *Aufgaben* um Reiter.

.. image:: ../images/gui/reiter.png

**Schaltflächen**

Schaltflächen (auch Buttons oder Knöpfe) sind Bedienelemente, welche das System anweisen, eine bestimmte Operation auszuführen. Beispiele hierfür sind die Schaltflächen *Speichern*, *Löschen* oder auch *Suche*.

.. image:: ../images/gui/schaltflaechen.png

**Operatoren**

Operatoren können in Suchfeldern angeben, wie ein bestimmtes Kriterium ausgewertet werden soll. Wählt man beispielsweise *ist gleich*, so werden ausschließlich jene Ergebnisse angezeigt, die exakt mit dem Kriterium übereinstimmen. Möglich ist die Verwendung folgender Operatoren:

**Auswahl-Menüs**

Auswahl-Menüs (auch Dropdown-Menüs oder Listenmenüs) sind eine platzsparende Möglichkeit, mehrere Listenpunkte verschachtelt anzuzeigen.

.. image:: ../images/gui/dropdown-menu.png


====================  =======
Operator              Wirkungsweise
====================  =======
Beginnt mit           Liefert alle Ergebnisse, die mit dem Kriterium beginnen (Mus **>** Mustermann, Muse)
Enthält               Liefert alle Ergebnisse, die das Kriterium enthalten (ster **>** Mustermann, Holstern)
Ist gleich            Liefert alle Ergebnisse, die identisch mit dem Kriterium sind (Mustermann **>** Mustermann)
Größer oder gleich    (Bei Datumsangaben) Liefert Kriterium und alle Tage danach (01. Januar **>** 01. Jan., 02. Jan., 03. Jan., ...)
Kleiner oder gleich   (Bei Datumsangaben) Liefert Kriterium und alle Tage davor (03. Januar **>** 03. Jan., 02. Jan., 01. Jan., ...)
Ist nicht gleich      (Bei Datumsangaben) Liefert alles, ausser Kriterium (02. Januar **>** 01. Jan., 03. Jan., ...)
Nicht gesetzt         Liefert alle Ergebnisse, bei denen keine Informationen zu diesem Feld vorliegen
Gesetzt               Liefert alle Ergebnisse, bei denen Informationen zu diesem Feld vorliegen
====================  =======

.. image:: ../images/gui/operator.png

Vorschaufunktion
----------------

Haben Sie eine Datenübersicht (Mitgliederliste,  Abteilungsliste, ...) geöffnet, so können Sie durch Klick auf einen der Einträge die Vorschaufunktion aufrufen. Diese erscheint am rechten Bildschirmrand und stellt die wichtigsten Daten und Funktionen zum ausgewählten Datensatz übersichtlich dar.

Sollten Sie zusätzlich dazu das *Bearbeiten*-Fenster öffnen und Änderungen vornehmen, so werden diese nach dem Speichern von der Vorschau-Funktion übernommen.

.. image:: ../images/gui/vorschaufunktion.png

Tastenkürzel
------------
:kbd:`Strg+S`
:kbd:`Alt+C`
:kbd:`Shift+V`
:kbd:`ESC`

=====  =====  ====== 
   Eingaben     Funktion 
------------  ------ 
STRG   S      speichert aktuelle Änderungen 
STRG   C      kopiert markierte Eingabe 
STRG   V      fügt kopierte Eingabe ein 
ESC           schließt aktives Fenster / den Vorschau-Bereich 
=====  =====  ======

