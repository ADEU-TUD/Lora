# Werkzeug-Analyse (14.11.2026)

Wie die Werkzeuge in Lora besser werden: 85 Vorschläge aus dem Abgleich aller Werkzeuge mit ihren Vorbildern und dem Alltag
an der TU Dresden (README, Arbeitsplan, Design-Arbeitsplan, Code). Was es schon gab oder schon geplant war (AP-126 bis AP-130,
APD-16/17b, AP-87 bis AP-102), ist nicht enthalten. Der Hauptnutzer hat 79 übernommen (F-07 Abstimmen im Hörsaal danach gestrichen); sie stehen als **AP-131 bis AP-154** im
[Arbeitsplan](ARBEITSPLAN.md) und als **APD-18/APD-19** im [Design-Arbeitsplan](DESIGN-ARBEITSPLAN.md). Priorität und Größe
sind der Vorschlag der Analyse (Größe: S bis 1 Tag · M einige Tage · L 1–2 Wochen).

## Für alle Werkzeuge

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| Q-01 | **Befehle des Werkzeugs in Strg+K suchen** – Wie „Menüs durchsuchen“ in Google Docs (Alt+/): Jede Menüfunktion des offenen Editors ist per Name findbar und ausführbar („Spalte einfügen“, „Seitenränder“, „Untertitel“). Wer die Funktion nicht findet, tippt einfach. | hoch ★ | M | AP-135 |
| Q-02 | **Weiterarbeiten: zuletzt bearbeitet über alle Werkzeuge** – Startseite und *Erstellen* zeigen die letzten Dateien aller Werkzeuge (Dokument, Videoprojekt, PDF, Transkript) und springen an die Stelle, an der man aufgehört hat. | mittel | S–M | AP-135 |
| Q-03 | **Tastenübersicht je Werkzeug** – Strg+/ zeigt im Video die Video-Tasten, in Tabellen die Excel-Tasten, im PDF die PDF-Tasten – heute nur App-Kürzel und Dokument. | mittel | S | AP-135 |
| Q-04 | **Ungespeicherte Arbeit nach Absturz wiederherstellen** – In jedem Editor (Video, Gestalten, Folien, PDF-Markierungen, Transkript-Korrekturen) einheitlich prüfen und ergänzen: Zwischenstand laufend sichern, beim nächsten Start „Wiederherstellen?“ anbieten. | hoch ★ | M | AP-134 |
| Q-05 | **Verlauf der Schritte mit Sprung zurück** – *Bearbeiten › Verlauf*: die letzten Schritte mit Namen („Spalte gelöscht“, „Bild verkleinert“), Klick springt dorthin zurück – wie in Photoshop. Ergänzt Strg+Z. | niedrig | M | AP-134 |
| Q-06 | **Lora kann alles, was die Menüs können** – Ein Test listet jede Menüfunktion ohne Lora-Aktion; die Lücken werden geschlossen, damit „Lora, mach …“ in jedem Werkzeug vollständig geht. | mittel | M | AP-142 |
| Q-07 | **Geführte Prüfung am Gerät** – Viele Pakete stehen auf ◐ „Prüfung am Gerät offen“. Eine Checkliste in der App (*Einstellungen › Über › Prüfungen*) führt Schritt für Schritt durch die offenen Prüfungen – Ja/Nein, Notiz, Bildschirmfoto – und schickt den Bericht über *Problem melden*. Baut den Rückstau gezielt ab. | hoch ★ | M | AP-133 |
| Q-08 | **Tempo großer Dateien messen und sichtbar machen** – Messkorpus (Dissertation mit 200 Seiten, Tabelle mit 50 000 Zeilen, Video 1 h, PDF mit 300 Seiten); Öffnen, Tippen, Speichern, Export werden je Release gemessen. Wird etwas langsamer, fällt es vor dem Release auf. | mittel | M | nicht übernommen |
| Q-09 | **Barrierefreiheit der App selbst (BITV)** – Jedes Werkzeug vollständig mit der Tastatur bedienbar (Fokusreihenfolge, sichtbarer Fokus), Screenreader-Beschriftungen mit NVDA geprüft, als Test abgesichert. Für Kolleg:innen mit Einschränkungen und für die Pflichten der TU. | mittel | M–L | APD-18 |
| Q-10 | **Teilen über die TU-Cloud mit Link** – Aus *Dateien* und jedem Editor einen Freigabelink in der Nextcloud (Datashare) erzeugen – mit Ablaufdatum und Passwort, Link in die Zwischenablage oder als Mail-Entwurf. | mittel | M | AP-143 |
| Q-11 | **„Herunterladen als …“ mit Verlustanzeige überall** – Die Verlustanzeige des Formatwandlers („geht verloren: Kommentare, Spaltenbreiten“) auch bei jedem Export aus den Editoren. | niedrig | S–M | AP-143 |
| Q-12 | **Strg+P überall** – Drucken mit Vorschau aus jedem Editor, dahinter der vorhandene Druck-Lotse (doppelseitig, Broschüre, Prüfung vor dem Druck). | mittel | S | AP-135 |
| Q-13 | **Inhalte zwischen Werkzeugen ziehen** – Tabellenbereich ins Dokument, Bild aus *Dateien* auf eine Folie, PDF-Seite als Bild ins Poster, Diagramm in die Präsentation – per Ziehen statt Export/Import. | mittel | M | AP-143 |
| Q-14 | **Hilfe zur aktuellen Ansicht** – „?“ in jedem Werkzeug öffnet eine kurze, bebilderte Hilfe genau zu dieser Ansicht (offline) und bietet die passende Tour an. | niedrig | S–M | APD-19 |

