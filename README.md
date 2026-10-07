# PwnVault — installeurs

Ce dépôt ne contient pas de code : il **distribue les installeurs de PwnVault**
pour Linux, Windows et macOS. Le code source est privé.

PwnVault est un espace de travail local pour le pentest, le CTF et l'OSINT :
notes horodatées, hôtes, services, vulnérabilités, identifiants et flags reliés
entre eux, import des sorties de `nmap`, `ffuf`, `nuclei`, `httpx` ou
`netexec`, et génération du writeup à la fin. Tout reste sur la machine :
aucun compte, aucun serveur, aucune synchronisation, aucune télémétrie.

## Télécharger

**[→ Dernière version](https://github.com/Corneille9/pwnvault-releases/releases/latest)**
· ou depuis [corneille.vercel.app/telechargements](https://corneille.vercel.app/telechargements)

| Système | Fichier |
| --- | --- |
| Debian, Ubuntu | `PwnVault_<version>_amd64.deb` |
| Toute distribution Linux | `PwnVault_<version>_amd64.AppImage` |
| Windows 10 / 11 | `PwnVault_<version>_x64-setup.exe` |
| macOS 11+ (Intel et Apple Silicon) | `PwnVault_<version>_universal.dmg` |

## Installer

```sh
# Debian / Ubuntu
sudo dpkg -i PwnVault_*_amd64.deb

# AppImage : rien à installer, juste à rendre exécutable
chmod +x PwnVault_*.AppImage && ./PwnVault_*.AppImage
```

Sur **Windows**, l'installeur n'est pas signé : SmartScreen affiche un
avertissement, choisissez « Informations complémentaires » puis « Exécuter
quand même ». Sur **macOS**, le binaire n'est pas signé non plus : au premier
lancement, clic droit sur l'application puis « Ouvrir ».

## Publication

Les fichiers sont construits et attachés ici automatiquement par le workflow
`release.yml` du dépôt source, à chaque tag `v*`. Ce dépôt n'est jamais
modifié à la main.

---

Par **Corneille BANKOLE** — [corneille.vercel.app](https://corneille.vercel.app/)
· [GitHub](https://github.com/Corneille9)
