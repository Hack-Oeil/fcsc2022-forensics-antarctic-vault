# FCSC 2022 Antarctic Vault 1/2

La société Antarctic Vault propose à ses clients du stockage au froid pour une meilleure conservation. 
Ce stockage est donc situé au plus profond de la couche de glace de l'antarctique au sein de nœuds à basse consommation.

Dans ces noeuds, une application permet le stockage de secrets et la récupération via une authentification asymétrique 
répondant aux plus hauts standards du marché. La connexion des clients aux coffre-forts se fait à l'aide de bornes Wi-Fi 
avec un niveau de sécurité très élevé.

Cependant, cette société, qui héberge des données très sensibles du FCSC, a pu se rendre compte qu'un acteur malveillant
s'était connecté sur un de ses équipements. Un point d'accès malveillant s'est présenté au nœud et celui-ci s'y est connecté.
Le Centre des Opération de Sécurité a pu réaliser deux captures : une capture réseau de la connexion du point d'accès et une
 capture mémoire du nœud avant les opérations de l'acteur malveillant.

Saurez-vous retrouver le secret qui a été exfiltré ?

Fichiers :
- [out.lime.xz](out.lime.xz)
- [capture1.pcap](capture1.pcap)


Cette épreuve a été découpée en deux parties :
- **Antarctic Vault 1/2**.
- [Antarctic Vault 2/2](README_2_2.md).


Auteurs : pva

Origine : [Antarctic Vault 1/2](https://hackropole.fr/fr/challenges/forensics/fcsc2022-forensics-antarctic-vault-1/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-forensics-antarctic-vault.git

> cd fcsc2022-forensics-antarctic-vault


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2022-forensics-antarctic-vault-1/