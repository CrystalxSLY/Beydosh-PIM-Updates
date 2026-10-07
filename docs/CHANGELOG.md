# Versionshistorie

[Übersicht](../README.md) · [Bedienung](USER_GUIDE.md)

Stand: 07.10.2026, aktiver Owner-Development-Release 0.9.97. Die historischen Einträge 0.9.1–0.9.58 bleiben erhalten; die Ergänzungen bis 0.9.97 geben die PatchNotes der öffentlich vorhandenen Versionsmanifeste wieder. Für 0.9.76 wurde kein veröffentlichtes Versionsmanifest gefunden; dafür wird kein Release behauptet. Die Einträge sind keine unabhängige QA- oder Live-Freigabe.

Zeitangaben sind die UTC-Erstellungszeit signierter Metadaten, nicht zwingend die GitHub-Veröffentlichungszeit. Maßgeblich bleibt der signierte Kanalindex; spätere Versionen können frühere Abläufe ersetzen.

## 0.9.97

Metadaten erstellt: 2026-10-07T08:23:36.7299785+00:00 · [Manifest](../updates/stable/0.9.97/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.97)

- Ergänzung zum Repository-Übergang: Die Anwendung fordert jetzt den kompatiblen Launcher und das Updatewerkzeug 0.9.97 an, statt die ältere Branding-Mindestversion genügen zu lassen.
- Der vorhandene signierte Wartungshelfer und die bestätigte Prozessübergabe bleiben der einzige Aktualisierungspfad. Keine manuelle Ersetzung von Programmdateien.
- Bereits aktuelle oder neuere Launcher werden nicht erneut aktualisiert oder zurückgestuft. Unbekannte Versionen und ältere App-Pakete bleiben durch die bisherigen Prüfungen geschützt.
- Die exakten Repositorypfade, Signaturen, Hashes und historischen Paket-URLs aus 0.9.96 bleiben erhalten. Das Repository wird erst nach bestätigtem Wartungsabschluss umbenannt.
- Keine unveröffentlichten eBay- oder Cloudflare-Funktionen und keine Live-Verkaufsfreigabe enthalten.

## 0.9.96

Metadaten erstellt: 2026-10-07T08:12:46.3753143+00:00 · [Manifest](../updates/stable/0.9.96/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.96)

- Übergangsupdate für den geplanten GitHub-Kanalnamen Beydosh-PIM-Updates.
- Der gemeinsame Updater erlaubt ausschließlich den exakten Namenswechsel unter demselben GitHub-Eigentümer. Signaturen, Hashes, Versionsbindung, Größenlimits und Replay-Schutz bleiben bestehen.
- Historische signierte Paket-URLs bleiben gültig. Fremde Ziele, geänderte Versions- oder Paketpfade und Weiterleitungsschleifen bleiben gesperrt.
- Das Repository bleibt bis zur bestätigten Installation des Übergangsupdates unter der bisherigen technischen Adresse erreichbar.
- Keine unveröffentlichten eBay- oder Cloudflare-Funktionen und keine Live-Verkaufsfreigabe enthalten.

## 0.9.95

Metadaten erstellt: 2026-10-05T14:21:51.1718461+00:00 · [Manifest](../updates/stable/0.9.95/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.95)

- eBay-Anmeldung im Echtbetrieb: Die deutsche Weiterleitung von auth2.ebay.com zu auth2.ebay.de wird nun ebenfalls zugelassen.
- Die erlaubten Ziele bleiben exakt begrenzt. HTTPS, Standardport, Sandbox-Trennung und sichere OAuth-Rückgabe bleiben geschützt.
- Gezielte eBay-Anmelde- und Sicherheitstests erfolgreich. Für den Echtbetrieb sind weiterhin Production-Zugangsdaten und die eigene eBay-Anmeldung erforderlich.

## 0.9.94

Metadaten erstellt: 2026-10-05T14:01:12.8353688+00:00 · [Manifest](../updates/stable/0.9.94/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.94)

- eBay-Echtbetrieb: Die bestätigte Weiterleitung auf auth2.ebay.com wird im Anmeldefenster zugelassen. HTTPS-, Host-, Sandbox- und Rückgabeschutz bleiben erhalten.
- Änderungen bestehender Marktregeln durch die KI behalten den bisherigen Aktivierungszustand. Neue Regeln bleiben zunächst pausiert.
- Märkte und Preisregeln im Produkt werden als klar getrennte, dunkle Karten mit verständlichen Auswahlzuständen dargestellt.
- 137 Desktop-Selbsttests und zusätzliche eBay-Anmeldetests erfolgreich. Keine automatische Live-Verkaufsfreigabe; Production-Zugangsdaten bleiben erforderlich.

## 0.9.93

Metadaten erstellt: 2026-10-04T20:02:12.1564666+00:00 · [Manifest](../updates/stable/0.9.93/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.93)

- Speicherfreigabe nach Hintergrundaufgaben und sichere Bereinigung temporärer Dateien verbessert.
- Produkt- und Attributassistenten lesen gezielt benötigte Daten, statt den gesamten Produktbestand zu laden.
- Große Produktlisten werden im Hintergrund gefiltert; veraltete Suchergebnisse werden verworfen.
- E-Mail-Entwurfslisten laden keine vollständigen Anhänge und Chats mehr. Einzelne Entwürfe werden bei Bedarf geladen.
- Entwurfssynchronisierung blockiert die Bedienung nicht mehr; parallele Speicheraktionen bleiben geschützt.
- Ungültige gespeicherte Daten werden kontrolliert abgefangen. Wiederherstellung von Attributen läuft im Hintergrund.
- 137 automatisierte Desktop-Selbsttests einschließlich synthetischer Oberflächen- und Speicherprüfungen erfolgreich. Keine Freigabe für Live-Verkauf oder echte Kundendaten.

## 0.9.92

Metadaten erstellt: 2026-10-04T19:06:30.7754571+00:00 · [Manifest](../updates/stable/0.9.92/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.92)

- Markt- und Versandkonfiguration laden nur noch die benötigten Grundlagen statt des gesamten Produktbestands.
- Speicherfehler beim Marktassistenten und beim normalen Speichern von Verkaufskanälen behoben.
- Verkaufskanäle, Versandkarten und Ländergruppen werden mit begrenztem Speicherbedarf atomar gespeichert; Produktdaten bleiben unverändert.
- Bestehende Produkttyp-Zuordnungen, Preisprüfungen und Konfliktschutz bleiben erhalten; geänderte Einkaufspreisgrundlagen werden zusätzlich erkannt.

## 0.9.91

Metadaten erstellt: 2026-10-04T17:41:08.0298295+00:00 · [Manifest](../updates/stable/0.9.91/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.91)

- Beydosh PIM 0.9.91
- Produktliste: Die große obere Filterleiste entfällt. Die kompakte weiße Suche mit Lupensymbol und Platzhalter steht ganz rechts.
- Aufklappbare Wertelistenfilter an allen Datenspalten, einschließlich Kategorie, Herkunft, Pflegezustand, EAN, Bestand und Einkaufspreis.
- Spaltenfilter lassen sich kombinieren und einzeln zurücksetzen. Verfügbare Werte berücksichtigen die anderen aktiven Spaltenfilter.
- Sortierung über die Spaltenköpfe bleibt erhalten. Produktauswahlen bleiben auch bei ausgeblendeten Zeilen bestehen.
- Produkt- und Importsuche verwenden einen gemeinsamen Suchbaustein; bestehende Spaltenfilter und Sortierregeln werden wiederverwendet.
- Die E-Mail-Assistentenverbesserungen aus 0.9.90 bleiben enthalten. Keine Änderung an eBay-Live-Sperren oder Versandfreigaben.
- Prüfung: 135 Desktop-Selbsttests einschließlich synthetischer Fensterregression bestanden; Produktansicht gerendert und visuell geprüft. Keine echte eBay-Veröffentlichung.

## 0.9.90

Metadaten erstellt: 2026-10-04T16:19:11.1740571+00:00 · [Manifest](../updates/stable/0.9.90/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.90)

- Beydosh PIM 0.9.90
- Kontaktpflege aus kurzen natürlichen Mailaufträgen: selbstständiger Import durch normale Postfachordner einschließlich Gesendet, ohne manuelle Mailauswahl und ohne erforderlichen E-Mail-Entwurf.
- Kontakte aus beobachteten Absender-, Empfänger-, CC- und Reply-To-Kopfzeilen. Geschäftliche Angaben aus Absender-Signaturen bleiben quellengebunden; keine Zuordnung fremder Signaturen an Empfänger.
- Geprüfte Kontaktangaben werden je Abschnitt gespeichert. Fehler in Entwurf oder globalen Quellen verwerfen gültige Kontaktbeobachtungen nicht mehr.
- Gezielte Rückmeldung und Korrektur fehlerhafter Kontaktangaben; gültige leere Auswertungen erzeugen keine unnötigen Rückfragen.
- Verschlüsselter lokaler Chat-Arbeitsstand auch ohne Entwurf. Unterbrochener Import lässt sich nach erneutem Öffnen fortsetzen; Wiederholung erzeugt keine doppelten Beobachtungen.
- Ausgabe nach Auftrag: Chatantwort, strukturierter Entwurf oder fachliche Rückfrage. Schreiben, PIM-Abfragen, Recherche, Antworten und Weiterleitungen verwenden die vorhandenen gemeinsamen Bausteine.
- Manuelle Kontaktkorrekturen, Löschmarkierungen, Postfach-/Arbeitsbereichstrennung, Lesefreigabe und Signaturverhalten bleiben erhalten. Kein automatischer Versand.
- Prüfung: synthetische Kontaktseiten über 203 Nachrichten und Fensterablauf über 147 Nachrichten mit Unterbrechung und Fortsetzung; bestehende Desktop- und UI-Regression. Keine Prüfung privater Postfächer und keine Garantie vollständiger Firmenangaben.

## 0.9.89

Metadaten erstellt: 2026-10-04T14:51:55.7489833+00:00 · [Manifest](../updates/stable/0.9.89/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.89)

- Beydosh PIM 0.9.89
- Kontakte unter Spam: lokale, filterbare Tabelle mit Firmen, Ansprechpartnern, Funktionen und Kontaktdaten; Hinzufügen, Bearbeiten und Löschen.
- Mailassistent vereinfacht: nur E-Mail-Vorschau und Rückfragen. Antworten, Allen antworten und Weiterleiten werden im Chat beauftragt, nicht über zusätzliche Aktionsbuttons.
- Reine Fragen und Analysen können direkt im Chat beantwortet werden, ohne neuen E-Mail-Entwurf.
- Postfachübersicht über Gesprächskopfzeilen einschließlich Gesendet; mögliche offene Antworten werden als Kandidaten gekennzeichnet, nicht als sicher unerledigt.
- Belegte recherchierte Firmenkontakte werden lokal gespeichert. Quellen bleiben prüfbedürftig.
- Produktassistent ohne Vorauswahl: selbstständige Katalogsuche mit allgemeinen Spaltenfiltern, Trefferzahlen, gruppierten Werten und Produktseiten. Änderungen werden je Artikel angezeigt und erst nach Bestätigung gespeichert.
- Bestehende Feldsperren, Postfach-Lesefreigaben, lokale Verschlüsselung und Revisionsprüfungen bleiben erhalten. Keine automatischen E-Mail-Sendungen.
- Hinweise: Produktänderungsvorschläge umfassen weiterhin bis zu 50 geladene Produkte pro Freigabe. Eine vollständige Kopfzeilenprüfung ist keine vollständige Inhaltsanalyse sämtlicher E-Mails. Getestet mit synthetischen Daten; kein Versand und keine Prüfung privater Postfächer.

## 0.9.88

Metadaten erstellt: 2026-10-04T10:17:46.8201884+00:00 · [Manifest](../updates/stable/0.9.88/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.88)

- Beydosh PIM 0.9.88
- Der E-Mail-Assistent bearbeitet umfangreiche Rechercheaufträge selbstständig und erhält bereits belegte Kontakte sowie gültige Entwürfe.
- Fehlerhafte Teilangaben werden einzeln geprüft und mit konkreter Rückmeldung zur Korrektur an die KI gegeben. Ein brauchbarer Entwurf bleibt erhalten.
- Der neue Reiter Kontakte & Firmen zeigt geschäftliche Ansprechpartner, Firma, Position, Abteilung, Website, Telefon und Anschrift mit Datum und Nachrichtenbeleg. Widersprüche bleiben sichtbar.
- Gesprächsbezüge, Nachrichtenkennungen und abweichende Antwortadressen werden aus freigegebenen E-Mails übernommen. Die Auswertung bleibt auf gezielt geladene Nachrichten beschränkt.
- Kontaktdaten und der vollständige Assistenten-Arbeitsstand werden lokal verschlüsselt und postfachgebunden gespeichert. Beim Laden eines KI-Entwurfs werden Chat, Quellen, Entscheidungen und offene Punkte wiederhergestellt.
- Antworten, Allen antworten und Weiterleiten verwenden dieselbe vorhandene E-Mail-Logik wie der Editor. Gespeicherte Postfachsignaturen werden beibehalten.
- Rechercheübersicht, Fortsetzen, lokale Zwischensicherung und vorherige Entwurfsversion unterstützen längere Aufgaben. Kopieren, Antworten und Aktivität öffnen erhalten die Leseposition im Chat.
- 135 Desktop-Selbsttests und zusätzliche Fenstertests erfolgreich. Kontaktextraktion mit synthetischen Nachrichten geprüft; eine echte Postfachabnahme bleibt offen.

## 0.9.87

Metadaten erstellt: 2026-10-01T21:55:49.6614243+00:00 · [Manifest](../updates/stable/0.9.87/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.87)

- Beydosh PIM 0.9.87
- Mailassistent: Korrekturversuche gelten pro Antwort statt für den gesamten Auftrag. Wiederholte Prüfprobleme führen zu sichtbaren Rückfragen; die konkrete Prüfmeldung erscheint im Aktivitätsverlauf.
- Vorhandene Entwürfe bleiben erhalten und können nach Beantwortung der Rückfrage weiterbearbeitet werden.
- Neue Aktionen: In Entwurf speichern neben Übernehmen sowie Aus Entwurf laden oberhalb der Reiter. Laden zeigt in Beydosh gespeicherte Entwürfe des gewählten Postfachs.
- Überschriften: E-Mail-Assistent links, Gespräch mit der KI rechts; E-Mail-Vorschau bleibt als Reiter.
- Vorhandene lokale Entwurfsverwaltung und Postfach-Synchronisierung werden wiederverwendet. Formatierung, Signaturen und Anhänge geladener Entwürfe bleiben erhalten.
- Desktop-Selbsttests und zusätzliche Fenstertests für Rückfragen, Wiederaufnahme, Speichern und Laden bestanden.

## 0.9.86

Metadaten erstellt: 2026-10-01T20:57:47.1157487+00:00 · [Manifest](../updates/stable/0.9.86/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.86)

- Beydosh PIM 0.9.86
- Mailassistent: konkrete Prüfmeldungen an die KI zurückgeben, damit fehlerhafte Antworten automatisch korrigiert werden können.
- Wird die Korrektur erneut abgewiesen, kann die KI eine verständliche Rückfrage im Reiter Rückfragen formulieren. Vorhandene Entwürfe bleiben erhalten.
- Korrekturversuche sind begrenzt; Quellenprüfung und Postfachberechtigungen bleiben wirksam.
- 134 automatisierte Desktop-Tests bestanden, einschließlich wiederholter Quellenfehler und Rückfrageablauf.

## 0.9.85

Metadaten erstellt: 2026-10-01T20:28:18.4738028+00:00 · [Manifest](../updates/stable/0.9.85/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.85)

- Beydosh PIM 0.9.85
- Mailassistent: tatsächlich recherchierte Webquellen im Quellenfeld korrekt zuordnen, damit verwendbare E-Mail-Entwürfe erhalten bleiben.
- Unbekannte Quellenkennungen einmalig automatisch korrigieren. Unbelegte Quellen bleiben gesperrt.
- Entzogene Postfach-Lesefreigaben bleiben auch bei der Quellenkorrektur wirksam.
- 134 automatisierte Desktop-Tests bestanden, einschließlich Quellenzuordnung, Reparaturablauf und Berechtigungsgrenzen.

## 0.9.84

Metadaten erstellt: 2026-10-01T20:13:24.602355+00:00 · [Manifest](../updates/stable/0.9.84/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.84)

