# RPC-DISCORD
Gérer un RPC (Rich Presence) sur Discord depuis un site web !

## Comment exécuter ?

***__VOUS DEVEZ AVOIR PYTHON3 INSTALLÉ!__*** https://www.python.org/downloads/

Ensuite, installez les dépendances :
```
pip3 install pypresence
```
and run the script:
```
python3 index.py
```

## Preparation
**Veuillez lire le message rouge avant. Vous devez créer une application sur la page des développeurs Discord :**
https://discord.com/developers/applications/

Et dans "Rich presence", puis dans "Art assets", vous devez télécharger 2 images. Une appelée "big" et une petite (minimum 512x512). (Téléchargez-les une seule fois, Discord ne rafraîchit pas très rapidement, mais une fois téléchargé, vous pouvez exécuter le script)

__Ensuite, allez simplement dans "Informations générales" et copiez l'ID de l'APPLICATION, puis collez-le dans le code lorsqu'on vous le demande__

### Si vous souhaitez exécuter directement sans avoir à taper quoi que ce soit dans le terminal (l'ID de l'application doit être enregistré dans config.json), utilisez quelque chose comme ceci :
```
python3 index.py --no-validation
```
**Pour le start.bat, faites clic droit et modifier en mettant le chemin réel de votre fichier ```Index.py``` et enregistrez, vous aurez plus qu'à double cliquer dessus.**

En cas de besoin contactez moi sur Discord : Firemansing
