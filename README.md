# SME External Environment Tracker

A comprehensive application helping small and medium enterprises (SMEs) track external factors that influence their business performance.

## Features

### Core Functionality
- **Account Management**: Create and manage company accounts with industry selection
- **Indicator Tracking**: Monitor macro indicators, news, weather, and regulations
- **Industry-Specific Suggestions**: Get automatic indicator recommendations based on your industry
- **Custom Selection**: Add, remove, and prioritize indicators manually

### Data Categories

#### 1. Macro Indicators
- GDP Growth Rate
- Inflation Rate
- Unemployment Rate
- Interest Rates
- Exchange Rates
- Consumer Confidence Index

#### 2. News
- Local and regional news aggregation
- Industry-specific news filtering
- Sentiment analysis
- Source tracking

#### 3. Weather Forecasts
- Temperature trends
- Precipitation data
- Humidity levels
- Wind speed
- Drought indices

#### 4. Regulations
- Local, regional, and national regulations
- Industry-specific compliance tracking
- Status monitoring (proposed, active, repealed)
- Effective date tracking

## Tech Stack

### Backend
- **Node.js** with Express
- **Prisma** ORM for PostgreSQL
- **JWT** authentication
- **Zod** for schema validation
- **bcrypt** for password hashing

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development
- **Tailwind CSS** for styling
- **TanStack Query** for data fetching
- **Recharts** for data visualization
- **Zustand** for state management
- **React Router** for navigation

### Database
- **PostgreSQL** for relational data storage