- Beydosh PIM 0.9.84
- Mailassistent: gespeicherte Postfachsignatur mit Formatierung verwenden; ohne gespeicherte Signatur eigene passende Signatur aus bekannten Absenderangaben.
- E-Mail-Editor: Datei, Signatur und Formatierungsaktionen in einer gemeinsamen Button-Zeile.
- Mailrecherche: offene Recherchepunkte selbstständig in Gruppen fortsetzen, geprüfte Kontakte erhalten, bei Stillstand Restliste anzeigen.
- KI-Chats: Kopieren, Antworten und Öffnen der Aktivität lösen keinen Sprung ans Chatende mehr aus.
- 134 automatisierte Desktop-Tests bestanden. Kein automatischer E-Mail-Versand. Vollständigkeit und aktuelle Kontaktangaben bleiben prüfbedürftig.

## 0.9.83

Metadaten erstellt: 2026-10-01T19:50:06.2474044+00:00 · [Manifest](../updates/stable/0.9.83/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.83)

- Beydosh PIM 0.9.83
- Mailassistent: Rechercheprüfung und E-Mail-Editor verwenden dieselbe Empfängerprüfung. Semikolonlisten und leere Felder mit Leerzeichen verursachen keinen nachträglichen Parserabbruch mehr.
- Belegte BCC-Empfänger bleiben erhalten; unbelegte Empfänger werden weiterhin herausgefiltert.
- 134 Desktop-Selbsttests erfolgreich, einschließlich mehrerer BCC-Adressen und vollständigem Entwurfsablauf.

## 0.9.82

Metadaten erstellt: 2026-10-01T19:39:07.2138035+00:00 · [Manifest](../updates/stable/0.9.82/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.82)

- Beydosh PIM 0.9.82
- Mailassistent: E-Mail-Vorschau und Rückfragen als getrennte Reiter. Rückfragen direkt im Eingabefeld beantworten; Übernehmen steht in der Vorschau bereit.
- Bei reinen Rechercheantworten wird der angeforderte Entwurf abschließend erstellt. Bleibt die Antwort unvollständig, erscheinen konkrete Rückfragen.
- Webquellen werden aufklappbar angezeigt. Unerwartete Hintergrundfehler werden im Assistenten gemeldet.
- 134 Desktop-Selbsttests sowie ein echter Recherchetest mit öffentlichem Hersteller und synthetischem BCC-Entwurf erfolgreich. Die vollständige Nutzerabfrage über den eigenen Herstellerbestand ist noch nicht bestätigt.

## 0.9.81

Metadaten erstellt: 2026-10-01T19:25:42.626722+00:00 · [Manifest](../updates/stable/0.9.81/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.81)

- Beydosh PIM 0.9.81
- E-Mail-Assistent: Widersprüchliche Anweisungen für Datenabfragen und Entwürfe korrigiert. Der Entwurf wird nach der Datenabfrage erstellt.
- Vermischt eine KI-Antwort beide Schritte, wird genau einmal eine korrigierte Antwort angefordert und vollständig geprüft. Bei erneutem Fehler bleibt ein vorhandener Entwurf erhalten.
- 134 Desktop-Selbsttests erfolgreich, einschließlich Korrekturversuch, Abbruchgrenze und Erhalt des Entwurfs.

## 0.9.80

Metadaten erstellt: 2026-10-01T19:15:12.09069+00:00 · [Manifest](../updates/stable/0.9.80/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.80)

- Beydosh PIM 0.9.80
- E-Mail-Assistent: Entwürfe bleiben bei offenen Recherchekontakten nutzbar. Unbestätigte Empfänger werden ausgelassen und kenntlich gemacht. Folgefragen erhalten den aktuellen Entwurf; Verbindungsfehler verwerfen ihn nicht.
- Produkt- und Attributassistent: Vorhandene Vorschläge werden bei Folgefragen berücksichtigt und bei Fehlern beibehalten.
- Alle KI-Assistenten: Nachrichten kopieren oder direkt darauf antworten; die ausgewählte Nachricht wird sichtbar an die neue Frage angeknüpft.
- E-Mail: Aktionssymbole werden vollständig innerhalb der Buttons angezeigt.
- 134 Desktop-Selbsttests erfolgreich. E-Mails werden erst durch die normale manuelle Versandaktion gesendet. Visuelle Abnahme durch den Nutzer steht noch aus.

## 0.9.79

Metadaten erstellt: 2026-10-01T18:35:10.1428755+00:00 · [Manifest](../updates/stable/0.9.79/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.79)

- Beydosh PIM 0.9.79: Mail-Recherche mit dem gemeinsamen KI-Zugang verbessert.
- Hersteller und andere freigegebene PIM-Felder lassen sich gefiltert und gruppiert abfragen; Wertelisten werden seitenweise geladen und verbleibende Grenzen sichtbar gekennzeichnet.
- Rechercheauftraege verlangen eine tatsaechlich ausgefuehrte Websuche. Aktuelle Quellenereignisse werden gemeinsam fuer alle Assistenten ausgewertet.
- Recherchierte BCC-Empfaenger werden gegen Kontakteintraege und transportgemeldete Quellen geprueft; unbekannte Angaben werden nicht erfunden.
- Keine Kategorienregeln im Mailassistenten, kein automatischer Versand, keine Produkt- oder Kategorieaenderungen. Entwurf und Empfaenger vor dem Versand pruefen.
- 134 Desktop-Selbsttests und ein echter Recherchetest mit einem oeffentlichen Hersteller erfolgreich. Visuelle Abnahme bleibt offen; Vorabversion im bestehenden Update-Kanal.

## 0.9.78

Metadaten erstellt: 2026-10-01T17:42:19.1864577+00:00 · [Manifest](../updates/stable/0.9.78/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.78)

- Beydosh PIM 0.9.78: Gemeinsame Webrecherche im Grundgeruest aller sechs KI-Assistenten.
- Mail-, Produkt- und Attributassistent recherchieren bei Bedarf oeffentliche Webquellen, ebenso Kategorien, Versand und Verkaufsmaerkte.
- Einheitlicher Recherche-Schalter und Quellenanzeige im Chat; fehlende Recherche und fehlende Quellen werden offen benannt.
- OpenAI-API und Codex unterstuetzt; keine stillen Anbieterwechsel bei anderen Anbindungen.
- Postfach-Lesefreigabe, Importsperren, Pruefung und manuelle Uebernahme bleiben erhalten. Keine automatische E-Mail-Sendung.
- 134 Desktop-Selbsttests erfolgreich. Echte Webrecherche und visuelle Abnahme stehen noch aus; Vorabversion fuer den bestehenden Update-Kanal.

## 0.9.77

Metadaten erstellt: 2026-10-01T17:05:08.4241761+00:00 · [Manifest](../updates/stable/0.9.77/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.77)

- Beydosh PIM 0.9.77
- Der Mailassistent korrigiert nicht verfügbare Produktspalten anhand der freigegebenen Feldübersicht. Wiederholte oder zu umfangreiche Recherche wird verständlich beendet statt mit einer pauschalen Fehlermeldung.
- Fehler erscheinen im Chat mit Diagnosecode. Postfach-Lesefreigabe, Antwortprüfung und Verbindungsfehler werden unterschieden; das vorhandene datensparsame Fehlerprotokoll enthält keine Mailtexte oder Zugangsdaten.
- Fehlende Herstellerländer und Kontaktadressen werden nicht erfunden. E-Mail-Entwürfe müssen weiterhin übernommen und vor dem Senden geprüft werden. Keine automatische E-Mail-Versendung.
- Das Update enthält den signierten Launcher-Wartungshelfer für Beydosh PIM. Das separat reparierte Setup und der Windows-Programmeintrag bleiben erhalten.
- Keine Freigabe für Kundendistribution oder Live-Verkäufe. Visuelle und echte KI-Abnahme bleiben gesondert.

## 0.9.75

Metadaten erstellt: 2026-10-01T15:50:40.0748753+00:00 · [Manifest](../updates/stable/0.9.75/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.75)

- Beydosh PIM 0.9.75
- Der Mailassistent kann Produktdaten jetzt gezielt wie eine Produktliste filtern: mehrere Spaltenbedingungen kombinieren, Attribute und Varianten berücksichtigen sowie Zahlen und fehlende Werte prüfen.
- Die KI kann bei Bedarf die verfügbaren Felder, reine Trefferzahlen, unterschiedliche Spaltenwerte oder ausgewählte Produktdetails abrufen. Hersteller sind nur ein Anwendungsfall. Große Kataloge werden lokal im Hintergrund ausgewertet; es wird nicht der gesamte Produktbestand an die KI übertragen.
- Die Suche berücksichtigt vorhandene manuelle Produktwerte, erfasst auch Treffer nach den ersten 50 Produkten und unterscheidet Kataloggröße von Filtertreffern. Fehlende Länder, Kontaktadressen oder Produktangaben werden nicht erfunden. Postfach-Lesefreigabe und manuelle Übernahme von E-Mail-Entwürfen bleiben erhalten; nichts wird automatisch gesendet.
- Die alten installierten Launcher-/Installer-Bezeichnungen sind in diesem App-Update noch nicht korrigiert. Keine Freigabe für kommerziellen Betrieb oder Live-Verkäufe.

## 0.9.74

Metadaten erstellt: 2026-10-01T14:55:40.8000517+00:00 · [Manifest](../updates/stable/0.9.74/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.74)

- Beydosh PIM: Gemeinsames KI-Assistentenlayout korrigiert.
- KI-Anfragen und neue Teilanfragen öffnen Vorgeschlagene Änderungen; Arbeitsanzeige und Stopp befinden sich oben in diesem Reiter.
- Aktueller Arbeitsverlauf im Chat für Kategorie-, Produkt-, Attribut-, Versand-, Markt- und Mailassistenten.
- Mailassistent mit Arbeitsanzeige in der E-Mail-Vorschau ohne zusätzliche Reiter.
- Attributvorlagen: kompakter KI-Assistent zwischen Attribut hinzufügen und rotem Aus Vorlage entfernen.
- Bestehende Lese-, Import-, Bestätigungs- und Abbruchgrenzen bleiben erhalten. Nichts wird automatisch versendet oder veröffentlicht.

## 0.9.73

Metadaten erstellt: 2026-10-01T14:05:18.7573022+00:00 · [Manifest](../updates/stable/0.9.73/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.73)

- Beydosh PIM 0.9.73 - Aufgeräumter Mailassistent und Ladeanzeige
- Mailassistent: E-Mail-Vorschau links, Gespräch rechts und Übernehmen unten; Empfänger, CC, BCC, Betreff und Text bleiben vor der Übernahme sichtbar.
- Manuelle Ladefelder entfallen. Die KI fordert benötigte Postfach- und PIM-Daten selbst über begrenzte, geprüfte Leseabfragen an.
- Postfachsuche über alle Serverordner, einschließlich eigener Ordner, mit gezielter Ordnerauswahl und Seitenabfragen; keine behauptete Vollständigkeit aus Teilergebnissen.
- KI-Lesefreigabe bleibt je Postfach erforderlich und standardmäßig aus. Widerruf entfernt mailbezogene Gesprächsdaten vor weiteren KI-Aufrufen.
- Mailtexte werden ohne Anhänge, Bilder oder Rohmail abgerufen. PIM-Zugriff bleibt ausschließlich lesend im bestehenden Arbeitsbereich.
- Übernehmen öffnet den vorhandenen E-Mail-Editor ohne Versand. Verschiebevorschläge benötigen weiterhin gesonderte Bestätigung.
- Abbruch, wiederholte Datenabfragen und kleine Fenstergrößen abgesichert; während einer Anfrage neu eingegebener Text bleibt erhalten.
- Nur ein Ladehinweis pro Fenster, auch bei parallelen Startvorgängen. Eigene Fortschritte bleiben erhalten und werden nach Abschluss wieder angezeigt.
- Bestehendes Chatlayout, Mailvalidierung, KI-Transport und PIM-Leser wiederverwendet; keine automatische Core-Synchronisierung.
- Beta-/Owner-Update: keine Kunden-Setup-Freigabe und keine Freigabe für echte Verkäufe oder reale Bestellungen. Echte KI-/IMAP-Abnahme bleibt offen.

## 0.9.72

Metadaten erstellt: 2026-09-30T22:58:30.6362682+00:00 · [Manifest](../updates/stable/0.9.72/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.72)

- Beydosh PIM 0.9.72 - Assistenten und flüssigeres Arbeiten
- Produktassistent: Produkttexte, Übersetzungen und Variantengruppen als geprüfte Vorschläge; importgepflegte Inhalte bleiben geschützt.
- Produkt- und Attributassistent: aktueller Stand, vorgeschlagene Änderungen und Rückfragen in getrennten Reitern; Übernahme nur nach ausdrücklicher Bestätigung.
- Attributassistent als eigener Chat über einen Button, spezialisiert auf die Struktur des jeweiligen Produkttyps.
- Mailassistent: Entwürfe mit An, CC, BCC und Betreff sowie lesende PIM-Grundlage; keine automatische Versendung.
- KI-Lesefreigabe für Nachrichten je Postfach als Schalter, standardmäßig ausgeschaltet.
- E-Mails werden beim Programmstart abgerufen; neue Benachrichtigungen zeigen Absender, Betreff und gekürzten Inhalt.
- Benachrichtigungen haben begrenzte, aufklappbare Inhalte; Doppelklick markiert sie gelesen und öffnet ein vorhandenes internes Ziel.
- Lade-, Speicher- und Schließvorgänge in den überarbeiteten Bereichen laufen im Hintergrund; ausstehende Speicherung wird beim Verlassen berücksichtigt.
- Unbekannte importierte Produkttypen bleiben erhalten und werden als noch nicht eingerichteter Produkttyp gemeldet.
- Gespeicherte Variantenlisten bleiben bestehen; manuelle Änderungen haben Vorrang vor der automatischen Erstinitialisierung.
- Beydosh PIM als sichtbarer Programmname auch in Launcher, Einrichtung und eigenen Programmverknüpfungen; technische Speicheridentitäten bleiben kompatibel.
- Gemeinsame Bausteine für KI-Reiter, Rückfragen, Hintergrundspeicherung, Schließen und Benachrichtigungen statt paralleler Implementierungen.
- Beta-/Owner-Update: keine Kunden-Setup-Freigabe, keine Freigabe für echte Verkäufe oder reale Bestellungen und keine automatische Core-Synchronisierung.

## 0.9.71

Metadaten erstellt: 2026-09-30T19:42:18.2112792+00:00 · [Manifest](../updates/stable/0.9.71/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.71)

- Beydosh PIM 0.9.71 – Produkttyp aus der Importtabelle
- Verbindungsvorlagen bieten jetzt das Standardfeld Produkttyp.
- Eine Quellspalte kann direkt dem Produkttyp zugeordnet werden.
- Die Zuordnung bleibt in der gespeicherten Vorlage erhalten.
- Passende Attribute werden bereits beim ersten Import übernommen.
- Vorhandene Werteübersetzungen gelten auch für Produkttypen.
- Unbekannte Produkttypen werden verständlich gemeldet, nicht erfunden.
- Beim Typwechsel bleiben keine fremden importierten Attribute zurück.
- Bestehende manuelle Zuordnungen behalten ihre bisherige Priorität.
- Die vorhandenen Sicherheits- und Verkaufssperren bleiben unverändert.

## 0.9.70

Metadaten erstellt: 2026-09-30T17:44:09.9589106+00:00 · [Manifest](../updates/stable/0.9.70/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.70)

- Beydosh PIM 0.9.70 Beta – kompakte eBay-Anbindung und Marktzuordnung.
- Der Markt für die Preisberechnung ist direkt bei der Konto-Anbindung auswählbar.
- Vorhandene Preisregeln und gespeicherte Marktkennungen werden unverändert wiederverwendet.
- Die doppelte Marktauswahl im Produktschritt entfällt.
- Ein Wechsel einer bestehenden Marktzuordnung verlangt eine ausdrückliche Bestätigung.
- Abbrechen erhält die bisherige Zuordnung; fehlende oder mehrdeutige Märkte werden nicht ersetzt.
- Lokale Entwicklerdaten sind unter Weitere Einstellungen eingeklappt und bleiben für den eigenen Betrieb verfügbar.
- Der Export-Auswahldialog passt seine Höhe dem Inhalt an; der redundante Erklärungstext entfällt.
- Gemeinsame Bedienbausteine, Marktwechsel-Regressionen und schmale sowie breite Ansichten wurden geprüft.
- Dieses Beta-Update schaltet weder die zentrale Kundenanmeldung noch echte Verkäufe oder Bestellimporte frei; die gemeinsame Nutzerabnahme bleibt offen.

## 0.9.69

Metadaten erstellt: 2026-09-30T14:42:01.4526646+00:00 · [Manifest](../updates/stable/0.9.69/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.69)

