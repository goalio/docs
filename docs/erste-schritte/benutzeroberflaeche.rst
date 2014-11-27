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

Fenster
.......

Ein Fenster (bzw. Formular oder Dialog) öffnet sich in der Regel bei einem Doppelklick auf einen Datensatz (also beispielsweise ein Mitglied in der Mitgliederliste), welcher daraufhin in der Regel bearbeitet werden kann.

.. image:: ../images/gui/fenster.png

Reiter
......

Ist ein Fenster durch ein horizontales Menü in unterschiedliche Abschnitte gegliedert, so spricht man von Reitern (oder Tabs). Betrachtet man also die Mitgliederliste, so handelt es sich bei einem Mitglied um einen Datensatz, beim Bearbeiten-Formular um ein Fenster, und bei den dortigen Abschnitten *Adresse*, *Zahlung* oder *Aufgaben* um Reiter.

.. image:: ../images/gui/reiter.png

Schaltflächen
.............

Schaltflächen (auch Buttons oder Knöpfe) sind Bedienelemente, welche das System anweisen, eine bestimmte Operation auszuführen. Beispiele hierfür sind die Schaltflächen *Speichern*, *Löschen* oder auch *Suche*.

.. image:: ../images/gui/schaltflaechen.png

Auswahl-Menüs
.............

Auswahl-Menüs (auch Dropdown-Menüs oder Listenmenüs) sind eine platzsparende Möglichkeit, mehrere Listenpunkte verschachtelt darzustellen. Sie öffnen sich erst, sobald sich der Mauszeiger auf der dafür vorgesehenen Fläche befindet.

.. image:: ../images/gui/dropdown-menu.png

Operatoren
..........

Operatoren können in Suchfeldern angeben, wie ein bestimmtes Kriterium ausgewertet werden soll. Wählt man beispielsweise *ist gleich*, so werden ausschließlich jene Ergebnisse angezeigt, die exakt mit dem Kriterium übereinstimmen. Möglich ist die Verwendung folgender Operatoren:

====================  =======
Operator              Wirkungsweise
====================  =======
Beginnt mit           Liefert alle Ergebnisse, die mit der Eingabe beginnen (Mus **>** Mustermann, Muse)
Enthält               Liefert alle Ergebnisse, welche die Eingabe beinhalten (ster **>** Mustermann, Holstern)
Ist gleich            Liefert alle Ergebnisse, die mit der Eingabe übereinstimmen (Mustermann **>** Mustermann)
Größer oder gleich    (Bei Datumsangaben) Liefert alle Ergebnisse, bei denen das Datum in der **Zukunft** liegt oder nicht ausgefüllt ist
Kleiner oder gleich   (Bei Datumsangaben) Liefert alle Ergebnisse, bei denen das Datum in der **Vergangenheit** liegt oder nicht ausgefüllt ist
Ist nicht gleich      (Bei Datumsangaben) Liefert alle Ergebnisse, die nicht dem Datum entsprechen
Nicht gesetzt         Liefert alle Ergebnisse, bei denen dieses Feld nicht ausgefüllt ist
Gesetzt               Liefert alle Ergebnisse, bei denen dieses Feld ausgefüllt ist
====================  =======

.. image:: ../images/gui/operator.png

Vorschaufunktion
----------------

Haben Sie eine Datenübersicht (Mitgliederliste,  Abteilungsliste, ...) geöffnet, so können Sie durch Klick auf einen der Einträge die Vorschaufunktion aufrufen. Diese erscheint am rechten Bildschirmrand und stellt die wichtigsten Daten und Funktionen zum ausgewählten Datensatz übersichtlich dar.

Sollten Sie zusätzlich dazu das *Bearbeiten*-Fenster öffnen und Änderungen vornehmen, so werden diese nach dem Speichern von der Vorschau-Funktion übernommen.

.. image:: ../images/gui/vorschaufunktion.png

Tastenkürzel
------------

===============  ===============
Eingaben         Funktion
---------------  ---------------
:kbd:`Strg+S`    speichert aktuelle Änderungen
:kbd:`Strg+C`    kopiert markierte Eingabe
:kbd:`Strg+V`    fügt kopierte Eingabe ein
:kbd:`ESC`       schließt aktives Fenster / den Vorschau-Bereich
===============  ===============

