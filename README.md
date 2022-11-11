#TO-DO APP 
Ceci est une application qui cree et affiche une liste de tâches en fonction de l'utilisateur. 
L'utilisateur s'inscrit dans la base de donnée une premiere fois, et peut à la suite se connecter avec n'importe quel pc pour avoir accès à sa liste de tâches.

# Bloc notes en ligne (avec python-flask)

`Bloc notes en ligne (avec python-flask)` est un carnet de note en ligne, avec les fonctions suivantes :

- Permettre aux utilisateurs de s'inscrire, se connecter/deconnecter
- Voir, Créer, Supprimer des notes

## Comment le lancer

Il y'a 2 manières. Premieremenet avec [`python`](https://www.python.org/downloads/) en ligne de commande:

    python main.py

La seconde manière avec flask avec pip (pip install Flask)

```sh
$ export FLASK_APP=main.py
$ flask run
```

Ouvrez http://127.0.0.1:5000/, personnalisez les fichiers du projet et **Amusez vous!**.

Si vous avez des idées pour améliorez le projet, [Forkez-le](https://github.com/Dia770/Bloc-notes-en-ligne/fork) et envoyez moi un pull request.

## Prérequis

- Installez [`python`](https://www.python.org/downloads/) (NB: ce projet fut réalisé avec la version 3.9.5)
- Rendez-vous dans le dossier du projet avec votre terminal et tapez :

```sh
$ pip install -r requirements.txt
```
