# Orientation Tester

Une application Flutter permettant de tester et visualiser les différents capteurs d'orientation d'un appareil mobile.

## Fonctionnalités

- Affichage des données de l'accéléromètre (x, y, z)
- Affichage des données du magnétomètre (x, y, z)
- Affichage de l'orientation du dispositif :
  - Via les capteurs natifs (azimuth, pitch, roll)
  - Via calculs mathématiques utilisant l'accéléromètre et le magnétomètre

## Configuration requise

- Flutter SDK ^3.7.2
- Un appareil mobile avec accéléromètre et magnétomètre

## Dépendances principales

- flutter_rotation_sensor: ^0.1.1
- sensors_plus: ^6.1.1

## Installation

1. Clonez le dépôt
2. Exécutez `flutter pub get` pour installer les dépendances
3. Lancez l'application avec `flutter run`

## Développement

Le projet utilise les packages suivants pour accéder aux capteurs :
- `sensors_plus` pour l'accéléromètre et le magnétomètre
- `flutter_rotation_sensor` pour les données d'orientation

## Ressources

Pour plus d'informations sur Flutter :
- [Documentation Flutter](https://docs.flutter.dev/)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
