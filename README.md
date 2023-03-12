# Créer une application de lancement de dés
Dans ce TP, nous allons créer une application de lancé de dés. L'objectif est de vous permettre de prendre en main les premières notions de Kotlin et Android. 

## Créer une nouvelle application
### Créer un projet "Activité vide"
- Si vous avez déjà ouvert un projet dans Android Studio, accédez à File > New > New Project... (Fichier > Nouveau > Nouveau projet…) pour ouvrir l'écran Create New Project (Créer un projet).
- Dans Create New Project (Créer un projet), créez un projet Kotlin à l'aide du modèle Empty Activity (Activité vide).
- Appelez l'application "Dice Roller", avec un niveau d'API minimal de 19 (KitKat).

![image](https://user-images.githubusercontent.com/3142010/224566329-271369cd-70c3-4313-8f9f-e4e2e3c2e747.png)

Exécutez la nouvelle application. Elle devrait ressembler à ceci.
![image](https://user-images.githubusercontent.com/3142010/224566352-83a5dff2-0d80-4046-b916-18d22a83476d.png)

## Créer la mise en page de l'application

### Ouvrir l'éditeur de mise en page

- Dans la fenêtre Project (Projet), double-cliquez sur activity_main.xml (app > res > layout > activity_main.xml) pour l'ouvrir. Vous devriez voir l'éditeur de mise en page, affichant uniquement le TextView TextView "Hello World" au centre de l'application.
![image](https://user-images.githubusercontent.com/3142010/224566387-ace35fdc-e8a0-4062-b910-f9717250ced6.png)

Vous allez maintenant ajouter un Button à votre application. Un Button est un élément d'interface utilisateur (UI) dans Android sur lequel l'utilisateur peut appuyer pour effectuer une action.

![image](https://user-images.githubusercontent.com/3142010/224566397-7f87417b-38cd-42b3-ae63-5780699355ce.png)

Dans cette tâche, vous allez ajouter un Button sous le TextView "Hello World". TextView et Button seront situés dans un ConstraintLayout, qui est un type de ViewGroup.

Si un ViewGroup comprend des Views, les Views sont considérées comme des enfants issus du parent ViewGroup. Dans le cas de votre application, TextView et Button sont considérés comme des enfants du parent ConstraintLayout.

![image](https://user-images.githubusercontent.com/3142010/224566410-2621b7c6-6941-4d83-b25e-950f73d64199.png)