- Beydosh PIM 0.9.69 (Beta): Modulare eBay-Einrichtung und produktbezogene Verkaufsauftraege.
- Gefuehrte eBay-Einrichtung mit getrennten Sandbox- und Echtbetrieb-Anmeldungen, geschuetzter Speicherung und automatischer Erneuerung der Zugangsberechtigung.
- Vorhandene Richtlinien und Versandstandorte laden; Kategorien, Artikelzustand und Produktmerkmale zuordnen und gegen eBay-Vorgaben pruefen.
- Preise & Maerkte mit gemeinsamem Markt-/Regelbaum und produktbezogenen Schaltern. Der Bulk-Editor verwendet denselben Auftrag fuer ausgewaehlte Produkte.
- Automatische Sandbox-Verarbeitung nach ausdruecklicher Freigabe der Verbindung: Bilder vorbereiten, Angebot veroeffentlichen, aktualisieren, beenden und erneut aktivieren.
- Separate manuelle Bilduebertragung und Sandbox-Entwurfsanlage entfernt. Produktpruefung und Vorschau bleiben erhalten.
- Gespeicherte Auftraege und geschuetzte Uebertragungsschritte verhindern ungeprueftes erneutes Senden. Sichere Vorbereitungen koennen nach Neustart fortgesetzt werden; unklare Ergebnisse bleiben gesperrt.
- Verstaendlichere Hinweise fuer fehlende Freigabe, unvollstaendige Produktdaten und noch nicht bestaetigte Uebertragungen.
- Gemeinsame Hintergrundverarbeitung fuer Lade-/Speichervorgaenge und Verkaufsauftraege; Doppelklick auf neue E-Mail-Benachrichtigungen oeffnet die zugehoerige Nachricht.
- Wichtig: Echtbetrieb-Veroeffentlichung und Bestellimport bleiben gesperrt. Varianten und weitere Pflichtangaben sowie der vollstaendige Fenster-/Bulk-Ablauf benoetigen weitere Pruefung. Sandbox-Nachweise sind keine kommerzielle Freigabe; visuelle Abnahme erfolgt mit dem Nutzer.

## 0.9.68

Metadaten erstellt: 2026-09-25T16:51:25.5378384+00:00 · [Manifest](../updates/stable/0.9.68/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.68)

- Beydosh PIM 0.9.68 (Beta): E-Mail-Ansicht, gemeinsame Entwuerfe und stabile dunkle Listen.
- Korrigiert: Ordner- und Nachrichtenlisten werden beim Wechseln, Laden oder Speichern nicht mehr durch die Windows-Standarddarstellung weiss.
- Gemeinsame Symbole fuer Postfachordner und Nachrichtenaktionen. Die Bedeutung der Aktionssymbole erscheint beim Darueberfahren.
- Eigene Ordner stehen unter den Standardordnern im Abschnitt Ordner. Ordner hinzufuegen steht unten; leere eigene Ordner lassen sich nach Rueckfrage loeschen. Systemordner bleiben geschuetzt.
- Der manuelle Abrufen-Button entfaellt. Nachrichten werden weiter automatisch aktualisiert.
- Bereinigter heller Lesebereich: HTML-Quelltext-Einrueckungen erzeugen keine riesigen Leerraeume, Listen erhalten sichtbare Aufzaehlungen. Weiterhin vereinfachte sichere HTML-Darstellung, kein vollstaendiger Browser.
- Eine gemeinsame Entwuerfe-Ansicht. Speichern sichert lokal verschluesselt und synchronisiert mit dem Server-Entwuerfe-Ordner. Nicht synchronisierte Sicherungen und erkannte Konflikte werden gekennzeichnet.
- Ausstehende Entwurfsuebertragungen werden bei laufender Anwendung und geschlossenem Editor erneut versucht. Voraussetzung sind ein vom Server gemeldeter Entwuerfe-Ordner und UIDPLUS; andernfalls bleibt die lokale Sicherung erhalten.
- Wiederaufnahme nach unterbrochenen Uebertragungen und gezieltes Entfernen der Server-Entwurfskopie nach bestaetigtem Versand. Ein unklarer Versand wird nicht automatisch wiederholt.
- Keine Aenderungen an Preisen, Versandkalkulation oder Verkaufskanaelen. Automatisierte Tests und Ansichten mit synthetischen Daten; echte Postfachanbieter und gleichzeitige Mehrgeraetebearbeitung benoetigen gesonderte Pruefung.

## 0.9.67

Metadaten erstellt: 2026-09-25T16:00:10.1627657+00:00 · [Manifest](../updates/stable/0.9.67/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.67)

- Beydosh PIM 0.9.67 (Beta): aufgeraeumter E-Mail-Bereich und stiller Nachrichtenabruf.
- Ordnerleiste, Nachrichtenliste mit einzelnen Karten und grosser Lesebereich. Gelesene und ungelesene Nachrichten sind klar unterscheidbar.
- Der Editor nutzt beim Schreiben mehr Breite; kompakte Empfaengerfelder lassen auch in kleineren Fenstern Platz fuer die Nachricht.
- Automatischer Abruf standardmaessig alle 60 Sekunden, pro Postfach einstellbar (15 bis 3600 Sekunden; 0 = manuell).
- Bestehende positive Minutenintervalle bleiben erhalten. Bisherige 0-Minuten-Vorgaben wechseln auf den neuen 60-Sekunden-Standard.
- Hintergrundabruf ohne Ladeanzeige; Auswahl, Lesebereich und Entwurf bleiben erhalten. Neue Nachrichten erscheinen oben.
- Neue ungelesene E-Mails werden ueber die Benachrichtigungszentrale gemeldet, solange Beydosh laeuft. Erstabgleich und wiederholte Abrufe melden alte Nachrichten nicht erneut.
- Bilder passen proportional in den Lesebereich; kleine Logos werden nicht hochskaliert. Lange Kurzinfos umbrechen, der Datenschutzhinweis steht lesbar unter dem Schieber.
- Skripte bleiben blockiert; externe Bilder behalten die vorhandenen Freigaberegeln. Vereinfachte HTML-Darstellung, kein vollstaendiges Browserlayout.
- Keine Aenderung an Marktpreisen oder Versandkalkulation. Tests mit synthetischen Nachrichten, kein Nachweis fuer einen echten Postfachanbieter.

## 0.9.66

Metadaten erstellt: 2026-09-25T15:16:10.2572606+00:00 · [Manifest](../updates/stable/0.9.66/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.66)

- Beydosh PIM 0.9.66 (Beta): erweiterter E-Mail-Bereich.
- Antworten, Allen antworten, Weiterleiten, An/Cc/Bcc, Anhaenge, Ordner, Suche, Markierungen, Archiv und Papierkorb.
- Formatierte Nachrichten und Signaturen mit Bildern und Links. Signaturen werden nach der Postfacheinrichtung verwaltet.
- Lokale verschluesselte Entwuerfe, EML-Export und Drucken. Unklarer Versand wird nicht automatisch wiederholt.
- HTML ist standardmaessig aktiviert. Externe Bilder werden standardmaessig blockiert und koennen je Nachricht freigegeben werden.
- Separate Postfach-Schieber fuer HTML und automatisches Laden externer Bilder. Skripte bleiben immer blockiert.
- Gemeinsame Schieberlogik fuer E-Mail-Einstellungen und Netto/Brutto. Gespeicherte Zugangsdaten werden durch Passwortpunkte angezeigt.
- Weitere Postfachoptionen fuer Signaturen, Antwortadresse, Gelesenstatus, Gesendet-Kopie, Ordnerzuordnung und optionalen Abruf.
- Beta-Grenzen: vereinfachte HTML-Darstellung, lokale Entwuerfe, keine Outlook-Funktionsparitaet. Anbieter-Kompatibilitaet muss mit einem eigenen Testpostfach geprueft werden.
- Keine Aenderung an Marktpreisen oder Versandkalkulation. Keine automatische Verbindung zu echten Postfaechern durch das Update.

## 0.9.65

Metadaten erstellt: 2026-09-25T14:04:58.4346763+00:00 · [Manifest](../updates/stable/0.9.65/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.65)

- Beydosh PIM 0.9.65 (Beta): aufgeräumte Postfachverwaltung und Kopfzeile.
- E-Mail-Einstellungen zeigen zunächst nur Postfach hinzufügen; eingerichtete Postfächer erscheinen links als Liste.
- Neue Postfächer werden in einem Popup mit Name, E-Mail und Verbindungsdaten angelegt. Abbrechen verwirft die Eingaben.
- Bei Auswahl eines Postfachs erscheinen rechts dessen Verbindungseinstellungen, Absender und Signatur.
- Anlegen und Bearbeiten verwenden ein gemeinsames Formular. Speicherfehler lassen den Dialog offen; neue Zugangsdaten werden bei fehlgeschlagenem Speichern zurückgenommen.
- Doppelte Bereichsüberschriften wurden aus der gemeinsamen Kopfzeile entfernt. Die Überschrift bleibt im jeweiligen Seiteninhalt.
- Keine Änderung an Preisberechnungen oder Versand. Keine automatische E-Mail-Übertragung beim Öffnen oder Anlegen eines Postfachs.

## 0.9.64

Metadaten erstellt: 2026-09-25T13:35:42.1042946+00:00 · [Manifest](../updates/stable/0.9.64/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.64)

- Gemeinsames Fundament: wiederverwendbare Symbole, Schliessen-Buttons, Eingabefelder und Aktionsbuttons fuer mehrere Programmteile zusammengefuehrt.
- E-Mail ohne eingerichtetes Postfach zeigt nur den mittigen Button E-Mail Dienst verbinden und Schliessen. Der Button fuehrt direkt zur Einrichtung.
- E-Mail mit Postfach nutzt eine durchgehend dunkle Darstellung. Lesen und Schreiben teilen sich den grossen rechten Bereich; Zurueck erhaelt den aktuellen Text waehrend der Sitzung.
- Der E-Mail-Button in der Kopfzeile ist an die Nachbarbuttons angeglichen. Gemeinsame Auswahllisten zeigen die Kontobezeichnung statt interner Objektdaten.
- Dezimalzahlen fuer Produktwerte, Marktstaffeln und Sortierung werden gemeinsam verarbeitet. Bestehende Zahlenformate und fachliche Grenzen bleiben erhalten; Preisformeln wurden nicht geaendert.
- KI-Verlaeufe und Kategorieentwuerfe verwenden eine gemeinsame atomare Dateispeicherung mit Sicherung der vorherigen Version. Konfliktpruefungen und Speichergrenzen bleiben erhalten.
- Ladehinweise ergaenzen Bitte kurz warten nicht mehr doppelt. Wiederverwendung ist als programmweite Entwicklungsregel dokumentiert und durch Regressionstests abgesichert.
- Beta-Testversion: keine neuen eBay-Livefunktionen, keine automatische E-Mail-Uebertragung und keine Core-Synchronisation. E-Mail bitte weiterhin mit einem separaten Testpostfach ohne echte Kundendaten pruefen.

## 0.9.63

Metadaten erstellt: 2026-09-25T12:38:47.7506103+00:00 · [Manifest](../updates/stable/0.9.63/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.63)

- Beydosh PIM: sichtbarer Programmname und neu gegliederte Einstellungen fuer Shopinformationen, Anzeige, Sprache, Daten & Betrieb, E-Mail sowie KI & Automatisierung.
- E-Mail-Testfunktion fuer vorhandene IMAP-/SMTP-Postfaecher: Konto und Signatur einrichten, Verbindung pruefen, Posteingang manuell abrufen, Klartext lesen und eine Nachricht ausdruecklich senden.
- Postfach-Zugangsdaten werden geschuetzt gespeichert. Konten erscheinen nur im aktiven lokalen Workspace. Keine automatische Abfrage, kein automatischer Versand und keine Aenderung von Produkt- oder Verkaufsdaten.
- Erste Beta-Ausbaustufe: noch keine Anhaenge, Suche, lokalen Entwuerfe oder Gesendet-Ablage und keine Core-/Mehrgeraete-Synchronisation. Zum Test bitte ein separates Testpostfach ohne echte Kundendaten verwenden.
- eBay kann als Exportanbieter vorbereitet werden; ohne genehmigte Entwicklerdaten erfolgt keine OAuth-Verbindung und keine Veroeffentlichung von Angeboten.

## 0.9.62

Metadaten erstellt: 2026-09-25T09:59:04.7304039+00:00 · [Manifest](../updates/stable/0.9.62/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.62)

- Preisregeln lassen sich manuell und im Markt-KI-Assistenten vorhandenen Produkttypen zuordnen. Mehrere Typen pro Regel sind moeglich; Kategorien beeinflussen die Zuordnung nicht.
- Im selben Verkaufskanal und Land koennen unterschiedliche Produkttypen unterschiedliche Preisregeln nutzen. Ueberschneidungen werden blockiert; fehlende Zuordnungen liefern keinen ungeprueften VK.
- Die Produktzuordnung ist im Preisregel-Editor, auf der Marktkarte und im KI-Entwurf sichtbar. Bestehende Regeln bleiben fuer alle Produkte gueltig, bis sie gezielt eingeschraenkt werden.
- Der Kalkulationsablauf zeigt Verzweigungen und Zusammenfuehrungen fuer Gewinnstaffeln, progressive Gebuehrenstaffeln und unterschiedliche EK-Steuergrundlagen. Grenzen und Saetze stammen aus der jeweiligen Regel; progressive Teilgebuehren werden addiert.
- Der zusaetzliche Lade-Popup im KI-Assistenten entfaellt. Arbeitsfortschritt und Stopp bleiben im Assistenten sichtbar.
- Alle 128 Desktop-Selbsttests erfolgreich, einschliesslich Produkttyp-Zuordnung, Speichern/Laden, KI-Pruefung und Fensterbedienung. Keine automatische Aenderung bestehender Produktdaten oder Gebuehrenwerte; keine externe Veroeffentlichung von Angeboten.

## 0.9.61

Metadaten erstellt: 2026-09-23T21:58:14.9664081+00:00 · [Manifest](../updates/stable/0.9.61/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.61)

- Netto-/Brutto-Schalter: Die sichtbare Markierung folgt jetzt korrekt der Auswahl. Eine alte Brutto-Animation konnte bisher die Netto-Position verdecken, obwohl der interne Wert bereits gewechselt hatte.
- Die Animation wird beim Verlassen des jeweiligen Zustands entfernt. Ein Regressionstest prueft ausdruecklich die sichtbare Netto-Position nach dem Klick; beide Richtungen wurden zusaetzlich mit echten Mausklicks in einer isolierten Testoberflaeche geprueft.
- Der Hinweistext unter dem Einkaufspreis-Schalter entfaellt. Der Abstand zwischen Ueberschrift und Schalter entspricht jetzt der Anordnung der Bearbeiten-Funktion in Attributkarten.
- Alle 128 Desktop-Selbsttests erfolgreich. Das Update aendert keine gespeicherten Einkaufsgrundlagen oder Produktdaten automatisch.

## 0.9.60

Metadaten erstellt: 2026-09-23T21:41:24.1935249+00:00 · [Manifest](../updates/stable/0.9.60/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.60)

- Der visuelle Kalkulationsablauf bleibt beim Bearbeiten sichtbar und aktualisiert sich unmittelbar mit den Einstellungen. Unvollstaendige Eingaben zeigen einen Hinweis; ein alter VK wird als neu zu berechnen markiert.
- Der Netto-/Brutto-Schalter reagiert auf einen Klick auf seine gesamte Flaeche. Die Einstellung bleibt wie bisher der urspruenglichen Importvorlage zugeordnet.
- Die EK-Steueransicht unterscheidet die automatisch verwendete Vorlagen-Einstellung von der Ersatzangabe fuer Produkte ohne Importquelle. Die KI beruecksichtigt die konfigurierten Quellgrundlagen.
- Einkaufssteuersatz und Vorsteuerabzug werden nicht geraten. Fehlende Angaben bleiben erkennbar und sperren weiterhin unvollstaendige Berechnungen.
- Das X im Preisregel-Editor ist als sauber zentriertes Symbol dargestellt.
- 128 Desktop-Selbsttests erfolgreich. Keine automatische Veroeffentlichung von Angeboten oder Aenderung bestehender Produktdaten durch dieses Update.

## 0.9.59

Metadaten erstellt: 2026-09-23T21:23:38.8117832+00:00 · [Manifest](../updates/stable/0.9.59/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.59)

