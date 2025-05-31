# Sensors Test 🚀

Bienvenue sur **Sensors Test** ! Ce projet Flutter innovant vous permet de tester et déployer une application multiplateforme, alliant performance et intégration native pour une expérience utilisateur optimale.

---

## 📖 Description

**Sensors Test** est une application Flutter exemplaire qui combine le code Flutter et l'intégration native pour offrir :
- **Multi-plateforme** : Support pour Linux, Windows, iOS et Web.
- **Intégration native avancée** : Utilisation de fichiers CMake pour configurer les composants natifs sous Linux et Windows.
- **Interface moderne** : Une UI soignée et réactive grâce à Flutter.
- **Extensibilité & Maintenance** : Architecture modulaire facilitant l'ajout de nouvelles fonctionnalités.

---

## 🔧 Prérequis

Avant de commencer, assurez-vous d'avoir installé :

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (version récente)
- [CMake](https://cmake.org/download/) (nécessaire pour la configuration native sur Linux et Windows)
- Un compilateur C++ (minGW, Visual Studio, etc.) pour la partie native
- IDE [Visual Studio Code](https://code.visualstudio.com/) avec les extensions Flutter et Dart
- Pour iOS : Xcode (macOS requis)
- Pour le Web : Un navigateur moderne

---

## 🛠️ Installation

1. **Cloner le repository** :

   ```bash
   git clone https://github.com/votre-utilisateur/sensors_test.git
   cd sensors_test
   ```

2. **Installer les dépendances Flutter** :

   ```bash
   flutter pub get
   ```

3. **Configurer les plateformes natives** :

   - **Linux/Windows :**  
     Les configurations natives se trouvent dans `sensors_tester/linux` et `sensors_tester/windows`. Consultez les fichiers `CMakeLists.txt` pour adapter la configuration à votre environnement.
   - **iOS :**  
     Ouvrez le dossier `ios/Runner` dans Xcode pour configurer et compiler l'application.
   - **Web :**  
     Le dossier `sensors_tester/web` contient la version web. Vérifiez que le `<base href>` dans le fichier [index.html](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\web\index.html) correspond à votre configuration de déploiement.

---

## 🖥️ Exécution

- **Mobile (Android/iOS) :**

   Lancez l'application en utilisant :

   ```bash
   flutter run
   ```

- **Desktop (Linux/Windows) :**

   Utilisez CMake pour configurer et compiler :
   - **Windows :**  
     Consultez [sensors_tester/windows/flutter/CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\windows\flutter\CMakeLists.txt) ou [sensors_tester/windows/runner/CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\windows\runner\CMakeLists.txt).
   - **Linux :**  
     Référez-vous au fichier [sensors_tester/linux/flutter/CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\linux\flutter\CMakeLists.txt) pour les instructions spécifiques.

- **Web :**

   Exécutez l'application web en lançant :

   ```bash
   flutter run -d chrome
   ```

*Astuce 💡 : Testez l'application sur différentes plateformes pour garantir une expérience cohérente et performante !*

---

## 📋 Structure du Projet

```
sensors_test/
├── ios/                    # Configuration iOS et Storyboards (ex. [Main.storyboard](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\ios\Runner\Base.lproj\Main.storyboard))
├── sensors_tester/         # Application Flutter principale
│   ├── lib/                # Code source Flutter (ex. [main.dart](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\lib\main.dart))
│   ├── linux/              # Configuration native pour Linux
│   │   └── flutter/        # Fichiers CMake pour Flutter sous Linux
│   ├── windows/            # Configuration native pour Windows
│   │   ├── flutter/        # Fichiers CMake pour Flutter sous Windows
│   │   └── runner/         # Runner Windows (ex. [CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\windows\runner\CMakeLists.txt))
│   └── web/                # Application Web (ex. [index.html](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\sensors_tester\web\index.html))
├── flutter/                # Librairies et outils supplémentaires Flutter
├── runner/                 # Configurations complémentaires pour l'application Flutter
└── README.md               # Documentation du projet
```

---

## 🎯 Objectifs du Projet

- **Éducation & Démonstration :**  
  Montrer l'intégration entre Flutter et du code natif sur diverses plateformes.
- **Extensibilité :**  
  Une architecture pensée pour faciliter l'ajout de nouvelles fonctionnalités.
- **Performance :**  
  Utilisation judicieuse des ressources natives pour garantir une performance optimale.

---

## 📚 Ressources Supplémentaires

- [Documentation Flutter](https://docs.flutter.dev/) 📘
- [Tutoriel CMake](https://cmake.org/cmake/help/latest/guide/tutorial/index.html) 🔨
- [Guide de Développement Multiplateforme](https://flutter.dev/desktop) 🌐

---

## 👥 Contribuer

Les contributions sont les bienvenues ! Voici comment contribuer :

1. Forkez le projet.
2. Créez une branche avec `git checkout -b feature/amélioration`.
3. Commitez vos changements avec `git commit -am 'Ajout d’une fonctionnalité'`.
4. Poussez votre branche `git push origin feature/amélioration`.
5. Ouvrez une Pull Request.

---

## 📄 Licence

Ce projet est sous [Licence MIT](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\LICENSE). Consultez ce fichier pour plus de détails.

---

## 🚀 Lancer les tests

Pour exécuter les tests unitaires :

```bash
flutter test
```

*Assurez-vous que toutes les fonctionnalités fonctionnent comme prévu avant de pousser vos changements !*

---

N'hésitez pas à consulter les fichiers de configuration spécifiques à chaque plateforme et à nous contacter pour toute question ou suggestion. Bon codage ! 💻✨
