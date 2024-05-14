
# Application Android Chat Bot
Pendant ce TP, j'ai développé une application mobile Android en utilisant Android Studio et Java. Cette application est une interface de chatbot interactif permettant d'obtenir des réponses à partir de l'IA BrainShop.
## Supervisé par :
* **Pr Abdelmajid Bousselham**
## Réalise Par : 
* **Oussama ElHachimi** - [osmel1](https://github.com/osmel1)

## 1. Ajout des dépendances nécessaires 


- **Retrofit** pour les appels réseau 
- **Gson** pour la conversion JSON 

## 2. Ajout des permissions internet dans le fichier AndroidManifest.xml

## 3. L'interface utilisateur (UI) 
- Le layout principal de l'application est défini dans un fichier XML nommé ```activity_main.xml```. Ce fichier décrit la structure de l'interface utilisateur en utilisant des balises XML pour chaque élément de l'UI.Dans cette Activity vous pouvez envoyez des questions au ai pour avoir des reponses .

## 4. Utilisation d'application

- Envoyez et recevez des reponses d'une methode instantanement

## 5. Les Modèles de Données
- Modèle représentant un message et la source de message pour faire une difference dans l'interface  . `MessageModel`
- Modèle représentant la réponse de l'API Brain Shop. `BrainShopResponse`

## 6. Interface pour effectuer des appels API vers Brain Shop.
`BrainShopApi`Une interface contenant une méthode pour rechercher des reponses en fonction d'une requête, qui sera utilisée ultérieurement dans l'application principale.

## 7. Adapteur ChatBotAdapter 
Adaptateur pour afficher les messages dans une Reactive list view qui affiche soit en forme d'une propriete dans le message model `sender`
