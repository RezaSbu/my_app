# My App 📱

A full-stack web app built with **React + Firebase** featuring user authentication and surveys.

## Overview

A simple but complete application with:

- **Register / Login** — Firebase Authentication
- **Survey** — form submission flow
- **Backend API** — Node.js + Express endpoints

## Tech Stack

- React
- Firebase (auth, database)
- Node.js + Express

## Features

| Endpoint | Description |
|---|---|
| `POST /register` | Create a user with Firebase Auth |
| `POST /login` | Sign in an existing user |
| `POST /survey` | Submit survey data |

## Getting Started

1. Configure your Firebase project credentials in `firebase.js` (API key, auth domain, database URL)
2. Install dependencies
3. Run the Node server and the React app

## Note

The repository uses placeholder credentials (`<API_KEY>`, `<AUTH_DOMAIN>`, `<DATABASE_URL>`) — replace them with your own Firebase config. Never commit real API keys.
