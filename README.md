# Markdown_Syntax_FR
Juste de l'aide pour écrire en markdown sur github 😃

### Markdown Cheatsheet<a name="TOP"></a>

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

[Texte avec un lien](https://github.com/EDM115/ "eheh c'est moi 😎") et liens sans texte : https://lien.fr/ ou <https://autrelien.com/>

    [Le texte](https://unlienrandom.fr/ "Le texte de l'info-bulle") https://lien.fr/ ou <https://autrelien.com/>

[Aller dans une autre catégorie](#texte "Bah vas-y 🤓")
    
    [nom du lien](#nom de l'ancre "info-bulle") ET <a name="nom de l'ancre"></a> à coté (ou devant) ton texte

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

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    ```javascript
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

OU

* Liste non ordonnée
    * Un point à côté
        * Encore à côté, …
* Autre liste non ordonnée
~~~

1. Liste numérotée
    1. Indentée
    2. La suite de l'indentation
2. Suite des numéros

~~~
1. Liste numérotée
    1. Indentée
    2. La suite de l'indentation
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

> Citation
>> Sous-citation

    > Citation
    >> Sous-citation

_Ligne horizontale :_
- - - -

    - - - -
    
    OU
    
    ---

_Image avec texte alternatif :_

![monimage](http://via.placeholder.com/200x150 "Le titre est optionnel")

    ![monimage](http://via.placeholder.com/200x150 "Le titre est optionnel")

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


Lien vers une partie spécifique du README.md :

[Va en haut](#TOP)
   
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
| Command (ou win) | ⌘ |
| Maj | ⇧ |
| Verr. Maj | ⇪ |
| Tab | ⇥ |
| Echap | ⎋ |
| Marche-arrêt | ⌽ |
| Entrée | ↩ |
| Suppr | ⌫ |
| Haut | ↑ |
| Bas | ↓ |
| Gauche | ← |
| Droite | → |

Emoji :

:exclamation: Utilise les emojis pour rendre un texte plus compréhensible :+1:  La liste est la même que pour Discord et Telegram [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    EXACTEMENT pareil que Discord et Telegram, c'est entre : :EMOJICODE:



<div data-view-component="true" class="Layout-main">          <div id="wiki-body" class="gollum-markdown-content">
              <div class="markdown-body">
                <p>This is intended as a quick reference and showcase. For more complete info, see <a href="http://daringfireball.net/projects/markdown/" rel="nofollow">John Gruber's original spec</a> and the <a href="http://github.github.com/github-flavored-markdown/">Github-flavored Markdown info page</a>.</p>
<p>This cheatsheet is specifically <em>Markdown Here's</em> version of Github-flavored Markdown. This differs slightly in styling and syntax from what Github uses, so what you see below might vary a little from what you get in a <em>Markdown Here</em> email, but it should be pretty close.</p>
<p>You can play around with Markdown on our <a href="http://www.markdown-here.com/livedemo.html" rel="nofollow">live demo page</a>.</p>
<p>(If you're not a Markdown Here user, check out the <a href="./Markdown-Cheatsheet">Markdown Cheatsheet</a> that is not specific to MDH. But, really, you should also use Markdown Here, because it's awesome. <a href="http://markdown-here.com" rel="nofollow">http://markdown-here.com</a>)</p>
<h5>
<a id="user-content-table-of-contents" class="anchor" href="#table-of-contents" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Table of Contents</h5>
<p><a href="#headers">Headers</a><br>
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
<a name="user-content-headers"></a>
<h2>
<a id="user-content-headers" class="anchor" href="#headers" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Headers</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------"><pre lang="no-highlight"><code># H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
</code></pre></div>
<h1>
<a id="user-content-h1" class="anchor" href="#h1" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H1</h1>
<h2>
<a id="user-content-h2" class="anchor" href="#h2" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H2</h2>
<h3>
<a id="user-content-h3" class="anchor" href="#h3" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H3</h3>
<h4>
<a id="user-content-h4" class="anchor" href="#h4" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H4</h4>
<h5>
<a id="user-content-h5" class="anchor" href="#h5" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H5</h5>
<h6>
<a id="user-content-h6" class="anchor" href="#h6" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>H6</h6>
<p>Alternatively, for H1 and H2, an underline-ish style:</p>
<h1>
<a id="user-content-alt-h1" class="anchor" href="#alt-h1" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Alt-H1</h1>
<h2>
<a id="user-content-alt-h2" class="anchor" href="#alt-h2" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Alt-H2</h2>
<a name="user-content-emphasis"></a>
<h2>
<a id="user-content-emphasis" class="anchor" href="#emphasis" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Emphasis</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~"><pre lang="no-highlight"><code>Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
</code></pre></div>
<p>Emphasis, aka italics, with <em>asterisks</em> or <em>underscores</em>.</p>
<p>Strong emphasis, aka bold, with <strong>asterisks</strong> or <strong>underscores</strong>.</p>
<p>Combined emphasis with <strong>asterisks and <em>underscores</em></strong>.</p>
<p>Strikethrough uses two tildes. <del>Scratch this.</del></p>
<a name="user-content-lists"></a>
<h2>
<a id="user-content-lists" class="anchor" href="#lists" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Lists</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses"><pre lang="no-highlight"><code>1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
</code></pre></div>
<ol>
<li>First ordered list item</li>
<li>Another item</li>
</ol>
<ul>
<li>Unordered sub-list.</li>
</ul>
<ol>
<li>
<p>Actual numbers don't matter, just that it's a number</p>
</li>
<li>
<p>Ordered sub-list</p>
</li>
<li>
<p>And another item.</p>
<p>Some text that should be aligned with the above item.</p>
</li>
</ol>
<ul>
<li>Unordered list can use asterisks</li>
</ul>
<ul>
<li>Or minuses</li>
</ul>
<ul>
<li>Or pluses</li>
</ul>
<a name="user-content-links"></a>
<h2>
<a id="user-content-links" class="anchor" href="#links" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Links</h2>
<p>There are two ways to create links.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or &lt;http://www.example.com&gt; and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com"><pre lang="no-highlight"><code>[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or &lt;http://www.example.com&gt; and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
</code></pre></div>
<p><a href="https://www.google.com" rel="nofollow">I'm an inline-style link</a></p>
<p><a href="https://www.mozilla.org" rel="nofollow">I'm a reference-style link</a></p>
<p><a href="http://slashdot.org" rel="nofollow">You can use numbers for reference-style link definitions</a></p>
<p>Or leave it empty and use the <a href="http://www.reddit.com" rel="nofollow">link text itself</a></p>
<p>URLs and URLs in angle brackets will automatically get turned into links.
<a href="http://www.example.com" rel="nofollow">http://www.example.com</a> or <a href="http://www.example.com" rel="nofollow">http://www.example.com</a> and sometimes
example.com (but not on Github, for example).</p>
<p>Some text to show that the reference links can follow later.</p>
<a name="user-content-images"></a>
<h2>
<a id="user-content-images" class="anchor" href="#images" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Images</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png &quot;Logo Title Text 1&quot;)

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png &quot;Logo Title Text 2&quot;"><pre lang="no-highlight"><code>Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
</code></pre></div>
<p>Here's our logo (hover to see the title text):</p>
<p>Inline-style:
<img src="https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png" alt="alt text" title="Logo Title Text 1"></p>
<p>Reference-style:
<img src="https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png" alt="alt text" title="Logo Title Text 2"></p>
<a name="user-content-code"></a>
<h2>
<a id="user-content-code-and-syntax-highlighting" class="anchor" href="#code-and-syntax-highlighting" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Code and Syntax Highlighting</h2>
<p>Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and <em>Markdown Here</em> -- support syntax highlighting. <em>Markdown Here</em> supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the <a href="http://softwaremaniacs.org/media/soft/highlight/test.html" rel="nofollow">highlight.js demo page</a>.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Inline `code` has `back-ticks around` it."><pre lang="no-highlight"><code>Inline `code` has `back-ticks around` it.
</code></pre></div>
<p>Inline <code>code</code> has <code>back-ticks around</code> it.</p>
<p>Blocks of code are either fenced by lines with three back-ticks <code>```</code>, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="```javascript
var s = &quot;JavaScript syntax highlighting&quot;;
alert(s);
```
 
```python
s = &quot;Python syntax highlighting&quot;
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a &lt;b&gt;tag&lt;/b&gt;.
```"><pre lang="no-highlight"><code>```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a &lt;b&gt;tag&lt;/b&gt;.
```
</code></pre></div>
<div class="highlight highlight-source-js position-relative overflow-auto" data-snippet-clipboard-copy-content='var s = "JavaScript syntax highlighting";
alert(s);'><pre><span class="pl-k">var</span> <span class="pl-s1">s</span> <span class="pl-c1">=</span> <span class="pl-s">"JavaScript syntax highlighting"</span><span class="pl-kos">;</span>
<span class="pl-en">alert</span><span class="pl-kos">(</span><span class="pl-s1">s</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre></div>
<div class="highlight highlight-source-python position-relative overflow-auto" data-snippet-clipboard-copy-content='s = "Python syntax highlighting"
print s'><pre><span class="pl-s1">s</span> <span class="pl-c1">=</span> <span class="pl-s">"Python syntax highlighting"</span>
<span class="pl-k">print</span> <span class="pl-s1">s</span></pre></div>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a &lt;b&gt;tag&lt;/b&gt;."><pre><code>No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a &lt;b&gt;tag&lt;/b&gt;.
</code></pre></div>
<p>Again, to see what languages are available for highlighting, and how to write those language names, see the <a href="http://softwaremaniacs.org/media/soft/highlight/test.html" rel="nofollow">highlight.js demo page</a>.</p>
<a name="user-content-tables"></a>
<h2>
<a id="user-content-tables" class="anchor" href="#tables" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Tables</h2>
<p>Tables aren't part of the core Markdown spec, but they are part of GFM and <em>Markdown Here</em> supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3"><pre lang="no-highlight"><code>Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
</code></pre></div>
<p>Colons can be used to align columns.</p>
<table role="table">
<thead>
<tr>
<th>Tables</th>
<th align="center">Are</th>
<th align="right">Cool</th>
</tr>
</thead>
<tbody>
<tr>
<td>col 3 is</td>
<td align="center">right-aligned</td>
<td align="right">$1600</td>
</tr>
<tr>
<td>col 2 is</td>
<td align="center">centered</td>
<td align="right">$12</td>
</tr>
<tr>
<td>zebra stripes</td>
<td align="center">are neat</td>
<td align="right">$1</td>
</tr>
</tbody>
</table>
<p>The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.</p>
<table role="table">
<thead>
<tr>
<th>Markdown</th>
<th>Less</th>
<th>Pretty</th>
</tr>
</thead>
<tbody>
<tr>
<td><em>Still</em></td>
<td><code>renders</code></td>
<td><strong>nicely</strong></td>
</tr>
<tr>
<td>1</td>
<td>2</td>
<td>3</td>
</tr>
</tbody>
</table>
<a name="user-content-blockquotes"></a>
<h2>
<a id="user-content-blockquotes" class="anchor" href="#blockquotes" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Blockquotes</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="&gt; Blockquotes are very handy in email to emulate reply text.
&gt; This line is part of the same quote.

Quote break.

&gt; This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. "><pre lang="no-highlight"><code>&gt; Blockquotes are very handy in email to emulate reply text.
&gt; This line is part of the same quote.

Quote break.

&gt; This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
</code></pre></div>
<blockquote>
<p>Blockquotes are very handy in email to emulate reply text.
This line is part of the same quote.</p>
</blockquote>
<p>Quote break.</p>
<blockquote>
<p>This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can <em>put</em> <strong>Markdown</strong> into a blockquote.</p>
</blockquote>
<a name="user-content-html"></a>
<h2>
<a id="user-content-inline-html" class="anchor" href="#inline-html" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Inline HTML</h2>
<p>You can also use raw HTML in your Markdown, and it'll mostly work pretty well.</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="&lt;dl&gt;
  &lt;dt&gt;Definition list&lt;/dt&gt;
  &lt;dd&gt;Is something people use sometimes.&lt;/dd&gt;

  &lt;dt&gt;Markdown in HTML&lt;/dt&gt;
  &lt;dd&gt;Does *not* work **very** well. Use HTML &lt;em&gt;tags&lt;/em&gt;.&lt;/dd&gt;
&lt;/dl&gt;"><pre lang="no-highlight"><code>&lt;dl&gt;
  &lt;dt&gt;Definition list&lt;/dt&gt;
  &lt;dd&gt;Is something people use sometimes.&lt;/dd&gt;

  &lt;dt&gt;Markdown in HTML&lt;/dt&gt;
  &lt;dd&gt;Does *not* work **very** well. Use HTML &lt;em&gt;tags&lt;/em&gt;.&lt;/dd&gt;
&lt;/dl&gt;
</code></pre></div>
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
<a name="user-content-hr"></a>
<h2>
<a id="user-content-horizontal-rule" class="anchor" href="#horizontal-rule" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Horizontal Rule</h2>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Three or more...

---

Hyphens

***

Asterisks

___

Underscores"><pre><code>Three or more...

---

Hyphens

***

Asterisks

___

Underscores
</code></pre></div>
<p>Three or more...</p>
<hr>
<p>Hyphens</p>
<hr>
<p>Asterisks</p>
<hr>
<p>Underscores</p>
<a name="user-content-lines"></a>
<h2>
<a id="user-content-line-breaks" class="anchor" href="#line-breaks" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Line Breaks</h2>
<p>My basic recommendation for learning how line breaks work is to experiment and discover -- hit &lt;Enter&gt; once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.</p>
<p>Here are some things to try out:</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*."><pre><code>Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
</code></pre></div>
<p>Here's a line for us to start with.</p>
<p>This line is separated from the one above by two newlines, so it will be a <em>separate paragraph</em>.</p>
<p>This line is also begins a separate paragraph, but...<br>
This line is only separated by a single newline, so it's a separate line in the <em>same paragraph</em>.</p>
<p>(Technical note: <em>Markdown Here</em> uses GFM line breaks, so there's no need to use MD's two-space line breaks.)</p>
<a name="user-content-videos"></a>
<h2>
<a id="user-content-youtube-videos" class="anchor" href="#youtube-videos" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>YouTube Videos</h2>
<p>They can't be added directly but you can add an image with a link to the video like this:</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content='&lt;a href="http://www.youtube.com/watch?feature=player_embedded&amp;v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"&gt;&lt;img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /&gt;&lt;/a&gt;'><pre lang="no-highlight"><code>&lt;a href="http://www.youtube.com/watch?feature=player_embedded&amp;v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"&gt;&lt;img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /&gt;&lt;/a&gt;
</code></pre></div>
<p>Or, in pure Markdown, but losing the image sizing and border:</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)"><pre lang="no-highlight"><code>[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
</code></pre></div>
<a name="user-content-tex"></a>
<h2>
<a id="user-content-tex-mathematical-formulae" class="anchor" href="#tex-mathematical-formulae" aria-hidden="true"><svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>TeX Mathematical Formulae</h2>
<p>A full description of TeX math symbols is beyond the scope of this cheatsheet. Here's a <a href="https://en.wikibooks.org/wiki/LaTeX/Mathematics" rel="nofollow">good reference</a>, and you can try stuff out on <a href="https://www.codecogs.com/latex/eqneditor.php" rel="nofollow">CodeCogs</a>. You can also play with formulae in the Markdown Here options page.</p>
<p>Here are some examples to try out:</p>
<div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content="$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$"><pre><code>$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$
</code></pre></div>
<p>The beginning and ending dollar signs (<code>$</code>) are the delimiters for the TeX markup.</p>

              </div>

          </div>
</div>
</div>    </div>
  </div>

---

#### Sources :
- [x] [adam-p](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)
- [x] [tchapi](https://github.com/tchapi/markdown-cheatsheet)
