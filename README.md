# Sproke — Update-Feed

Automatische Updates für die [Sproke](https://sproke.vercel.app)-Diktat-App (Sparkle).

- `appcast.xml` — der Update-Feed, den die App abfragt
- `Sproke-X.Y.Z.dmg` — notarisierte Release-Images

Jede Version ist EdDSA-signiert; die App installiert nur Updates mit gültiger Signatur.
