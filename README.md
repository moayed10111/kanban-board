# Kanban Board

## Overview

Kanban Board is a sophisticated task management application designed to enhance your productivity by visualizing your workflow, limiting work-in-progress, and maximizing efficiency. It leverages the Kanban methodology to manage tasks through an intuitive visual board.

## Features

- User authentication (Log in)
- Create, edit, and delete tasks
- Drag and drop tasks between columns
- Manage multiple boards


## Tech Stack

- **Backend:** Node.js, Express, Sequelize (PostgreSQL)
- **Frontend:** React, CSS/Bootstrap
- **Other:** JWT (Authentication)

## Installation

### Prerequisites

- Node.js
- PostgreSQL
- Git

### Steps
1. Clone the repo:
   ```bash
   git clone git@github.com:moayed10111/kanban-board.git
   cd kanban-board-app

2. Install dependencies:
   ```bash
   npm install 

3. Set up environment variables in .env:
    ```bash
    DB_NAME=kanban_db
    DB_USER=postgres
    DB_PASSWORD=(your postgress password)
    JWT_SECRET_KEY=(your jwt key)
    ```

4. Seed your data:
    ```bash
    npm run seed

5. Start your app:
    ```bash
    npm run start:dev

6. Open your browser and navigate to `http://localhost:3000` to see the application in action.


 ## Contributing

    We welcome contributions! Please follow these steps:

    1. Fork the repository.
    2. Create a new branch (`git checkout -b feature/YourFeature`).
    3. Commit your changes (`git commit -m 'Add some feature'`).
    4. Push to the branch (`git push origin feature/YourFeature`).
    5. Open a pull request.


## Usage

- log in to start using the app.
- Create boards and tasks, then move tasks between columns.

## License
  This project it licensed under [MIT](https://opensource.org/licenses/MIT).
  

## Questions
If you have any questions or would like to git in touch, please feel free to contact
me via email or visit my GitHub profile.

-Email: moayed10111@gmail.com

-GitHub: https://github.com/moayed10111
