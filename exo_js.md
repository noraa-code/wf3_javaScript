Voici dix exercices de programmation JavaScript, répartis en trois niveaux de difficulté, ainsi que 20 questions à choix multiples (QCM) correspondantes. VOus devrez envoyer avant la fin du temps imparti les réponses sur votre propre dépôt GitHub.

### Exercices

1. Écrivez une fonction nommée `add` qui prend deux paramètres (a et b) et renvoie leur somme.
        function add(a, b) {
            return a + b;
            }
        add(2, 3);

2. Créez une fonction `multiply` qui prend deux paramètres (x et y) et renvoie leur produit par additions successives.

        function multiply(x,y){
            <!-- resultat -->
            let result = 0;
            let count = 0;
            while (count < y ){
                result += x;
                count++;
            }
            return result;
        }

3. Écrivez une fonction `isEven` qui prend un nombre en paramètre et renvoie `true` s'il est pair et `false` s'il est impair.

        function isEven(number) {
            return number % 2 === 0;
        }
        isEven(7); isEven(8);


4. Écrivez une fonction `reverseString` qui prend une chaîne de caractères en entrée et renvoie cette chaîne inversée.



5. Créez une fonction `findMax` qui prend un tableau de nombres en entrée et renvoie le nombre le plus élevé.
6. Écrivez une fonction `capitalizeWords` qui prend une phrase en paramètre et renvoie la même phrase avec chaque mot en majuscules.
7. Écrivez une fonction `filterEvenNumbers` qui prend un tableau de nombres en entrée et renvoie un nouveau tableau contenant uniquement les nombres pairs.
8. Créez une fonction `calculateFactorial` qui prend un nombre entier positif en paramètre et renvoie sa factorielle.
9. Écrivez une fonction `findLongestWord` qui prend un tableau de mots en entrée et renvoie le mot le plus long.
10. Écrivez une fonction `isPalindrome` qui prend une chaîne de caractères en entrée et renvoie `true` si la chaîne est un palindrome (se lit de la même manière de gauche à droite et de droite à gauche), sinon renvoie `false`.

### Questions à choix multiples (QCM)

1. Quelle est la sortie de `console.log(typeof "123")` ?
   - a) "string"

2. Quelle méthode JavaScript est utilisée pour supprimer le dernier élément d'un tableau ?
   - a) `pop()`

3. Quel opérateur est utilisé pour vérifier l'égalité stricte, c'est-à-dire que les valeurs et les types doivent correspondre ?
   - b) `===`


4. Comment déclarez-vous une variable en JavaScript ?
   - c) `var x;`

5. Quelle boucle JavaScript est principalement utilisée pour parcourir les éléments d'un tableau ?
   - a) `while`


6. Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?

   - c) `push()`

7. Quel opérateur est utilisé pour vérifier si une valeur est supérieure à une autre en JavaScript ?
   - a) `>`


8. Quelle méthode JavaScript est utilisée pour convertir une chaîne de caractères en minuscules ?
   - a) `toLowerCase()`


9. Quelle fonction JavaScript est utilisée pour générer un nombre aléatoire entre 0 et 1 ?
   - b) `Math.random()`


10. Comment accédez-vous au premier élément d'un tableau appelé `myArray` en JavaScript ?
    - a) `myArray[0]`
