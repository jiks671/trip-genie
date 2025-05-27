# 📁 Trip Genie Project Structure

```
trip-genie/
├── mobile/                 # React Native Mobile App
│   ├── src/
│   │   ├── assets/        # Images, fonts, etc.
│   │   ├── components/    # Reusable UI components
│   │   ├── screens/       # Screen components
│   │   ├── navigation/    # Navigation configuration
│   │   ├── services/      # API services
│   │   ├── store/         # State management
│   │   ├── utils/         # Helper functions
│   │   └── config/        # App configuration
│   ├── android/           # Android specific files
│   └── ios/               # iOS specific files
│
├── backend/               # Node.js Backend
│   ├── src/
│   │   ├── controllers/   # Route controllers
│   │   ├── models/        # Database models
│   │   ├── routes/        # API routes
│   │   ├── services/      # Business logic
│   │   ├── utils/         # Helper functions
│   │   └── config/        # Server configuration
│   └── tests/             # Backend tests
│
├── web/                   # Next.js Web App (Optional)
│   ├── public/            # Static files
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── pages/         # Next.js pages
│   │   ├── styles/        # CSS/SCSS files
│   │   └── utils/         # Helper functions
│   └── tests/             # Frontend tests
│
├── shared/                # Shared code between platforms
│   ├── constants/         # Shared constants
│   ├── types/            # TypeScript types
│   └── utils/            # Shared utilities
│
├── docs/                  # Documentation
│   ├── BUILD_PLAN.md     # Build plan
│   ├── API.md            # API documentation
│   └── DEPLOYMENT.md     # Deployment guide
│
├── scripts/              # Build and deployment scripts
│
└── .github/             # GitHub Actions workflows
```

## 📝 Directory Descriptions

### Mobile App (`mobile/`)
- **assets/**: Static assets like images, fonts, and icons
- **components/**: Reusable UI components
- **screens/**: Full screen components
- **navigation/**: Navigation configuration and routing
- **services/**: API integration and external services
- **store/**: State management (Redux/Context)
- **utils/**: Helper functions and utilities
- **config/**: Environment and app configuration

### Backend (`backend/`)
- **controllers/**: Request handlers and business logic
- **models/**: Database models and schemas
- **routes/**: API endpoint definitions
- **services/**: Core business logic and external service integration
- **utils/**: Helper functions and utilities
- **config/**: Server configuration and environment variables

### Web App (`web/`)
- **public/**: Static files served directly
- **components/**: Reusable React components
- **pages/**: Next.js page components
- **styles/**: CSS/SCSS styles
- **utils/**: Helper functions

### Shared (`shared/`)
- **constants/**: Shared constants and enums
- **types/**: TypeScript type definitions
- **utils/**: Shared utility functions

### Documentation (`docs/`)
- **BUILD_PLAN.md**: Project build plan and roadmap
- **API.md**: API documentation
- **DEPLOYMENT.md**: Deployment instructions

### Scripts (`scripts/`)
- Build scripts
- Deployment scripts
- Database migration scripts
- Environment setup scripts

### GitHub Actions (`.github/`)
- CI/CD workflows
- Automated testing
- Deployment automation 