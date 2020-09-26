# Electron React

A boilderplate [Electron](https://github.com/electron/electron) app with [React](https://github.com/facebook/react). This app was created using [create-react-app](https://github.com/facebook/create-react-app).

(Electron Builder)[https://github.com/electron-userland/electron-builder] is being used for building and packaging the app. Currently only includes configuration for Linux.

## Scripts

### `npm start`

Starts the react app on `http://localhost:3000` and runs an electron app which loads this URL.

### `npm run dev`

Starts the react app without electron. Currently no hot reload is setup. So, running `npm start` then making changes won't reload the app and you would have to manually reload to update changes. So, prefer to use this while developing the app. The app would run fine on electron as long as it is responsive to screen sizes.

### `npm run build`

Builds the app for production and creates an app image.
