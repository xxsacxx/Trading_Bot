# Trading Bot #
![Gordon Gekko](http://mikevanrossum.nl/static/gekko.jpg)

*The most valuable commodity I know of is information.*

-Gordon Gekko

Uses Gekko which is a Bitcoin TA trading and backtesting platform that connects to popular Bitcoin exchanges. It is written in JavaScript and runs on [Node.js](http://nodejs.org).

*Use Gekko at your own risk.*

## Installation ##
```
git clone https://github.com/xxsacxx/Trading_Bot
cd Trading_Bot
```
## Installing Gekko's dependencies ##
```
yarn install --only=production
```

## launch the UI ##
```
node gekko --ui
```
## This will open UI ##
![UI](https://i.imgur.com/tJnTixk.png)

## Using strategy : Neural net
![Neural net](https://i.imgur.com/w6xkEY0.png)

Upload data to do backtest

### Strategy 
It helps us creating policy (which decides the action to sell,buy,hold) given a state (bank account details) also considering the observation (Sentiment Analysis etc)
