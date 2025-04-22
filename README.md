# 📱 Mobile Starter App (React Native)

Application mobile complète développée avec **React Native + Expo**, conçue comme un starter pour des projets d'application mobile modernes.

Elle inclut les composants essentiels d’une app réelle : navigation, authentification, appels API, gestion d’état, stockage local, thème, accessibilité, etc.

---

## 🚀 Fonctionnalités incluses

- 🔐 Authentification (login/register avec validation)
- 📦 State management avec Zustand (ou Redux Toolkit)
- 🌐 Appels API (axios + interceptors + mock JSON)
- 🔄 Navigation stack + tabs (React Navigation)
- 💾 Stockage local (AsyncStorage)
- 🎨 Thème clair/sombre + UI responsive
- 🧪 Tests unitaires de composants
- 🔍 Accessibilité de base (labels, contrastes, navigation clavier)
- 🧹 Nettoyage des erreurs, loading states, toast de feedback

---

## 🛠️ Stack technique

- ⚛️ React Native (Expo SDK 50+)
- 🧭 React Navigation
- ⚙️ Zustand (ou Redux Toolkit)
- 📡 Axios
- 💾 AsyncStorage
- 📱 Native Base / Tailwind / React Native Paper
- 🧪 Jest + Testing Library

---

## 📁 Structure recommandée

```plaintext
mobile-starter-app/
├── assets/
├── src/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── store/
│   ├── services/
│   ├── utils/
│   ├── hooks/
│   └── theme/
├── .env
├── app.json
├── babel.config.js
└── README.md
