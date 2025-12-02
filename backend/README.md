# Data Visualization Backend
## Getting Started
1. Install dependencies: `npm install`
2. Create a `.env` file with your database URL and secret key
3. Run the application: `npm start`
## API Endpoints
### Dashboards
* `GET /api/dashboards` - Retrieve a list of available dashboards
* `GET /api/dashboards/:id` - Retrieve a specific dashboard by ID
* `POST /api/dashboards` - Create a new dashboard
* `PUT /api/dashboards/:id` - Update a specific dashboard by ID
* `DELETE /api/dashboards/:id` - Delete a specific dashboard by ID
### Widgets
* `GET /api/widgets` - Retrieve a list of available widgets
* `POST /api/widgets` - Create a new widget