- Einkaufspreis-Karten in Verbindungsvorlagen haben einen Netto-/Brutto-Schalter. Standard ist Brutto; bitte entsprechend der Importquelle einstellen.
- Nach dem Speichern gilt die Einstellung auch fuer bereits importierte Produkte, ohne Neuimport oder Aenderung der gespeicherten EK-Betraege und Anhaenge.
- Die Kalkulation verwendet die urspruengliche Importvorlage des Produkts. Unterschiedliche Netto-/Brutto-Quellen koennen im selben Verkaufskanal verwendet werden.
- Der EK-Steuerfaktor ist in der visuellen Markt-Kalkulationsreihe, KI-Entwurfsvorschau und im Produkt-Rechenweg sichtbar: multiplizieren, dividieren oder unveraendert.
- Einkaufssteuersatz und Vorsteuerabzug bleiben je Preisregel konfigurierbar. Fehlende Grundlagen sperren die Berechnung; gespeicherte Verkaufspreise werden nicht automatisch veroeffentlicht.
- Preisregel bearbeiten hat oben rechts Preisregel in Karte uebernehmen und daneben ein X fuer die Rueckkehr im selben Fenster. Der bisherige Abbrechen-Button entfaellt; ungespeicherte Aenderungen bleiben durch die Verwerfen-Rueckfrage geschuetzt.
- Der visuelle Kalkulationsablauf nutzt das breite abgerundete Feld unten und wird bei Bedarf mit Verbindungspfeilen in weiteren Zeilen fortgesetzt.

## 0.9.58

[Manifest](../updates/stable/0.9.58/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.58)

- Ausdrückliche EK-Steuerbasis; unbekannte Netto-/Brutto-Grundlage sperrt die Kalkulation statt einen ungesicherten VK auszugeben.
- Frei konfigurierbare Gewinnstaffeln und progressive Gebührenstaffeln, sichtbar im Regelentwurf/Rechenweg und vom Markt-KI-Assistenten vorschlagbar.
- Vorsichtige Gebührenrundung und Zielverdienstprüfung; keine Garantie für nicht erfasste Kosten oder unbestätigte Steuer-/Gebührenannahmen.
- Automatische Variantenverknüpfung über gleiche vollständige Produktnamen; vorhandene manuelle Gruppen bleiben erhalten.
- Variantenverwaltung im Produktfenster mit X zum Zurückkehren, Umbenennen, Hinzufügen und Entfernen von Mitgliedern.
- Gruppen unter zwei Mitgliedern werden aufgelöst, Produkte bleiben erhalten. Manuell entfernte Mitglieder werden nicht automatisch erneut zugeordnet.
- 128 automatisierte Desktop-Tests einschließlich 70.000 synthetischer Produkte und 3.000 progressiver Gebührenbeispiele erfolgreich.

## 0.9.57

[Manifest](../updates/stable/0.9.57/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.57)

- Preisregel-Bearbeitung im selben Verkaufskanal-Fenster, mit Rückkehr zur erhaltenen Karte.
- Kalkulationsablauf über volle Fensterbreite, automatischer Zeilenumbruch mit Verbindungspfeilen.
- Numerische Sortierung für EK und Bestand; chronologische Sortierung für Änderungszeitpunkte.
- Sichtbare Sortierpfeile und Drei-Klick-Zyklus: aufsteigend, absteigend, aufgehoben.
- Keine Veränderung bestehender Produktpreise oder Preisregeln.

## 0.9.56

Metadaten erstellt: 2026-09-23T19:00:05.3491027+00:00 · [Manifest](../updates/stable/0.9.56/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.56)

- Beydosh 0.9.56 – Visuelle Kalkulationsreihe
- Bei Auswahl eines Verkaufskanals erscheinen seine Preisregeln als waagerechte Rechenreihe von EK bis VK brutto.
- Pfeile, Plus, Minus, Multiplikation, Division und Klammern machen die tatsächliche Berechnungsreihenfolge sichtbar; lange Reihen sind seitlich scrollbar.
- Gewinnmodell, Gebührenbasis, Verkaufssteuer, Währungsumrechnung und abschließende Rundung stammen aus der jeweiligen Regel, ohne feste Anbieter- oder Gewinnvorgaben.
- Die Preisregel-Beispielrechnung zeigt dieselbe Reihe; geänderte Eingaben blenden veraltete Ergebnisse bis zur Neuberechnung aus.
- Enthält alle Verbesserungen aus 0.9.55. Keine Änderung bestehender Preisregeln und keine automatische Veröffentlichung auf Verkaufsplattformen.
- Behebt den Importabbruch bei uneindeutiger Wiedererkennung gelöschter Produkte: problematische Zeilen bekommen einen konkreten Hinweis; unabhängige eindeutige Zeilen können weiter reserviert und importiert werden.
- Zusätzliche passende SKU-/Artikelkennungen können eine mehrfach vorhandene EAN eindeutig zuordnen; widersprüchliche Identitäten bleiben gesperrt.
- Owner-Preview; konkrete Gebühren, Steuerstatus und tatsächliche Produktpreise weiterhin prüfen.

## 0.9.55

Metadaten erstellt: 2026-09-23T18:43:29.8767223+00:00 · [Manifest](../updates/stable/0.9.55/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.55)

- Beydosh 0.9.55
- Große Produktlöschungen laufen im Hintergrund mit Ladeanzeige, Schutz gegen Doppelklicks und vorheriger Sicherung.
- Einheitliche Ladehinweise für neuere Import-, Markt-, Versand-, KI- und Dateiaktionen ergänzt.
- Beim erneuten Öffnen gespeicherter Importdaten sind bereits reservierte Beydosh-IDs sofort sichtbar.
- Wiederimport gelöschter Produkte kann die bisherige Beydosh-ID anhand eindeutiger, lieferantenbezogener Identitätsmerkmale wiederherstellen. Widersprüche und Mehrdeutigkeiten werden gesperrt; IDs werden niemals allgemein recycelt.
- Verkaufskanal-Preise sind ausdrücklich als Brutto-Endpreise gekennzeichnet. Der Rechenweg zeigt Netto, enthaltene Verkaufssteuer und Endpreis. Vorhandene Steuersätze werden nicht automatisch verändert.
- Die Märkte-KI klärt unklare Netto-/Brutto-Vorgaben und Steuergrundlagen, unterscheidet Verkaufssteuer von Gebührensteuer und berücksichtigt, dass der Import nur Währungen umrechnet.
- Owner-Preview: keine Freigabe für Live-Verkäufe, Bestellungen oder automatische Veröffentlichungen. Gebühren, Steuerstatus und tatsächliche Produktpreise vor Nutzung prüfen.

## 0.9.54

Metadaten erstellt: 2026-09-21T22:32:03.076Z · [Manifest](../updates/stable/0.9.54/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.54)

- Beydosh 0.9.54 – Importauswahl wiederherstellen
- Beim Öffnen von Daten bearbeiten werden eindeutig zuordenbare, bereits importierte Produkte wieder ausgewählt.
- Die Zuordnung erfolgt über Produktkennungen und Lieferant statt über Zeilennummern. Neue Produkte bleiben unmarkiert.
- Die EK-Währung kann geändert und dieselbe Produktauswahl erneut importiert werden.
- Bestehende Produkt-IDs, Bilder, benannte Downloads und lokale Dateien bleiben beim Neuimport erhalten.
- Keine automatische Veröffentlichung von Angeboten und keine Änderung der Quelldatei.

## 0.9.53

Metadaten erstellt: 2026-09-21T22:13:33.874Z · [Manifest](../updates/stable/0.9.53/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.53)

- Beydosh 0.9.53 – EK-Währung im Import
- Neben dem Zahlenformat kann die Einkaufspreis-Währung der Quelldaten gewählt werden. Alternativ bleibt eine zugeordnete Währungsspalte möglich.
- Einkaufspreise werden vor dem Speichern in die Shopwährung umgerechnet. Gleiche Währungen benötigen keinen Wechselkurs.
- Quellbetrag, Quellwährung, Originaldaten und verwendeter Wechselkurs bleiben nachvollziehbar. Wiederholte Importe rechnen stets den Originalbetrag um.
- Automatische Abrufe verwenden die gespeicherte EK-Währung. Fehlende, widersprüchliche oder veraltete Währungsgrundlagen überschreiben keine bestehenden Preise.
- Produkte zeigen den importierten EK in Shopwährung. Aktive Verkaufskanäle kalkulieren daraus automatisch die Länder-VK.
- Die bisher irreführende Meldung bei fehlender EK-Währung verweist jetzt auf die Währungsauswahl und den erneuten Import.
- Bestehende Produkte ohne EK-Währung bitte mit gewählter Quellwährung erneut importieren. Es wird keine Währung geraten.
- Keine automatische Angebotsveröffentlichung, Versandbuchung oder Änderung der Quelldatei.

## 0.9.52

Metadaten erstellt: 2026-09-21T21:51:32.779Z · [Manifest](../updates/stable/0.9.52/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.52)

- Beydosh 0.9.52 – Verkaufskanäle und Länderpreise
- Ein Verkaufskanal kann unterschiedliche Preisregeln für mehrere Länder enthalten.
- Kosten und Gewinnziele werden in der Shopwährung kalkuliert; die Umrechnung und Rundung erfolgen am Schluss in der Angebotswährung.
- Produkte zeigen aktuelle Kanalpreise nach Ländern gruppiert mit lokalem VK und Euro-Gegenwert. Pausierte Regeln bleiben ausdrücklich Vorschauen.
- Marktkarten zeigen aktiv/inaktiv und bieten Aktivieren/Deaktivieren. Die Länderanzahl berücksichtigt auch pausierte Regeln.
- Die Shopwährung ist einstellbar. Bestehende Preisregeln und Kanalpreise sperren einen Wechsel ohne geprüfte Umrechnung.
- KI-Entwürfe berücksichtigen die Shopwährung und bleiben auf den jeweiligen Arbeitsbereich begrenzt.
- Fehlende oder veraltete Wechselkurse sperren die Berechnung. Keine automatische Veröffentlichung oder Versandbuchung.
- Die ausdrückliche Zuordnung der EK-Währung beim Import wird in einem späteren Update ergänzt.

## 0.9.51

Metadaten erstellt: 2026-09-21T20:59:32.097Z · [Manifest](../updates/stable/0.9.51/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.51)

- Beydosh 0.9.51 – KI-Recherche und Kalkulationshilfe
- Märkte- und Versandassistent recherchieren und erklären selbstständig statt pauschaler Rückfragenlisten. Berechtigte Rückfragen und die strikte Bereichstrennung bleiben bestehen.
- Nutzer- und anbieterneutrale Kalkulation: eigene Gewinnziele, Kosten und Regeln; Produkt-EK wird je Produkt eingesetzt. Keine fest eingebauten persönlichen Gewinnwerte oder Anbietergebühren.
- Webrecherche ist für neue unterstützte Gespräche vorausgewählt. Bestehende Rechercheeinstellungen werden respektiert. Keine erfundenen Konditionen oder automatischen Freigaben.
- Rückfragen lassen sich mit Doppelpunkt ins Eingabefeld übernehmen. Weitere Fragen stehen mit einer Leerzeile Abstand; erneuter Klick springt zur vorhandenen Frage und hebt sie kurz hervor. Antworten bleiben erhalten.
- Schatteneffekte auf KI-Inhaltsflächen entfernt, damit Texte und Bedienelemente nicht mit der gesamten Fläche gerastert werden.
- Leere Arbeitsaufträge älterer Markt- und Versandgespräche werden aus der ersten Nachricht wiederhergestellt; vorhandene Aufträge und bewusst geleerte neue Aufträge bleiben erhalten.
- Im Chat gewünschte Arbeitsauftragsänderungen werden bei Märkten und Versand direkt übernommen und im Gespräch dokumentiert. Die Prüfung fachlicher Entwürfe bleibt separat.
- Versand bleibt separat. Keine Live-Verkäufe, Versandbuchungen oder automatische Veröffentlichung von KI-Entwürfen.

## 0.9.50

Metadaten erstellt: 2026-09-21T20:27:28.819Z · [Manifest](../updates/stable/0.9.50/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.50)

- Beydosh 0.9.50 – Gemeinsamer KI-Assistent
- - Neuer Reiter Rückfragen bei Kategorien, Märkten und Versand. Offene Fragen öffnen den Reiter automatisch und bleiben im gespeicherten Gespräch erhalten.
- - Antwortvorschläge stehen bei den Rückfragen, damit mehr Platz für den Chat bleibt.
- - Arbeitsaktivität im Chat sowie Fortschritt und Abbrechen beim Entwurf vereinheitlicht.
- - Mehrstufige Entwürfe, bestätigte Arbeitsauftragsänderungen, Quellenlinks, Schriftgröße und Speicherhinweise in den gemeinsamen Grundfunktionen ergänzt.
- - Zusätzliche Sende-Checkbox entfernt; Daten- und Kostenhinweise bleiben verfügbar.
- - Fachliche Berechtigungen bleiben getrennt. Versand wird separat kalkuliert. Keine automatische Veröffentlichung oder Übernahme von KI-Entwürfen.

## 0.9.49

Metadaten erstellt: 2026-09-21T19:53:54.169Z · [Manifest](../updates/stable/0.9.49/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.49)

- Beydosh 0.9.49 – Einheitliches KI-Grundlayout
- Kategorien, Märkte und Versand verwenden eine gemeinsame Layout-Komponente: Entwurf links, Gespräch rechts, einheitliche Überschriften, Spaltentrenner und abgerundeter Eingabebereich.
- Gemeinsame Nachrichten- und Eingabebausteine auch im eingebetteten Attribut-Assistenten. Fachfunktionen, Datenzugriffe und Bereichsregeln bleiben getrennt.
- Verlauf exportieren und Neues Gespräch wurden aus den Markt- und Versandassistenten entfernt. Die lokale Chat-Speicherung bleibt erhalten.
- Der weiße Auswahlrahmen für Markt- und Versandkarten wird anhand der festen Karten-ID zugeordnet und bleibt nach dem Neuladen erhalten.
- Keine Änderungen an Preisformeln, keine neuen Versandaufschläge, keine Live-Verkäufe oder Versandbuchungen.

## 0.9.48

Metadaten erstellt: 2026-09-21T19:32:56.149Z · [Manifest](../updates/stable/0.9.48/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.48)

- Beydosh 0.9.48 – KI-Assistenten für Märkte und Versand
- Entwurf links, Gespräch rechts. Sofort sichtbare Nachrichten, animierte Aktivität und Stopp auch bei ausbleibender Antwort.
- Getrennte lokale Chats je Mandant, Bereich und Karte mit Arbeitsauftrag, Rechercheauswahl und Wiederherstellung. Speicherkonflikte verhindern Überschreiben.
- Entwürfe als JSON laden und speichern, Verlauf exportieren, neues Gespräch und anklickbare Rückfragen. Geladene Entwürfe werden erneut auf Bereich und Karte geprüft.
- Optionale Webrecherche, Quellenhinweise und gemeldeter Tokenverbrauch. Nicht bestätigte Recherche wird ausdrücklich gekennzeichnet.
- Neue Marktentwürfe kalkulieren EK plus marktbezogene Kosten und Verdienst. Versand bleibt separat im Menü Versand. Kein neuer Versandaufschlag auf den Produktpreis; bestehende Verknüpfungen bleiben unverändert.
- Verkaufskanalkarten mit Innenabstand und weißem Auswahlrahmen. Auswahl zeigt den Kanalnamen.
- Kategorien-KI bleibt unverändert. Keine automatische Übernahme von KI-Entwürfen, keine Live-Angebote, Bestellungen oder Versandbuchungen.

## 0.9.47

Metadaten erstellt: 2026-09-21T18:57:52.403Z · [Manifest](../updates/stable/0.9.47/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.47)

- Beydosh 0.9.47 – Einheitliche KI-Assistenten und sichere Kartenspeicherung
- Preise & Märkte und Versand: Gespräch links, aktueller Stand und vorgeschlagene Änderungen rechts. Übersichtliche Regel-/Tarifkarten, aufklappbare Feldänderungen und Entwurf verwerfen.
- KI-Assistent wird erst nach Auswahl einer gespeicherten Karte aktiv. Neue Kanäle können zunächst nur mit Namen, Versandkarten mit Namen und Kostenwährung gespeichert werden.
- Strikte Bereichsgrenzen: Märkte, Versand, Kategorien und Attributvorlagen akzeptieren keine fremden Änderungsfelder. Märkte dürfen bestehende Versandtarife nur unverändert referenzieren. Keine automatische Speicherung, Kontoanbindung oder Angebotsveröffentlichung.
- Unabhängige Produktänderungen blockieren das Speichern von Kanal- und Versandkarten nicht mehr. Gleichzeitige Änderungen an der Karte oder ihren Konfigurationsgrundlagen werden weiterhin abgewiesen.
- Einstellungen / Unternehmen zeigt Shopwährung (Basiswährung): EUR (€) – Euro. Derzeit schreibgeschützt, da die Kalkulation EUR voraussetzt; keine Umdeutung bestehender Beträge. Zielwährungen bleiben je Verkaufskanal möglich.
- Automatisierte Vertrags-, Speicher- und Fenstertests durchgeführt. Kein echter KI-Anbieteraufruf für diese Veröffentlichung. Keine Freigabe für Live-Verkauf, Versandbuchung oder echte Bestellungen.