## Dokumente

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| D-01 | **Eigene Ersetzungen in der Autokorrektur** – Offen aus AP-125 (b): eigene Liste („mfg“ → „Mit freundlichen Grüßen“, „TUD“ → „TU Dresden“) unter *Extras › Autokorrektur*. | mittel | S | AP-125 (f) |
| D-02 | **Seitenplan für umflossene Bilder genau** – Offen aus AP-125 (e): ein Bild, das höher ist als der Text daneben, wird in der Seitenansicht richtig eingeplant (kein Überstehen am Seitenende). | mittel | S–M | AP-125 (f) |
| D-03 | **Geschlechtergerechte Sprache nach dem Leitfaden der TU** – Als Regel der Hausstil-Prüfung: markierte Stellen mit Vorschlägen im Rechtsklick, wie die Rechtschreibung. Einstellbar (Doppelpunkt, Paarform, neutral). | mittel | M | AP-140 |
| D-04 | **Lesbarkeit und Leichte Sprache** – Lesbarkeitswert je Absatz (Wiener Sachtextformel), zu schwierige Absätze markiert; Lora schlägt eine einfachere Fassung vor; Modus „Leichte Sprache“ für Merkblätter und Aushänge. | niedrig | S–M | AP-140 |
| D-05 | **Ausfüllbare Formulare im Dokument** – Felder einfügen: Textfeld, Kontrollkästchen, Auswahlliste, Datum – in Word als Inhaltssteuerelemente, im PDF ausfüllbar. Für Anträge und Formulare der Verwaltung. | hoch ★ | M–L | AP-140 |
| D-06 | **Serienbrief im Editor** – Die vorhandenen Serienbriefe in den Dokument-Editor holen: Feld aus Tabelle einfügen, Vorschau je Datensatz blättern, Ausgabe als ein PDF, einzelne Dateien oder Entwürfe in Outlook. | mittel | M | nicht übernommen |
| D-07 | **Gleichzeitige Änderung über die Cloud zusammenführen** – Wurde dieselbe Datei auf einem anderen PC geändert, führt der Editor beide Fassungen Absatz für Absatz zusammen (Konflikte zum Auswählen) statt eine neue Version anzulegen. | mittel | M | nicht übernommen |
| D-08 | **Kommentare mit @Person und Aufgabe** – @Name im Kommentar weist eine Aufgabe zu; auf Wunsch Mail-Entwurf an die Person mit Link zur Stelle; offene Aufgaben in der Statusleiste. | niedrig | S–M | AP-140 |
| D-09 | **LaTeX öffnen** – .tex-Dateien von Kolleg:innen als Dokument öffnen (Abschnitte, Formeln, Literatur, Tabellen) – Export nach LaTeX gibt es schon. | niedrig | M | AP-153 |
| D-10 | **Großes Werk aus mehreren Dateien** – Dissertation oder Skript als Kapitel-Dateien mit gemeinsamem Inhalts-, Abbildungs- und Literaturverzeichnis und fortlaufenden Nummern – wie ein Masterdokument. | mittel | L | AP-153 |
| D-11 | **Ganzes Dokument übersetzen, Layout bleibt** – DE ↔ EN als neue Datei mit gleicher Formatierung, Tabellen und Bildern; eigenes Glossar (Fachbegriffe, Namen der TU-Einrichtungen). | mittel | M | AP-140 |

