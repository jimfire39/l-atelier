# L'Atelier — Formation Claude Code

Site statique : de débutant à intermédiaire sur Claude Code, jusqu'à la création d'une équipe d'agents IA.

## Fichiers
- `index.html` — accueil, méthode, fil rouge, programme des 10 sessions
- `session-1.html` — leçon 1 complète (cours, exercice, quiz, récap)
- `.nojekyll` — désactive le traitement Jekyll de GitHub Pages

Chaque page est autonome (styles et scripts intégrés). La progression et les scores sont enregistrés dans le navigateur (localStorage).

## Mise en ligne sur GitHub Pages
1. Crée un dépôt sur github.com (ex. `atelier-claude-code`), public.
2. Bouton **Add file → Upload files** : dépose `index.html`, `session-1.html`, `README.md` et `.nojekyll`. Valide avec **Commit changes**.
3. **Settings → Pages** : Source = *Deploy from a branch*, Branch = `main`, dossier `/ (root)`, **Save**.
4. Après une à deux minutes, le site est disponible à `https://<ton-pseudo>.github.io/atelier-claude-code/`.

Astuce : si `.nojekyll` n'apparaît pas dans ton explorateur (fichier caché), crée-le directement sur GitHub via **Add file → Create new file**, nommé `.nojekyll`, contenu vide.
