# Créer une application de lancé de dés
Dans ce TP, vous allez réaliser une application de lancé de dés à partir de Google Codelabs. Dans un second temps, vous allez enrichir l'application pour rendre le jeu plus interessant. Et finalement, vous allez expérimenter la navigation entre plusieurs écrans dans une application Android. 

# Etape 1
Suivre les instructions étapes par étapes via ce lien [https://developer.android.com/codelabs/basic-android-kotlin-training-create-dice-roller-app-with-button](https://developer.android.com/codelabs/basic-android-kotlin-training-create-dice-roller-app-with-button?hl=fr#0)


# Etape 2 Transformer l'application en Casino :) 
Maintenant, vous allez modifier l'application pour la rendre un peu plus cool, en la transformant en une table de Casino. 

1. Modifiez l'interface de l'application pour ajouter un deuxième dé. 
2. Quand l'utilisateur clique sur le bouton, faitez tourner les 2 dés en même temps. 
3. Si les 2 dés affichent le même numéro, l'utilisateur gagne. Affichez un message de félicitations. 

# Etape 2 Faites vos jeux 
Nous allons encore rendre l'application plus interessant en permettant à l'utilisateur de définir un nombre à trouver en lancant les dés. Ainsi, lorsque les dés sont lancés si la somme est égale à la valeur choisie, l'utilisateur gagne sinon il perd. 

1. Ajoutez une entrée permettant à l'utilisateur de définir le nombre à trouver, vous pouvez utiliser un champ de text, un radiogroup, un spinner, un slider ou n'importe quelle widget qui permet de définir une entrée. 
2. Une fois, le nombre choisi activer le bouton de lancé de dés (ie. le bouton est désactivé tant qu'on n'a pas spécifié un nombre)
3. L'utilisateur gagne si la somme des dés est égale au nombre choisi. 

# Etape 3 
1. Lancez automatiquement les dés quand l'utilisateur défini un nombre (i.e. le bouton n'est plus utilisé)
2. Quand l'utilisateur gagne une partie : animer les dés (bouger de bas en haut ou de droite à gauche, afficher des paillettes, ...).

# Erape 4 
Ajoutez une nouvelle activité (HomeActvity) et définissez-la comme activité par défaut. 
Dans le layout de la nouvelle activité, ajoutez 4 boutons centrés verticalement dans l'écran. 
Nommez les boutons "Jouer", "SOS", "Itinéraires" et "Aide".
Associez à chaque bouton les actions permettant de rediriger l'utilisateur vers l'écran correspondant : 
1. "Jouer" redirige l'utilisateur vers l'écran developpé dans les étapes précédantes.
2. "SOS" lance un appel aux urgences.
3. "Itinéraires" démarre un itinéraire d'un point A (eg. l'école) vers un point B (eg. l'aéroport)
4. "Aide" redirige l'utilisateur vers le site de l'école.
   

# Contrainte 
- Le travail est individuel
- Veuillez à effectuer votre dernier commit avant la deadline
