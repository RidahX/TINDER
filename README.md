Projet Tinder
On va créer un mini-projet s'inspirant de Tinder. Pour cela on va avoir 2 parties dans notre projet : la partie Backend et la partie Frontend.

BACKEND
La partie Backend sert à créer les profiles et à les rendre disponible au Frontend. Pour effectuer cela on utilise Flask qui va générer une route pour stocker les données au format JSON. Le Backend contient 3 éléments.

Le premier élément est l'environnement virtuel de notre projet il contiendra tous les packages qu'on va installer. Il existe différents systèmes d'exploitation pour installer l'environnement. Ecrivez sur le terminal les commandes pour l'installer. Si vous avez bien créé l'environnement vous aurez un dossier qui sera nommé comme le nom de votre environnement qui sera présent dans la partie Backend.

Le 2e élément est un fichier texte contenant tous les pip install qu'on effectuera. Au lieu de les faire chacune manuellement il suffit de faire pip install -r requirements.txt

Le dernier est un fichier python appelé app.py. C'est le fichier qui contient le serveur Flask et les informations qu'on aura récupéré. Il est essentiel de pouvoir lancer le serveur Flask dans le terminal de commandes en écrivant la commande ci-dessous : "flask run". Vous pouvez sinon écrire la commande "app.py" si cela ne marche pas. Attention il est essentiel quand on utilise le serveur Flask d'être dirigé dans le dossier API contenant tous les fichiers sur cette partie. Sinon vous ne pourrez pas lancer le serveur.

FRONTEND
La partie Frontend va quant à elle récupérer les données mise à disposition par le Backend par un appel de sa route et afficher celles qu'il aura sélectionné pour répondre à la problématique et le cahier des charges fixés pour le projet. On retrouve 2 fichiers essentiels à notre projet :

App.js qui permet l'affichage des données sur la page web App.css qui permet de rendre un meilleur affichage pour notre page web.

Pour créer la partie la partie Frontend il faudra utiliser React. Pour cela dirigez vous sur votre terminal et ensuite dans le dossier contenant tout le projet et ensuite exécutez la commande "npx create-react-app app". Celle-ci va créer le dossier de la partie Frontend. Après avoir fait cela dirigez vous dans le dossier Frontend et crééz les 2 fichiers vous pouvez executez les commandes : "npm install axios" et "npm install react-swipeable".

Vous avez fait toutes les configurations nécessaires pour le fonctionnement du projet maintenant lancez React avec la commande "npm run start".

Ci-dessous les exigences fixées pour le projet :

Cahier des charges
Frontend (React) — Create a React application implementing the Tinder swiping screen — Display user profiles with the ability to swipe left (dislike) or right (like). — Choose existing React components to implement the UI faster — Use CSS for styling the app

Backend (Flask) — Develop a Flask web service to manage user profiles. — Implement a backend endpoint to retrieve n number of profile by API call. — No algorithm needs to be implemented. You can use any public API to retrieve users with their photos and profile information — No database is required for this project — No authentication needed for this web service# TINDER