## 0.9.46

Metadaten erstellt: 2026-09-21T18:12:47.977Z · [Manifest](../updates/stable/0.9.46/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.46)

- Beydosh 0.9.46 – Universelle KI-Konfiguration und Bedienung
- Preise & Märkte und Versand: beliebige Karten mit der zentralen KI anlegen oder bearbeiten. Rückfragen, Änderungsübersicht und ausdrückliche Datenfreigabe; keine automatische Speicherung. Neue oder geänderte Regeln bleiben pausiert und werden im normalen Editor geprüft.
- Keine fest eingebauten Plattformgebühren, keine automatische Kontoanbindung und keine recherchierten Konditionen. Echte KI-Anbieteraufrufe wurden für dieses Update nicht ausgeführt; automatisierte Vertrags- und Fenstertests wurden durchgeführt.
- Produktbilder und Downloads: Drag & Drop tauscht ausschließlich belegte Plätze im selben Bereich. Ein einzelnes Bild bleibt auf Bild 1. Das Anzeigebild folgt dem ersten Platz; Speicherung im Hintergrund.
- Downloadnamen lassen sich für lokale Dateien und externe Links bearbeiten, ohne das Dateiziel zu ändern.
- Titelleiste berücksichtigt den unsichtbaren Rahmen maximierter Fenster und die Bildschirm-Skalierung.
- Filterpfeile behalten ihren Platz neben langen Überschriften; vollständige Namen bleiben als Tooltip verfügbar.
- Kategoriefilter als aufklappbarer Baum mit Mehrfachauswahl und sichtbaren Elternpfaden bei der Suche. Der technische ODER-/UND-Hinweis entfällt; bestehende Filterlogik bleibt erhalten.
- Keine Veröffentlichung von Angeboten, keine Versandbuchung und keine Freigabe für Live-Verkauf oder echte Bestellungen.

## 0.9.45

Metadaten erstellt: 2026-09-20T21:06:53.999Z · [Manifest](../updates/stable/0.9.45/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.45)

- Beydosh 0.9.45 – Visuelle Feinarbeit
- Kompakte, flache dunkelblaue Titelleiste mit schlichten Fensterknöpfen und rotem Schließen-Hover.
- Aktive Register gehen ohne Trennlinie oder Farbbruch in die Inhaltsfläche über. Inaktive Register bleiben abgegrenzt.
- Buttons heben sich mit kräftigerem Blau und helleren Konturen deutlicher von den Inhaltsflächen ab.
- Produktzellen sind einheitlich vertikal zentriert. Die Hover-Vorschau reagiert auf die gesamte Produktzeile und bleibt beim Verweilen geöffnet.
- Die Tabelle der Sammelbearbeitung wächst mit dem Fenster und nutzt den verfügbaren Platz. Die Aktionen bleiben darunter sichtbar.
- Kategorien haben abgerundete, abgegrenzte Zeilen und wieder sichtbare Ausklappbuttons.
- Benachrichtigungen zeigen ausschließlich abgerundete Karten, auch bei Auswahl und Tastaturfokus.
- Zahlenformat-Beschriftung und Auswahlfeld sind gemeinsam rechtsbündig ausgerichtet.
- Keine Änderung an gespeicherten Produktdaten, Preisregeln oder Live-Freigaben.

## 0.9.44

Metadaten erstellt: 2026-09-20T20:41:15.868Z · [Manifest](../updates/stable/0.9.44/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.44)

- Beydosh 0.9.44 – Register und visuelle Feinarbeit
- Reiter stehen im gesamten Programm nebeneinander wie Aktenregister und schließen direkt an ihren Inhaltsbereich an. Schmale Fenster bieten horizontales Scrollen.
- Eigene blaue Titelleisten für die Anwendungsfenster mit Minimieren, Maximieren, Wiederherstellen und Schließen. Bestehende Schutzabfragen bleiben erhalten; System-Dateidialoge bleiben unverändert.
- Importprüfung und Sammelbearbeitung verwenden wieder helle Tabellen mit abwechselnd weißen und hellorangen Zeilen. Zahlenformat und Suche sind rechts zusammengefasst, Aktionen und Feldzuordnungen haben mehr Abstand.
- Produkttabelle mit deutlicheren Namen und kompakter, abgerundeter Vorschau. Produktüberschrift, Liste und Vorschau zeigen Hersteller plus Artikelname, sofern der Hersteller hinterlegt ist. Bulk-Exporte behalten beide Felder getrennt.
- Kategorien erscheinen als ruhiger Baum ohne dunkle Streifen. Vorlagen- und Benachrichtigungsbuttons sind einheitlicher ausgerichtet.
- Benachrichtigungen erhalten blaue Karten; Popups sind in Breite und Höhe begrenzt und bieten den Zugriff auf Details.
- Keine Änderung an Preisregeln, Importdaten oder Live-Freigaben. Kein automatischer Versand an Verkaufsplattformen.

## 0.9.43

Metadaten erstellt: 2026-09-20T20:02:41.729Z · [Manifest](../updates/stable/0.9.43/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.43)

- Beydosh 0.9.43 – Neue blaue Oberfläche
- Weich angehobene blaue Bereiche mit abgerundeten Kanten, dezenten Verläufen und klarer visueller Hierarchie.
- Einheitliche Gestaltung für Dashboard, Produktansichten, Vorlagen, Einstellungen und Kalkulationsdialoge.
- Preis- und Versandregeln sind in übersichtliche Abschnitte aufgeteilt. Beispielrechnung, Ergebnis und Aktionen sind deutlicher getrennt.
- Bulk-Editor und Import erhalten dunkle, ruhigere Tabellen. Filter, Bearbeitung und Schutz importierter Werte bleiben erhalten.
- Ladehinweise, Eingaben, Buttons und Register passen zum neuen Stil.
- Keine Änderung an Preisformeln, Live-Freigaben oder vorhandenen Produktdaten. Launcher und Installer behalten ihre bisherige Gestaltung.

## 0.9.42

Metadaten erstellt: 2026-09-20T18:46:48.511Z · [Manifest](../updates/stable/0.9.42/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.42)

- Beydosh 0.9.42 – Preise, Märkte und Versand
- Eigene Verkaufskanal- und Versandkarten mit frei wählbaren Namen. Länder und wiederverwendbare Ländergruppen lassen sich gemeinsam einrichten. Die Länderübersicht zeigt vorhandene Preisregeln und Versandzuordnungen.
- Versandtarife unterstützen Festbeträge, Preisstaffeln und eigene Formeln je Bestellung, Artikel oder Paket. Optionale Grenzen für Gewicht, Maße, Versandklasse und Postleitzahlen. Beispielrechnungen zeigen fehlende Angaben und den Rechenweg.
- Preisregeln unterstützen festen Verdienst, Kostenaufschlag, Zielmarge oder eine eigene Erlösformel. Versandkosten, Verkaufsgebühren, kalkulatorischer Steuersatz und zusätzlicher Produktverdienst werden berücksichtigt. Umrechnung über verfügbare EZB-Referenzkurse; Rundung erst in der Zielwährung.
- Produktpreise werden vor der Übernahme angezeigt und erneut geprüft. Einkaufspreise bleiben unverändert. Geänderte Berechnungsgrundlagen werden kenntlich gemacht. Bestehende Marktregeln bleiben separat erhalten.
- Das Standardfeld Hersteller ergänzt die Produktanzeige ohne doppelte Namensvorsätze. Bulk-Export und Rückimport behalten Produktname und Hersteller getrennt und unverändert.
- Die Produktkalkulation gilt für einen Artikel. Keine automatische Paketaufteilung, Steuerermittlung, Etikettenbuchung oder Übertragung an Verkaufsplattformen. Fehlende Angaben, widersprüchliche Regeln und fehlende oder veraltete Kurse sperren die Berechnung. Keine Freigabe für Live-Verkauf oder echte Bestellungen.

## 0.9.41

Metadaten erstellt: 2026-09-19T23:25:31.038Z · [Manifest](../updates/stable/0.9.41/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.41)

- Beydosh 0.9.41
- Preise & Märkte ist in vier übersichtliche Bereiche gegliedert: Markt und Währung, Preisregel und Rundung, Kosten und Zielwerte sowie Berechnungsvorschau. Der Bereich lässt sich als eigenes Fenster öffnen.
- Marktregeln werden dauerhaft gespeichert. Je Plattform und Land sind Marktstandards, Kategorieabweichungen und Produktausnahmen möglich. Die spezifischste Regel gilt; gleichrangige Konflikte sperren die Berechnung. Ausnahmen lassen sich zurücksetzen.
- Preisvorschläge zeigen bisherigen Preis, neuen Nettoverkaufspreis, Gebühren, Marge, verwendete Regel und Kursdatum. Erst die ausdrückliche Übernahme speichert Produktpreise; Einkaufspreise bleiben unverändert. Änderungen werden protokolliert. Zwischenzeitliche Datenänderungen verlangen eine neue Vorschau.
- Produktansichten zeigen gespeicherte Marktpreise tabellarisch mit Euro-Gegenwert und aktuell passender Regel. Euro-Gegenwerte werden auf Wunsch mit verfügbaren EZB-Referenzkursen aktualisiert. Die Produktliste zeigt statt der kombinierten Preis-/Marktspalte nur den Bestand.
- Kostenbasis bleibt ein ausdrücklich hinterlegter EUR-Einkaufspreis. Alle Kalkulationen sind netto; Steuern und Bankaufschläge sind nicht enthalten. Fehlende Angaben, unzureichende Marge sowie fehlende oder veraltete Kurse verhindern die Übernahme.
- Keine automatische Übertragung an Shops oder Verkaufsplattformen. Eine eBay-Anbindung ist noch nicht enthalten. Keine Freigabe für Live-Verkauf oder echte Bestellungen.

## 0.9.40

Metadaten erstellt: 2026-09-19T22:32:03.693Z · [Manifest](../updates/stable/0.9.40/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.40)

- Beydosh 0.9.40
- Neuer Menüpunkt Preise & Märkte als ausdrücklich gekennzeichnete Berechnungsvorschau. Plattform-/Ländermärkte können mit getrennten Regeln, Gebühren, Zielwährung und Mindestmarge angelegt werden. Einstellungen bleiben nur in der laufenden Sitzung; keine dauerhafte Speicherung oder Änderung echter Produktpreise.
- Aufschlag, Zielmarge und Festpreis werden nachvollziehbar auf Nettobasis berechnet. Kostenbasis ist EUR. Steuern, Kategorie-/Produktregeln, Marktveröffentlichung und Preisverlauf sind noch nicht angebunden.
- Fremdwährungsberechnungen rufen die aktuellen verfügbaren EZB-Referenzkurse ab. Quelle und Kursdatum werden angezeigt. Fehlende, ungültige oder mehr als vier Kalendertage alte Kurse sperren die Berechnung. Kein Echtzeit-Handelskurs und keine Bankgebühren enthalten.
- Preisrundung je Markt: Währungs-Nachkommastellen, nächster 99er-Preis sowie nächste 5er- oder 10er-Stufe minus 0,01. Passende Preise bleiben unverändert; es wird nicht abgerundet. Marge und Gebühren werden anhand des Endpreises berechnet.
- Produktnamen zeigen beim Verweilen mit der Maus eine kompakte Datenvorschau. Externe Bilder werden weiterhin erst im Produktdetail geladen.
- Scrollgriffe bleiben auch bei großen Listen mindestens 36 Pixel lang, Scrollleisten sind breiter. Produktbilder zeigen keine überflüssige Rollenauswahl mehr; Downloads behalten ihre Rollen.
- Keine automatische Shop-Übertragung und keine Freigabe externer Verkaufsaktionen.

## 0.9.39

Metadaten erstellt: 2026-09-19T21:49:42.574Z · [Manifest](../updates/stable/0.9.39/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.39)

- Beydosh 0.9.39
- Freie Bild- und Downloadplätze lassen sich direkt anklicken. Im Dialog kann eine lokale Datei oder ein externer HTTPS-Link gewählt werden. Die allgemeinen Hinzufügen-Buttons unter den Tabellen entfallen. Freie Plätze werden der Reihe nach gefüllt.
- Der CSV-Rückimport zeigt beim Prüfen die tatsächliche Zahl verarbeiteter Produkte und einen Prozentbalken. Während der Bestätigung im Importvergleich läuft keine irreführende Ladeanimation mehr.
- Beim Übernehmen werden vorbereitete Änderungen gezählt. Nicht messbare Phasen wie das Laden des Datenbestands und das abschließende Schreiben werden ausdrücklich benannt, ohne erfundene Prozentangaben. Die gemeinsame Ladeanzeige unterstützt nun auch messbaren Fortschritt; andere Abläufe liefern noch nicht durchgehend Fortschrittsdaten.
- Die Importprüfung verwendet einen Produktindex statt wiederholter vollständiger Produktsuchen. Reine Asset-Änderungen umgehen unnötige Prüfungen anderer Produktfelder. Eine Zeitersparnis am realen großen Datenbestand ist noch nicht gemessen; der gesamte Datenbestand wird für die Prüfung weiterhin kopiert.
- Zwischenzeitliche Änderungen am Datenbestand werden mit BYD-CONFLICT-001 und einer konkreten Anleitung zum erneuten Öffnen und Prüfen gemeldet. Konflikte werden nicht übergangen, und abgelehnte Änderungen werden nicht gespeichert.
- Keine automatische Änderung vorhandener Produktdaten, keine Recherche und keine Freigabe externer Verkaufsaktionen.

## 0.9.38

Metadaten erstellt: 2026-09-19T20:56:26.880Z · [Manifest](../updates/stable/0.9.38/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.38)

- Beydosh 0.9.38
- Produktbilder und Downloads werden in zwei Tabellen mit je sechs Plätzen angezeigt. Die erste Bildzeile ist als Anzeigebild hervorgehoben und entspricht der Reihenfolge in Vorschau und Export.
- Die Produktpflege zeigt unter 60 Prozent Kritisch, ab 60 Prozent In Ordnung, ab 90 Prozent Top gepflegt in Grün und bei vollständig erfüllten Prüfungen Perfekt in Blau. Produktansicht, Liste, Filter und Dashboard verwenden dieselben vier Stufen. Offene und blockierende Prüfungen bleiben separat erhalten; keine Freigabe externer Aktionen.
- Produkte werden mit Ladehinweis im Hintergrund geöffnet. Wiederholtes Anklicken funktioniert auch nach einem abgebrochenen Öffnen; Mehrfachöffnungen werden verhindert.
- Die Dateigrenze für den Produktlisten-Export und Rückimport wurde auf 1 GiB erhöht. Der tatsächliche Arbeitsspeicherbedarf kann größer als die Dateigröße sein.
- Bestehende Produktdaten und lokale Assets werden durch das Update nicht automatisch verändert. Kein Live-Verkauf und keine automatische Veröffentlichung auf Verkaufsplattformen.

## 0.9.37

Metadaten erstellt: 2026-09-19T20:27:20.273Z · [Manifest](../updates/stable/0.9.37/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.37)

- Beydosh 0.9.37
- Pro Produkt können bis zu sechs Bilder und sechs Downloads als direkte öffentliche HTTPS-Links hinterlegt werden. Lokale Uploads bleiben im verwalteten Beydosh-Assetordner; bestehende Dateien werden nicht automatisch gelöscht.
- Die Sammelbearbeitung exportiert Bild 1 URL bis Bild 6 URL sowie Download 1 URL bis Download 6 URL mit Downloadnamen. Rückimporte prüfen Produkt-ID, bestehende Werte und Konflikte. Leere Zellen löschen Links nur bei ausdrücklicher Löschoption.
- Verlinkte Bilder werden erst in der geöffneten Produktvorschau geladen, nicht beim Start oder Listenexport. Sie bleiben ausschließlich im Anwendungsspeicher; beim Verlassen des Produkts werden Vorschauen freigegeben und laufende Abrufe abgebrochen. Keine dauerhafte DAM-Bildkopie.
- Öffentliche HTTPS-Direktlinks ohne Anmeldung werden unterstützt. Weiterleitungen und lokale Netzwerkadressen werden beim Vorschauabruf abgewiesen. Downloads werden nur nach Bestätigung im Browser geöffnet; der Browser kann Dateien speichern.
- Varianten-Vorschläge vergleichen Hersteller, Profil und Produkttyp aus eindeutig zugeordneten Importquellen. Vorschläge müssen einzeln ausgewählt und bestätigt werden. Bestehende Variantengruppen bleiben unverändert; es werden keine Produktdaten erfunden.
- Verbindungsvorlagen werden mit Ladeanzeige im Hintergrund gespeichert. Mehrfachklicks und das Verlassen des Editors während des Speicherns sind gesperrt.
- Keine eigenständige Recherche oder nachträgliche Änderung bestehender Produktdaten durch das Update. Die RSU-Recherche folgt separat. Ein eigener Papierkorb und authentifizierte DAM-Adapter sind nicht Bestandteil dieses Updates.

