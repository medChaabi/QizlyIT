# Contribuer au projet QizlyIT 🤝

Merci de votre intérêt à contribuer à QizlyIT ! Ce document fournit des instructions et des lignes directrices pour le dépôt et ses ressources partagées.

## 📁 Structure du Dépôt

Vos fichiers doivent être organisés selon la structure suivante :

*   **`Files/`** : copies locales des **PDF** (et autres documents de référence du même type), lorsque vous les versionnez dans le dépôt. Ce dossier ne sert **pas** aux fichiers JSON des quiz.
*   **`JSON/`** : fichiers `.json` compatibles avec l’application Qizly.
*   **Google Drive (recommandé pour le partage)** : liens de **téléchargement direct** au même format que dans le `README.md` :

    - PDF : `https://drive.google.com/uc?export=download&id=FILE_ID`
    - JSON : `https://drive.google.com/uc?export=download&id=FILE_ID` (même format)

L’identifiant `FILE_ID` se trouve dans l’URL du fichier partagé : `https://drive.google.com/file/d/FILE_ID/view`.

## Liens du tableau (README)

Dans la colonne **Fichier JSON Qizly** :

- **JSON ⬇️** : lien `raw.githubusercontent.com` vers le fichier dans `JSON/` — accès direct au contenu (import dans Qizly ou enregistrement).
- **fichier** : lien vers la copie dans le dépôt sur GitHub (`JSON/`).

Pour le JSON, privilégier le même lien Google Drive que pour les PDF (`uc?export=download&id=…`) dès que le fichier est sur Drive ; sinon le format `raw.githubusercontent.com` ci-dessus convient jusqu’à ce que le lien Drive soit ajouté.

Les **PDF** passent en priorité par Google Drive ; une copie locale optionnelle se place dans `Files/` (pas les JSON).

## 📝 Comment ajouter votre contribution

1. **Forkez le dépôt** : Créez une copie personnelle de ce dépôt sur GitHub.
2. **Clonez votre fork** : Téléchargez le dépôt sur votre ordinateur.
3. **Ajoutez vos fichiers** : placez les quiz dans `JSON/`, les PDF éventuels dans `Files/`, et/ou hébergez les versions « officielles » sur Google Drive avec partage par lien.
4. **Mettez à jour le tableau du README.md** :
   - Ajoutez une nouvelle ligne à la Table des Ressources.
   - Exemple (PDF en Drive, JSON en Drive + copie dans `JSON/`) :
     ```markdown
     | Nom | Type | Date | Ressource (PDF) | Fichier JSON Qizly | Code Qizly | Par |
     | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
     | Mon Quiz | Genre | 2024 | [PDF 📄](https://drive.google.com/uc?export=download&id=VOTRE_ID_PDF) | [JSON ⬇️](https://drive.google.com/uc?export=download&id=VOTRE_ID_JSON) · [fichier](./JSON/mon-quiz.json) | `VOTRE-CODE` | [@votre_pseudo](https://github.com/votre_pseudo) |
     ```
   - Si vous versionnez aussi le PDF dans le dépôt, vous pouvez ajouter un second lien dans la colonne PDF, par ex. ` · [PDF local](./Files/mon-quiz.pdf)`.
   - Si le JSON n’est **pas** encore sur Drive, vous pouvez temporairement utiliser un lien `raw.githubusercontent.com` vers `JSON/` comme dans le README actuel, puis le remplacer par le lien Drive une fois le fichier uploadé.
5. **Commettez et Poussez (Commit and Push)** : Envoyez vos modifications vers votre fork sur GitHub.
6. **Ouvrez une Pull Request** : Soumettez vos changements pour examen dans le dépôt principal.

## ✅ Liste de contrôle pour les contributions

- [ ] Les fichiers sont dans le bon dossier (`Files/` pour les PDF, `JSON/` pour les quiz).
- [ ] Les noms de fichiers sont clairs et descriptifs.
- [ ] Pas d’espaces dans les noms de fichiers (utilisez des tirets ou des underscores).
- [ ] Le contenu du PDF et du JSON est cohérent.
- [ ] Le tableau du `README.md` est mis à jour correctement (liens Drive `uc?export=download` pour téléchargement direct lorsque c’est possible).
- [ ] Aucun matériel sous droits d’auteur sans autorisation de partage.

---
Merci de nous aider à faire grandir la communauté Qizly !
