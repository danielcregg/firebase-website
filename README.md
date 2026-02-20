# Firebase Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A simple multi-page website hosted on Firebase Hosting with Firebase Analytics and Firestore integration.

## Overview

This project demonstrates how to set up and deploy a basic website using Firebase Hosting. It includes a landing page with navigation to multiple sub-pages, Firebase Analytics for tracking user activity, and Firestore security rules for database access control.

## Features

- Static multi-page website served via Firebase Hosting
- Firebase Analytics integration for visitor tracking
- Firestore database with configurable security rules
- Single-page application URL rewriting support
- Clean, lightweight HTML structure

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [Firebase CLI](https://firebase.google.com/docs/cli) (`npm install -g firebase-tools`)
- A Firebase project (create one at [Firebase Console](https://console.firebase.google.com/))

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/firebase-website.git
   cd firebase-website
   ```

2. Log in to Firebase:
   ```bash
   firebase login
   ```

3. Initialize or link your Firebase project:
   ```bash
   firebase use --add
   ```

### Usage

To serve the site locally for development:
```bash
firebase serve
```

To deploy the site to Firebase Hosting:
```bash
firebase deploy
```

Once deployed, the site will be available at your Firebase Hosting URL.

## Tech Stack

- **HTML5** - Page structure and content
- **JavaScript (ES Modules)** - Firebase SDK initialization and analytics
- **Firebase Hosting** - Static site hosting and URL rewrites
- **Firebase Analytics** - User activity tracking
- **Cloud Firestore** - Database with security rules

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
