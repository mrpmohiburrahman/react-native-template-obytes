<p align="center">
    <img alt="React Native Template Obytes" src="https://raw.githubusercontent.com/obytes/react-native-template-obytes/master/logo.png" width="200" />

</p>
<h1 align="center">
  React Native Template Obytes
</h1>

A simple React Native Template based on Obytes Mobile tribe best practices.

## Features

- ✅ Typescript by default based on official Typescript template
- ✅ Generate App Icon and Splash screen
- ✅ React Navigation Pre installed
- ✅ A clean project structure based on our experience with React Native
- ✅ Minimal UI kit Setup using restyle
- ✅ A good approach to handel forms based on react-hook-form
- ✅ A complete setup to Handel Errors
- ✅ Handel environnement variables with react-native-env
- ✅ Localization
- More ...

## Usage

```
npx react-native init MyApp --template https://github.com/obytes/react-native-template-obytes
```

## App Icon & Splash screen

Replace App logo template `logo.png` with your logo under `assets` folder

Run the following command to generate App icons assets :

```
react-native set-icon  --path ./assets/logo.png --background "#FFF"

```

> For android icon Make sure to provide a logo with more padding and generate a new app icon for android :

```
react-native set-icon  --platform android  --path ./assets/android_logo.png --background "#FFF"

```

To generate a standard splash screen using bootsplash package.

```sh
yarn react-native generate-bootsplash assets/logo.png \
  --background-color=FFFFFF \
  --logo-width=150 \
  --assets-path=assets
```

More details [how to customize App Icon and Splash screen](https://handbook.obytes.com/docs/mobile/generate-app-icon)

## Read More About Modules

👉 https://handbook.obytes.com/docs/mobile/get-started

## 💻 Contributing

TO BE DONE
