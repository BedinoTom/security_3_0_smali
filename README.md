# Security 3.0 - SMALI

**SMALI** est le language assembleur d'Android. Dans ce TP nous avons dû le manipuler afin de passer des barrières de vérification et d'afficher un mot de passe caché.

## Structure

```
. 
├── app1
│    └── dist 
│           └── out
└── out 
```

Ici :
- **app1/**: contient les classes assembleurs **SMALI** de *app1.apk*
- **out/**: contient les classes décompilées en **Java** de *app1.apk*
- **app1/dist/out/**: contient les classes décompilées en **Java** de *app1.apk*, après avoir été modifié (modification du **SMALI**)

## Outils

Voici les outils que nous avons utilisé:
- **JDAX**: pour la décompilation en JAVA
- **apktool**: pour la décompilation en SMALI