Au debut, on obtient les données du site <a href="https://data.worldbank.org/">World Bank</a> en format Excel.

Après il faut effacer les colonnes des données qu'on ne va pas utiliser pour le projet.

L'étape suivante est de faire la suppression des pays qui n'appartiennent pas au territoire européen et ceux qui ne possèdent pas les données suffisantes.

Ensuite, on construit un fichier CSV à partir du fichier Excel et on substitue les symboles ';' par des virgules ',' afin que l'algorithme implementé en D3 soit capable de bien lire les données.
