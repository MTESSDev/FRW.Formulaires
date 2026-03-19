# 🧪 Bac à sable FRW — Formulaires Web

Testez et modifiez des formulaires FRW directement dans votre navigateur, sans installer quoi que ce soit.

---

## 🚀 Ouvrir l'éditeur en ligne

Cliquez sur le lien suivant pour ouvrir le repo dans VS Code Web :

**👉 [Ouvrir dans github.dev](https://github.dev/MTESSDev/FRW.Formulaires)**

> Vous pouvez aussi remplacer `github.com` par `github.dev` dans n'importe quelle URL du repo.

---

## 🔌 Étape 1 — Installer l'extension FRW

À l'ouverture, VS Code affiche une notification en bas à droite :

> *"Voulez-vous installer le 'MTESS - Formulaires bac-a-sable' l'extension de MTESS recommandé pour ce dépôt?"*

Cliquez sur **Installer**.

Si la notification n'apparaît pas :

1. Ouvrez le panneau Extensions avec `Ctrl+Shift+X`
2. Tapez `mtessdev` dans la barre de recherche
3. Cliquez **Install** sur l'extension **FRW Bac à sable**

> ⚠️ L'installation ne dure que quelques secondes et ne se fait qu'une seule fois — l'extension reste mémorisée pour les prochaines visites.

---

## 📄 Étape 2 — Ouvrir un fichier formulaire

Dans l'explorateur de fichiers à gauche (`Ctrl+Shift+E`), naviguez vers un fichier `.form.yml` et cliquez dessus pour l'ouvrir.

Exemple :

```
formulaires/
  demo.v1.form.yml   ← cliquez ici
```

---

## ✏️ Étape 3 — Modifier le formulaire

Faites vos modifications directement dans l'éditeur. Vous bénéficiez de :

- **IntelliSense** — autocomplétion des champs, types et propriétés FRW
- **Validation en temps réel** — les erreurs de schéma sont soulignées
- **Snippets** — tapez `frw-` pour voir les extraits disponibles

Exemple de modification rapide — changer le titre d'une page :

```yaml
pages:
  - id: page1
    titre: Mon nouveau titre   # ← modifiez ici
```

---

## 👁️ Étape 4 — Ouvrir le bac à sable

Une fois le fichier ouvert, lancez la prévisualisation du formulaire :

- Via la palette de commandes : `Ctrl+Shift+P` → tapez **FRW** → sélectionnez **FRW : Ouvrir le bac à sable**
- Ou via l'icône d'aperçu dans la barre d'outils de l'éditeur (si disponible)

Le bac à sable s'ouvre dans un panneau à droite et se rafraîchit à chaque sauvegarde (`Ctrl+S`).

---

## 💾 Sauvegarder vos modifications

Les modifications faites dans `github.dev` restent dans le navigateur jusqu'à ce que vous les committez.

Pour sauvegarder dans le repo :

1. Ouvrez le panneau **Source Control** (`Ctrl+Shift+G`)
2. Entrez un message de commit
3. Cliquez **Commit & Push**

> Vous devez avoir les droits d'écriture sur le repo, ou passer par une **Pull Request** si vous travaillez sur un fork.

---

## ❓ Dépannage

| Problème | Solution |
|---|---|
| La notification d'extension n'apparaît pas | `Ctrl+Shift+X` → chercher `mtessdev` → Install |
| Le bac à sable ne s'ouvre pas | Vérifiez que l'extension est bien installée et activée |
| Les modifications ne sont pas sauvegardées | Utiliser Source Control (`Ctrl+Shift+G`) pour committer |
| L'IntelliSense ne fonctionne pas | Recharger la fenêtre : `Ctrl+Shift+P` → *Reload Window* |