## 0.9.36

Metadaten erstellt: 2026-09-19T19:54:07.153Z · [Manifest](../updates/stable/0.9.36/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.36)

- Beydosh 0.9.36
- Das Speichern einer Verbindungsvorlage wird nicht mehr durch unabhängige Produktänderungen oder Hintergrundsynchronisation blockiert. Gleichzeitige Änderungen derselben Vorlage bleiben geschützt.
- Daten bearbeiten verwendet die aktuelle gespeicherte Vorlage, auch wenn der Importentwurf noch eine ältere Vorlage enthält.
- Offene Datenfenster übernehmen neue Vorlagenfelder, sofern keine ungespeicherten Änderungen oder laufenden Aktionen bestehen. Andernfalls erscheint ein Hinweis zum erneuten Öffnen.
- Neue Felder wie Produktname müssen anschließend einer Quellspalte zugeordnet werden. Bestehende Produktdaten werden durch das Update allein nicht verändert.

## 0.9.35

Metadaten erstellt: 2026-09-19T19:10:11.996Z · [Manifest](../updates/stable/0.9.35/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.35)

- Beydosh 0.9.35
- Leere EANs und beschreibende Importfelder blockieren den Import nicht mehr. Eine eindeutige Produktkennung bleibt erforderlich; widersprüchliche Kennungen werden weiterhin abgewiesen.
- Leere Preise und Bestände erhalten bestehende Werte und werden als Hinweis im Änderungsprotokoll erfasst. Fehlende Werte werden nicht zu Null umgewandelt.
- Importgepflegte Attribute bleiben unabhängig von der aktuellen Importauswahl gesperrt. Eigene geschützte Werte bleiben erhalten.
- Die Sammelbearbeitung enthält einen roten Löschbutton für sichtbare, markierte Produkte mit Sicherheitsabfrage und wiederherstellbarer lokaler Sicherung. Ausgeblendete Produkte bleiben unverändert; ungespeicherte Tabellenänderungen müssen vorher abgeschlossen werden.
- Ein eigener Papierkorb mit Wiederherstellen-Oberfläche ist nicht Bestandteil dieser Version. Vorhandene Produktdaten werden durch das Update allein nicht nachträglich geändert.

## 0.9.34

Metadaten erstellt: 2026-09-19T18:47:01.835Z · [Manifest](../updates/stable/0.9.34/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.34)

- Beydosh 0.9.34
- Attributwerte bestehender Produkte werden auch aus inzwischen abgewählten Importzeilen übernommen. Die Zuordnung erfolgt über eindeutige Lieferanten-Produktkennungen; widersprüchliche oder mehrdeutige Quellen bleiben gesperrt.
- Eigene geschützte Attributwerte bleiben bei erneuter Übernahme erhalten.
- Abgewiesene Hintergrundimporte zeigen konkrete Prüfhinweise statt ausschließlich einer allgemeinen Fehlermeldung.
- Geänderte Benachrichtigungen zeigen den aktuellen Ereigniszeitpunkt; unveränderte Meldungen behalten ihren Zeitpunkt.
- Diese Version führt keine eigenständige Bestandsdaten-Reparatur aus. Fehlende Saisonangaben in den Quelldaten werden nicht geraten.

## 0.9.33

Metadaten erstellt: 2026-09-19T18:18:16.990Z · [Manifest](../updates/stable/0.9.33/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.33)

- Beydosh 0.9.33
- Verbindungs- und Attributvorlagen werden beim Anwendungsstart vorbereitet und anschließend wiederverwendet.
- Das Öffnen und Suchen in Verbindungsvorlagen liest den großen Produktbestand nicht mehr wiederholt auf dem Oberflächen-Thread.
- Kategorie-Verknüpfungen verwenden gemeinsame Suchindizes statt wiederholter Vollsuchen über alle Importzeilen.
- Beim Speichern werden verarbeitete Produktzahlen und die anschließende Ansichtsaktualisierung getrennt angezeigt.
- Alle vorhandenen Desktop-Wartebalken laufen einheitlich von links nach rechts, ohne Rücklauf.
- 121 lokale Desktop-Selbsttests einschließlich 20.000 synthetischer Kategoriezuordnungen erfolgreich. Kein Lasttest mit echten Nutzerdaten.
- Owner Development / Private Preview. Keine Freigabe für Live-Verkauf oder echte Bestellungen.

## 0.9.32

Metadaten erstellt: 2026-09-19T17:49:33.284Z · [Manifest](../updates/stable/0.9.32/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.32)

- Beydosh 0.9.32
- Fehlercodes und eindeutige Vorgangs-IDs erleichtern die Zuordnung von Screenshots zum lokalen Fehlerprotokoll.
- Mehrfach gestapelte Absturzdialoge werden verhindert; Laufzeitfehler werden nicht mehr als Startfehler bezeichnet.
- Erwartete Import- und Synchronisationsfehler werden kontrolliert abgefangen, ohne die gesamte Anwendung zu beenden.
- Ladehinweise zeigen die Verarbeitung bei Kategorien, Importen, Synchronisation und Sammelbearbeitung an.
- Kategorie-Umbenennung und aufwendige Katalogvorbereitung erfolgen im Hintergrund; mehrere Namensänderungen werden zusammen aktualisiert.
- Die Sammelbearbeitung bereitet große Tabellen im Hintergrund vor; Kategorie-Trefferprüfungen verwerfen veraltete Ergebnisse.
- 120 lokale Desktop-Selbsttests erfolgreich. Der genaue Auslöser früherer Startabbruch-Meldungen bleibt ohne detaillierten Alt-Log offen.
- Owner Development / Private Preview. Keine Freigabe für Live-Verkauf oder echte Bestellungen.

## 0.9.31

Metadaten erstellt: 2026-09-19T16:12:40.933Z · [Manifest](../updates/stable/0.9.31/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.31)

- Beydosh 0.9.31
- - Spaltenfilter im Import und Bulk-Editor: vorhandene Werte anklicken, Mehrfachauswahl, Suche und leere Werte.
- - Lesbare Filterdialoge mit passenden Kontrasten.
- - Bulk-Editor: sichtbare Produkte markieren und mehrere Felder gemeinsam setzen.
- - Produkttyp aus vorhandenen Vorlagen auswählen; standardmäßig nur leere Felder ergänzen.
- - Änderungsvorschau mit Bisher/Neu und verständlichen Validierungsfehlern. Ausgeblendete Zeilen, Importsperren und geschützte eigene Werte bleiben geschützt.
- - Produkttypwechsel warnt vor dem Entfernen bisheriger Attribute. Passende Importattribute werden beim Speichern übernommen.
- - Optimierte Sammelzuweisung durch gemeinsame Suchindizes und gebündelte Tabellenänderungen.
- Hinweis: Der separat gemeldete Startabbruch ist mit diesem Update nicht als behoben bestätigt. Keine automatische KI-Zuordnung enthalten.

## 0.9.30

Metadaten erstellt: 2026-09-19T15:28:13.884Z · [Manifest](../updates/stable/0.9.30/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.30)

- Beydosh 0.9.30
- Spaltenfilter im Importfenster: Dropdown-Pfeile oeffnen Filter fuer Text, exakte Werte und leere oder gefuellte Zellen. Mehrere Filter werden gemeinsam angewendet.
- Alle auswaehlen und abwaehlen wirkt nur auf die gefilterte Liste. Ausgeblendete Zeilen behalten ihre Auswahl. Zaehler nennen die gesamte und ausgeblendete Auswahl, auch in der Produktliste.
- Die Produktvorschau zeigt alle Attribute einschliesslich leerer Felder und die vollstaendige Beschreibung.
- Sammelbearbeitung als CSV exportieren und zurueckimportieren: Zuordnung ueber Produkt-ID, Vergleich bisher/neu, sichtbare Fehler und Konflikte. Importsperren bleiben erhalten. Keine automatische Neuanlage. Leere Zellen bleiben standardmaessig unveraendert; Loeschen muss ausdruecklich aktiviert werden.
- Dateiverarbeitung und Bulk-Speicherung laufen im Hintergrund. Atomare Speicherung mit Revisionspruefung verhindert konkurrierendes Ueberschreiben. Die Importreservierung arbeitet mit einer getrennten Auswahlkopie.
- Reine App-Updates erzwingen bei einem ausreichend aktuellen Launcher keine weitere Launcher-Wartung samt zweitem Neustart. Tatsaechlich erforderliche Launcher-Upgrades bleiben ueber den bisherigen geprueften Wartungsweg erhalten.
- Synchronisierung: hoechstens zwei parallele Abrufe und nur ein laufender Abruf je Mandant und Verbindung. Ohne faelligen Abruf wird der gesamte Importbestand nicht mehr alle fuenf Sekunden eingelesen.
- Nach Synchronisierung und Autosave werden Katalog und Kategoriezuordnungen im Hintergrund vorbereitet. Ausgeklappte Bereiche teilen weiterhin denselben Datenstand; eigene Eingaben bleiben geschuetzt.
- Grosse Produktlisten werden gesammelt aktualisiert und virtualisiert dargestellt. Wiederholte Suchen nach Attributen, Produkttypen und Varianten wurden durch Indizes ersetzt. Aktive Listenfilter bleiben beim Aktualisieren erhalten.

## 0.9.29

Metadaten erstellt: 2026-09-13T19:36:23.537Z · [Manifest](../updates/stable/0.9.29/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.29)

- Beydosh 0.9.29
- Produktangaben werden nach kurzer Eingabepause automatisch im Hintergrund gespeichert. Der manuelle Produkt-speichern-Button entfällt. Fehler werden angezeigt, Eingaben bleiben erhalten.
- Attributkarten sind durch Rahmen, Hintergrund und Innenabstand klar getrennt. Synchronisierte Felder sind grau und schreibgeschuetzt; eigene Ueberschreibungen werden gruen hervorgehoben und bleiben vor Importaktualisierungen geschuetzt.
- Attribute ohne Importzuweisung sind direkt bearbeitbar und als manuell gepflegt gekennzeichnet. Ein zusaetzliches Ueberschreiben-Haekchen ist dort nicht notwendig.
- Neue Attribut-Kategorieverknuepfungen laden vorhandene zugeordnete Quelldaten fuer Produkte des passenden Produkttyps nach. Ein manuelles Oeffnen und Speichern jedes Produkts ist dafuer nicht mehr erforderlich.
- Doppelte Kategorieanzeige in den Produktdaten entfernt. Lieferanten-Artikelnummer und EAN erhalten eindeutige Beschriftungen.

## 0.9.28

Metadaten erstellt: 2026-09-13T18:59:24.926Z · [Manifest](../updates/stable/0.9.28/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.28)

- Beydosh 0.9.28
- Leere Attributwerte werden leer importiert und blockieren die Aktualisierung nicht. Fehlende Pflichtattribute bleiben als Qualitaetshinweis sichtbar. Identitaets-, Preis- und Bestandspruefungen bleiben bestehen.
- Je Produktattribut kann ein eigener Wert verwendet und vor Importaktualisierungen geschuetzt werden, auch bewusst leer. Ohne Haekchen gilt wieder der aktuelle Importwert. Der Importwert bleibt zum Vergleich erhalten.
- Kategorien mit Produkttyp, Attribut und Wert verknuepfen: eigenen Wert eingeben oder vorhandenen Wert auswaehlen. Passende Produkte werden dynamisch zugeordnet; manuelle Zuordnungen bleiben erhalten.
- Kategorienamen werden beim Bearbeiten automatisch gespeichert. Ueberfluessige Aktionen fuer Hinzufuegen, Umbenennen und Verschieben wurden entfernt; Unterkategorien und Drag-and-Drop bleiben verfuegbar.
- Die Kategorie-KI kann Aenderungen am Arbeitsauftrag vorschlagen. Dauerhafte Aenderungen werden erst nach ausdruecklicher Bestaetigung uebernommen; alternativ nur einmal verwenden oder ablehnen.
- Sammelbearbeitung mit dem hellen Import-Tabellenlayout. Ein gemeinsames Auswahlkaestchen ersetzt die getrennten Aktionen fuer Alle auswaehlen und Alle abwaehlen.

## 0.9.27

Metadaten erstellt: 2026-09-13T17:18:57.053Z · [Manifest](../updates/stable/0.9.27/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.27)

- Beydosh 0.9.27
- Produkte direkt ueber Auswahlkaestchen links markieren. Alle auswaehlen und alle abwaehlen gelten fuer die sichtbare Produktliste.
- Sammelbearbeitung als Tabelleneditor fuer genau die ausgewaehlten Produkte. Unterschiedliche Werte je Zeile bearbeiten und gemeinsam speichern. Importgesperrte Felder bleiben geschuetzt.
- Roter Produkt(e) loeschen-Button links neben Produkt hinzufuegen. Ohne Auswahl bleiben Loeschen und Sammelbearbeitung deaktiviert.
- Loeschen erfordert eine Bestaetigung und legt zuvor eine lokale Sicherung an. Dateien bleiben zur Wiederherstellung erhalten. Geloeschte Produkte werden aus der gespeicherten Importauswahl entfernt; IDs werden nicht wiederverwendet.

## 0.9.26

Metadaten erstellt: 2026-09-13T16:52:01.526Z · [Manifest](../updates/stable/0.9.26/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.26)

- Beydosh 0.9.26
- Produktseite mit fester Vorschau links, klaren Bereichen und kompakten Eingabefeldern rechts.
- Drei anklickbare Vorschaubilder unter dem Hauptbild. Weitere Bilder per Pfeilen oder Mausrad anzeigen.
- Produkttypen laden passende Attribute und vorhandene Importwerte. Beim Typwechsel werden alte Attributwerte entfernt.
- Automatische Verbindungsabrufe aktualisieren Produkte erst nach erfolgreicher Pruefung. Fehlerhafte Abrufe erhalten den vorherigen Datenstand.
- Lange Feldnamen in Verbindungsvorlagen werden umgebrochen. Das aktive Zuordnungsfeld bleibt bei der Spaltenwahl hervorgehoben.

## 0.9.25

Metadaten erstellt: 2026-09-13T15:46:59.218Z · [Manifest](../updates/stable/0.9.25/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.25)

- Alle Felder in Verbindungsvorlagen haben dieselbe doppelte Hoehe fuer ein gleichmaessiges Sortierraster.
- Bereits zugeordnete Attribute werden in der Auswahl gruen markiert. Die aktuelle Auswahl wird gesondert gekennzeichnet.
- Auch ungespeicherte Zuordnungen werden beruecksichtigt. Gleichnamige Attribute verschiedener Vorlagen bleiben getrennt.
- Beim Auswaehlen eines Attributs uebernimmt die Feldueberschrift automatisch dessen Namen.

## 0.9.24

Metadaten erstellt: 2026-09-13T15:06:43.120Z · [Manifest](../updates/stable/0.9.24/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.24)

- Attributauswahl nach aufklappbaren Vorlagen: Suche nach Attribut- und Vorlagennamen. Zugeordnete Felder zeigen den Namen der uebergeordneten Vorlage.
- Nur Attribute aus Vorlagen stehen zur Auswahl. Unbenutzte Altdefinitionen werden beim Oeffnen der Verbindungsvorlagen mit Wiederherstellungsnachweis bereinigt. Bestehende Produktwerte und verwendete Zuordnungen bleiben erhalten.
- Beim Import werden Attribute ausschliesslich fuer den gespeicherten Produkttyp uebernommen. Dieselbe CSV-Spalte kann Reifen- und Felgenattribute versorgen, ohne beide am selben Produkt zu befuellen. Ohne Produkttyp werden keine Attributwerte zugewiesen oder angezeigt.
- Werte uebersetzen im Importfenster: Spaltenkopf auswaehlen und unterschiedliche Quellwerte in einer kleinen Tabelle uebersetzen. Leere Uebersetzungen uebernehmen den Originalwert unveraendert.
- Die Importvorschau zeigt Originalwert und Uebersetzung mit einem Pfeil. Die Quelldatei und gespeicherten Originalzeilen bleiben unveraendert; ins passende Produktattribut gelangt nur der uebersetzte Wert.
- Uebersetzungen werden mit Entwurf speichern oder Importieren in der Verbindungsvorlage gespeichert und bei weiteren Importen wiederverwendet. Nicht mehr in der aktuellen Datei vorkommende Uebersetzungen bleiben erhalten.
- Uebersetzte Attributwerte werden auf Datentyp und erlaubte Auswahlwerte geprueft. Produktkennungen sind von Uebersetzungen ausgenommen. Gleichzeitige Aenderungen an Uebersetzungen werden nicht still ueberschrieben.

