Stem 
====
[![Dependency Status](https://david-dm.org/Alvinlz/stem.png)](https://david-dm.org/Alvinlz/stem)   
A simple Steam bot based on [node-steam](https://github.com/seishun/node-steam) that can run on Windows, Mac, and Linux. The bot is still in it's early stages but is stable enough to perform basic actions.
![Stem Screenshot](https://photos-3.dropbox.com/t/0/AACunSjq-iixeELywziCBy-gpq-lJx7HckZhXiUsmdnj5w/12/7985699/png/2048x1536/3/1374004800/0/2/Screenshot%202013-07-16%2014.56.03.png/WS3Na_NIDcM-6412v0OCEVRVpg6a1m_x9PNZqxO0cyc)
## Features
As of [v0.3.0](https://github.com/Alvinlz/stem/releases/tag/v0.3.0) the bot is capable of the following
- Game idling (can idle multiple games at once)
- Basic trading (can only accept items as of [v0.3.0](https://github.com/Alvinlz/stem/releases/tag/v0.3.0))
  - Trade whitelist
  - Trade validation to avoid Steam trade exploits
- Logging

## Installation (Mac / Linux)
- Download and install [node.js](http://nodejs.org/)
  - If you are running linux you can follow [this guide](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) as well
- Run `git clone https://github.com/Alvinlz/stem.git`
  - Alternatively you can just download the zip or tar from github and unzip
- Go into the stem folder
- Run `npm install`
  - If you are on a mac you will need Xcode and the Command Line tools from Xcode 
- Rename the config.example.json file to config.json
- Edit config.json to your needs (only username and password is required)
- Run `node app.js` to start the bot
