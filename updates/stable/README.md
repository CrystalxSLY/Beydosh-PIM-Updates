# Signierter Kanal stable

[Übersicht](../../README.md) · [Veröffentlichungsverfahren](../../docs/PUBLISHING.md)

Dokumentationsstand 07.10.2026: **0.9.97** ist aktiviert. `stable` ist eine technische Kanalkennung, keine öffentliche Produkt- oder Live-Freigabe. Die Veröffentlichung bleibt eine Owner-Development-Vorabversion.

## Aufbau

- [latest.beydosh.json](latest.beydosh.json): signierter, veränderlicher Kanalindex.
- `<version>/manifest.beydosh.json`: unveränderliches signiertes Versionsmanifest.
- GitHub-Release `v<version>`: unveränderliche `00001.bupd` und gegebenenfalls weitere Transportchunks.

Der Index bindet die Manifestbytes per SHA-256. Das Manifest bindet Paket-URLs, Größen, Hashes, Inventar und Kompatibilität. Paketformat: `beydosh-signed-plain-v2`. Pakete und Manifest müssen öffentlich erreichbar und geprüft sein, bevor Latest zuletzt aktiviert wird. Bestehende Versionsinhalte werden nicht ersetzt.

## Aktueller veröffentlichter Stand

- Version: 0.9.97
- Veröffentlichung: 07.10.2026
- MinimumLauncher: 0.9.0
- Plattform: Windows/x64, .NET 9 Desktop Runtime erforderlich
- SourceCommit: `ec31bac166743aa00671bd12b4448b5e895eef8b`
- Manifest-SHA-256: `7AF601014AEA4C6D58E630A929429AE8906330E44C5A32B5FC462A7E6D722C1B`
- Transportpaket: 26.780.059 Bytes
- Transport-SHA-256: `1E015C378C2F4DBCEEE78FD87DFC47F9CD3FCD2DC2D7FB619DC60339A2A71C46`
- Aktivierung: [7ab6fa5](https://github.com/CrystalxSLY/Beydosh-PIM-Updates/commit/7ab6fa5347c60975e807e10cea7f4f4941819317)
- [Signiertes Manifest](0.9.97/manifest.beydosh.json)
- [Veröffentlichungsnachweis und Testgrenzen](../../docs/releases/0.9.97-publication.md)

Diese Angaben sind ein Schnappschuss; der vom Launcher verifizierte Live-Index bleibt maßgeblich. Fehlender Index bedeutet nicht „aktuell“. Netzfehler oder ungültige Signaturen sind kein erfolgreicher Versionsvergleich. Dokumentationsänderungen verändern den signierten Kanal nicht.

## Name und Übergang

Das Repository wurde am 07.10.2026 in `CrystalxSLY/Beydosh-PIM-Updates` umbenannt. App, Launcher und Updatewerkzeug der Nutzerinstallation stehen geprüft auf 0.9.97. Downloads über die bisherige und neue Adresse sowie ein historisches Paket bestanden mit dem installierten Verifier. [Abschlussnachweis](../../docs/releases/2026-10-07-update-channel-rename.md).

Der ausgelieferte Übergangs-Updater verwendet noch die alte Adresse als kompatiblen Alias. Historische signierte URLs und Releasebytes bleiben unverändert. Den früheren Namen nicht für ein neues Repository verwenden. Ältere Installationen ohne Übergang sind nicht pauschal bestätigt.
