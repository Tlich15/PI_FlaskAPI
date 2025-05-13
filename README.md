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



=> API Hugging Face:
Utilise le modèle gpt2 (ou tout autre modèle compatible avec text generation).

Exemple de requête POST :

POST http://localhost:5001/api/chat
{
  "message": "Bonjour, que peux-tu faire ?"
}


🧪 Exemple de message Angular → Flask
typescript
Copier
Modifier
this.http.post('http://localhost:5001/api/chat', {
  message: "Bonjour"
}).subscribe(res => {
  console.log(res);
});
