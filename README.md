# Cookie Clicker Shared

## Overview

Cookie Clicker Shared is a collaborative twist on the classic idle game where everyone can contribute in a single session. Inspired by the top comment from [this video](https://www.youtube.com/watch?v=8pGyUW_UTJ0), the aim of this project is to create a multiplayer experience where players work together to maximize cookie production.

## Technology Stack

- **Frontend**: React
- **Backend**: Node.js (using WebSockets for real-time interaction)

## Features

- **Single Session Gameplay**: All players share the same cookie count and work collaboratively.
- **Real-Time Updates**: Instantaneous updates via WebSockets to ensure smooth gameplay.
- **Unlock Upgrades**: Players can work together to unlock various upgrades and achievements.

## Setup

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/jonesjughead/cookie-clicker-shared.git
   cd cookie-clicker-shared
   ```

2. Install dependencies for both the frontend and backend:
   ```bash
   # For frontend
   cd client
   npm install

   # For backend
   cd server
   npm install
   ```

3. Run the application:
   ```bash
   # Start the backend
   cd server
   npm start

   # Start the frontend
   cd client
   npm start
   ```

## Contribution

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.