## 0.9.23

Metadaten erstellt: 2026-09-13T11:29:41.971Z · [Manifest](../updates/stable/0.9.23/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.23)

- Beydosh 0.9.23
- Attribute sind pro Attributvorlage eindeutig. Reifen und Felgen koennen gleichnamige Attribute mit unabhaengigen Datentypen, Einheiten und Auswahlwerten besitzen.
- Beim Speichern bestehender Vorlagen werden deren Attribute eindeutig zugeordnet. Vorhandene Produktwerte bleiben erhalten. Eindeutige Importzuordnungen werden mitgefuehrt; mehrdeutige Altzuordnungen verlangen eine ausdrueckliche Auswahl im Importeditor.
- Leere Attribute lassen sich auch bei bereits zugeordneten Produkten bearbeiten. Unvereinbare Aenderungen an bereits gefuellten Produktwerten werden mit konkretem Produkthinweis verhindert; keine automatische Umrechnung von Einheiten.
- Die Auswahl des Produkttyps in der Produktuebersicht laedt sofort die passenden Felder im Bereich Attribute unter Produktdaten. Noch nicht gespeicherte Eingaben bleiben beim Wechsel zwischen Produkttypen im Editor erhalten.
- Attributvorlagen speichern automatisch. Der alte Verwerfen-Dialog wurde entfernt. Bei ungueltigen Eingaben bleibt die Seite mit konkreter Meldung offen; der gespeicherte Stand kann direkt wiederhergestellt werden.
- KI-Entwuerfe und Verbindungsvorlagen verwenden die vorlagenbezogene Zuordnung. In der Attributauswahl wird der zugehoerige Produkttyp angezeigt.

## 0.9.22

Metadaten erstellt: 2026-09-13T00:13:43.582Z · [Manifest](../updates/stable/0.9.22/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.22)

- Verbindungsvorlagen: neuer einheitlicher Name, eigenes ausklappbares Fenster und 50/50-Aufteilung zwischen Vorlagenliste und Bearbeitung.
- Attributvorlagen speichern gueltige Aenderungen automatisch nach kurzer Eingabepause. Der manuelle Speichern-Button entfaellt. Ungueltige Eingaben bleiben sichtbar und ueberschreiben keine gespeicherten Daten.
- Unabhaengige Aenderungen im Datenbereich blockieren das Speichern von Attributvorlagen nicht mehr. Gleichzeitige Aenderungen derselben Vorlage oder ihrer Attribute bleiben geschuetzt.
- Plus Attribut fuegt oben direkt Neues Attribut 1, 2 usw. ein. Die bisherige Auswahl zum Wiederverwenden entfaellt.
- Vorlagenname heisst bei Attributvorlagen jetzt Produkttyp. Allgemeine Merkmale unter Produkten heisst Attribute.
- Die Produkt-Attributfelder wechseln direkt mit dem ausgewaehlten Produkttyp. Gespeicherte Werte anderer Vorlagen bleiben erhalten. Preis, EAN und Waehrung stehen in der Uebersicht.
- Die freie Eingabe Eigenes Merkmal hinzufuegen am Produkt wurde entfernt. Neue Attributfelder werden ueber die Vorlagen definiert.

## 0.9.21

Metadaten erstellt: 2026-09-12T23:40:16.966Z · [Manifest](../updates/stable/0.9.21/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.21)

- Attributvorlagen stehen als eigenstaendiger Menuepunkt unter Kategoriemodelle und koennen in einem eigenen Fenster geoeffnet werden.
- Vorlagenliste und Vorlageneditor nutzen je eine Haelfte der Attributvorlagen-Seite. Dunkle Zeilen und vertikal zentrierte Texte verbessern die Lesbarkeit.
- Attributfelder werden ueber Ziehgriffe statt Pfeilbuttons sortiert. Ein Klick auf den Griff erlaubt die Positionsauswahl ohne Ziehen.
- Schnittstellenfelder machen waehrend des Ziehens sichtbar Platz. Die gruene Zielflaeche erscheint beim Betreten einer Position; Abbrechen stellt die urspruengliche Anordnung wieder her.
- Groessere Ziehgriffe und vertikal zentrierte Texte in Schnittstellenvorlagen. Positionsauswahl auch per Klick und Tastatur.
- Kategorie ist nicht mehr als neuer Schnittstellen-Feldtyp auswaehlbar. Vorhandene Kategorie-Felder alter Vorlagen bleiben aus Kompatibilitaetsgruenden erhalten. Die gezielte Zuordnung ueber Bearbeiten betrifft Attribute.

## 0.9.20

Metadaten erstellt: 2026-09-12T22:33:40.303Z · [Manifest](../updates/stable/0.9.20/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.20)

- Attributvorlagen stehen unter Kategoriemodelle zur Verfügung. Vorlagen enthalten Datentypen, Einheiten, Auswahlwerte, Pflichtfelder und Bearbeitungsregeln.
- Der Attributvorlagen-Assistent verwendet die zentrale KI-Verbindung. Vorschläge werden erst nach Prüfung übernommen und separat gespeichert; tatsächliche Produkteigenschaften werden nicht erfunden.
- Importvorlagen werden direkt auf einer Seite bearbeitet: Vorlagenliste links, ausgewählte Vorlage rechts.
- Attributfelder lassen sich über Bearbeiten und eine Suche mit bestehenden Attributen verknüpfen. Die Zielzuordnung bleibt unabhängig von der Feldbezeichnung erhalten.
- Ungültige Attributwerte und veraltete Zielzuordnungen werden beim Import gemeldet. Bestehende freie Attributfelder bleiben kompatibel.
- Das Feldraster zeigt bis zu drei Spalten. Zwei kleine Felder passen neben ein doppelt hohes Attributfeld; freie Plätze werden kompakt genutzt.
- Drag & Drop zeigt die erwartete Zielposition grün an. Ziehen am Griff, Abbrechen und Verschieben per Alt plus Pfeiltasten werden unterstützt.
- Einstellungen und Info & Hilfe bleiben am unteren Ende des Menüs. Keine zusätzliche KI-Spaltenzuordnung in diesem Update.

## 0.9.19

Metadaten erstellt: 2026-09-12T20:45:39.942Z · [Manifest](../updates/stable/0.9.19/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.19)

- Der Kategorie-Assistent zeigt nach jedem geprueften KI-Teilschritt den bisherigen Gesamtvorschlag direkt unter der laufenden Aktivitaetsanzeige.
- Der Zwischenstand bleibt waehrend weiterer Teilanfragen sichtbar. Neue Kategorien bleiben gruen hervorgehoben.
- Status und Stopp-Button stehen oberhalb des Baums. Die Anzeige nennt den zuletzt geprueften Teilschritt.
- Nach Abschluss verschwindet die Aktivitaetsanzeige; der Vorschlag bleibt stehen. Bei Abbruch bleiben fertig gepruefte Teilvorschlaege erhalten.
- Der gespeicherte Kategoriebaum bleibt unveraendert, bis der Nutzer den Vorschlag nach Ende der Anfrage anwendet.

## 0.9.18

Metadaten erstellt: 2026-09-12T20:20:44.128Z · [Manifest](../updates/stable/0.9.18/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.18)

- Kategorie-Assistent: Antwortlokale Entwurfsschluessel werden bei weiteren Teilschritten eindeutig zugeordnet. Bestehende Kategorien und bisherige Teilvorschlaege bleiben erhalten.
- Jeder KI-Teilschritt zeigt eine eigene aktualisierte Aktivitaet. Fehler und abgebrochene Fortsetzungen werden nicht mehr als erfolgreicher Abschluss angezeigt.
- Im Benachrichtigungsverlauf entfallen die Aktionen zum Als-gelesen-Markieren. In aktuellen Benachrichtigungen bleiben sie verfuegbar.
- Prozentwerte der Produkt-Pflegezustaende werden korrekt angezeigt, zum Beispiel 100 % statt 10000 %.
- Das Dashboard zeigt einen Netto-Umsatzverlauf mit Zeitraeumen 1 Tag, 1 Woche, 1 Monat, 1 Jahr, 3 Jahre und benutzerdefinierter Kalenderauswahl.
- Der Kalender erlaubt Start- und Enddatum, eine gruene Bereichsmarkierung und das Zuruecksetzen mit dem dritten Klick.
- Der Umsatzverlauf verwendet ausschliesslich vorhandene datierte Tagesumsaetze. Ohne solche Daten wird ein Hinweis statt erfundener Werte angezeigt.
- Windows-Icons fuer Anwendung, Launcher und Setup nutzen die verfuegbare Flaeche besser. Das bestehende Logo bleibt unveraendert.

## 0.9.17

Metadaten erstellt: 2026-09-12T19:18:14.233Z · [Manifest](../updates/stable/0.9.17/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.17)

- Grosse Kategorie-Auftraege werden in Teilanfragen automatisch fortgesetzt und zu einem ungespeicherten Vorschlag zusammengefuehrt. Jede Teilanfrage kann Kontingent oder Gebuehren verbrauchen.
- Stopp rechts neben der Aktivitaetsanzeige beendet den laufenden Auftrag. Fertige Teilvorschlaege und offene Fortsetzung bleiben im Kategorie-Chat erhalten.
- Keine feste Gesamtanzahl fuer Vorschlagskategorien oder Teilanfragen. Technische Anfrage-, Anbieter- und Arbeitsspeichergrenzen sowie das eingestellte Zeitlimit bleiben wirksam. Keine automatische Wiederholung nach Fehlern oder fehlendem Fortschritt.
- Der Uebergangsbutton zum Zuordnen frueherer Gesamtmodell-Chats wurde entfernt. Bestehende gespeicherte Chats bleiben erhalten.
- Der Launcher verwendet das rahmenlose Fortschrittsfenster auch beim normalen Start. Echte Meldungen zeigen Installationspruefung, Nutzerdaten laden und Anwendung laden.
- Nutzerdaten bleiben bei Deinstallation mit Datenerhalt und anschliessender Neuinstallation getrennt von den Programmdateien erhalten, einschliesslich vorhandener Starteinstellungen.
- Die vorhandene Wartung kennt jetzt auch Produkt-/Importworkspaces, Kataloge und den zentralen Datenbereich fuer kuenftige Funktionen. Vollstaendige Datenentfernung erfolgt vor endgueltiger Entfernung der Programmdateien; Fehler werden im Setup gemeldet.
- Unbekannte oder beschaedigte Einstellungsformate werden nicht mehr stillschweigend durch Standardwerte ersetzt. Vorhandene Daten bleiben unveraendert.

## 0.9.16

Metadaten erstellt: 2026-09-12T18:00:47.458Z · [Manifest](../updates/stable/0.9.16/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.16)

- Ein KI-Chat pro Kategoriebaum: Auch Unterkategorien oeffnen den Chat des obersten Knotens. Die Bereichsauswahl im Assistenten entfaellt.
- Neue Kategoriebaeume erscheinen sofort mit nummerierten Platzhalternamen und werden ausgewaehlt. Ohne Kategorieauswahl bleibt der KI-Assistent deaktiviert.
- KI-Ergaenzungen behalten offene Entwuerfe bei; widerspruechliche Schluessel werden abgewiesen. Die Vorschau zeigt den gesamten Baum einschliesslich unveraenderter Zweige wie BMW.
- Der Name der Baumwurzel kann als KI-Vorschlag geaendert werden. Kategorie-ID und Chat bleiben erhalten; gespeichert wird erst nach Vorschlag anwenden.
- Fruehere Gesamtmodell-Chats lassen sich bewusst einem leeren Baum-Chat zuordnen. Der urspruengliche Verlauf bleibt erhalten.
- Aktivitaetsmeldungen der KI scrollen automatisch mit und zeigen auch bei langen Anfragen die neuesten Schritte.
- Drag und Drop zeigt Einfuegelinien, hervorgehobene Unterkategorie-Ziele und den vollstaendigen Zielpfad. Zweige oeffnen sich nach kurzem Verweilen; Randscrollen erleichtert tiefe Hierarchien.
- Das globale KI-Zeitlimit speichert gueltige Eingaben automatisch. Eine Trennlinie trennt es optisch von API und Anmeldung.
- Benachrichtigungen und Planansicht erhalten einen quadratischen Schliessen-Button.
- Rahmenloses Launcher-Fortschrittsfenster im Setup-Format mit Beydosh-Hintergrund, weissem Schriftzug und animierter gruener Anzeige nach dem Schliessen der Anwendung.
- Der signierte Launcher-Wartungsweg unterstuetzt kuenftige Zielversionen ohne feste Bindung an 0.9.4. Signaturpruefung, Versionsbindung, Downgrade-Schutz und Wiederherstellung bleiben erhalten.
- Dieses Update aktualisiert nach dem App-Update auch den Launcher. Dabei kann Beydosh ein weiteres Mal schliessen und automatisch starten. Download und Pruefung erfolgen weiterhin vor dem Schliessen.

## 0.9.15

Metadaten erstellt: 2026-09-12T16:38:48.219Z · [Manifest](../updates/stable/0.9.15/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.15)

- KI-Aktivität: Deutlich sichtbarer grüner Strich bewegt sich im Vorschlagsbereich hin und her.
- KI-Zeitlimit: Global in Einstellungen konfigurierbar, 1 bis 120 Minuten; Standard 10 Minuten. Gilt ab der nächsten Inhaltsanfrage für API und Anmeldung.
- Datenerhalt: Nach Abbruch, Fehler oder Rückfrage wird der vorherige Vorschlag mit seiner Auswahl wiederhergestellt. Ausdrückliches Verwerfen bleibt wirksam.
- Aktivitätsverlauf: Aufklappbare Prozessanzeige mit Uhrzeiten im Chat, getrennt von der fertigen Antwort. Codex meldet echte Verarbeitungsschritte und Webrecherche-Ereignisse.
- API-Status: Senden, Empfangen und Prüfen sichtbar. Fehlende Live-Zwischenschritte werden ehrlich kenntlich gemacht; keine erfundenen Fortschrittsangaben oder internen Gedankengänge.

## 0.9.14

Metadaten erstellt: 2026-09-12T13:20:11.333Z · [Manifest](../updates/stable/0.9.14/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.14)

- Kategorie-Assistent: Beim Senden wird automatisch auf Vorgeschlagene Änderungen gewechselt. Eine Ladeanimation zeigt die laufende Anfrage; der alte Vorschlag wird ausgeblendet.
- Vorschau: Reiner Kategoriebaum mit Auswahlhäkchen, ohne eingeblendete Quellenbelege, Hinweise oder Links. Quelldaten bleiben erhalten.
- Arbeitsauftrag: Separat über Arbeitsauftrag öffnen erreichbar, schließbar und weiterhin automatisch gespeichert und berücksichtigt.
- Vorschlag anwenden: Übernimmt die ausgewählten Ergänzungen und zeigt den gespeicherten aktuellen Baum. Fehler und Rückfragen lassen keine alte Vorschau anwendbar.
- Chat: Eingabebereich optisch getrennt. Neuer Chat entfernt; Gespräche bleiben an ihre Kategorie-ID gebunden.

## 0.9.13

Metadaten erstellt: 2026-09-12T11:46:53.312Z · [Manifest](../updates/stable/0.9.13/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.13)

- Kategorie-Assistent: Maximiertes Fenster mit Entwurf links und Chat rechts. Folgefragen können direkt beantwortet werden.
- Recherche: Zuschaltbare Webrecherche für OpenAI-API und Codex-Anmeldung. Quellen und Unsicherheiten am Vorschlag; keine automatische Kompatibilitätsfreigabe.
- Gespräche: Chat, Arbeitsauftrag und Entwurf bleiben pro Kategorie-ID lokal gespeichert und können nach einem Neustart fortgesetzt werden.
- Übersicht: Bereich wechseln, gespeicherten Baum und vorgeschlagene Änderungen getrennt prüfen sowie passende Antwortvorschläge übernehmen.
- Bedienung: Größere Schrift, sichtbarer Tastaturfokus, Screenreader-Beschriftungen und dauerhafte Status- und Speicherhinweise.
- Datenerhalt: Bestehende Kategorie-JSONs und ältere Chat-Dateien bleiben lesbar; Speicherkonflikte und beschädigte Dateien werden nicht stillschweigend überschrieben.

