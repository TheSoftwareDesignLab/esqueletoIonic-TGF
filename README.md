<h1>The Game Factory Template Project</h1>

This is the base project for The Game Factory (TGF) micro-games.

<section id="1"></section>
<h2>1. Creating a micro-game</h2>

If you want to create a micro-game for TGF this is the base project in which you should create the game to assure that you game will be accepted. Each micro-game in TGF is going to be consider as an independent Module in ionic. Your game is able to have more that one component, but it should not have more than one module. 

Download this project and use the GamePage (src/app/game) as the module for the game. 

Develop the game in the module and then test it.

To test it, open a terminal/cmd window, go to the root of the project and then do:

- npm install
- ionic serve

That would triger ionic in the port 8000. Use a web navigator to see it. You will see in a button in the main screen that says "Go to Game", if you click it, it will take you to the GamePage, and you can see if your game works. 

When you have your micro-game ready go to --Section 3--, where you will learn how to upload the game so that it can be added as one of the micro-games available in TGF. If you game works on the ionic project of this repo it will work on any of the apps generated by TGF.

While developing the game you can add new dependencies and new assets. But take into account that the following dependencies are the baseline for the apps that TGF generates. So if your micro-game is not compatible with these dependencies it might not work in the TGF apps.

    "@angular/common": "~8.1.2",
    "@angular/compiler": "~8.1.2",
    "@angular/core": "~8.1.2",
    "@angular/forms": "~8.1.2",
    "@angular/platform-browser": "~8.1.2",
    "@angular/platform-browser-dynamic": "~8.1.2",
    "@angular/router": "~8.1.2",
    "@ionic-native/core": "^5.0.0",
    "@ionic-native/splash-screen": "^5.0.0",
    "@ionic-native/status-bar": "^5.0.0",
    "@ionic/angular": "^4.7.1",
    "core-js": "^2.5.4",
    "rxjs": "~6.5.1",
    "tslib": "^1.9.0",
    "zone.js": "~0.9.1"

<section id="2"></section>
<h2>Testing a micro-game developed in other enviroment</h2>

Any HTML/Javascript game shoulkd work as a micro-game for TGF. But it needs to be writen on Angular architecture. So, you can use the ionic project in this repository to test your game. 

Download this project and place tour game in the GamePage (src/app/game) module.

To test it, open a terminal/cmd window, go to the root of the project and then do:

- npm install
- ionic serve

That would triger ionic in the port 8000. Use a web navigator to see it. You will see in a button in the main screen that says "Go to Game", if you click it, it will take you to the GamePage, and you can see if your game works. 

<section id="2"></section>
<h2>Upload a new game to TGF</h2>

