# dataview-web-app

A data visualization web application for displaying KPIs, visual reports, and interactive charts.

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: Node.js/Express + Prisma
- **Design**: Figma ([View Design](https://www.figma.com/design/fzvMscSRhEdiO9Cqj77mcv/30--Chart-UI-Components-%7C-BRIX-Templates--Community-?node-id=15-4&t=r0tdqiHATOC6zXDN-1))

## Project Structure

```
dataview-web-app/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- responsive design
- real-time updates
- customizable dashboards
- alerting and notifications
- user management

## API Endpoints

- `GET /api/dashboard` - Retrieve a list of available dashboards
- `GET /api/dashboard/:id` - Retrieve a specific dashboard by ID
- `POST /api/dashboard` - Create a new dashboard
- `PUT /api/dashboard/:id` - Update a specific dashboard by ID
- `DELETE /api/dashboard/:id` - Delete a specific dashboard by ID
- `GET /api/widgets` - Retrieve a list of available widgets
- `POST /api/widgets` - Create a new widget

## License

MIT
