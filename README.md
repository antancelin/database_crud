# CRUD sur base de données MySQL

1. Création d'une base de données : 'CountriesDatas'
2. Ajout de deux tables à cette nouvelle base :
     - 'countries' (code, name)
     - 'populations' (id, LOCATION, TIME , Value)

3. Remplissage des tables 'countries' et 'populations', respectivement à l'aide des fichiers suivants :
     - 'country.txt'
     - 'population.csv'

4. Exécution d'une requête de type 'SELECT' sur la table 'population', en incluant un 'JOIN' sur la table 'countries'. Le but étant d'afficher les éléments 'name' de la table 'countries' au lieu des 'location' de la table 'populations'.

NB: la requête doit retourner une liste de tuple du type :
[(217, 'Canada', datetime.date(1950, 1, 1), 14018600.0), (218, 'Canada', datetime.date(1951, 1, 1), 14318200.0), (219, 'Canada', datetime.date(1952, 1, 1), 14776300.0), (220, 'Canada', datetime.date(1953, 1, 1), 15169800.0), ...]

5. Conversion du résultat de la requête précédente en dataframe.