## 0.9.12

Metadaten erstellt: 2026-09-12T10:39:03.033Z · [Manifest](../updates/stable/0.9.12/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.12)

- Produkte: Eigene Produkte anlegen und mehrere Produkte mit Vorschau gemeinsam bearbeiten. Importgeschützte Felder bleiben gesperrt.
- Varianten: Eigenständige Produkte verknüpfen; jede SKU, jeder Bestand und alle Importdaten bleiben getrennt.
- Produktpflege: Strukturierte Attribute, Einheiten, Auswahlwerte und zusätzliche Pflichtfelder je Produkttyp konfigurieren.
- Sprachen und Märkte: Produkttexte sowie lokale Verkaufspreise und Währungen bearbeiten, ohne den Basispreis zu überschreiben oder Plattformexporte auszulösen.
- Assets: Bilder anzeigen, ein Hauptbild festlegen, Reihenfolge ändern und Dokumentrollen vergeben.
- Feldverlauf: Frühere manuelle Feldwerte vergleichen und unter Beachtung aktueller Importsperren wiederherstellen.
- KI-Anmeldung: API und Anmeldung ohne ODER; OpenAI-Anmeldung lädt verfügbare Modelle automatisch. Modell und Denkintensität erscheinen nach erfolgreicher Verbindung.
- Kategorie-Assistent: Abgewiesene Codex-Anfragen durch korrigierte Protokollparameter behoben; keine zusätzliche Sende-Checkbox.
- Kategorien: Kategorie samt Unterzweigen nach Bestätigung löschen, keine Wiederverwendung gelöschter Kategorie-IDs und kompakte Suche mit Lupensymbol.

## 0.9.11

Metadaten erstellt: 2026-09-12T09:03:37.854Z · [Manifest](../updates/stable/0.9.11/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.11)

- KI-Verbindung: In den Einstellungen zwischen API ODER Chatbot wechseln; die aktive Verbindung wird hervorgehoben.
- Chatbot: Codex mit ChatGPT-Anmeldung, eigener geschützter Anmeldung und Modellauswahl nutzen. Eine lokale Codex-Installation ist erforderlich.
- Verbindungen testen: API-Schlüssel und Modell beziehungsweise Chatbot-Anmeldestatus ohne Textgenerierung prüfen; Gebühren- und Kontingenthinweise bleiben sichtbar.
- Neustart: Die gespeicherte Chatbot-Verbindung wird geprüft. Keine automatische Anmeldung und kein stiller Wechsel zur API.
- Kategorie-Assistent: Die ausgewählte Verbindung erstellt ausschließlich prüfbare Vorschläge; Übernahme bleibt ausdrücklich manuell.
- Claude- und Gemini-Chatbot-Abonnements sind noch nicht angebunden; deren API-Anbindung bleibt verfügbar.

## 0.9.10

Metadaten erstellt: 2026-09-11T17:23:54.372Z · [Manifest](../updates/stable/0.9.10/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.10)

- Beydosh 0.9.10
- KI-Assistent: Ungültige oder unvollständige Antworten sowie API-Fehler werden verständlich im Assistenten und als Benachrichtigung angezeigt. Kein irreführender Startabbruch bei diesen Fehlern.
- KI-Einstellungen: Auswahl zwischen OpenAI, Anthropic/Claude und Google/Gemini. Darunter stehen anbieterspezifische Modellvorschläge und die Eingabe einer eigenen Modell-ID bereit.
- Denkintensität: Für GPT-5.6 Sol und GPT-6 Astra können Modellstandard, Low, Medium oder High gewählt werden. Andere Modelle verwenden zunächst ihren Modellstandard.
- Anbietersicherheit: Schlüssel bleiben an ihren Anbieter gebunden. Beim Wechsel wird die bisherige zentrale Verbindung ausdrücklich ersetzt. Kein automatischer Anbieterwechsel und keine automatischen Wiederholungen.
- Kategorieentwürfe bleiben bis zur manuellen Bestätigung unverbindliche Vorschläge. API-Zugang und Kosten werden durch den jeweiligen Anbieter bestimmt.

## 0.9.9

Metadaten erstellt: 2026-09-09T09:37:21.512Z · [Manifest](../updates/stable/0.9.9/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.9)

- Kategorien: KI-Assistent mit strukturierten JSON-Vorschlägen, Rückfragen und auswählbarer Vorschau. Bestehende Kategorien werden nicht automatisch verändert.
- KI-Verbindung: zentraler API-Schlüssel und Modell in Einstellungen. Schlüssel bleiben im Windows-Anmeldeinformationsspeicher und werden nicht exportiert.
- Kategorien: JSON-Import und -Export sowie Speicherung separater Entwürfe. Übernahme erst nach Prüfung und bewusster Auswahl.
- Kategorien: zusätzliche Absicherung gegen doppelte Einträge, zyklische Verknüpfungen und veraltete Vorschauen; Sicherung des vorherigen Modells.
- Kategorien: letzte übernommene Ergänzung innerhalb der Sitzung sicher archivieren, ohne bestehende Produkt-IDs zu löschen.
- Oberfläche: breiterer Kategoriebaum, kompaktere Bearbeitung, getrennte Bildläufe und grün hervorgehobene neue Kategorien in der Vorschau.
- Menü: Ausklappen öffnet das zusätzliche Fenster, ohne im Hauptfenster die aktuelle Seite oder Überschrift zu wechseln.
- KI-Sicherheit: nur ausdrücklich gestartete Anfragen, begrenzter Kontext und begrenzte Antwortgröße, keine automatischen Wiederholungen und keine erzeugten Produktkompatibilitäten.

## 0.9.8

Metadaten erstellt: 2026-09-08T22:48:04.906Z · [Manifest](../updates/stable/0.9.8/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.8)

- Produktübersicht mit bearbeitbarem Namen und Beschreibung, kopierbarer SKU, Bestand sowie Zurück und Produkt speichern. Ungespeicherte Änderungen werden beim Verlassen abgefragt.
- Importvorlagen bestimmen die Feldsperren auch bei fehlenden Werten. Manuelle Ergänzungen bleiben erhalten; abweichende spätere Importwerte werden als Konflikt gemeldet und können ausdrücklich übernommen werden.
- Produktdetails zeigen den Produktnamen als Überschrift, einen kompakten Pflegezustand und keine Listenaktionen. Eigene Merkmale, Währung und Feldherkunft ergänzen den Editor.
- Neuer Reiter Assets: Bilder und PDF-Dateien lokal zum Produkt hinzufügen und Zuordnungen entfernen, ohne Originaldateien zu löschen. Kein Plattformupload.
- Freie Kategorienbäume mit aufklappbaren Zweigen, Suche, vollständigen Pfaden, Sortierung und Verschieben. Produkte können mehrere Endpunkte erhalten; Vorfahren werden automatisch berücksichtigt.
- Kategorienfilter kombinieren ODER innerhalb eines Baums und UND zwischen Bäumen. Trefferzahlen grenzen die Auswahl ein; ausgewählte Werte ohne Treffer bleiben sichtbar.
- Optionale Kategorie-Regeln verbinden exakte Importwerte mit Endpunkten und mehreren Bedingungen. Manuelle Zuordnungen bleiben getrennt; fehlende Regelfelder werden im Center gemeldet.
- Dunkle Scrollbars, lesbares Ausklappen-Menü und kontrastreiche Tooltips. Das Löschsymbol der Vorlagenfelder ist ein gezeichnetes Mülleimer-Icon und benötigt keine Symbolschrift.
- Kompakte Zuordnungsbuttons, gleich hohe Such- und Aktualisierungsfelder, ausgerichtete Vorlagenbeschriftungen und Vorlagennamen ohne technische Objektdarstellung. Text-Clipping in Eingabefeldern korrigiert.
- Benachrichtigungen zeigen die aktive Ansicht im Titel. Der alte Hinweisbalken entfällt; Informationen und Speicherergebnisse stehen im Center und nutzen die kurzen Popups. Sicherheitsupdate- und Rollback-Dialoge bleiben erhalten.

## 0.9.7

Metadaten erstellt: 2026-09-08T21:25:39.163Z · [Manifest](../updates/stable/0.9.7/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.7)

- ID-Vergabe beim Auswählen, Speichern und Wiederöffnen von Importentwürfen korrigiert.
- Importierte Produkte werden sofort in Produkte angezeigt, mit Lieferanten-Artikelnummer, EAN, Einkaufspreis und Bestand.
- Verbindungsdaten öffnen im eigenen Fenster mit dem Titel Daten von und dem jeweiligen Verbindungsnamen. Kompaktere Zuordnungsfelder, Auswahlbutton links neben der Suche und horizontales Mausrad während der Spaltenauswahl.
- Lieferanten-ID rechts neben der Vorlagenauswahl sowie als Spalte zwischen Name und Intervall.
- Vorlagenfelder als kompakte Zeilen mit Papierkorb, Trennlinie und Drag-and-drop-Sortierung mit Einfügelücke und automatischem Scrollen in den äußeren 15 Prozent.
- Gelesene Nachrichten verlassen das aktive Center und bleiben im tageweise gruppierten Benachrichtigungsverlauf erhalten. Doppelklick führt die hinterlegte Aktion aus und markiert die Nachricht als gelesen.
- Update-Benachrichtigungen öffnen per Doppelklick Updates und Installation mit Hervorhebung. Neue Meldungen und erfolgreiche Importe erscheinen unten rechts für drei Sekunden und blenden aus.
- Hinweise im Importeditor sind kontrastreich lesbar. Ausgeklappte Menüfenster tragen Beydosh im Titel.
- CSV-Aktualisierungen prüfen zugeordnete Spaltenüberschriften. Fehlende oder mehrdeutige Spalten blockieren die Übernahme und werden rot sowie im Center gemeldet. Geänderte Reihenfolgen bleiben über die Namen zugeordnet.
- Einrichtung ersetzt die Demo-Auswahl und zeigt dieselben lokalen Produkte und Kategorien wie Live. Die orange Kennzeichnung Einrichtungsmodus steht links neben der Versionsanzeige. Plattformexporte bleiben in Einrichtung gesperrt; Live umgeht keine zusätzlichen Freigaben.

## 0.9.6

Metadaten erstellt: 2026-09-08T20:20:15.776Z · [Manifest](../updates/stable/0.9.6/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.6)

- Vorlagen Schnittstelle: Benennbare Vorlagen mit vorkonfigurierten Feldern und eigenen Attributen erstellen und in einem separaten Fenster bearbeiten.
- Verbindungen: Gemeinsame Lieferanten-ID vergeben und eine gespeicherte Importvorlage auswählen.
- Spaltenzuordnung: Zweigeteilte Feldbuttons, rote Markierung fehlender Zuordnungen und direkte Spaltenauswahl mit abgedunkeltem Fenster und weiterhin bedienbarer Tabelle.
- Importentwürfe können unvollständig gespeichert und nach Neustart über Daten bearbeiten erneut geöffnet werden. Fehlende Felder und Konflikte erscheinen im Benachrichtigungscenter.
- Produkte aus getrennten Listen werden über gemeinsame eindeutige Lieferanten-Artikelnummern, EAN oder SKU abgeglichen; fehlende Felder löschen keine bestehenden Werte.
- Beydosh-IDs erscheinen neben den Auswahlkästchen. Vorläufige Reservierungen sind wiederverwendbar; bereits importierte Produkt-IDs bleiben dauerhaft vergeben.
- Die Importtabelle zeigt abwechselnd weiße und hellpfirsichfarbene Zeilen. Die Suche steht rechts über der Tabelle mit Lupensymbol und Suchen-Platzhalter.
- Sammelbearbeitung und Datenzeitpunkt-Zuordnung entfernt. Der ursprüngliche Abrufzeitpunkt bleibt beim Speichern und Wiederöffnen erhalten.

## 0.9.5

Metadaten erstellt: 2026-09-08T18:43:03.950Z · [Manifest](../updates/stable/0.9.5/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.5)

- CSV-Import: Anführungszeichen innerhalb unquotierter Felder werden als Originaltext erhalten und verhindern das Laden des Importentwurfs nicht mehr.
- CSV-Feldgrenzen, korrekt quotierte Inhalte und die Prüfung beschädigter Datensätze bleiben erhalten.
- Menü: Navigation und Ausklappen bilden optisch einen gemeinsamen Button mit dezenter Trennlinie.

## 0.9.4

Metadaten erstellt: 2026-09-08T17:53:34.186Z · [Manifest](../updates/stable/0.9.4/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.4)

- - Große Kataloge werden beim Laden abschnittsweise verarbeitet; Download-Fortschritt und Abbrechen sind verfügbar.
- - Importfehler werden im Importbereich angezeigt, statt einen allgemeinen Startabbruch auszulösen.
- - Der WPF-Startabsturz des Launcher-Wartungshelfers durch eine ungültige StartupUri-Zuweisung ist korrigiert.
- - Patch-Notes zeigen die Versionsnummer der installierten Anwendung.
- - Dashboard, Produkte, Kategorienmodell und Verbindungen lassen sich in eigene Fenster ausklappen.
- - Das Menü wird über das Drei-Striche-Symbol oder einen Klick außerhalb geschlossen; Zurück-Buttons entfallen.
- - Sicherheitsmeldungen stehen im Benachrichtigungscenter vor normalen Meldungen und sind rot mit „Sicherheit“ gekennzeichnet.
- - Sicherheitsupdates bieten „Jetzt aktualisieren“ und eine Erinnerung frühestens nach vier Stunden und einem späteren Programmstart.

## 0.9.3

Metadaten erstellt: 2026-09-08T16:06:43.311Z · [Manifest](../updates/stable/0.9.3/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.3)

- Importentwürfe zeigen eine bearbeitbare Tabelle mit Auswahlkästchen, Originalwerten und vorhandenen Produktdaten. Alle Zeilen sind zunächst abgewählt.
- Nur ausgewählte und manuell geprüfte Produkte werden nach ausdrücklicher Bestätigung importiert. Änderungen verwerfen eine bestehende Prüfung.
- KI-Prüfung ist an eine ausdrückliche Auswahlaktion gebunden. Ohne separat eingerichtete KI-Verbindung erfolgen keine externen KI-Aufrufe.
- Verbindungen speichern ein Aktualisierungsintervall in Sekunden und zeigen es in beiden Listen. Automatische Downloads werden dadurch noch nicht gestartet.
- Während des Update-Downloads und der Verifikation erscheint ein Ladebalken ohne unbelegte Prozentwerte.
- Versionsgebundene Patch-Notes werden mit der App ausgeliefert; verifizierte Updateinformationen ergänzen den aktuellen Stand.
- Ein fehlender Datenbestand zeigt einen Leerzustand ohne internen Dateipfad; beschädigte Daten bleiben gesperrt.
- Ein separat geprüfter Wartungshelfer aktualisiert den Launcher beim ersten Start nach dem Update. Die bestehende Reparatur und Deinstallation bleiben erhalten; fehlgeschlagene Versuche erzeugen keine automatische Neustartschleife.

## 0.9.2

Metadaten erstellt: 2026-09-08T14:08:47.366Z · [Manifest](../updates/stable/0.9.2/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.2)

- Die Anwendung zeigt beim Start immer zuerst das Dashboard.
- Download-Links bleiben bei der Eingabe sichtbar und werden nach dem Speichern bis auf die ersten zehn Zeichen verdeckt. Klartext anzeigen blendet den gespeicherten Link ein.
- Verbindung prüfen testet den Datenempfang vom gespeicherten HTTPS-Download-Link mit Zeitlimit und verständlicher Fehlermeldung. Es werden keine Produkte importiert und keine Bestände verändert.
- Die beiden Verbindungslisten verwenden die Spaltenüberschrift Schlüssel.

## 0.9.1

Metadaten erstellt: 2026-09-08T13:41:39.813Z · [Manifest](../updates/stable/0.9.1/manifest.beydosh.json) · [GitHub-Release](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/releases/tag/v0.9.1)

- Ein noch nicht veröffentlichter Updatekanal wird verständlich angezeigt. Sicherheitsfehler bleiben weiterhin Fehler.
- Import- und Export-Verbindungen werden direkt als gespeicherte, ausgewählte Zeile angelegt und unter „Ausgewählte Verbindung“ bearbeitet.
