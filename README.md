# FCSC 2024 Horreur, malheur 1/5 - Archive chiffrée

Vous venez d’être embauché en tant que Responsable de la Sécurité des Systèmes d’Information (RSSI) d’une entreprise stratégique.

En arrivant à votre bureau le premier jour, vous vous rendez compte que votre prédécesseur vous a laissé une clé USB avec une note dessus : ```VPN compromis (intégrité). Version 22.3R1 b1647```.

Sur la clé USB, vous trouvez deux fichiers : une archive chiffrée et les journaux de l’équipement. Vous commencez par lister le contenu de l’archive, dont vous ne connaissez pas le mot de passe. Vous gardez en tête un article que vous avez lu : il paraît que les paquets installés sur l’équipement ne sont pas à jour…

Le flag est le mot de passe de l’archive.

**Remarque :** Le mot de passe est long et aléatoire, inutile de chercher à le bruteforcer.

Cette épreuve a été découpée en cinq parties :

- **Horreur, malheur 1/5 - Archive chiffrée**.
- Horreur, malheur 2/5 - Accès initial.
- Horreur, malheur 3/5 - Simple persistance.
- Horreur, malheur 4/5 - Pas si simple persistance.
- Horreur, malheur 5/5 - Un peu de CTI.

Auteur : \E

Origine : [Horreur, malheur 1/5 - Archive chiffrée](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-1/)


Fichiers :
- [archive.encrypted](archive.encrypted)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-horreur-malheur-1.git

> cd fcsc2024-forensics-horreur-malheur-1


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-1/