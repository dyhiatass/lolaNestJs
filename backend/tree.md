src/
├── app.controller.spec.ts
├── app.controller.ts
├── app.module.ts
├── app.service.ts
├── main.ts
├── config/                        # Configuration et variables d'environnement
│   └── config.module.ts           # Module de configuration
├── modules/                       # Dossier pour les différents modules de votre application
│   ├── user/                     # Module pour les utilisateurs
│   │   ├── user.controller.ts    # Contrôleur pour les utilisateurs
│   │   ├── user.service.ts       # Service pour les utilisateurs
│   │   ├── user.module.ts        # Module pour les utilisateurs
│   │   ├── user.schema.ts        # Schéma Mongoose pour les utilisateurs
│   │   ├── dto/
│   │   │   ├── create-user.dto.ts  # DTO pour la création d'un utilisateur
│   │   │   └── update-user.dto.ts  # DTO pour la mise à jour d'un utilisateur
│   ├── product/                  # Module pour les produits
│   │   ├── product.controller.ts # Contrôleur pour les produits
│   │   ├── product.service.ts    # Service pour les produits
│   │   ├── product.module.ts     # Module pour les produits
│   │   ├── product.schema.ts     # Schéma Mongoose pour les produits
│   │   ├── dto/
│   │   │   ├── create-product.dto.ts  # DTO pour la création d'un produit
│   │   │   └── update-product.dto.ts  # DTO pour la mise à jour d'un produit
│   └── auth/                     # Module pour l'authentification
│       ├── auth.controller.ts    # Contrôleur pour l'authentification
│       ├── auth.service.ts       # Service pour l'authentification
│       ├── auth.module.ts        # Module pour l'authentification
│       ├── auth.schema.ts        # Schéma Mongoose pour l'authentification
│       ├── dto/
│       │   ├── login.dto.ts      # DTO pour la connexion
│       │   └── register.dto.ts   # DTO pour l'inscription
│       └── strategies/
│           └── jwt.strategy.ts   # Stratégie JWT pour l'authentification
├── shared/                      # Dossier pour les éléments partagés
│   └── filters/
│       └── http-exception.filter.ts # Filtre pour les exceptions HTTP
└── common/                      # Dossier pour les classes et utilitaires communs
    └── utils/
        └── logger.service.ts     # Service de logging
