# FCSC 2022 Antarctic Vault 2/2

Suite à l’intrusion repérée précédemment, la société Antarctic Vault a lancé une procédure de nettoyage des traces de l’attaquant.

Nous soupçonnons que cela n’ait pas été suffisant et que l’attaquant se soit énervé. En effet, nous avons perdu l’accès au nœud. Malheureusement, nous n’avons aucune équipe sur place (contrairement à l’attaquant) et le prochain bateau mettra 2 mois avant d’arriver à bon port. Nous avons absolument besoin de reprendre la main sur ce coffre-fort.

Lors de l’attaque précédente, nous avions réalisé un archivage du système de fichiers expurgé des données sensibles (logs, secrets, etc.). De plus, en regardant les traces réseau données par notre point d’accès Wi-Fi, nous avons remarqué des trames inhabituelles. Nous pensons que l’image mémoire de la première partie, l’extrait du système de fichiers ainsi que cette capture vous permettront de nous redonner le contrôle sur notre équipement et ce sans avoir à se déplacer.

On compte sur vous !

Notes :

Un généreux bienfaiteur anonyme vous fait don d’un profil pour Volatility2. Le patch appliqué au générateur de profil est fourni avec. Il a été adapté pour correspondre à la version de Linux en usage.
Volatility2 n’étant pas adapté aux noyaux Linux les plus récents, des modifications sur celui-ci seront à appliquer.


Fichiers :
- [out.lime.xz](out.lime.xz)
- [capture2.pcap](capture2.pcap)
- [out.tar.xz](https://hackropole.fr/filer/fcsc2022-forensics-antarctic-vault/public_filer/out.tar.xz)
- [RPiOSFCSC2022.zip](RPiOSFCSC2022.zip)
- [volatility2.patch](volatility2.patch)



Cette épreuve a été découpée en deux parties :
- [Antarctic Vault 1/2](README_1_2.md).
- **Antarctic Vault 2/2**.


Auteurs : pva

Origine : [Antarctic Vault 2/2](https://hackropole.fr/fr/challenges/forensics/fcsc2022-forensics-antarctic-vault-2/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-forensics-antarctic-vault.git

> cd fcsc2022-forensics-antarctic-vault


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2022-forensics-antarctic-vault-2/