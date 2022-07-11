Supervisuer : Coach Malik Ba

pour la digitalisation de son système de gestion des statistiques des joueurs, La FTF a lancé un appel d'offre pour la conception d'une solution répondant aux critères de performance suivants :

L'API passe les tests GET, POST, PUT et DELETE sur PostMan 

et le Site déployé sur Heroku

CRITERES DE PERFORMANCES:
 * L'API passe les tests suivants sur PostMan : GET :

	- Si l'entrée est trouvée, l'API retourne les statistiques en format en format JSON.
		Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
		POST:

	- La nouvelle entrée est bien créée
		L'API affiche le status code 201 après réussite de l'opération.
		PUT:

	- Si la mise à jour est réussie, l'API affiche le status code 200.
		Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
		DELETE:

	- L'entrée ciblée est bien supprimée
		Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
		Le back-end reste fonctionnel.


	Technologies utilisées pour construire l'API :
		- NodeJSName
		- Express.js - Framework Web rapide, sans opinion et minimaliste pour Node.js

	Packages installés
		- nvm
		- npm
		- Node.js
	Express installé avec npm (npm install express body-parser morgan).