## Tabellen

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| T-01 | **Echte Pivot-Tabellen** – Felder in Zeilen, Spalten, Werte ziehen; Filter; als echte PivotTable nach Excel. Heute nur „wie Pivot“ über Lora. | mittel | L | AP-144 |
| T-02 | **Bedingte Formatierung bearbeiten** – Farbskalen, Datenbalken, Regeln („über 90 % grün“) anlegen und ändern – heute bleibt sie nur erhalten. | mittel | M | AP-144 |
| T-03 | **Zahlen- und Datumsformate wie Excel** – Währung, Prozent, Tausendertrennzeichen, Nachkommastellen, eigene Formate („0,0 "Pkt."“), Datum/Uhrzeit-Formate – als Menü und Leistenknöpfe. | mittel | S–M | AP-144 |
| T-04 | **Notenliste für die Lehre** – OPAL-Bewertungsexport einlesen, Punkte nach Notenschlüssel der Prüfungsordnung in Noten umrechnen, Notenspiegel als Diagramm, Export für Selma. Ergebnis wird nicht entschieden, nur berechnet (KI-Verordnung bleibt gewahrt). | hoch ★ | M | nicht übernommen |
| T-05 | **Daten auswerten mit Statistik-Assistent** – Beschreibende Statistik, t-Test, Chi², Korrelation, Regression – mit Erklärung in Klartext und Ergebnissatz im APA-Stil; Ergebnisse als Tabelle neben den Daten. | mittel | M–L | AP-145 |
| T-06 | **Formel Schritt für Schritt auswerten** – Wie Excels „Formel auswerten“: Teilausdrücke nacheinander berechnen, Fehlerquelle sehen. | niedrig | S–M | AP-144 |
| T-07 | **Zwei Listen abgleichen** – Zwei Teilnehmer- oder Inventarlisten vergleichen: neu, fehlt, geändert – farbig und als Ergebnisblatt. | mittel | S–M | AP-144 |
| T-08 | **Diagramme ausbauen** – Fehlerbalken, zweite Achse, Werte am Punkt, Farben je Reihe, Achsenbereich – für Paper und Berichte. | mittel | M | AP-144 |
| T-09 | **Eingabemaske für Zeilen** – Aus den Spalten ein Formular zum bequemen Erfassen und Blättern von Datensätzen (wie Excels Maske). | niedrig | S–M | AP-144 |

