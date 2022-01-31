# Markdown_Syntax_FR
Juste de l'aide pour écrire en markdown sur github 😃

## Markdown Cheatsheet<a name="top"></a>

## Sommaire :

- Les titres
- La mise en forme du texte (comme dans Word)
- Les liens
- Les listes
- Les tableaux
- Les images
- Le code (`ça`)
- Comment sauter une ligne
- Les séparateurs
- Vidéos YouTube
- Crédits

<a href="#headers">Headers</a><br>
<a href="#emphasis">Emphasis</a><br>
<a href="#lists">Lists</a><br>
<a href="#links">Links</a><br>
<a href="#images">Images</a><br>
<a href="#code">Code and Syntax Highlighting</a><br>
<a href="#tables">Tables</a><br>
<a href="#blockquotes">Blockquotes</a><br>
<a href="#html">Inline HTML</a><br>
<a href="#hr">Horizontal Rule</a><br>
<a href="#lines">Line Breaks</a><br>
<a href="#videos">YouTube Videos</a><br>
<a href="#tex">TeX Mathematical Formulae</a></p>

---

# Titre 1 #

    # Titre 1 #

    ou

    ============= (en dessous du Titre 1)

## Titre 2 ##

    ## Titre 2 ##

    ou

    --------------- (en dessous du Titre 2)

### Titre 3 ###

    ### Titre 3 ###

#### Titre 4 ####

    #### Titre 4 ####

##### Titre 5 #####

    ##### Titre 5 #####


###### Titre 6 ######

    ###### Titre 6 ######

Texte<a name="texte"></a>

    Juste écrit

_Italique_

    _Ita_ *lique*

