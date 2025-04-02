# 🌐 Horizon 3D

**Horizon 3D** est un site web de vente de packs d'assets 3D destiné aux créateurs de jeux vidéo. Il propose également des concours où les utilisateurs peuvent participer et tenter de gagner des packs gratuitement.

## ✨ Fonctionnalités

- Affichage de packs d'assets 3D (environnements, personnages, effets, etc.)
- Section concours avec formulaire de participation
- Formulaire de contact pour toute demande
- Page de confirmation après envoi d'un formulaire
- Design responsive et moderne avec **Tailwind CSS**

## 🖼 Aperçu

![screenshot](screenshot.png) <!-- Tu peux ajouter une capture d'écran de ton site ici -->

## 🚀 Installation locale

1. Clone ce dépôt :
   ```bash
   git clone https://github.com/ton-utilisateur/horizon3d.git
   cd horizon3d
   ```

2. Ouvre le projet dans VS Code ou un éditeur de ton choix.

3. Utilise une des méthodes suivantes pour lancer un **serveur local** (nécessaire pour les formulaires) :

### Avec Live Server (VS Code)
- Installe l'extension "Live Server" dans VS Code
- Clique droit sur `index.html` > **Ouvrir avec Live Server**

### Avec Python (si installé)
```bash
python3 -m http.server
```
Et accède à `http://localhost:8000`

### Avec Node.js (si installé)
```bash
npx serve .
```
Et accède à `http://localhost:3000` (ou autre port indiqué)

## 📂 Structure
```
.
├── index.html              # Page d'accueil principale
├── merci.html              # Page de confirmation après formulaire
├── pack.html               # Exemple de page fiche produit
├── /assets                 # Images (packs, logos...)
└── README.md               # Ce fichier
```

## 📬 Configuration des formulaires
Les formulaires utilisent [FormSubmit](https://formsubmit.co) :
- Remplace `TON_EMAIL@mail.com` par ton vrai email dans `index.html`
- Tu recevras un email de validation la première fois
- Une redirection vers `merci.html` s'effectue automatiquement après envoi

## 📄 Licence
Projet libre pour usage éducatif ou personnel.

---
Créé avec passion par [TonNom] 💙