## Folien

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| F-01 | **Präsentation aufzeichnen → Lehrvideo** – Vorführen mit Mikrofon (und Kamerabild in der Ecke), danach direkt als Video im Videoeditor: Folienwechsel als Kapitel, Untertitel aus der Transkription. Der schnellste Weg zum Lehrvideo. | hoch ★ | L | AP-141 |
| F-02 | **Video und Ton auf Folien** – Einbetten, beim Vorführen abspielen, in PowerPoint mitnehmen. | mittel | M | AP-141 |
| F-03 | **Barrierefreiheits-Check für Folien** – Folientitel, Lesereihenfolge, Alternativtexte, Kontrast – mit *Beheben* wie im Dokument. | mittel | S–M | AP-146 |
| F-04 | **Vertonte Präsentation ohne Aufnahme** – Sprechertexte mit der natürlichen Stimme auf dem Gerät (AP-111) vorlesen lassen und als Video ausgeben – für Erklärvideos ohne eigene Aufnahme. | mittel | M | AP-141 |
| F-05 | **Foliensatz übersetzen, Layout bleibt** – DE ↔ EN mit gleichem Layout, Notizen mit übersetzt; zu lange Texte werden markiert. | niedrig | S–M | AP-146 |
| F-06 | **Lückenhandout für Studierende** – Aus den Folien ein Handout mit Lücken (Schlüsselbegriffe ausgespart) und Lösungsblatt. | niedrig | S | AP-146 |
| F-07 | **Abstimmen im Hörsaal** – Frage-Folie mit QR-Code, Antworten per Handy, Ergebnis live auf der Folie. Braucht einen kleinen Dienst oder einen Export zu einem vorhandenen Abstimmungswerkzeug der TU – zuerst klären. | niedrig | L | gestrichen |

## Gestalten und Whiteboard

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| G-01 | **Whiteboard für Brainstorming** – Haftnotizen, Rahmen für Gruppen, Abstimmungspunkte; Lora ordnet die Notizen zu Themen und schreibt ein Ergebnisprotokoll. | mittel | M | AP-148 |
| G-02 | **Verbinder auf der Gestalten-Leinwand** – Offen aus AP-50/AP-61: Linien und Pfeile, die an Formen haften, auch in Gestalten (heute nur in Diagrammen). | mittel | S–M | AP-148 |
| G-03 | **Tagungsposter aus dem Paper** – Lora füllt die Poster-Vorlage aus einem PDF: Abschnitte, Abbildungen, Literatur, QR-Code zum Paper – wie heute schon bei Folien. | mittel | M | AP-148 |
| G-04 | **Druckfarben-Vorschau** – Vorschau, wie das Poster im Druck (CMYK) aussieht, mit Hinweis auf Farben außerhalb des Druckbereichs. | niedrig | M | AP-148 |

## PDF

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| P-01 | **Text im PDF wirklich bearbeiten** – Absatz ändern mit gleicher Schrift und neuem Zeilenumbruch, statt weiß zu überdecken. | mittel | L | AP-149 |
| P-02 | **Tabellen für PDF/UA erkennen** – Offen aus AP-60: Tags für Tabellen (Kopfzeilen, Zellen), damit barrierefreie PDFs vollständig sind. | mittel | M | AP-149 |
| P-03 | **Stapelverarbeitung im Werkzeugkasten** – Viele PDFs oder einen Ordner auf einmal: Texterkennung, verkleinern, PDF/A, Wasserzeichen, Schwärzen nach Liste – mit Fortschritt und Bericht. (Heute über Lora/Abläufe, ohne eigene Ansicht.) | hoch ★ | M | AP-137 |
| P-04 | **Wasserzeichen und Kopfzeile ins PDF** – „Entwurf“, „Vertraulich“, Datum, Seitenzahl „x von y“ auf alle Seiten. | mittel | S | AP-137 |
| P-05 | **Seiten zwischen Tabs ziehen** – Seiten aus einem offenen PDF in ein anderes ziehen (kopieren oder verschieben). | mittel | S–M | AP-137 |
| P-06 | **Lesezeichen bearbeiten** – Inhaltsverzeichnis des PDF anlegen, umbenennen, verschachteln; aus Überschriften erzeugen. | niedrig | S | AP-137 |
| P-07 | **Markierungen werden Literaturnotizen** – Hervorhebungen und Notizen eines Papers landen als Exzerpt am Literatureintrag (mit Seite). | mittel | M | AP-149 |
| P-08 | **Android zieht nach** – Offen aus AP-64: Schwärzen, Passwort, PDF/A auf dem Handy. | niedrig | M | AP-149 |

