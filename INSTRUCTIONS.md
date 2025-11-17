# 📋 Instructions pour publier sur GitHub Pages

## ✅ Étape 1 : Créer le dépôt sur GitHub

1. Aller sur **https://github.com/new**
2. **Repository name** : `zoma-privacy-policy`
3. **Description** : "Privacy policy for Zoma mobile app"
4. Cocher **Public** (obligatoire pour GitHub Pages gratuit)
5. **NE PAS** cocher "Add a README file" (on l'a déjà)
6. Cliquer sur **Create repository**

## ✅ Étape 2 : Connecter le dépôt local

Dans le terminal (vous êtes déjà dans `C:\zoma-privacy-policy`), exécutez :

```bash
git remote add origin https://github.com/Jc20036/zoma-privacy-policy.git
git branch -M main
git push -u origin main
```

## ✅ Étape 3 : Activer GitHub Pages

1. Aller sur **https://github.com/Jc20036/zoma-privacy-policy**
2. Cliquer sur **Settings** (en haut à droite)
3. Dans le menu de gauche, cliquer sur **Pages**
4. Sous **Source** :
   - **Branch** : `main`
   - **Folder** : `/ (root)`
5. Cliquer sur **Save**

## ✅ Étape 4 : Attendre et obtenir l'URL

Attendre **1-2 minutes**, puis votre URL sera disponible :

```
https://Jc20036.github.io/zoma-privacy-policy/privacy-policy.html
```

## ✅ Étape 5 : Vérifier

1. Ouvrir l'URL dans un navigateur (navigation privée)
2. Vérifier que la page s'affiche correctement
3. Vérifier que l'URL commence par `https://`

## ✅ Étape 6 : Utiliser dans Google Play

Copier l'URL et la coller dans le champ "URL des règles de confidentialité" du formulaire Google Play Console.

---

**Note :** Si vous avez besoin de mettre à jour la politique plus tard, modifiez `privacy-policy.html`, puis :
```bash
git add privacy-policy.html
git commit -m "Update privacy policy"
git push
```

