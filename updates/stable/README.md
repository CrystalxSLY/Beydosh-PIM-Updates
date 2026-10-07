# Signierter Kanal stable

[Übersicht](../../README.md) · [Veröffentlichungsverfahren](../../docs/PUBLISHING.md)

Dokumentationsstand 07.10.2026: **0.9.96** ist aktiviert. `stable` ist eine technische Kanalkennung, keine öffentliche Produkt- oder Live-Freigabe. Die Veröffentlichung bleibt eine Owner-Development-Vorabversion.

## Aufbau

- [latest.beydosh.json](latest.beydosh.json): signierter, veränderlicher Kanalindex.
- `<version>/manifest.beydosh.json`: unveränderliches signiertes Versionsmanifest.
- GitHub-Release `v<version>`: unveränderliche `00001.bupd` und gegebenenfalls weitere Transportchunks.

Der Index bindet die Manifestbytes per SHA-256. Das Manifest bindet Paket-URLs, Größen, Hashes, Inventar und Kompatibilität. Paketformat: `beydosh-signed-plain-v2`. Pakete und Manifest müssen öffentlich erreichbar und geprüft sein, bevor Latest zuletzt aktiviert wird. Bestehende Versionsinhalte werden nicht ersetzt.

## Aktueller veröffentlichter Stand

- Version: 0.9.96
- Veröffentlichung: 07.10.2026
- MinimumLauncher: 0.9.0
- Plattform: Windows/x64, .NET 9 Desktop Runtime erforderlich
- SourceCommit: `777944e4f576d7f555869db70d9d6db337d97bfa`
- Manifest-SHA-256: `807A66488C7D87F28E9E5ECA81193FFE3FDBEB5B0913959DCA4B5C4893FF5AE2`
- Transportpaket: 26.780.059 Bytes
- Transport-SHA-256: `EF8287D83BB4E32E5F98FB7215F5B7E1675A4A758346DE7BF556ED702A2E782C`
- Aktivierung: [7da91da](https://github.com/CrystalxSLY/beydosh-updates/commit/7da91da427d42b8a135c2d9adb89798a1efa97e0)
- [Signiertes Manifest](0.9.96/manifest.beydosh.json)
- [Veröffentlichungsnachweis und Testgrenzen](../../docs/releases/0.9.96-publication.md)

Diese Angaben sind ein Schnappschuss; der vom Launcher verifizierte Live-Index bleibt maßgeblich. Fehlender Index bedeutet nicht „aktuell“. Netzfehler oder ungültige Signaturen sind kein erfolgreicher Versionsvergleich. Dokumentationsänderungen verändern den signierten Kanal nicht.

## Name und Übergang

Der gewünschte Repositoryname lautet `Beydosh-PIM-Updates`. Die technische Adresse bleibt bis zum geprüften Übergangsupdate `CrystalxSLY/beydosh-updates`, damit bestehende Installationen nicht durch die Umbenennung ihren Updatezugang verlieren. Historische signierte URLs und Releasebytes werden nicht nachträglich ersetzt.

Das Übergangsupdate 0.9.96 ist veröffentlicht und aktiviert. Die reale Nutzerinstallation und die anschließende Repositoryumbenennung sind getrennte, noch offene Schritte. [Übergangsnachweis](../../docs/releases/0.9.96-publication.md).
