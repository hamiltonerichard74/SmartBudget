# SmartBudget

[![GitHub stars](https://img.shields.io/github/stars/hamiltonerichard74/SmartBudget?style=social)](https://github.com/hamiltonerichard74/SmartBudget/stargazers)  
[![License](https://img.shields.io/github/license/hamiltonerichard74/SmartBudget)](LICENSE)

---

## Overview

SmartBudget is a sleek and intuitive personal budgeting application designed to simplify your financial management. Integrating smart categorization and goal-setting features, it helps you track expenses, set savings goals, and visualize your financial health with ease.

## Features

- Smart expense categorization using AI-assisted tagging
- Customizable budgeting and saving goals
- Interactive spending analytics and charts
- Recurring expense tracking and reminders
- Export reports in PDF and CSV formats
- Responsive design for mobile and desktop

## Tech Stack

- Frontend: React.js with Redux
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Charts: Chart.js

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hamiltonerichard74/SmartBudget.git
   cd SmartBudget
   ```
2. Install dependencies for backend and frontend:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```
3. Set up environment variables:
   Create a `.env` file in the `backend` folder with the following:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```
4. Start the backend server:
   ```bash
   cd backend
   npm start
   ```
5. Start the frontend application:
   ```bash
   cd ../frontend
   npm start
   ```

## Usage

- Visit `http://localhost:3000` after starting the frontend app.
- Sign up or log in using your credentials.
- Add expenses and categorize them with smart suggestions.
- Set monthly budgets and savings goals.
- Monitor your spending habits through detailed charts.

## Screenshots

![Dashboard Placeholder](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Expenses Overview Placeholder](https://via.placeholder.com/800x400?text=Expenses+Overview+Screenshot)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository [here](https://github.com/hamiltonerichard74/SmartBudget/fork).
2. Create a new feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a Pull Request describing your changes.

Please follow the code style and include tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

[hamiltonerichard74](https://github.com/hamiltonerichard74)

Feel free to connect and explore more projects on my [GitHub profile](https://github.com/hamiltonerichard74).
