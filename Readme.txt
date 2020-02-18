############################################################ GUIDE D'INSTALLATION ##########################################################################################

Voici les étapes à suivre pour installer ce projet de scrapping du site Légifrance: 

_ Installations nécessaires

	+ .NET Core :

		- Sur l'adresse https://dotnet.microsoft.com/download, téléchargez puis installez .NET Core SDK.
	
	+ Google Chrome :

		- Si vous ne l'avez pas déjà, installez Google Chrome sur le lien suivant : https://www.google.fr/chrome/



_ Pour Télécharger le programme de scrapping :
		

	+ Allez sur https://github.com/JulienRollinat/Scrapping_Legifrance/blob/master/myScrapp.zip, cliquez sur "download",

	+ Une fois le dossier téléchargé, dézippez-le.



_ Pour installez le projet de scrapping :	

	+ Sur Windows :

		- Ouvrir l'expolorateur de fichiers, allez sur le dossier "myScrapp" (sans cliquer dessus, il faut juste que le dossier soit surligné).
		- Dans l'explorateur de fichiers, cliquez sur "acceuil" puis "copier le chemin d'accès"
		- En bas à gauche de l'écran, à côté du menu démarrer, dans la barre de recherche, incrivez "invite de commande" puis cliquez sur l'application "invite de commande",
		- Une fois que celle-ci est ouverte, écrivez "cd" tapez sur la barre espace puis tapez simultanément sur les touches "Ctrl" et "V".
		- Tapez sur la touche "Entrée" puis écrivez "dotnet run".
		- Le programme est lancé !

	+ Sur Mac :

		- Ouvrir le finder, selectionner le dossier "myScrapp" (sans cliquer dessus, il faut juste que le dossier soit surligné) puis cliquer sur l'onglet de roue mécanique en haut à droite du finder enfin selectionner "ouvrir un nouveau terminal". 
		- Si vous êtes perdu, plus d'informations ici (https://yann.me/mac-ouvrir-un-dossier-dans-le-terminal-depuis-finder/),
		- Une fois que le terminal est ouvert écrivez "dotnet run".
		- Le programme est lancé !
		
	+ Pour lancer la génération de graphiques, ouvrir le terminal, se déplacer dans le dossier myScrapp du programme puis lancer la terminal "Python3 to_launch_for_Graphics.py"
		
_ Bug possibles : 

	+ Attention , ce programme ne fonctionne qu'avec la dernière version de chrome (la version 75), si un bug arrive au moment du lancement du programme (après avoir tapé "dotnet run" veuillez vérifier que vous avez la bonne version de chrome en mettant à jour ce dernier). Pour plus d'informations sur les modalités de mise à jour de chrome consultez ce lien : https://fr.wikihow.com/mettre-%C3%A0-jour-Google-Chrome
