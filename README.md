# RegisterYourFuture

A simple web app for collecting and viewing event registrations.

## Installation

1. Install dependencies:
   ```
   npm install
   ```
2. Start the local development server:
   ```
   npm start
   ```

## Environment Variables

The project uses Firebase for data storage. Configure your Firebase credentials as environment variables before running the app. Create a `.env` file in the project root or export these variables in your shell:

```
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_DATABASE_URL=https://your_project-default-rtdb.firebaseio.com
FIREBASE_PROJECT_ID=your_project
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```

## Usage

1. Open `http://localhost:5000` in your browser.
2. Fill out the registration form and submit.
3. View submitted registrations at `http://localhost:5000/seeRegistrations.html`.
