
## About
Appium is a test automation framework which drives iOS, Android, and Desktop apps using the WebDriver protocol. In this repository, a demo Android app will be tested on an Android simulator.

## Setup
1. There are two ways to install Appium, one is using `npm`:
    ```sh
    npm install -g appium
    ```
    and the other is installing the [Appium-Desktop](https://github.com/appium/appium-desktop).

2. Start Appium server.

3. Run an Android Siumlator.

4. Install the Node.js modules:
    ```sh
    cd /path/of/this/repo
    npm install
    ```

## Run Test
```sh
npm test
```

## Future Work
- Dockerize the Android simulator.
- Dockerize this application.
- Integrate with CI system.
- Test iOS, Cordova, React Native, web, Electron app.
- Test with real devices.

## Reference
- http://appium.io/docs/en/about-appium/getting-started/?lang=zh
- https://medium.com/@kentchen_tw/appium-1-app-%E6%B8%AC%E8%A9%A6%E8%87%AA%E5%8B%95%E5%8C%96%E6%A1%86%E6%9E%B6-c929d8f7a439
- https://hub.docker.com/r/quamotion/appium-docker-ios
- https://segmentfault.com/a/1190000020103800
- https://blog.patw.me/archives/1326/reactnative-ios-android-e2e-testing-with-appium/
- https://github.com/asialgearoid/cordova-appium-example
- https://github.com/kotarella1110/cordova-appium-example
- https://ordina-jworks.github.io/ionic/2018/09/30/e2e-testing-ionic-protractor-appium-e2e-testing.html#configure-the-e2e-testing-tools-in-your-ionic-project