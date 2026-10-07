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
- Aktivierung: [7ab6fa5](https://github.com/CrystalxSLY/beydosh-updates/commit/7ab6fa5347c60975e807e10cea7f4f4941819317)
- [Signiertes Manifest](0.9.97/manifest.beydosh.json)
- [Veröffentlichungsnachweis und Testgrenzen](../../docs/releases/0.9.97-publication.md)

Diese Angaben sind ein Schnappschuss; der vom Launcher verifizierte Live-Index bleibt maßgeblich. Fehlender Index bedeutet nicht „aktuell“. Netzfehler oder ungültige Signaturen sind kein erfolgreicher Versionsvergleich. Dokumentationsänderungen verändern den signierten Kanal nicht.

## Name und Übergang

Der gewünschte Repositoryname lautet `Beydosh-PIM-Updates`. Die technische Adresse bleibt bis zum geprüften Übergangsupdate `CrystalxSLY/beydosh-updates`, damit bestehende Installationen nicht durch die Umbenennung ihren Updatezugang verlieren. Historische signierte URLs und Releasebytes werden nicht nachträglich ersetzt.

Das Übergangsupdate 0.9.97 ist veröffentlicht und aktiviert. Die reale Nutzerinstallation und die anschließende Repositoryumbenennung sind getrennte, noch offene Schritte. [Übergangsnachweis](../../docs/releases/0.9.97-publication.md).
