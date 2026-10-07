# Umbenennung des Updatekanals

Am 7. Oktober 2026 wurde das bestehende öffentliche Repository in
[CrystalxSLY/Beydosh-PIM-Updates](https://github.com/CrystalxSLY/Beydosh-PIM-Updates)
umbenannt. Repository-ID 1358476739, Inhalt, Releases und Vertrauensmodell bleiben
identisch. Der aktive signierte Kanalstand ist 0.9.97.

## Installierter Übergang

Die Nutzerinstallation wurde vor der Umbenennung gelesen: aktive App 0.9.97,
Launcher und Updatewerkzeug 0.9.97. Launcher EXE, Launcher DLL und Launcher Core
stimmen bytegenau mit dem geprüften Build überein; Updatewerkzeug DLL und Setup
Core stimmen mit dem eingebetteten Stable-Tool überein. Das Maintenance-Tool ist
ein anderer Build als das installierte Stable-Tool und kein passender Hashvergleich.
Der Wartungsstatus nennt ebenfalls Launcher und aktive App 0.9.97.

Der gemeinsame Updater enthält die exakte Namenswechselprüfung. Die ausgelieferte
0.9.97-Konfiguration verwendet weiterhin den bisherigen Namen beydosh-updates als
Übergangsadresse. Das ist kein zweites Repository und keine zweite Schreibquelle.
Aktuelle Dokumentations- und Veröffentlichungsziele verwenden Beydosh-PIM-Updates.
Historische signierte Manifeste und Paket-URLs werden nicht umgeschrieben.

## Tatsächliche Abrufprüfung

Mit der tatsächlich installierten Launcher-Core-DLL wurden vor und nach der
Umbenennung Latest, Manifest und vollständiges Updatepaket über die alte Adresse
geladen. Die P-256-Signaturen, die Latest-Manifest-Bindung und der Paket-SHA-256
wurden erfolgreich geprüft. Dabei wurde kein Update installiert oder aktiviert.

Nach der Umbenennung wurden zusätzlich die neue direkte Metadatenadresse und die
neue direkte Paketadresse sowie das historische 0.9.95-Manifest und dessen Paket
mit dem installierten Verifier und Transport geprüft. Alle Abrufe bestanden;
Signaturen und Bytes blieben unverändert.

- Latest-Blob: 5e018c9fc2cca1025431afae7d3f46ea128efc23
- 0.9.97 Manifest SHA256: 7AF601014AEA4C6D58E630A929429AE8906330E44C5A32B5FC462A7E6D722C1B
- 0.9.97 Paket SHA256: 1E015C378C2F4DBCEEE78FD87DFC47F9CD3FCD2DC2D7FB619DC60339A2A71C46
- 0.9.95 Manifest SHA256: 4D0D40E4E75785266AA18CE8F9D510D576D7DD55E6200C7DA67A5837F0F3F27C
- 0.9.95 Paket SHA256: 9BB971D43C43F80D78E37D83AD30AFDE139290CD46B206756353E1F7D6F91FE9

## Dauerhafte Grenzen

Den früheren Repositorynamen nicht für ein neues Repository verwenden: Dadurch
würden die GitHub-Weiterleitungen entfallen. Siehe
[GitHub zur Repositoryumbenennung](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository).
Der tatsächliche Kompatibilitätsnachweis gilt für die geprüfte 0.9.97-Installation;
ältere Installationen ohne Übergang werden dadurch nicht pauschal bestätigt.

Die Umbenennung ersetzt weder die Versionsprüfung noch Signaturen, Hashes,
Inventarprüfung, Replay-Schutz oder den genehmigten Updatepfad. Für eine spätere
primäre Umstellung des ausgelieferten Konfigurationsnamens muss die Kompatibilität
mit den historischen signierten URLs erhalten und erneut getestet werden.

Keine Veröffentlichung einer neuen App-Version durch diese Dokumentationspflege,
keine Änderung von Latest oder historischen Releasebytes, kein Source-main-Merge,
keine eBay-Anmeldung, keine Bestellungen und keine Live-Verkaufsfreigabe.
