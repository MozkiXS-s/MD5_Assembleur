# MD5 Assembleur

Ce projet implémente un algorithme de hachage MD5 en assembleur. Le code est conçu pour fonctionner sur des systèmes Linux x86_64.

## Description

L'algorithme de hachage MD5 prend en entrée un message de longueur variable et produit une empreinte de 128 bits (16 octets). Ce projet propose une implémentation de l'algorithme en assembleur, avec quelques modifications spécifiques.

## Structure du projet

- `md5.asm` : Fichier principal contenant le code source en assembleur.

## Utilisation

### Compilation

Pour compiler le code, utilisez `nasm` et `ld` :
```sh
nasm -f elf64 md5.asm -o md5.o
ld md5.o -o md5
