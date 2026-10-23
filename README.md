# Futures Risk Calculator (MGC / MNQ / MES)

Mini-calculateur statique, en français, sans dépendance, sans compte et sans backend.

## Lancer en local
Ouvre `index.html` dans un navigateur.

## Héberger gratuitement sur GitHub Pages
1. Crée un dépôt GitHub, par exemple `futures-risk-calculator`.
2. Envoie `index.html` et `README.md` à la racine du dépôt.
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Dans **Build and deployment**, sélectionne **Deploy from a branch**.
5. Choisis la branche `main`, le dossier `/ (root)`, puis **Save**.
6. Attends le déploiement : GitHub affiche l’adresse publique dans la section Pages.

## Fonctionnalités
- Sélection MGC, MNQ ou MES.
- Achat (Long) ou vente (Short).
- Prix d'entrée et prix de stop-loss.
- Risque maximal en dollars, ratio de TP, frais estimés par contrat.
- Nombre entier maximal de contrats, perte estimée, prix du TP et gain potentiel.
- Vérification du sens du stop.

## Valeurs utilisées
- MGC : 10 USD par point, tick 0,10, soit 1 USD par tick.
- MNQ : 2 USD par point, tick 0,25, soit 0,50 USD par tick.
- MES : 5 USD par point, tick 0,25, soit 1,25 USD par tick.

Les symboles avec échéance `Z6` sont des contrats de décembre 2026. Vérifie les spécifications du contrat et le symbole exact auprès de ton broker. Le risque réel peut dépasser le calcul en raison du slippage, des gaps et des frais réels. Cet outil ne passe aucun ordre et ne constitue pas un conseil financier.
