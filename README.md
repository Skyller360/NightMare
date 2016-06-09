### Rules

You're lost in a forest full of monster with only your flashlight in hand ....
Aim for the monsters to make them disappear !

### Installation

Nightmare requires [Node.js](https://nodejs.org/) to run.

You need [Express](http://expressjs.com/) and [Socket.IO](http://socket.io/) installed.

```sh
$ npm install express
$ npm install socket.io
```

### Launching

First of all, make an ipconfig in your console to know your own IP address

```sh
$ ipconfig
```

Go into Assets/Scripts/Javascript/Game/Config.js and change the url variable to your own ip + the port 8000, and do the same in control.html.

```javascript
 // Assets/Scripts/Javascript/Game/Config.js line 23
 var url = 'yourOwnIpAddress:8000';
 // control.html line 18
  var url = 'yourOwnIpAddress:8000';
```

After this, open a console, go to the main folder and launch the app.js file using NodeJS.

```sh
$ cd /DirectoryToColorarium
$ node app.js
```

Open a browser and connect to your own Ip adress on the port 8000+/index.html. (192.168.0.15:8000/index.html for example).

You'll arrive on the main screen and where you can choose your character.

Connect your phone on the same network (!!!) and go to your own Ip adress on the port 8000 + /control.html (192.168.0.15:8000/control.html for example).

You'll arrive on a page with a big 'Calibrate' button

Click start on the computer to launch the game.
When the game is launched, it'll start when you click on 'Calibrate' on your mobile.

Once it's done, the game's launched and you can now move your character by rotating on yourself with your phone in hand.
