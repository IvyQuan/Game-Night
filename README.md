# Game Night
A web app for hosting game nights: create a session, add players, play 3 games, and track scores on a live leaderboard.

**Live demo:** https://drive.google.com/file/d/1ziNoWLZbALkj62h5s0NgLBoq0aFA71cU/view 

## Features
- Create a game session by entering player names
- Play Wavelength, 2 truths 1 lie, and triva; points update automatically
- Each game features AI generation options (e.g. generate a question and possible answers for trivia or make your own)
- End-of-game flow that saves results and updates the leaderboard
- Persistent leaderboard backed by Firestore

## Tech Stack
- **Frontend:** React, TypeScript, Vite, Mantine UI, React Router
- **Backend:** Node.js, Express (REST API)
- **Database:** Firebase Firestore

## Architecture
React frontend → Express REST API → Firestore

It features the following:

-   [Mantine UI Library](https://mantine.dev/) for prefabricated components
-   [Lucide Icon Library](https://lucide.dev/) for prefabricated icons
-   [React Router](https://reactrouter.com/) for routing

It also utilizes the following core libraries:

-   React
-   Vite
-   SWC![alt text](image.png)
-   TypeScript
-   Pnpm
-   
## Getting Started
**Prerequisites:** Node.js, pnpm, a Firebase project

1. Clone the repo and run `pnpm install` in both the root and `server/`
2. Add your Firebase credentials to `server/.env` (see `.env.example`)
3. Start the server: `cd server && node index.js`
4. Start the frontend: `pnpm dev`
5. Open `http://localhost:5173`


