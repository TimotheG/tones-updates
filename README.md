# Canal de mise à jour de Tones

Fichiers lus par les appareils Tones (mise à jour par Internet) :

- `manifest.json` : dernière version publiée (version, fichier, taille, SHA-256, notes) ;
- `tones-X.Y.Z.bin` : firmwares utilisateurs, compilés par la CI du projet.

Ne rien modifier à la main : publication avec `tools/publish_release.py` du dépôt du firmware.
