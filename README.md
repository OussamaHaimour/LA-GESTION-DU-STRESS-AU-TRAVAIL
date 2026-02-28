# 🧠 Human vs AI – Stress Source Challenge

**Human vs AI – Stress Source Challenge** est une application web interactive conçue pour aider les étudiants et les professionnels à identifier les sources de stress au travail en utilisant la méthodologie des **5 Pourquoi**. Le jeu compare en temps réel les analyses de l'utilisateur avec celles d'une Intelligence Artificielle (GPT-4o mini).

---

## 🚀 Fonctionnalités principales

- **🎯 17 Profils d'Étudiants :** Incarnez différents profils pour analyser des situations variées.
- **💼 5 Situations Réelles :** Basées sur des cas concrets de stress au travail (Surcharge, Délais, Conflits, Environnement, etc.).
- **🔍 Méthode des 5 Pourquoi :** Une analyse approfondie étape par étape pour trouver la cause racine du stress.
- **🤖 IA Adversaire :** Comparez vos choix avec une IA qui analyse la situation avec mantiq (logique froide).
- **📊 Comparaison en Temps Réel :** Visualisation immédiate des points d'accord et de désaccord entre l'humain et l'IA.
- **✨ Design Premium :** Interface moderne en mode sombre (Dark Mode) avec effets de Glassmorphism et animations fluides.

---

## 🛠️ Stack Technique

- **Frontend :** React.js, Vite, CSS3 (Vanilla), Axios.
- **Backend :** Node.js, Express.js.
- **IA :** API OpenRouter (Modèle GPT-4o mini).
- **Utilitaires :** UUID (Gestion de sessions), Dotenv (Variables d'environnement).

---

## 📦 Installation et Lancement

### 1. Cloner le projet
```bash
git clone https://github.com/OussamaHaimour/human-vs-ai-stress-game.git
cd human-vs-ai-stress-game
```

### 2. Configurer les variables d'environnement
Allez dans le dossier `backend`, créez un fichier `.env` et ajoutez votre clé API :

```bash
# backend/.env
OPENROUTER_API_KEY=votre_cle_api_ici
PORT=5000
LLM_MODEL=openai/gpt-4o-mini
```

### 3. Installer les dépendances
À la racine du projet, lancez :
```bash
npm run install-all
```

### 4. Lancer l'application
Pour lancer le backend et le frontend simultanément :
```bash
npm run dev
```
- **Frontend :** http://localhost:5173
- **Backend :** http://localhost:5000

---

## 📁 Structure du Projet

```text
├── backend/            # Serveur Express & Logique IA
│   ├── data/           # Situations et données du jeu
│   ├── routes/         # Endpoints de l'API
│   └── server.js       # Entrée du serveur
├── frontend/           # Application React
│   ├── src/
│   │   ├── components/ # Composants UI (Situation, Question, Results...)
│   │   └── App.jsx     # Logique principale du jeu
└── package.json        # Scripts de lancement global
```

---

## 🛡️ Sécurité
Le fichier `.gitignore` est configuré pour ne **jamais** uploader vos clés API (`.env`) sur GitHub. Utilisez toujours le fichier `.env.example` comme modèle.

---

## 👥 Crédits
Projet réalisé dans le cadre du module **Gestion du Stress au Travail**.
**Équipe :** Oussama B., Anoir, Yasser et Oussama H.

---
⭐ *N'hésitez pas à mettre une étoile au projet si vous l'appréciez !*
