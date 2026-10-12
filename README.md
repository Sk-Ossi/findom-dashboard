# Findom Dashboard · DTC Digital

Lokales Kassenbuch für die Übersicht über manuell erfasste Tribute und Zahlungen in einer einvernehmlichen Findom-Dynamik zwischen Erwachsenen.

## Version 1.0.0

Erste Veröffentlichung der bereitgestellten Datei `Findom_Dashboard.html`. Die Originaldatei bleibt unverändert.

## Funktionen

- Zahlungen mit Datum, Betrag, Kategorie, Zahlungsweg, Session und Notiz erfassen und bearbeiten.
- Monatsübersichten, Jahresverlauf und Summen anzeigen.
- Zahlungen nach Sessions gruppieren und durchsuchen.
- Monatliches Spielbudget mit Übersicht über Ausgaben und verbleibendes Budget festlegen.
- Schuldscheine erfassen und Zahlungen zuordnen.
- Hinterlegte Tributstufen anzeigen.
- Zahlungseinträge als CSV exportieren und CSV- oder JSON-Dateien importieren.

## Verwendung

ZIP entpacken und `Findom_Dashboard.html` im Browser öffnen. Keine Installation oder Anmeldung erforderlich. Zahlungen werden nur dokumentiert; das Tool führt keine Überweisungen aus.

Die Daten bleiben im lokalen Browserspeicher. Keine automatische Synchronisierung oder Übermittlung an DTC Digital. Der vorhandene X-Profillink wird erst beim Anklicken geöffnet. Die Datei lädt keine externen Bibliotheken.

## Datensicherung

Regelmäßig exportieren, besonders vor Gerätewechsel oder dem Löschen von Browserdaten. Das Archiv und die Exporte sind nicht verschlüsselt.

**Der vorhandene CSV-Export ist kein vollständiges Backup:** Er enthält Zahlungseinträge, Empfänger, Jahre und Budgets, aber keine Schuldschein-Datensätze und keine Zuordnungen von Zahlungen zu Schuldscheinen. Der Import stellt diese deshalb nicht wieder her. Mehrzeilige Notizen können beim CSV-Import ebenfalls unvollständig eingelesen werden. Die Originaldatei wurde für diese Veröffentlichung nicht geändert.

## Veröffentlichung

Öffentliches Repository: `Sk-Ossi/findom-dashboard`

Release-Tag: `v1.0.0`

Release-Titel: `Findom Dashboard 1.0.0`

Release-Datei: `Findom-Dashboard-v1.0.0.zip`

Die vorhandene Copyright-Angabe bleibt erhalten. Kostenloser Download bedeutet keine zusätzliche Erlaubnis zur Weiterverbreitung oder Änderung.
