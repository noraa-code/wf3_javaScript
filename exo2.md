# Exercices, partie 2 :
***Les exercicess peuvent se faire par groupe de deux personnes (max). Vous pouvez faire des recerches sur Internet pour (re)trouver les informations fournies en classe, voire de vous documenter sur les supports étudiés en cours. Il faudra, à chaque exercice, __mettre à jouer son dépôt Git__ afin que le formateur puisse surveiller votre avancement.***

*Les réponses à ces __dix premiers__ exercices seront fournies et étudiées en formation demain matin :* __

1. Écrivez un programme JavaScript qui affiche "Bonjour, monde !" dans la console.

    console.log("Bonjour, monde!")

2. Créez une fonction qui prend deux nombres en entrée et les additionne. Appelez cette fonction et affichez le résultat dans la console.

    function nombre(nb1, nb2){
        return nb1 + nb2;
    }
    nombre(1,2);

3. Écrivez un programme JavaScript qui vérifie si un nombre est pair ou impair et affiche le résultat dans la console.

    function nombre(pair){
        return pair % 2 === 0;
    }
    pair(5);

4. Créez un tableau contenant trois noms, puis bouclez sur le tableau pour afficher chaque nom dans la console.

        let fruit =["pomme","banane", "orange"];
        let i = 0;
        while (i <3){
            console.log(fruit[i]);
            i++ ;
        }

5. Écrivez un programme JavaScript qui demande à l'utilisateur son prénom, puis affiche "Bonjour, [prénom] !" dans une boîte de dialogue.

    function hello(){
        let prenom = prompt("Quel est votre prénom");
        alert("Bonjour " + prenom + "!");
    }
        hello();

6. Créez une fonction qui calcule l'aire d'un rectangle en prenant sa largeur et sa hauteur en entrée. Affichez le résultat dans la console.

7. Écrivez un programme JavaScript qui génère un nombre aléatoire entre 1 et 10, puis demande à l'utilisateur de deviner ce nombre. Donnez des indices pour aider l'utilisateur à deviner.

8. Créez une fonction qui prend une chaîne de caractères en entrée et retourne sa longueur. Affichez la longueur d'une chaîne donnée dans la console.

9. Écrivez un programme JavaScript qui calcule la somme des nombres de 1 à 100 et affiche le résultat dans la console.

10. Créez un tableau de nombres, puis utilisez une boucle pour trouver le plus grand nombre dans le tableau. Affichez ce nombre dans la console.

---


1. Créez une fonction qui prend un tableau de nombres en entrée et renvoie la somme de tous les nombres pairs du tableau.

2. Écrivez un programme JavaScript qui vérifie si une chaîne de caractères est un palindrome (elle se lit de la même manière de gauche à droite et de droite à gauche).

3. Créez un objet représentant un livre avec des propriétés comme le titre, l'auteur et l'année de publication. Écrivez une fonction qui affiche ces propriétés dans la console.

4. Écrivez un programme JavaScript qui utilise la récursivité pour calculer le factoriel d'un nombre donné.

5. Créez une fonction qui prend une chaîne de caractères en entrée et renvoie cette chaîne inversée (par exemple, "Hello" devrait devenir "olleH").

6. Écrivez un programme JavaScript qui trie un tableau de nombres dans l'ordre croissant en utilisant l'algorithme de tri à bulles.

7. Créez un objet représentant un compte bancaire avec des propriétés pour le solde et un numéro de compte. Écrivez des méthodes pour effectuer des dépôts et des retraits, et affichez le solde dans la console.

8. Écrivez un programme JavaScript qui génère un nombre aléatoire entre 1 et 1000, puis demande à l'utilisateur de deviner ce nombre en utilisant une boucle. Donnez des indications pour guider l'utilisateur.

9. Créez une fonction qui prend un tableau de nombres en entrée et renvoie un nouveau tableau contenant les nombres uniques (supprimez les doublons).

10. Écrivez un programme JavaScript qui crée une calculatrice simple avec des fonctions pour l'addition, la soustraction, la multiplication et la division. Demandez à l'utilisateur de saisir deux nombres et une opération, puis affichez le résultat dans la console.