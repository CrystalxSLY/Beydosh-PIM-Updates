# Signierter Kanal stable

[Übersicht](../../README.md) · [Veröffentlichungsverfahren](../../docs/PUBLISHING.md)

Dokumentationsstand 06.10.2026: **0.9.95** ist aktiviert. `stable` ist eine technische Kanalkennung, keine öffentliche Produkt- oder Live-Freigabe. Die Veröffentlichung bleibt eine Owner-Development-Vorabversion.

## Aufbau

- [latest.beydosh.json](latest.beydosh.json): signierter, veränderlicher Kanalindex.
- `<version>/manifest.beydosh.json`: unveränderliches signiertes Versionsmanifest.
- GitHub-Release `v<version>`: unveränderliche `00001.bupd` und gegebenenfalls weitere Transportchunks.

Der Index bindet die Manifestbytes per SHA-256. Das Manifest bindet Paket-URLs, Größen, Hashes, Inventar und Kompatibilität. Paketformat: `beydosh-signed-plain-v2`. Pakete und Manifest müssen öffentlich erreichbar und geprüft sein, bevor Latest zuletzt aktiviert wird. Bestehende Versionsinhalte werden nicht ersetzt.

## Aktueller veröffentlichter Stand

- Version: 0.9.95
- Veröffentlichung: 05.10.2026
- MinimumLauncher: 0.9.0
- Plattform: Windows/x64, .NET 9 Desktop Runtime erforderlich
- SourceCommit: `b01f5013421fda7440184d3978eabe7a08c94334`
- Manifest-SHA-256: `4D0D40E4E75785266AA18CE8F9D510D576D7DD55E6200C7DA67A5837F0F3F27C`
- Transportpaket: 26.775.451 Bytes
- Transport-SHA-256: `9BB971D43C43F80D78E37D83AD30AFDE139290CD46B206756353E1F7D6F91FE9`
- Aktivierung: [e8b95ec](https://github.com/CrystalxSLY/beydosh-updates/commit/e8b95ecda66d049e381911940ff46b7eac28c962)
- [Signiertes Manifest](0.9.95/manifest.beydosh.json)
- [Veröffentlichungsnachweis und Testgrenzen](../../docs/releases/0.9.95-publication.md)

Diese Angaben sind ein Schnappschuss; der vom Launcher verifizierte Live-Index bleibt maßgeblich. Fehlender Index bedeutet nicht „aktuell“. Netzfehler oder ungültige Signaturen sind kein erfolgreicher Versionsvergleich. Dokumentationsänderungen verändern den signierten Kanal nicht.

## Name und Übergang

Der gewünschte Repositoryname lautet `Beydosh-PIM-Updates`. Die technische Adresse bleibt bis zum geprüften Übergangsupdate `CrystalxSLY/beydosh-updates`, damit bestehende Installationen nicht durch die Umbenennung ihren Updatezugang verlieren. Historische signierte URLs und Releasebytes werden nicht nachträglich ersetzt.
