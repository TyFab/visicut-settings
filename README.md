Visicut settings
================

Fichiers de configuration pour [VisiCut](https://github.com/t-oster/VisiCut) utilisé pour les machines du TyFab.

Instructions
------------

 * Effacer la configuration actuelle avant de copier ce dépôt :
    
    ```bash
    rm -rf ~/.visicut-old/
    mv ~/.visicut/ ~/.visicut-old/
    ```

 * Récupérer ce dépôt dans ~/.visicut :
    
    ```bash
    git clone https://github.com/TyFab/visicut-settings.git ~/.visicut
    ```


 * Mise à jour :

    ```bash
    cd ~/.visicut
    git pull
    ```

 * Avant de partager vos modifications, vérifier que les paramètres fonctionnent parfaitement, et faire :
    `git diff`
  et
    `git status`

 *  Ensuite, envoyer vos modifications :
    
    ```bash
    git add -A
    git commit -A
    ```
