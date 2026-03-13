# paywalan-poc
# PayWalan - Solution d'interopérabilité des paiements par QR code au Cameroun

## 🎯 Problématique
Au Cameroun, plusieurs solutions de paiement mobile coexistent (Orange Money, MTN Money, CampostMoney, Kang...). Un client ne peut pas payer un commerçant qui n'accepte pas son opérateur. **PayWalan** résout ce problème.

## 💡 Solution
Une passerelle de paiement universelle qui permet à n'importe quel client de payer n'importe quel commerçant via un QR code unique, indépendamment de l'opérateur utilisé.

## 🛠️ Architecture technique (en cours)
- Backend : API REST avec Node.js/Express
- Frontend : Application mobile (React Native)
- Base de données : MongoDB
- Sécurité : Authentification JWT, chiffrement SSL

## 📁 Structure du projet
paywalan-poc/
├── backend/ # API et logique métier
├── mobile-app/ # Application client/commerçant
├── docs/ # Documentation
└── README.md # Présentation du projet
