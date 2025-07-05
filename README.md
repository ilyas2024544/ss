## 📁 Structure du projet

```
projet-psah/
├── prisma/
│   ├── schema.prisma       # Schéma de la base de données
│   └── migrations/         # Migrations de la base de données
│   └── seeder/             # Un dossier qui contient les fichiers de seeders spécialiser 
│   seed.js                 # Script qui insert des donneé dans la base pour tester 
├── src/
│   ├── controllers/        # Contrôleurs REST pour chaque ressource
│   ├── middleware/         # Middlewares (auth, validation, etc.)
│   ├── models/             # Modèles et logique métier
│   ├── routes/             # Définition des routes de l'API
│   ├── services/           # Services et logique métier complexe
│   ├── utils/              # Utilitaires et fonctions d'aide
│   ├── config/             # Configuration de l'application
│   ├── swagger/            # Documentation Swagger
│   └── server.js           # Point d'entrée de l'application
├── tests/
│   ├── models/             # Tests pour les modèles
│   ├── controllers/        # Tests pour les contrôleurs
│   ├── middleware/         # Tests pour les middlewares
│   └── routes/             # Tests pour les routes
├── __mocks__/              # Mocks pour les tests Jest
├── uploads/                # Dossier pour les fichiers uploadés (images, etc.)
├── .env                    # Variables d'environnement (à créer)
├── jest.config.js          # Configuration de Jest pour les tests
├── jest.setup.js           # Configuration initiale pour les tests
├── jest.teardown.js        # Nettoyage après les tests
├── jsdoc.conf.json         # Configuration pour la génération de documentation
├── eslint.config.js        # Configuration ESLint
├── package.json
└── README.md
```
