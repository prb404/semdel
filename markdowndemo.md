# Titre Niveau 1

Texte introductif avec **gras**, *italique*, ~~barré~~, ==highlight==, `inline code`, H~2~O et 2^10^.  
Emoji : 🚀 ✨

---

## Liens & Images

Lien absolu [example](https://example.com) et lien relatif [profil](/membres).  
![Image classique](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Relationship_between_Wikipedia_and_the_press.svg/250px-Relationship_between_Wikipedia_and_the_press.svg.png)

![Image redimensionnée](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Relationship_between_Wikipedia_and_the_press.svg/250px-Relationship_between_Wikipedia_and_the_press.svg.png =120x80)

---

## Citations

> Paragraphe dans un blockquote.
>
> > Blockquote imbriqué
>
> Ligne suivant la citation pour vérifier l’espacement.

---

## Listes

Liste non ordonnée mixte :
- Item A
 * Item B
 + Item C
   - Sous-item C1

Liste ordonnée :
1. Premier
2. Deuxième
3. Troisième
   1. Sous-élément

Liste de tâches :
- [ ] Faire un test
- [x] Case cochée
- [ ] Élément supplémentaire

---

## Tableaux

Table simple :

| Produit  | Prix | Stock |
| -------- | ---: | :---: |
| Clavier  | €120 |  ✅   |
| Souris   |  €45 |  ❌   |
| Écran    | €499 |  ✅   |

Table multiligne :

Titre | Description
----- | -----------
Ligne 1 | Texte long sur plusieurs lignes avec retour explicite (ou pas).
Ligne 2 | Autre description

---

## Code Fences

```
// JS générique
console.log('Hello world');
```

```javascript
const greet = (name) => {
  console.log(`Bonjour ${name}`);
};
greet('Obsia');
```

```python
def fib(n):
    if n <= 1:
        return n
    return fib(n-1) + fib(n-2)
```

---

## Définition & Abréviations

Markdown
: Conversion texte → HTML
yo[^yo]
[^yo]: yoyo là haut

StackEdit
: Exemple historique

*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets

---

## Notes de bas de page

Un texte avec une note de bas de page.[^demo]

[^demo]: Voici le contenu de la note.

---

## Mélange final

### Titre spécial
---------------------------
Texte normal juste après.  
> Citation rapide.  
> Encore une ligne.

Du texte suivit d’un séparateur horizontal.

---