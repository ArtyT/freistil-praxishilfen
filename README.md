# Praxishilfen für Büroabläufe

Fünf originale CSV-Arbeitshilfen von Freistil Consulting / FreiStil ApS. Sie helfen euch, einen Ablauf einzugrenzen, offene Entscheidungen festzuhalten und eine Vorführung oder einen Test vorzubereiten. Wählt die Tabelle nach der Frage, die ihr gerade klären müsst.

Alle in den CSV-Dateien vorgegebenen Beispiele, Mengen, Zeiten und Prüffälle sind synthetisch. Sie beschreiben keine Kundenarbeit und keine gemessenen Projektergebnisse. Die Kundenonboarding-Checkliste ist eine leere Vorlage mit vorgeschlagenen Anforderungszeilen. Keine Tabelle belegt, dass ein bestimmtes Programm oder eine Freistil-Anbindung die beschriebenen Schritte bereits beherrscht.

## Die passende Tabelle wählen

| Eure Frage | CSV | Leitfaden und Download |
| --- | --- | --- |
| Welchen wiederkehrenden Ablauf sollten wir zuerst vereinfachen? | [Workflow-Auswahl](csv/workflow-auswahl.csv) | [Aufwand, Ausnahmen und Nutzen abwägen](https://www.freistil-consulting.de/de/ressourcen/workflow-auswahl) · [Original-CSV](https://www.freistil-consulting.de/ressourcen/workflow-auswahl.csv) |
| Gehört eine Nachricht zu einer bestehenden Anfrage oder beginnt ein neuer Vorgang? | [Anfragezuordnung prüfen](csv/anfragen-pruefen.csv) | [Zuordnung und Wiederholungen prüfen](https://www.freistil-consulting.de/de/anwendungen/anfragen-zuordnen#anfragen-pruefen) · [Original-CSV](https://www.freistil-consulting.de/ressourcen/anfragen-pruefen.csv) |
| Ist eine Lieferantenrechnung am vereinbarten Ziel angekommen? | [Rechnungsübergabe prüfen](csv/rechnungsuebergabe-pruefen.csv) | [Vorbereitung, Freigabe und Übergabe unterscheiden](https://www.freistil-consulting.de/de/anwendungen/lieferantenrechnungen-vorbereiten) · [Original-CSV](https://www.freistil-consulting.de/ressourcen/rechnungsuebergabe-pruefen.csv) |
| Welche Unterlagen und Entscheidungen fehlen vor dem Start eines Kundenauftrags? | [Kundenonboarding-Checkliste](csv/kundenonboarding-checkliste.csv) | [Auftragsstart vorbereiten](https://www.freistil-consulting.de/de/anwendungen/auftragsstart-vorbereiten#kundenonboarding-checkliste) · [Original-CSV](https://www.freistil-consulting.de/ressourcen/kundenonboarding-checkliste.csv) |
| Welcher Wert einer HubSpot-Kontakteigenschaft ist zu einem früheren Stichtag belegt? | [CRM-Stichtag prüfen: CSV herunterladen](https://github.com/ArtyT/freistil-praxishilfen/raw/refs/heads/main/csv/hubspot-stichtag-pruefen.csv) | [Synthetische Fälle, Quellenabdeckung und Zeitzonen prüfen](guides/hubspot-stichtag-pruefen.md) |

## Zwei CSV-Ausgaben über IDs vergleichen

Gleiche Zeilenzahlen können fehlende oder wiederholte IDs verdecken. Im [CSV-ID-Vergleich](https://www.freistil-consulting.de/de/ressourcen/berichte-abgleichen#csv-vergleich) könnt ihr zwei eigene Dateien oder eingefügten Text ohne Anmeldung lokal im Browser prüfen; die Inhalte werden weder hochgeladen noch dauerhaft gespeichert. Die [Kurzanleitung](guides/csv-id-vergleich.md) zeigt Eingabe, Vergleichsgrundlage und Ergebnisgrenzen anhand eines synthetischen Beispiels. Der Abgleich prüft ausschließlich IDs, keine Beträge oder fachliche Berichtsrichtigkeit.

## Öffnen und prüfen

Ladet die passende CSV herunter und öffnet eine Arbeitskopie in eurem Tabellenprogramm. Wählt beim Import UTF-8. Die vier Dateien mit Website-Originaldownload verwenden Semikolon als Trennzeichen, das neue CRM-Stichtagsblatt verwendet Komma. Die Dateien enthalten keine Formeln, programmierten Auswahlfelder oder automatischen Verbindungen. In der Workflow-Auswahl sind Beispielrechnungen vorbereitet; für eigene Werte müsst ihr die Rechnungen selbst aktualisieren. Bewertete Arbeitszeit ist keine nachgewiesene Einsparung.

Grenzt vor einer Prüfung Anfang, Ende und beteiligte Programme ein. Stimmt die vorgeschlagenen Solltexte mit den verantwortlichen Personen ab. Nutzt für Anfrage- und Rechnungstests ausschließlich erfundene Daten in einer getrennten Testumgebung oder einer Vorführung mit simuliertem Ziel. Es dürfen keine echten Nachrichten, Buchungen, Zahlungen oder Übergaben ans Steuerbüro entstehen. Tragt keine Zugangsdaten oder vertraulichen Unterlagen ein und veröffentlicht keine ausgefüllten Betriebsdaten in diesem Repository.

Haltet anschließend die tatsächliche Beobachtung, den zugehörigen Nachweis, die Entscheidung und den nächsten Schritt mit Zuständigkeit fest. Leere Ergebnisfelder bedeuten nicht „bestanden“. Bei unbekanntem Sendeausgang prüft ihr zuerst das Ziel, bevor ihr erneut sendet. In der Onboarding-Tabelle ist die Gesamtentscheidung zum Auftragsstart von der Prüfung einzelner Anforderungen getrennt.

Die Leitfäden erläutern diese Unterschiede ausführlicher. Die vier CSV-Dateien mit Website-Originaldownload sind unveränderte Kopien der ursprünglichen Freistil-Arbeitshilfen. Das neue CRM-Stichtagsblatt wird hier zusammen mit seiner Anleitung veröffentlicht. Sie dienen der betrieblichen Vorbereitung; die fachlichen Anforderungen einer Rechnungsübergabe klärt ihr mit eurer Buchhaltung oder eurem Steuerbüro.

## Aus Roberts Projektarbeit: CRM-Historie für Auswertungen

Eine frühere Projektaufgabe war, HubSpot-Daten einschließlich ihrer Historie für Attributionsanalysen bereitzustellen. Laut seinen dokumentierten Projektangaben übernahm Robert die technische Konzeption und rund 80 Prozent der Python-Programmierung. Die Verarbeitung lief asynchron und parallel auf AWS. Historische Daten aus dieser Pipeline flossen später in den Vergleich verschiedener Attributionsmodelle in Tableau ein.

Für eure Vorbereitung: Klärt, ob eure Auswertung den heutigen Datenstand oder frühere Zustände braucht. Haltet im Prüffall fest, auf welchen Zeitpunkt sich das erwartete Ergebnis bezieht.

Dieser anonymisierte Rückblick beschreibt frühere Projektarbeit. Die CSV-Arbeitshilfen oben enthalten weiterhin ausschließlich synthetische Beispiele beziehungsweise leere Vorlagen.

## Einen offenen Ablauf besprechen

Freistil berät und setzt individuelle Lösungen passend zu euren Abläufen und vorhandenen Programmen um. Beschreibt zunächst die beteiligten Programme und einen offenen Prüffall. Auf [Roberts öffentlichem Profil](https://www.freistil-consulting.de/de/robert) findet ihr seinen Hintergrund und den Kontaktweg.

English orientation: These German worksheets help scope office workflows, check a historical CRM property value and record agreed test expectations and actual observations. All examples supplied in the worksheets are synthetic; the onboarding sheet starts blank. The linked German guides explain each worksheet.