## Video

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| VI-01 | **Export für Videocampus Sachsen und OPAL** – Voreinstellung mit passender Auflösung und Bitrate, Untertitel als VTT daneben, Kapitel; Anleitung zum Hochladen. | mittel | S–M | AP-147 |
| VI-02 | **Kapitel aus dem Transkript** – Lora schlägt Kapitel vor; sie landen in der MP4 und als Liste für die Videobeschreibung. | mittel | S–M | AP-147 |
| VI-03 | **Untertitel-Prüfung** – Zeilenlänge, Lesegeschwindigkeit, Abstände und Lücken prüfen und beheben – für barrierefreie Lehrvideos. | mittel | S | AP-147 |

## Transkription

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| TR-01 | **Qualitative Codierung im Transkript** – Codes an Textstellen, Codebaum, Memos, Übersicht „wo kommt Code X vor“, Export nach REFI-QDA mit Codes – die Auswertung beginnt in Lora statt erst in MAXQDA. | hoch ★ | L | AP-136 |
| TR-02 | **Sprecher über Aufnahmen hinweg wiedererkennen** – Stimmprofil auf dem Gerät merken: „Sprecher 1“ heißt in der nächsten Sitzung gleich wieder „Prof. X“. | niedrig | M | AP-136 |
| TR-03 | **Interviews pseudonymisieren** – Namen, Orte, Einrichtungen im Transkript durchgängig durch Pseudonyme ersetzen (Lora Namensschutz), mit Schlüsselliste im Tresor – für Ethik und Datenschutz in der Forschung. | hoch ★ | S–M | AP-136 |
| TR-04 | **Besprechung → Ergebnisprotokoll mit Aufgaben** – Aus Aufnahme oder Live-Text ein Ergebnisprotokoll im TUD-Design mit Beschlüssen und Aufgaben (wer, was, bis wann); Aufgaben als Outlook-Aufgaben. | mittel | M | AP-150 |
| TR-05 | **Ordner über Nacht transkribieren** – Stapel aus einem Ordner in die Warteschlange, Bericht am Morgen. | niedrig | S | AP-150 |

## Literatur

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| L-01 | **Beliebige Zitierstile (CSL)** – Jeden Stil aus der CSL-Sammlung oder eine Datei des Verlags/Lehrstuhls laden, statt der 8 festen. | hoch ★ | M | AP-138 |
| L-02 | **Citavi-Projekte übernehmen** – Import aus Citavi (Export-Datei) mit Notizen und Schlagwörtern – für Umsteiger an der TU. | niedrig | S–M | AP-138 |
| L-03 | **Volltexte automatisch finden** – Zu jedem Eintrag die frei verfügbare PDF-Fassung suchen (Open Access) und ablegen. | mittel | S–M | AP-138 |
| L-04 | **Literatur-Wächter (nur auf Wunsch)** – Gespeicherte Suche als geplante Aufgabe: neue Paper zum Thema einmal pro Woche als Liste – ohne Benachrichtigungsflut. | niedrig | S–M | AP-138 |
| L-05 | **ISBN/DOI mit der Handykamera** – Buchrücken oder Barcode fotografieren → Eintrag in der Sammlung. | niedrig | S | AP-138 |
| L-06 | **Zitierprüfung im Dokument** – Jede Quelle im Text hat einen Eintrag im Verzeichnis und umgekehrt; fehlende Seitenangaben bei wörtlichen Zitaten markiert. | mittel | S–M | AP-138 |

