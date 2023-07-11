# Kotlin Scraping
## Description
Le challenge, c'est de créer une application Kotlin qui fait du web scraping et qui récupère les
articles de blog sur (https://www.letecode.com/) et les sauvegarder dans un fichier JSON.
Lors de son lancement, l'application affiche un menu à l'utilisateur.
1. Ajouter des articles
2. Afficher les articles
3. Faire Un backup
1. Ajouter des articles
   Contraintes :
   • Les donnes précédemment enregistrées ne doivent pas être perdues
   • L'utilisateur entre les nombres d'articles qu'il veut scraper, si un article est déjà dans le fichier
   JSON, on ne l'ajoute pas, on ajoute que ceux qui n'y figurent pas.
   • À la fin des opérations, on affiche le nombre d'articles ajoutés et le nombre de ceux qui n'ont
   pas été ajoute (notamment les doublons)
2. Afficher les articles
   L'utilisateur affiche les articles qui sont dans le fichier JSON
3. Faire un backup
   Le fichier JSON sera uploadé sur un repo GitHub
   Contraintes :
   • Le nom du fichier doit être "j-m-yyyy-minutes-secondes.json"
   • À la fin du backup, on vide le fichier JSON qui est en local
   Contraintes Générales :
   • Afficher un loader lorsque une opération peut prendre beaucoup des temps
   • Utiliser le Principe SOLID
   • Écrire des tests et avoir un test coverage > à 50