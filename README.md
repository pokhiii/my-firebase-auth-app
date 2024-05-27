# Firebase Auth App

## Setup

1. Create a `firebaseConfig.js` file in the root of the project with the following content:

    ```javascript
    const firebaseConfig = {
      apiKey: "YOUR_API_KEY",
      authDomain: "YOUR_AUTH_DOMAIN",
      projectId: "YOUR_PROJECT_ID",
      storageBucket: "YOUR_STORAGE_BUCKET",
      messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
      appId: "YOUR_APP_ID",
    };

    export default firebaseConfig;
    ```


## Run on localhost

1. Install `http-server` globally if you haven't already:
    ```sh
    npm install -g http-server
    ```

1. Serve the static site:
    ```sh
    http-server -p 8000 --cors
    ```
