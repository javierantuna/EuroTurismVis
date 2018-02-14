Au debut, on obtient les données du site <a href="https://data.worldbank.org/">World Bank</a> en format Excel.

Après il faut effacer les colonnes des données qu'on ne va pas utiliser pour le projet.

L'étape suivante est de faire la suppression des pays qui n'appartiennent pas au territoire européen et ceux qui ne possèdent pas les données suffisantes.

Ensuite, on construit un fichier CSV à partir du fichier Excel et on substitue les symboles ';' par des virgules ',' afin que l'algorithme implementé en D3 soit capable de bien lire les données.

On a dû aussi travailler dans le fichier qui contient les interactions. Dans ce fichier la première action a été vérifier les données. On a constaté que les données contenues dans ce fichier ne montraient pas les données qu’on avait avant du nombre de sorties et arrivées de chaque et à chaque pays. Pour cette raison on a dû modifier les données pour obtenir des résultats logiques qui peuvent être représentés. Tout ce processus a été fait à la main.

Une fois les données vérifiés et complètes on a fait quelques calcules sur les feuilles Excel. On a, par exemple, calculé le % qui représente chaque pays dans les arrivées et sorties de chaque pays. Après on a dû transformer le fichier en csv pour pouvoir le lire, en modifiant les « , » par « . », et les « ; » par « , ».

