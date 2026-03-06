# Questionnaire client - GitHub Pages

Ce dépôt publie un questionnaire de satisfaction client via GitHub Pages.

## Fonctionnement

- La page `index.html` est le formulaire à partager aux clients.
- Les réponses sont envoyées par e-mail à `ani.sargsyan@ivar-fr.com` via FormSubmit.
- Après envoi, l'utilisateur est redirigé vers `merci.html`.

## Mise en place (toutes les étapes)

1. **Activer GitHub Pages**
   - Aller dans `Settings` > `Pages`.
   - Choisir `Deploy from a branch`.
   - Sélectionner la branche `main` (ou la branche de publication) et le dossier `/ (root)`.
2. **Récupérer le lien à partager**
   - Le questionnaire sera disponible à l'adresse :
     `https://kayhalan.github.io/test-formulaire-ivar/`
3. **Valider l'e-mail de réception FormSubmit (obligatoire au 1er envoi)**
   - Ouvrir le formulaire publié et envoyer un premier test.
   - FormSubmit enverra un e-mail de confirmation à `ani.sargsyan@ivar-fr.com`.
   - Cliquer sur le lien de validation pour autoriser la réception des réponses.
4. **Tester le parcours complet**
   - Soumettre une réponse de test.
   - Vérifier la réception de l'e-mail et la redirection vers la page de remerciement.

## Questions liminaires intégrées

Le formulaire inclut une section "Questions liminaires" avec :
- nom et prénom,
- e-mail,
- entreprise,
- date du dernier échange.
