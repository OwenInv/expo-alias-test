# Activity Alias Issue

To test the specific scenario, please run the following steps:
1. Install node modules (`npm i`)
2. Run `npx expo run:android`.
   - At this point, you should get an error from the CLI stating that the AndroidManifest.xml is missing a runnable activity.
3. Run `npx patch-package`.
4. Run step two again, this time it shouldn't give an error and proceed to build and install the app.

> I'm making the assumption that you have already got Android Studio up and running, if not look [here](https://docs.expo.dev/get-started/set-up-your-environment/).