# Template-mobile-app
Production-ready REST API template with  FastAPI, JWT auth, PostgreSQL and Docker
# Template Flutter App — JWT + REST API



![Flutter](https://img.shields.io/badge/Flutter-3.0-blue)




![Dart](https://img.shields.io/badge/Dart-3.0-blue)




![License](https://img.shields.io/badge/License-MIT-yellow)



Flutter mobile app template with JWT 
authentication and REST API integration.

## 🛠 Stack
- Flutter + Dart
- Riverpod (state management)
- Dio (HTTP client)
- SharedPreferences (stockage local)
- Flutter Secure Storage (JWT)

## ✅ Fonctionnalités
- [ ] Écran login / register
- [ ] JWT stocké localement
- [ ] Liste d'éléments depuis API (pagination)
- [ ] Détail d'un élément
- [ ] Création / modification / suppression
- [ ] Gestion erreurs réseau
- [ ] Loading states + feedback utilisateur
- [ ] Design responsive
- [ ] Dark mode / Light mode

## 📁 Structure
\```
template-flutter-app/
├── lib/
│   ├── screens/
│   │   ├── auth/
│   │   ├── home/
│   │   └── detail/
│   ├── widgets/
│   ├── services/
│   │   └── api_service.dart
│   ├── models/
│   ├── providers/
│   └── utils/
├── assets/
│   ├── images/
│   └── icons/
├── test/
└── README.md
\```

## ⚙️ Installation
\```bash
git clone [repo-url]
cd template-flutter-app
flutter pub get
# Configurer API_URL dans lib/core/config.dart
flutter run
\```

## 📌 Règles
- Commits en anglais
- Une branche par fonctionnalité
- PR obligatoire avant merge sur main
- Screenshots obligatoires dans le README

## 👤 Assigné à
Membre Mobile (Flutter)

## 📅 Deadline
Vendredi

## 📞 Support
Telegram : #tech-support
