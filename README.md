# verre-bleu-apk

APK de l'appli « Verre bleu natif » (Android), lue par l'appli elle-même pour se mettre à jour.

- `version.json` : dernière version publiée (`code`, `version`, `apk`, `sha256`, `details`).
- `CHANGEMENTS.md` : historique des versions.
- Aucune adresse ni aucun jeton dans l'APK ou dans ce dépôt.

Sécurité : l'appli n'installe qu'un fichier venant de ce dépôt, dont l'empreinte SHA-256 correspond à `version.json` ; Android n'accepte la mise à jour que si elle est signée par la même clé que l'appli installée (clé qui n'est pas dans ce dépôt).
