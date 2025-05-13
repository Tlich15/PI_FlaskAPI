# PI_FlaskAPI

Chatbot IA avec Flask & Angular
Ce projet est une application complète de chatbot IA construite avec :

Flask pour le backend et l'intégration avec Hugging Face (modèle GPT2).

Angular pour le frontend (interface utilisateur du chatbot).

Une interface d’administration (à compléter selon votre implémentation).

🧠 Fonctionnalités
Intégration d’un chatbot intelligent via Hugging Face.

Interface utilisateur interactive en Angular.

API REST sécurisée avec Flask.

Support de CORS pour les communications cross-domain.

Système d’administration (ajouter utilisateurs, logs, etc. si applicable).

📦 Structure du projet
bash
Copier
Modifier
/chatbot-project
│
├── backend/
│   ├── app.py                 # API Flask
│   └── requirements.txt       # Dépendances Python
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   └── chat-bot/      # Composant Angular pour le chatbot
│   └── angular.json
│
├── admin/                     # Interface admin (ex: Angular ou autre)
│   └── ...
│
└── README.md
