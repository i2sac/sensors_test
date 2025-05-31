# Sensors Test 🚀

Bienvenue sur **Sensors Test** ! Ce projet Flutter innovant est conçu pour vous aider à démarrer rapidement avec une application Flutter robuste et multi-plateforme.

---

## 📖 Description

Sensors Test est une application Flutter exemplaire qui intègre :
- **Multi-plateforme** : support de Linux, Windows et iOS.
- **Intégration native** : configuration spécifique pour chacune des plateformes grâce aux scripts CMake dédiés.
- **Interface moderne** : UI soignée avec Storyboards pour iOS et configurations optimisées pour Windows/Linux.
- **Plugins Flutter** : construction et gestion des plugins pour enrichir les fonctionnalités.

---

## 🔧 Prérequis

Assurez-vous d'avoir installé :

- [Flutter SDK](https://docs.flutter.dev/get-started/install) version à jour.
- [CMake](https://cmake.org/download/) pour la configuration native (Windows & Linux).
- IDE [Visual Studio Code](https://code.visualstudio.com/) avec les extensions Flutter et Dart.
- Compilateur C++ (minGW, Visual Studio ou autre, selon votre plateforme) pour la partie native.
- Xcode pour le développement iOS (macOS requis pour la compilation iOS).

---

## 🛠️ Installation

1. **Clonez le repository** :

   ```bash
   git clone https://github.com/votre-utilisateur/sensors_test.git
   cd sensors_test
   ```

2. **Installez les dépendances Flutter** :

   ```bash
   flutter pub get
   ```

3. **Configuration de la plateforme native :**

   - **Linux/Windows :**  
     Le projet utilise CMake pour la configuration des parties natives. Les fichiers se trouvent dans les dossiers `linux` et `windows`. Assurez-vous d'avoir CMake installé et configurez votre environnement en fonction de votre plateforme.
   - **iOS :**  
     Ouvrez le dossier `ios/Runner` dans Xcode pour configurer et compiler l'application pour iOS.

---

## 🖥️ Exécution

- **Mobile (Android/iOS) :**

   Utilisez la commande Flutter classique :

   ```bash
   flutter run
   ```

- **Desktop (Linux/Windows) :**

   Compilations via CMake :
   - **Windows :** Lisez le fichier [windows/CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\windows\CMakeLists.txt) pour la configuration des installations via Visual Studio.
   - **Linux :** Consultez [linux/CMakeLists.txt](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\linux\CMakeLists.txt) pour obtenir les instructions spécifiques.

*Astuce 💡 : La compilation multi-plateforme offre un excellent moyen de tester l'application dans divers environnements pour garantir une expérience utilisateur homogène.*

---

## 📋 Structure du Projet

```
sensors_test/
├── ios/                  # Configuration iOS et Storyboards (ex: [Main.storyboard](c:\Users\7MAKSACOD PC\Documents\repositories\github\sensors_test\ios\Runner\Base.lproj\Main.storyboard))
├── linux/                # Scripts CMake et configuration pour Linux
├── windows/              # Scripts CMake et configuration pour Windows
├── flutter/              # Librairie et outils Flutter
├── runner/               # Configuration de l'application Flutter
└── README.md             # Documentation du projet
```

---

## 🎯 Objectifs du Projet

- **Éducation & Démonstration :**  
  Fournir un exemple concret d’intégration entre Flutter et du code natif pour différentes plateformes.

- **Extensibilité :**  
  Permettre une expansion rapide et l’ajout de nouvelles fonctionnalités grâce à une architecture modulaire et bien documentée.

- **Performance :**  
  Optimisé pour offrir des performances optimales sur chacune des plateformes cibles grâce à une utilisation judicieuse des ressources natives.

---

## 📚 Ressources Supplémentaires

- [Documentation Flutter](https://docs.flutter.dev/) 📘
- [CMake Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html) 🔨
- [Guide de Développement Multiplateforme](https://flutter.dev/desktop) 🌐

---

## 👥 Contribuer

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet.
2. Créez votre branche (`git checkout -b feature/amélioration`).
3. Commitez vos changements (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`).
4. Poussez vers la branche (`git push origin feature/amélioration`).
5. Ouvrez une Pull Request.

---

## 📄 Licence

Ce projet est sous [Licence MIT](LICENSE). Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## 🚀 Lancer les tests

Pour exécuter les tests unitaires :

```bash
flutter test
```

*Facile et efficace pour s'assurer que tout fonctionne comme prévu !*

---

N'hésitez pas à consulter les fichiers de configuration spécifiques pour chaque plateforme et à nous contacter pour toute question ou suggestion. Bon codage ! 💻✨
