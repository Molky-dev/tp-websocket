# Exercice pratique : Application de Chat avec Pseudo

## Partie 1 : Configuration de base

1. Créez un nouveau dossier pour votre projet.

2. Initialisez votre projet avec npm en exécutant `npm init -y`.

3. Installez les dépendances nécessaires (Express et Socket.io) en utilisant la commande :
   ```bash
   npm install express socket.io
   ```
   

## Partie 2 : Configuration du serveur

4. Créez un fichier `app.js` et configurez un serveur Express avec Socket.io.

5. Configurez Express pour servir des fichiers statiques à partir d'un dossier `public`.

## Partie 3 : Interface utilisateur

6. Créez un fichier HTML (`index.html`) avec les éléments nécessaires pour le chat (formulaire, liste des messages, etc.).

7. Ajoutez un champ pour que l'utilisateur puisse saisir son pseudo lorsqu'il rejoint le chat.

8. Ajoutez un champ pour que l'utilisateur puisse saisir les messages à envoyer.

9. Incluez le fichier CSS dans votre fichier HTML pour styliser l'interface.

## Partie 4 : Gestion du Chat

10. Dans `app.js`, ajoutez la logique pour gérer les connexions Socket.io.

11. Ajoutez la gestion du pseudo lorsque l'utilisateur rejoint le chat.

12. Implémentez la gestion des messages du chat (envoi et réception).

13. Ajoutez la gestion de la déconnexion des utilisateurs.

## Partie 5 : Test et Exécution

14. Exécutez votre serveur en utilisant
    ```bash
    node app.js
    ```

15. Ouvrez votre navigateur et accédez à l'application de chat.

16. Testez la fonctionnalité en choisissant des pseudos différents et en envoyant des messages.

## Bonus (Optionnel) :

17. Ajoutez des fonctionnalités supplémentaires comme la gestion d'émoticônes, des notifications, ou tout autre élément qui pourrait améliorer l'expérience utilisateur.

18. Mettez en œuvre la persistence des messages ou d'autres fonctionnalités avancées.

- Documentation Socket.io : [Socket.io](https://socket.io/docs/v4/tutorial/introduction/)
- Documentation Express : [Express.js](https://expressjs.com/)
