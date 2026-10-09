# PwnVault

Espace de travail local pour le pentest, le CTF et l'OSINT, disponible sur
Linux, Windows et macOS.

Un engagement entier tient au même endroit : notes horodatées, hôtes, services,
vulnérabilités, identifiants et flags sont reliés entre eux. Les sorties de
`nmap`, `ffuf`, `nuclei`, `httpx` et `netexec` s'importent directement, et le
rapport se rédige à partir de ce qui a déjà été collecté.

Tout reste sur votre machine : aucun compte, aucun serveur, aucune télémétrie.

## Télécharger

[**→ Dernière version**](https://github.com/Corneille9/pwnvault-releases/releases/latest)
· ou depuis [corneille.vercel.app/telechargements](https://corneille.vercel.app/telechargements)

| Système | Fichier |
| --- | --- |
| Debian, Ubuntu | `PwnVault_<version>_amd64.deb` |
| Autres distributions Linux | `PwnVault_<version>_amd64.AppImage` |
| Windows 10 et 11 | `PwnVault_<version>_x64-setup.exe` |
| macOS 11 et plus (Intel et Apple Silicon) | `PwnVault_<version>_universal.dmg` |

## Installer

**Debian, Ubuntu**

```sh
sudo dpkg -i PwnVault_*_amd64.deb
```

**Autres distributions Linux**

```sh
chmod +x PwnVault_*.AppImage
./PwnVault_*.AppImage
```

**Windows** — lancez l'installeur. Si un avertissement SmartScreen s'affiche,
choisissez « Informations complémentaires » puis « Exécuter quand même ».

**macOS** — ouvrez le `.dmg` et glissez PwnVault dans Applications. Au premier
lancement, faites un clic droit sur l'application puis « Ouvrir ».

## Configuration requise

- Linux : distribution récente avec WebKitGTK 4.1 (Ubuntu 22.04+, Fedora 38+)
- Windows 10 ou 11, 64 bits
- macOS 11 Big Sur ou plus récent, Intel ou Apple Silicon

---

Par **Corneille BANKOLE** — [corneille.vercel.app](https://corneille.vercel.app/)
· [GitHub](https://github.com/Corneille9)
