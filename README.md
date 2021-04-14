Hey there 👋, visit [Quick-Notes](https://quick-notes-1748a.web.app/) for live demo.

## How to run locally

1. Clone this repo

2. Setup `.env` file like this (You can find these credentials in your firebase project setup guide).

```
REACT_APP_API_KEY=""
REACT_APP_AUTH_DOMAIN=""
REACT_APP_DATABASE_URL=""
REACT_APP_PROJECT_ID=""
REACT_APP_STORAGE_BUCKET=""
REACT_APP_MESSAGE_SENDER_ID=""
REACT_APP_APP_ID=""
REACT_APP_MEASUREMENT_ID=""
```

3. To install dependencies run,

```
$ npm install
```

4. To start on `localhost`

```
$ npm start
```

This app is using firebase, Material-UI. I've used firestore as database and firebase auth for authenticating users.

**Note:**- This app uses Web Speech API which is provided by browser. Current Voice search works in `chrome` browser only.
