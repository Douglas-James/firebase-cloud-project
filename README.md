# Firebase Functions Project

This is a Firebase Cloud Functions project designed to handle backend logic using Google's Firebase platform. The project is automatically deployed using GitHub Actions when changes are pushed to the `main` branch.

## Features

- **Serverless Functions**: This project includes multiple serverless functions that are deployed to Firebase Cloud Functions.
- **Continuous Deployment**: Automated deployment pipeline set up using GitHub Actions.
- **CI/CD with GitHub**: Deployment of Firebase functions is triggered on every push to the `main` branch using Firebase's CLI and a secret token stored in GitHub Secrets.

## Prerequisites

To run and deploy this project locally, ensure you have the following:

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [Firebase CLI](https://firebase.google.com/docs/cli) (`npm install -g firebase-tools`)
- A Firebase project with functions enabled.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Douglas-James/firebase-cloud-project.git
   ```
