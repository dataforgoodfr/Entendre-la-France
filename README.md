# Entendre-la-France

Repo public du projet Entendre la France, contenant les données en csv et une base de code compilée dans un notebook.

Pour vous lancer, faites un pull du projet et installez les modules du fichier requirements. Il vous faudra installer Anaconda pour éxécuter les notebooks. Vous pouvez le télécharger ici https://www.anaconda.com/distribution/.

Toute participation au projet est la bienvenue !

# Présentation du dataset

### Table Users

|Colonne         |Exemple                        |Type                      |
|----------------|-------------------------------|-----------------------------|
|user_id	       |17960	|integer
|code_postal	|32000	|string
|commune	|AUCH (32)	|string
|type_commune	|Urbain	|string
|nom_departement	|Gers (32)	|string
|departement	|32	|string
|sexe	|Homme	|string
|age	|55-64 ans	|string
|formation	|?	|string
|profession	|Employé	|string
|taille_org	|Plus de 5000	|string
|position_gj	|Soutient	|string

### Table Answers Free

|Colonne         |Exemple                        |Type                      |
|----------------|-------------------------------|-----------------------------|
|customer_id	|17465	|integer
|question_id	|DC1	|string
|answer	|Rendre la politique intéressante	|string

### Table Answers QCM

|Colonne         |Exemple                        |Type                      |
|----------------|-------------------------------|-----------------------------|
|customer_id	|17469	|integer
|question_id	|FI1	|string
|answer	|1️⃣	|string

### Table Matching Questions 

|Colonne         |Exemple                        |Type                      |
|----------------|-------------------------------|-----------------------------|
|question_id	|TE11	|integer
|type	|Libre	|string
|theme	|Transition écologique	|string
|title	|🌎Q11 - Que faites-vous aujourd’hui pour protéger l’environnement et/ou que pourriez-vous faire ?	|string

### Table Matching Answers QCM

|Colonne         |Exemple                        |Type                      |
|----------------|-------------------------------|-----------------------------|
|question_id	|TE1	|integer
|answer_id	|1️⃣	|string
|answer_title	|La pollution de l'air	string
