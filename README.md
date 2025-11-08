# Welcome to BeliveScreener Mobile app 👋

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


## App working Mechanism:
- This app use real time data from https://www.believescreener.com/
- I have utilized websocket data for real time token prices, by understanding how the ping pong mechanism is working on actual website.
- For the statistics , i have setup a proxy server and then serving the html from that proxy, then scraping the statistics every 10 secs .
- Proxy server is used to avoid cors error on browser.
- I have no intention to misuse or exploit the data of your website, i declare that i wont use it for my personal benefit. 

- Note: Please dont forget to give feedback after reviewing , so that i can improve , i accept your choice to reject or accept my submission.

