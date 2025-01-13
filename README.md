# Custom BI Dashboard

A customizable business intelligence (BI) dashboard for visualizing and analyzing data in real time. Built with a modern tech stack: Node.js, Express, and React.

## Features
- **Interactive Dashboards**: Create and view custom dashboards with charts and tables.
- **Data Integration**: Connect to APIs, databases (e.g., MySQL, MongoDB), or file uploads (CSV, Excel).
- **Dynamic Visualizations**: Line charts, bar charts, pie charts, and more using Chart.js or D3.js.
- **Authentication**: (Optional) User authentication for private dashboards.
- **Responsive Design**: Optimized for mobile and desktop.

## Tech Stack
- **Frontend**: React, Axios, Chart.js/D3.js
- **Backend**: Node.js, Express
- **Database**: MySQL (configurable)

## Installation

### Prerequisites
- Node.js >= 18.x
- MySQL (optional: use `.env` to configure)

### Clone the Repository
```bash
git clone https://github.com/yourusername/custom-bi-dashboard.git
cd custom-bi-dashboard
```

### Setup Backend
1. Navigate to the `backend/` folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file:
   ```bash
   cp .env.example .env
   ```
4. Start the server:
   ```bash
   npm start
   ```

### Setup Frontend
1. Navigate to the `frontend/` folder:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```

## Usage
1. Access the frontend at [http://localhost:3000](http://localhost:3000).
2. Use the backend API at [http://localhost:5000](http://localhost:5000) for data fetching.

## Contributing
Contributions are welcome! Please see the `CONTRIBUTING.md` file for guidelines.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
