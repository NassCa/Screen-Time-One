# Screen Time One: Nutzung und Prüfhinweise

Digitale Mini-DIPS-Arbeitsfassung, Version 2.0, Stand 14. September 2026. Grundlage ist die bereitgestellte PDF „Mini-DIPS Open Access“, Jürgen Margraf und Jan Christopher Cwik, 2., überarbeitete Auflage, © 2017.

## Starten

- **Einzeldatei:** `screen-time-one.html` herunterladen und in einem aktuellen Desktop-Browser öffnen. Interview, Schrift, Original-Seitenbilder und Original-PDF sind eingebettet; eine Internetverbindung ist hierfür nicht erforderlich.
- **Offline-Paket:** Die ZIP-Datei vollständig entpacken. `index.html` ist der Einstiegspunkt; Unterordner und Begleitdateien müssen zusammenbleiben.
- **PWA:** Für die Installation das entpackte Paket über HTTPS oder localhost bereitstellen, einmal vollständig online öffnen und anschließend die Installationsfunktion des Browsers verwenden. Die Installation aus einer direkt geöffneten Datei ist nicht vorgesehen. Eine Installation auf einem realen iPhone oder Android-Gerät wurde nicht geprüft.
- **Private Vorschau:** Zum Ausprobieren mit erfundenen Angaben geeignet. Ist der Browserspeicher dort gesperrt, weist die App darauf hin; Eingaben dann als JSON sichern.

## Was übertragen wurde

Die Arbeitsfassung enthält 38 digitale Interviewkapitel einschließlich Stammdaten und Abschluss. Interviewtexte, Unterfragen und klinische Kriterien wurden aus der PDF übertragen; die Originalansicht bleibt zum Vergleich erreichbar.

- **Antwortfelder:** 283 Interview- und Steuerfelder sowie 105 fachliche Kriterienfelder. Die 283 Felder umfassen ausdrücklich markierte digitale Ergänzungen und sind daher keine Zählung ausschließlich ursprünglicher Fragen.
- **Wortlaut:** Auch bestätigte Schreibfehler und die unvollständige Frage auf Originalseite 68 bleiben erhalten. Sie wurden nicht stillschweigend korrigiert.
- **Originalansicht:** „Originalseite vergleichen“ öffnet den Textauszug; „Original-Seitenbild anzeigen“ zeigt das ursprüngliche Layout. Die vollständige Original-PDF ist ebenfalls enthalten.
- **Fachliche Einschätzung:** Kriterien, Beurteilung, Zeitbezug und Schweregrad werden durch die interviewende Fachperson dokumentiert. Die klinische Originalskala reicht von 0 bis 8; zusätzliche Verlaufseingaben sind keine diagnostischen Testwerte.

## Ablauf und Sprungregeln

Antworten steuern die angebotenen Kapitel und Detailfragen. Die App unterscheidet „NEIN“, „Unklar / nicht beurteilbar“, fehlende Antworten und durch Sprungregel nicht erhobene Angaben; sie leitet daraus keine automatische Diagnose ab.

- **Antwortänderungen:** Abhängige Detailangaben, Kriterienbewertungen und Gesamtbeurteilungen werden bei relevanten Änderungen zurückgesetzt. Ein späterer Rückwechsel bringt keine veralteten Antworten zurück.
- **Explizite Sprünge:** Ein ausdrücklich genanntes Ziel der Vorlage hat Vorrang vor einem zuvor negativen Screening des Zielbereichs. Dies gilt auch aus manuell zusätzlich aufgenommenen Modulen.
- **Zusammenfassendes „Falls NEIN“:** Wo die Vorlage mehrere Screeningfragen mit einer gemeinsamen Sprunganweisung verbindet, wird der Gruppensprung erst bei ausschließlich negativen Antworten ausgeführt. Das ist eine dokumentierte Umsetzungsentscheidung, keine nachträgliche Präzisierung durch die Originalautoren.
- **Zusätzliche Steuerfelder:** Wo Freitext allein keinen eindeutigen digitalen Sprung erlaubt, gibt es gekennzeichnete fachliche Steuerentscheidungen. Diese Felder werden nicht als Originaltext ausgegeben.
- **Trauma und Zeitbezug:** Die unterschiedliche Formulierung „vier Wochen“ beziehungsweise „letzter Monat“ wird nicht aus einer freien Datumsangabe automatisch interpretiert. Die Fachperson entscheidet im gekennzeichneten Steuerfeld; weitere Ereignisse können getrennt dokumentiert werden.
- **Sicherheitsfragen:** Das Suizidscreening bleibt Bestandteil des Ablaufs. Hinweise in der Oberfläche ersetzen keine persönliche fachliche Abklärung und sind keine Risikoberechnung.