## Mail und Kalender

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| M-01 | **Textbausteine für Antworten** – Häufige Antworten (Sprechstunde, Prüfungsanmeldung, Abgabefrist) mit Platzhaltern; Lora schlägt den passenden Baustein vor. | hoch ★ | S | AP-139 |
| M-02 | **Anhänge automatisch ablegen** – Regel: Rechnungen, Abgaben, Gutachten → Ordner im Lora-Ordner, mit Vorschau und Rückgängig. | mittel | M | AP-139 |
| M-03 | **Terminmappe** – Vor einem Termin: die Mails, Dateien und das letzte Protokoll zum Thema in einer Mappe (lokal). | niedrig | M | AP-139 |
| M-04 | **Sprechstunden-Zeiten verschicken** – Freie Zeiten aus dem Kalender als Liste oder ICS für eine Mail an Studierende. | niedrig | S | AP-139 |
| M-05 | **Kalender und Aufgaben über den Server** – Abhängig von Offener Frage 3 (Exchange der TU): Termine und Aufgaben auch ohne klassisches Outlook und auf dem Handy. | niedrig | L | AP-154 |

## Dateien und Scanner

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| DA-01 | **Eingangsordner automatisch einsortieren** – Regeln für *Downloads* oder einen Eingangsordner (Rechnungen, Paper, Fotos) mit Vorschau und Rückgängig. | mittel | M | AP-151 |
| DA-02 | **Ordner-Vorlagen für Vorhaben** – „Neues Projekt“ legt die übliche Struktur an (Antrag, Lehrveranstaltung, Abschlussarbeit) – eigene Vorlagen speicherbar. | mittel | S | AP-151 |
| DA-03 | **Scanner: Einzug und doppelseitig** – Offen aus AP-62: mehrere Seiten aus dem Einzug, Vorder- und Rückseiten zusammenführen. | mittel | S–M | AP-151 |
| DA-04 | **Texterkennung auf Android ohne Server** – Offen aus AP-62: eingebaute Texterkennung auf dem Handy statt Bildmodell. | niedrig | M | AP-151 |
| DA-05 | **Speicherplatz-Übersicht** – Was belegt Platz (Videos, Modelle, Cache, Papierkorb) – mit Aufräumen auf Klick. | mittel | S–M | AP-151 |

## Server-Terminal und Tresor

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| S-01 | **Dateien per SFTP** – Seitenfenster mit den Dateien des Servers: hoch- und herunterladen per Ziehen. | mittel | M | AP-131 |
| S-02 | **Gespeicherte Verbindungen und SSH-Schlüssel** – Schlüssel erzeugen und im Tresor ablegen, Verbindungen mit Namen speichern. | mittel | S–M | AP-131 |
| S-03 | **Mehrere Sitzungen in Tabs** – Mehrere Server nebeneinander; Lora sieht, in welcher Sitzung sie hilft. | niedrig | M | AP-131 |
| TS-01 | **Tresor: Schutz bei Fehlversuchen** – Offen: Wartezeit nach falschen PINs, Hinweis bei verdächtigen Versuchen. | mittel | S | AP-152 |
| TS-02 | **Tresor-Projekt verschlüsselt weitergeben** – Ein Forschungsprojekt verschlüsselt an eine Kollegin übergeben (Passwort getrennt mitteilen). | niedrig | M | AP-152 |

## Entwicklung und Qualität

| Nr. | Vorschlag | Priorität | Größe | Paket |
| --- | --- | --- | --- | --- |
| E-01 | **Schnellere Tests für PRs** – Heute rund 27 Minuten lokal für alle Tests. Für PRs nur die betroffenen Bereiche (plus Kern), die volle Sammlung nachts bzw. vor dem Release. | mittel | M | AP-132 |
| E-02 | **Vorher/Nachher automatisch vergleichen** – Bildvergleich mit Abweichung in Prozent und markierten Stellen – die Vergleichsseiten der Design-Stufen entstehen auf Knopfdruck. | mittel | M | AP-132 |
| E-03 | **Sehr große Dateien aufteilen** – LoraFigure.kt (3 600 Zeilen), FlowEditor.kt (2 900), VideoScreen.kt (1 500) in kleinere Teile – leichter zu ändern, weniger Fehler. | niedrig | M | nicht übernommen |
