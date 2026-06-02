# CRM - Customer Relationship Management System

A modern, scalable CRM MVP built with production-ready architecture.

## Features

- **Contact Management**: Create, read, update, and delete customer contacts
- **Lead Tracking**: Manage sales leads with pipeline stages
- **Interaction History**: Track all customer interactions and communications
- **Task Management**: Assign and manage tasks related to contacts
- **Dashboard**: Key metrics and performance indicators
- **User Authentication**: Role-based access control (Admin, Manager, User)
- **Activity Timeline**: Complete audit trail of all activities

## Tech Stack

- **Backend**: Node.js / Express.js
- **Frontend**: React.js / TypeScript
- **Database**: PostgreSQL
- **Real-time**: WebSocket support
- **API**: RESTful + GraphQL
- **Testing**: Jest, Vitest
- **Deployment**: Docker, Docker Compose

## Project Structure

```
crm-/
├── backend/          # Node.js API server
│   ├── src/
│   │   ├── models/   # Database models
│   │   ├── routes/   # API routes
│   │   ├── controllers/ # Business logic
│   │   ├── middleware/ # Auth, validation
│   │   ├── services/ # Business services
│   │   └── utils/    # Utilities
│   ├── tests/
│   └── Dockerfile
├── frontend/         # React application
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── public/
│   └── Dockerfile
├── database/         # Database migrations & seeds
├── docker-compose.yml
└── .env.example
```

## Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 14+
- Docker & Docker Compose (optional)

### Development

1. Clone the repository
2. Copy `.env.example` to `.env` and configure
3. Install dependencies
4. Run database migrations
5. Start the development server

### Production Deployment

See deployment documentation in `/docs/deployment.md`

## API Documentation

API documentation is available at `/api/docs` when the server is running.

## Contributing

See CONTRIBUTING.md for guidelines.

## License

MIT