Vor einer fachlichen Freigabe sind insbesondere die zusammenfassenden NEIN-Sprünge auf den Seiten 16, 24, 36, 42, 48 und 56, lokale Sprungziele bei negativem vorherigem Screening, die Ereignisabgrenzung auf den Traumaseiten und die BN/BE-Verzweigung auf den Seiten 38/40 zu prüfen. Alle übernommenen Routing-Hinweise sind in der App unter „Vorlage, Prüfhinweise und Sprungregeln“ zugänglich.

## Speichern, Exportieren und Datenschutz

Die App selbst enthält keine Serverübertragung der eingegebenen Antworten, keine Analyse-Telemetrie und keine externe Schriftabfrage. Das ist keine Aussage über die Sicherheits- oder Datenschutzfreigabe eines gewählten Hostingdienstes, Endgeräts oder Browsers.

- **Lokale Sicherung:** Autosave ist optional. Ohne aktivierte und verfügbare lokale Sicherung gehen Eingaben beim Schließen oder Neuladen verloren.
- **Unverschlüsselte Daten:** Browserspeicher, JSON, CSV und gedruckte Protokolle sind nicht durch diese App verschlüsselt. Sie können sensible Angaben enthalten und müssen entsprechend geschützt werden.
- **JSON:** Für die Sicherung und spätere Fortsetzung in derselben Inhaltsversion verwenden. Importierte Antworten und Bewertungen werden validiert; unzulässige oder nicht mehr aktive Werte werden abgewiesen oder bereinigt.
- **Ältere App-Daten:** Alte Datenbestände werden nicht automatisch migriert. JSON-Dateien der früheren Platzhalterfassung oder mit abweichendem Inhaltsstand werden nicht als passend angenommen.
- **CSV und PDF:** CSV dient der tabellarischen Dokumentation. Über „Drucken / PDF“ kann das Interviewprotokoll mit der PDF-Funktion des Browsers ausgegeben werden.
- **Änderungsprotokoll:** Änderungen sind innerhalb des Fallbestands nachvollziehbar. Dies ist kein manipulationssicheres, revisionsfestes Audit-System.
- **Dateimodus:** Die Verfügbarkeit und Beständigkeit des Browserspeichers beim direkten Öffnen einer HTML-Datei hängen vom Browser ab. Regelmäßige JSON-Sicherungen bleiben erforderlich.

## Durchgeführte technische Prüfungen

Die Tests wurden ausschließlich mit synthetischen Angaben ausgeführt. Die bereitgestellten App-Dateien enthalten keine ausgefüllten Testfälle oder Patientendaten.

- **Regel- und Zustandstests:** 403 von 403 automatisierten Testfällen bestanden. Dazu gehören Screeningkombinationen, explizite Sprünge, unklare Angaben, Kriterieninvalidierung, manuell aufgenommene Module, Ereignisarchivierung und Importvalidierung.
- **Browseroberfläche:** Alle 38 Kapitel bei 1440 und 375 Pixeln Breite aufgerufen; keine horizontale Überbreite oder JavaScript-Laufzeitfehler festgestellt. Zusätzlich wurden unter anderem Navigation, Quellenansicht, dunkle Darstellung, Druckansicht, JSON-Import/Export und lokale Fortsetzung geprüft.
- **Einzeldatei:** Im lokalen Dateimodus ohne externe HTTP-Anfragen geladen; eingebettetes Originalseitenbild und PDF-Download geprüft.
- **Offline-PWA:** Nach erfolgreichem erstmaligem Laden und Aktivierung des Service Workers die Netzwerkverbindung im Testbrowser deaktiviert, neu geladen und eine Originalseite geöffnet.
- **Gesperrter Speicher:** App bleibt bedienbar und zeigt einen klaren Hinweis zur notwendigen JSON-Sicherung.

Diese Ergebnisse sind technische und textliche Qualitätssicherung im Chromium-Testbrowser. Sie sind keine vollständige klinische Validierung, keine unabhängige fachliche Freigabe des gesamten digitalen Verfahrens und kein Nachweis umfassender Browser-, Barrierefreiheits- oder Medizinproduktkonformität.

## Nutzungsvorbehalt

Die Fassung ist zur fachlichen Prüfung vorgesehen. Vor einem Einsatz mit Patienten sind insbesondere fachliche Freigabe, Datenschutz, Endgeräteschutz und Nutzungsrechte zu klären.

Die Vorlage nennt die Lizenz [CC BY-NC-ND 4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/). Mit der Bereitstellung dieser Arbeitsfassung wird keine Erlaubnis zur kommerziellen Nutzung oder zur Weitergabe einer bearbeiteten Fassung zugesichert; eine öffentliche Veröffentlichung wurde nicht vorgenommen.
