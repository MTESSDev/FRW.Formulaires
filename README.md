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
2. Tapez `MTESS` dans la barre de recherche
3. Cliquez **Install** sur l'extension **MTESS - Formulaires bac-a-sable**

> ⚠️ L'installation ne dure que quelques secondes et ne se fait qu'une seule fois — l'extension reste mémorisée pour les prochaines visites.

---

## 📄 Étape 2 — Ouvrir un fichier formulaire

Dans l'explorateur de fichiers à gauche (`Ctrl+Shift+E`), naviguez vers un fichier `.form.yml` et cliquez dessus pour l'ouvrir.

Exemple :

```
Personnes-immigrantes/
  Personnes-immigrantes.v1.form.yml   ← cliquez ici
```

---

## ✏️ Étape 3 — Modifier le formulaire

Faites vos modifications directement dans l'éditeur. Vous bénéficiez de :

- **IntelliSense** — autocomplétion des champs, types et propriétés FRW
- **Validation en temps réel** — les erreurs de schéma sont soulignées

Exemple de modification rapide — changer le titre du formulaire :

```yaml
form:
  title:
    fr: "Demande de prise en charge d’une personne immigrante"
```

---

## 👁️ Étape 4 — Ouvrir le bac à sable

Une fois le fichier ouvert ou modifié, lancez la prévisualisation du formulaire avec le raccourci clavier (`Ctrl+S`) qui permet en même temps de sauvegarder le document.

---

## 💾 Sauvegarder vos modifications

Les modifications faites dans `github.dev` restent dans le navigateur jusqu'à ce que vous les committez. Pour conserver une copie rapidement, faites un ``Fork`` du repo, cela créera une copie à vous dans votre compte github accessible via github.dev et cela vous permettra de ne rien perdre en attendant d'aller plus loin 😁.

---

## ❓ Dépannage

| Problème | Solution |
|---|---|
| La notification d'extension n'apparaît pas | `Ctrl+Shift+X` → chercher `mtess` → Install |
| Le bac à sable ne s'ouvre pas | Vérifiez que l'extension est bien installée et activée |
| Les modifications ne sont pas sauvegardées | Utiliser Source Control (`Ctrl+Shift+G`) pour committer |
| L'IntelliSense ne fonctionne pas | Recharger la fenêtre : `Ctrl+Shift+P` → *Reload Window* |