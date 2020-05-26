Ceci est un paragraphe de texte.

Cela aura pour effet de traduire le texte en HTML, comme ceci :

<p>Ceci est un paragraphe de texte.</p>


Titre de niveau 1
=================

Titre de niveau 2
-----------------

# Titre de niveau 1

## Titre de niveau 2

### Titre de niveau 3

* Une puce
* Une autre puce
* Et encore une autre puce !

ou + ou - 

- Une puce
- Une autre puce
- Et encore une autre puce !

* Une puce
* Une autre puce
 * Une sous-puce
   * Une autre sous-puce
* Et encore une autre puce !


--------------
Les cellules du tableau sont délimitées par un trait vertical dénommé pipe en anglais s'effectuant avec la combinaison AltGr - 6

Le tableau se découpe en 3 parties distinctes

    la première ligne l'en-tête du tableau
    la seconde précise l'alignement du texte dans les cellules
    :- à gauche
    :-: centré
    -: à droite
    le contenu du tableau

Ce tableau

    || Lille |Arras|Amiens|
    |-:|:-:|:-:|:-:|
    |Anglais|Oui|Oui|Oui|
    |Chinois|Non|Oui|Non|
    |Allemand|Oui|Oui|Oui|
    |Russe|Non|Non|Oui|

donne

|| Lille |Arras|Amiens|
|-:|:-:|:-:|:-:|
|Anglais|Oui|Oui|Oui|
|Chinois|Non|Oui|Non|
|Allemand|Oui|Oui|Oui|
|Russe|Non|Non|Oui|



------------





Pour insérer un code source, il suffit de l'indenter, c'est-à-dire de le faire précéder de 4 espaces ou d'une tabulation :

Voici un code en C :


    int main()

    {

        printf("Hello world!\n");

        return 0;

    }
 
 Code en ligne

Si vous voulez écrire un morceau de code au milieu d'un paragraphe, entourez-le d'accents graves comme ceci : `. Exemple :

La fonction `printf()` permet d'afficher du texte


Barre de séparation

Faire une barre de séparation en Markdown ? Rien de plus intuitif !

-----------------


Les images s'insèrent de la même façon que les liens. Vous devez simplement mettre un point d'exclamation devant les premiers crochets :
Utiliser le download link !

![figure_001.png](https://jupyter.lyceeconnecte.fr/user/luc.vincent/files/Webinaire%20/FrontendKernel.png?_xsrf=2%7C482a92eb%7C0641d2e14678eed8e1344d8efef617c2%7C1590099676)

---------------

Pour créer un lien, vous devez placer le texte du lien entre crochets suivis de l'URL entre parenthèses :

Rendez-vous sur le [Site du lycée](https://www.lyceedesgraves.fr/) pour tout apprendre  !

[Le site officiel de Markdown](https://daringfireball.net/projects/markdown/syntax)

--------------
On peut ecrire du code en ligne `import numpy as np`

Ecrire

    ```python
    
    print "Hello World"
    
    ```
Affichera

```python
print "Hello World" 
```
Et écrire 

    ```javascript
    
    console.log("Hello World")
    
    ```
Affichera
```javascript
console.log("Hello World")
```

-----------
Et du Latex

Des expressions en ligne peuvent être ajoutées en entourant le code latex avec `$`: $e^{i\pi} + 1 = 0$

Les expressions sur leur propre ligne sont entourées de `$$`
$$e^x=\sum_{i=0}^\infty \frac{1}{i!}x^i$$


