![alt text](https://raw.githubusercontent.com/NowDB/Pro7/master/www/img/ide.png "Pro7 IDE"){:width="100%"}

Integrated Development Environment for build Progressive Web Application (PWA) based on Framework7. It enables user to design, develop, debug, test, and release application quickly.

Windows|MacOS|Ubuntu
--|--|--
[Download](https://github.com/NowDB/Pro7/releases/download/v0.0.3/Pro7.Setup.0.0.3.exe)|[Download](https://github.com/NowDB/Pro7/releases/download/v0.0.3/Pro7-0.0.3.dmg)|[Download](https://github.com/NowDB/Pro7/releases/download/v0.0.3/pro7_0.0.3_amd64.deb)

## Instalation
1. [Download latest executable release](https://github.com/NowDB/Pro7/releases/tag/v0.0.3).
2. Open cmd/terminal on your computer.
3. Install serve using yarn.
```sh
npm install -g yarn
yarn global add serve
```
3. or Install serve using npm.
```sh
npm install -g serve
```
5. Test serve on your cmd/terminal.
```sh
serve -v
```

## Publish (Firebase)
1. Open cmd/terminal on your computer.
2. Install firebase tools using bellow command.
```sh
npm install -g firebase-tools
```
3. Login to firebase user cmd/terminal on your computer.
```sh
firebase login
```
4. Open Your Project on Pro7.
5. Access Terminal from your Project on Pro7.
6. Registering your app to firebase using bellow command.
```sh
firebase init
```
7. Choose Hosting
8. Answer question with the example below.
```sh
? What do you want to use as your public directory? www
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? File www/index.html already exists. Overwrite? No
```
9. Klik Firebase Deploy from your Project on Pro7.
10. Access the link show on your Project Terminal.

## Usefull Links
1. [Framework7](https://framework7.io/)
2. [PWA](https://web.dev/progressive-web-apps/)
3. [PWA manifest & icons generator](https://app-manifest.firebaseapp.com/)
4. [Favicons generator](https://www.favicon-generator.org/)
