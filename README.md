# Ninjas React Firebase Bootcamp.


## Project Structure

```
src
├── components
│   ├── App.js
│   ├── MainContainer.js
│   ├── Sidebar.js
│   ├── SignIn.js
│   ├── Slack.js
│   └── index.js
├── firebase.js
├── index.css
├── index.js
└── providers
    └── UserProvider.js
```

## Hosting the project on Firbase

- For first time users, you have to donwload the `firebase-cli`.

  ```
    npm run build
    npm i -g firebase-tools
    firebase login
    firebase deploy
  ```

- For second time users (who have already done the above steps).

  ```
    npm run build
    firebase deploy
  ```

You can read more about firebase cli [here](https://firebase.google.com/docs/cli).
