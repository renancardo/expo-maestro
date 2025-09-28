# React Native Expo App with Maestro E2E Testing 👋

This is a simple React Native project built with [Expo](https://expo.dev) and configured with [Maestro](https://maestro.dev) for end-to-end testing. The project was created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Maestro E2E Testing

This project comes pre-configured with Maestro for end-to-end testing. To get started with Maestro:

1. **Install Maestro** following the official installation guide:
   - [Installing Maestro](https://docs.maestro.dev/getting-started/installing-maestro)

2. **Learn about E2E testing with Expo and Maestro**:
   - [EAS Workflows Examples - E2E Tests](https://docs.expo.dev/eas/workflows/examples/e2e-tests/)

3. **Run Maestro tests**:
   ```bash
   maestro test maestro/
   ```

The `maestro/` directory contains the test files for your app's end-to-end testing scenarios.

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
