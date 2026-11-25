# Passman pour Windows / Passman for Windows

Installateurs de [Passman](https://passman.ridatic.com), le gestionnaire de mots de passe de Ridatic. Ce dépôt ne contient pas le code source.

## Télécharger

Prenez le fichier `passman-setup-x.y.z-n.exe` de la [dernière version](../../releases/latest). Windows 10 ou 11, 64 bits.

L'installateur n'est pas signé : Windows peut afficher « Windows a protégé votre ordinateur ». Cliquez sur « Informations complémentaires », puis « Exécuter quand même ».

Pour vérifier le fichier, comparez son empreinte avec celle publiée dans le fichier `.sha256` :

```powershell
Get-FileHash .\passman-setup-x.y.z-n.exe -Algorithm SHA256
```

Installer une nouvelle version par-dessus l'ancienne conserve votre coffre. La désinstallation ne l'efface pas.

---

## Download

Get `passman-setup-x.y.z-n.exe` from the [latest release](../../releases/latest). Windows 10 or 11, 64-bit.

The installer is not signed: Windows may show "Windows protected your PC". Click "More info", then "Run anyway".

To check the file, compare its hash with the one in the `.sha256` file (command above). Installing a newer version over an older one keeps your vault. Uninstalling does not erase it.

[Conditions / Terms](https://ridatic.com/passman/conditions) - [Confidentialité / Privacy](https://ridatic.com/passman/confidentialite)
