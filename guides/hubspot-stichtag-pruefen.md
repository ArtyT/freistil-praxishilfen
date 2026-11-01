# HubSpot-Kontaktwerte zum Stichtag prüfen

Um einen früheren Kontaktwert zu belegen, braucht ihr Datensatz, Eigenschaft, Stichtag und eine Quelle, die den betreffenden Zeitraum abdeckt. Mit diesem [CSV-Arbeitsblatt](../csv/hubspot-stichtag-pruefen.csv) könnt ihr diese Angaben und die vereinbarte Prüferwartung festhalten.

Das Blatt enthält acht unabhängige synthetische Prüffälle und zwei freie Zeilen. Die Kontakt-IDs, das Feld `test_status`, Werte und Zeiten sind erfunden. Ihr könnt die Übung ohne HubSpot-Zugang durchgehen. Beobachtungs-, Nachweis- und Entscheidungsfelder beginnen leer.

## Die Frage eingrenzen

Legt pro Fall einen Kontakt und eine Eigenschaft fest. Notiert die fachliche Frage, die stabile Datensatz-ID, den internen Eigenschaftsnamen und den Stichtag einschließlich Zeitzone. Klärt auch die Grenze: In den Beispielen gilt eine Änderung ab ihrem Zeitstempel einschließlich. Das ist die vereinbarte Regel der Übung.

Haltet drei Zeiten getrennt:

| Zeitangabe | Was sie beschreibt |
| --- | --- |
| Stichtag | Den Zeitpunkt, dessen Feldwert ihr nachweisen wollt |
| Änderungszeit | Wann der Wert laut Quelle im CRM geändert wurde |
| Abruf- oder Exportzeit | Wann ihr den untersuchten Datenstand erhalten habt |

Enthält die Eigenschaft selbst ein fachliches Datum, etwa ein Vertragsdatum, ist auch dieses vom Änderungszeitpunkt zu unterscheiden.

## Die Quelle und ihre Abdeckung festhalten

Notiert Datei oder Ansicht, Abrufzeit, Filter und den tatsächlich verfügbaren Zeitraum. Ein heutiger Wert allein beantwortet keine frühere Stichtagsfrage. Der normale [Datensatzexport](https://knowledge.hubspot.com/import-and-export/export-records) liefert aktuelle Eigenschaftswerte; für frühere Änderungen beschreibt HubSpot einen gesonderten [Historienexport](https://knowledge.hubspot.com/properties/export-property-history).

Die englische Exportdokumentation nennt bis zu 45 gespeicherte Revisionen je Kontakt-Eigenschaft. Das ist keine Zusage einer lückenlosen Lebensgeschichte. Der Export berücksichtigt Datensätze, die einen Wert haben oder früher hatten, und verwendet UTC für Änderungsdaten. Ein fehlender Datensatz beweist daher für sich genommen weder einen leeren früheren Wert noch, dass der Kontakt damals nicht existierte. Exportzugang erfordert laut Dokumentation CRM Export sowie die passende Edit-All-Berechtigung.

Für einen einzelnen Kontakt kann die [Eigenschaftshistorie in der Datensatzansicht](https://knowledge.hubspot.com/records/view-record-property-history) einen zusätzlichen Beleg liefern. Prüft die dort angezeigte Zeitdarstellung gesondert.

## Die Prüffälle durcharbeiten

Öffnet eine Arbeitskopie als UTF-8 mit Semikolon als Trennzeichen. Importiert Zeitangaben als Text, damit Offset und Schreibweise erhalten bleiben. Das Arbeitsblatt ist für die manuelle Prüfung gedacht.

Die Fälle unterscheiden einen belegten Zwischenwert, eine Änderung genau am Stichtag, fehlende frühere Historie, einen aktuellen Snapshot, einen fehlenden Exportdatensatz, zwei lokale Uhrzeiten mit unterschiedlichen Offsets, widersprüchliche gleichzeitige Änderungen und begrenzte Historienabdeckung. Eindeutige Sollwerte gelten nur für die ausdrücklich als vollständig beschriebenen Beispielintervalle. Bei unzureichenden oder widersprüchlichen Belegen bleibt das Ergebnis offen.

Tragt eure tatsächliche Beobachtung, den zugehörigen Nachweis und die Entscheidung mit nächstem Schritt ein. Ein erfolgreich heruntergeladenes Dokument ist ein Abrufbeleg; für den historischen Wert braucht ihr die passende inhaltliche Abdeckung. In den freien Zeilen könnt ihr eigene Prüfungen vorbereiten. Betriebliche Belege bleiben in eurer privaten Arbeitskopie.

## Einen konkreten Prüffall besprechen

Beschreibt uns das beteiligte System, die Kontakt-Eigenschaft, den Stichtag und welche Daten bereits vorliegen. Über [Roberts Profil und Kontaktweg](https://www.freistil-consulting.de/de/robert) könnt ihr eine Prüfung und mögliche Umsetzung mit Freistil besprechen. Umfang und Preis richten sich nach eurem Vorhaben.

Stand: 1. November 2026. Herstellerangaben beziehen sich auf die verlinkte englische Dokumentation. Die Prüffälle sind eigene Lehrbeispiele von Freistil Consulting / FreiStil ApS; es wurden dafür keine Kunden- oder Portaltests durchgeführt.
