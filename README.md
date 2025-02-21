# Ping Pong Web App

This web application is a fully-featured Ping Pong game built using modern web technologies. It incorporates real-time communication, matchmaking, user interaction, and 3D graphics for an immersive experience.

## Technologies Used

- **Backend**: Built with **NestJS** and **Socket.IO** for real-time communication.
- **Frontend**: Developed using **React** for a dynamic, responsive user interface.
- **Authentication**: Uses **JWT** (JSON Web Tokens) for secure user authentication.
- **3D Graphics**: Powered by **Three.js** for rich 3D visualizations.
- **State Management**: **React State** and context are used for efficient state management across the app.
- **Containerization**: The app is containerized using **Docker** for easy deployment and environment consistency.
- **Database**: **PostgreSQL** for data storage and management.

## Features

- **Real-Time Gameplay**: Play against others in real-time, using **Socket.IO** for smooth multiplayer interactions.
- **Matchmaking**: Automated matchmaking system to find players based on skill and availability.
- **User Accounts**: Secure sign-up and login with **JWT** for authentication.
- **3D Gameplay**: Interactive 3D game environment rendered using **Three.js** and **Blender** assets.
- **Chat System**: Integrated chat for players to communicate during games.
- **Leaderboard**: Track and view player rankings in the leaderboard.
- **Friends & Groups**: Create groups, add friends, and organize matches together.
- **Docker Support**: Set up with **Docker** for an easy-to-deploy environment.

## 🚀 Check Out the Demo in Action!  


https://github.com/user-attachments/assets/fe203c90-6eaf-4681-bccb-d5777dbd193e


## Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/pingpong-web-app.git
```

### 2. Install dependencies

```bash
npm install
```

### 4. Set up Docker

Run the `init_docker.sh` script to initialize Docker.

```bash
./init_docker.sh
```

### 5. Running PostgreSQL with Docker

Navigate to the `/postgresql` directory and run:

```bash
docker-compose up -d
```

Make sure PostgreSQL is up and running before starting the application.

### 6. Start the application

For development:

```bash
npm run start:dev
```

For production:

```bash
npm run start:prod
```


## Tests

Run unit tests:

```bash
npm run test
```

Run e2e tests:

```bash
npm run test:e2e
```

Check test coverage:

```bash
npm run test:cov
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
