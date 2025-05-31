# Sensors Test 🚀

> Une application Flutter moderne pour tester les capteurs sur différentes plateformes.

[![Flutter Version](https://img.shields.io/badge/Flutter-3.x-blue.svg)](https://flutter.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📖 Vue d'ensemble

**Sensors Test** est une application Flutter innovante qui démontre l'intégration native des capteurs sur plusieurs plateformes :

- 📱 **Multi-plateforme** - Android, iOS, Linux, Windows et Web
- 🔌 **Intégration native** - Accès optimisé aux capteurs système
- 🎨 **Interface moderne** - Design épuré et responsive
- 🛠️ **Architecture robuste** - Code modulaire et maintenable

---

## ⚡ Fonctionnalités

- 🔄 Lecture en temps réel des capteurs
- 📊 Visualisation des données
- ⚙️ Configuration personnalisable
- 💾 Exportation des données
- 🌐 Support multi-langues

---

## 🔧 Prérequis

- [Flutter](https://flutter.dev/docs/get-started/install) (version >= 3.0.0)
- [Visual Studio Code](https://code.visualstudio.com/) avec extensions Flutter & Dart
- [CMake](https://cmake.org/download/) (≥ 3.14.0)
- [Git](https://git-scm.com/)

**Selon la plateforme cible :**
- 🪟 Windows : Visual Studio ou MinGW
- 🐧 Linux : GCC et bibliothèques de développement
- 🍎 iOS : Xcode (macOS requis)
- 🌐 Web : Chrome ou Edge

---

## 🚀 Installation

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/votre-nom/sensors_test.git
   cd sensors_test
   ```

2. **Installer les dépendances :**
   ```bash
   flutter pub get
   ```

3. **Configuration native :**

   - **Windows/Linux :**  
     Les fichiers CMake sont dans `windows/` et `linux/`. 

   - **iOS :**  
     ```bash
     cd ios
     pod install
     ```

---

## 💻 Développement

**Lancer en mode debug :**
```bash
flutter run
```

**Build pour production :**
```bash
flutter build <plateforme>
```
Où `<plateforme>` = `apk`, `ios`, `windows`, `linux`, `web`

---

## 📁 Structure du Projet

```
sensors_test/
├── lib/
│   ├── models/         # Modèles de données
│   ├── services/       # Services (capteurs, API...)
│   ├── ui/            # Widgets et écrans
│   └── utils/         # Utilitaires
├── native/            # Code natif spécifique
│   ├── windows/       # ⊞ Configuration Windows
│   └── linux/         # 🐧 Configuration Linux
└── test/             # Tests unitaires et d'intégration
```

---

## 🧪 Tests

**Exécuter les tests :**
```bash
flutter test
```

**Tests avec couverture :**
```bash
flutter test --coverage
```

---

## 📚 Documentation

- [Wiki du projet](https://github.com/votre-nom/sensors_test/wiki)
- [Guide API](docs/API.md)
- [Guide contribution](CONTRIBUTING.md)

---

## 🤝 Contribuer

Les contributions sont bienvenues ! 

1. Fork le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add: AmazingFeature'`)
4. Push sur la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

---

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## 👥 Contact

- **Auteur** : Louis Isaac DIOUF
- **Email** : [contact@example.com](mailto:contact@example.com)
- **Twitter** : [@VotreCompte](https://twitter.com/VotreCompte)

---

*Fait avec ❤️ par la communauté Flutter*