~~Barré~~ (problèmes d'affichage sur certains navigateurs ou OS pas à jour)

    ~~Barré~~

__Gras__

    __Gras__ **pas gros**

___Gras + italique___

    ___pour les forceurs___ ***ou si c'est très important***

[Texte avec un lien](https://github.com/EDM115/ "eheh c'est moi 😎") et liens sans texte : https://lien.fr/ ou <https://autrelien.com/> (marche aussi avec les <adresses@mail.com>)

    [Le texte](https://unlienrandom.fr/ "Le texte de l'info-bulle") https://lien.fr/ ou <https://autrelien.com/> (marche aussi avec les <adresses@mail.com>)

[Aller dans une autre catégorie](#texte "Bah vas-y 🤓")
    
    [nom du lien](#nom de l'ancre "info-bulle") ET <a name="nom de l'ancre"></a> à coté (ou devant) ton texte

[Les liens d'auto-référence][Juste du texte, peu importe SI LES MAJUSCULES sont présentes ou NON]

    [Les liens d'auto-référence][Juste du texte, peu importe SI LES MAJUSCULES sont présentes ou NON]

[Pour ces liens-là, on peut aussi utiliser des chiffres (utile par exemple pour des références comme sur Wikipédia)][1]

    [Pour ces liens-là, on peut aussi utiliser des chiffres (utile par exemple pour des références comme sur Wikipédia)][1]

Et AILLEURS dans le `.md`, tu mets tes références (là, elles seront en bas du doc)


Un tableau, comme ici :

Colonne 1 | Colonne 2
------------- | -------------
Text | Texte
Texte  | Texte

```
Colonne 1  | Colonne 2
---------- | ---------
Texte      | Texte
Texte      | Texte
(note : les | n'ont pas besoin d'être alignées)
```

Ajouter `|` Dans un tableau :

Colonne 1  | Colonne 2
---------- | ---------
Texte      | Texte
Texte      | \|

```
Ajoute un antislash avant : \| 
```

Tableau aligné à gauche, centre, droite

Gauche | Centre | Droite
| :--- | :---: | ---:
◀️  | ⏺️ | ▶️
⬅️  | 🔛 | ➡️

```
Gauche | Centre | Droite
| :--- | :---: | ---:
◀️  | ⏺️ | ▶️
⬅️  | 🔛 | ➡️
```

`code()`

    `code()`
    
    OU
    
    <code>code()</code>
    
    OU
    
    Tu l'entoure avec des retours à la ligne et tabulations/4 espaces :
    ↵
    ↹code()
    ↵


```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "404+DJ+teke+me+home",
            "lookedUpItem": {
                "name": "Take me home",
                "artist": "404__DJ",
                "album": "Take me home",
                "picture": "https://i.scdn.co/image/ab67616d00001e02ebcc01a9709ceb39f0dbc68b",
                "link": "https://open.spotify.com/track/3b935Jhv7ZnWZQqWin2DJy?si=c2e942ea62d94838"
            }
        }
    }
```

    ```javascript
    ```

```python
    while True:
        print("I love coffee")
```

    ```python
    ```

* Liste non ordonnée
    * Un point à côté
        * Encore à côté, …
* Autre liste non ordonnée

~~~
* Liste non ordonnée
    * Un point à côté
        * Encore à côté, …
* Autre liste non ordonnée

Caractères utilisables : * - +
~~~

1. Liste numérotée
    1. Indentée
    2. La suite de l'indentation
    4. Les chiffres utilisés n'importent pas
    8. Du moment que c'est des chiffres
2. Suite des numéros

~~~
1. Liste numérotée
    1. Indentée
    2. La suite de l'indentation
    4. Les chiffres utilisés n'importent pas
    8. Du moment que c'est des chiffres
2. Suite des numéros
~~~

- [ ] Tâche non complétée
    - [ ] Une sous-tâche
- [x] Tâche finie

~~~
- [ ] Tâche non complétée
    - [ ] Une sous-tâche
- [x] Tâche finie
~~~

Blocs de citation :

> Citation
>> Sous-citation
>>> Sous-sous-...

    > Citation
    >> Sous-citation
    >>> Utile pour recréer des réponses

_Ligne horizontale :_
- - - -

    - - - -
    
    OU
    
    ---

_Image avec texte alternatif :_

![monimage](http://via.placeholder.com/200x150 "Le titre est optionnel")

    ![monimage](http://via.placeholder.com/200x150 "Le titre est optionnel")

Comme avec les liens, on peut les mettre en auto-référence :

![Moi askip][logo]

    ![Moi askip][logo]

Texte (ou n'importe quoi) dépliable :

<details>
  <summary>Titre 1</summary>
    <p>Ce genre de truc est utile pour faire des menus avec dedans des trucs pas très importants</p>
</details>
<details>
  <summary>Spoiler Alert</summary>
    <p>Ils meurent tous à la fin (ouais, y'a pas de truc "spoiler" comme sur Discord ou Telegram, ce truc peut donc être utile pour ça)</p>
</details>

    <details>
      <summary>Titre 1</summary>
        <p>Ce genre de truc est utile pour faire des menus avec dedans des trucs pas très importants</p>
    </details>
    <details>
      <summary>Spoiler Alert</summary>
        <p>Ils meurent tous à la fin (ouais, y'a pas de truc "spoiler" comme sur Discord ou Telegram, ce truc peut donc être utile pour ça)</p>
    </details>

Affichage de balises HTML (coloration syntaxique) :

```html
<h3>HTML</h3>
<p>Un peu de HTML ici (oui, les balises HTML sont compatibles sur GitHub 😃)</p>
```

    ```html
    <h3>HTML</h3>
    <p>Un peu de HTML ici (oui, les balises HTML sont compatibles sur GitHub 😃)</p>
    ```

Retour à la ligne :
C'est pas aussi simple que vous le pensez...
Là par exemple, j'ai fait un ↩ mais... Ça n'apparaît pas !  
La solution, y'en a plusieurs en fait :  

    Utiliser un tag <br>
    Utiliser DEUX espaces à la fin d'une ligne ⎵ ⎵
    Sauter DEUX lignes ↩ ↩

Lien vers une partie spécifique du README.md :

[Va en haut](#top)
   
    [Nom de l'ancre](#id)
    ET
    À côté de la destination de ton ancre : <a name="id"></a>    

Touche du clavier :

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    <kbd>⌘F</kbd>

*Liste des touches compatibles :*

| Touche | Symbole |
| --- | --- |
| Option | ⌥ |
| Contrôle | ⌃ |
| Command (ou win) | ⌘ / ⊞ Win |
| Maj | ⇧ |
| Verr. Maj | ⇪ |
| Tab | ⇥ / ↹ |
| Echap | ⎋ |
| Marche-arrêt | ⌽ / ⏻ |
| Entrée | ↩ / ↵ |
| Suppr | ⌫ |
| Haut | ↑ |
| Bas | ↓ |
| Gauche | ← |
| Droite | → |

Emoji :

:exclamation: Utilise les emojis pour rendre un texte plus compréhensible :+1:  La liste est la même que pour Discord et Telegram [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    EXACTEMENT pareil que Discord et Telegram, c'est entre : :EMOJICODE:

Vidéos YouTube :  
Y'a pas de support direct, **en revanche** tu peux mettre une image avec un lien vers la vidéo :  
[![Revealed Music 24/7 Live Stream Radio Best EDM - Big Room, Progressive House, Electro House, Dance](http://img.youtube.com/vi/LDJ-LsCDpLM/0.jpg)](http://www.youtube.com/watch?v=LDJ-LsCDpLM)

    [![Texte pour l'info-bulle](http://img.youtube.com/vi/l'ID de la vidéo/0.jpg)](http://www.youtube.com/watch?v=l'ID de la vidéo)

Si tu veux une taille spécifique, tu passe en html :  
<a href  ="https://www.youtube.com/watch?feature=player_embedded&v=LDJ-LsCDpLM" target="_blank"><img src="http://img.youtube.com/vi/LDJ-LsCDpLM/0.jpg" alt="Revealed Music 24/7 Live Stream Radio Best EDM - Big Room, Progressive House, Electro House, Dance" width="240" height="180" border="10"/></a>

    <a href  ="https://www.youtube.com/watch?feature=player_embedded&v=LDJ-LsCDpLM" target="_blank"><img src="http://img.youtube.com/vi/LDJ-LsCDpLM/0.jpg" alt="Revealed Music 24/7 Live Stream Radio Best EDM - Big Room, Progressive House, Electro House, Dance" width="240" height="180" border="10"/></a>

<h6>Références :</h6>
[juste du texte, peu importe si les majuscules sont présentes ou non]:https://google.com
[1]:http://t.me/EDM115
[logo]:https://github.com/EDM115/EDM115.github.io/raw/main/thumbnail.jpg

---

#### Sources :
- [x] [adam-p](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)
- [x] [tchapi](https://github.com/tchapi/markdown-cheatsheet)
