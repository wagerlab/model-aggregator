# WagerLab Betting Model Aggregator
[WagerLab's](https://www.wagerlab.app/) Model Aggregator is a sports betting predictor that takes predicted spreads from 50+ unique models found on [ThePredictionTracker](http://www.thepredictiontracker.com/) and converts them into a ordered list of value picks by standardizing and combining the distributions of each pick's predicted value over the current spread.

<br/>

This model was built by the developer of WagerLab, a mobile app for betting on sports and current events with your friends. Please consider giving the app a download (and a nice review:pray:). I'd really apprecieate it! :grimacing:
- [WagerLab - Bet with Friends for iOS](https://apps.apple.com/us/app/wagerlab/id1460332027)
- [WagerLab - Bet with Friends for Android](https://play.google.com/store/apps/details?id=com.socialbet.android)

<br/>

Feel free to use, copy, and modify this code as much as you'd like.  If you have questions, you can reach me directly at william@wagerlab.app.


## Methodology
### Theory
TODO
### Implementation
TODO

## Usage
Feel free to copy this for your own purposes or contribute. If you have questions, reach out to william@wagerlab.app.
### Commands

`npm run nfl` Runs the NFL point spread model 

`npm run ncaaf` Runs the NCAA Football point spread model 

`npm run nba` Runs the NBA point spread model 

`npm run ncaab` Runs the NCAA Basketball point spread model 


### Walkthrough

1. **Pull down this package**
   - You can also do this manually using the green "Clone or download" button above or on the command line by running `git clone https://github.com/wagerlab/model-aggregator.git` 
   - Once you have this package, navigate to it on the command line
2. **Ensure you have the proper dependencies and permissions**
   - You will need to have node and npm installed. Check if node is installed by running `node -v`. Check if npm is installed by running `npm -v`. If you see a version number, the software is installed, but if you get nothing back, you need to install it.  [Here is info about how to install node and/or npm](https://www.npmjs.com/get-npm).
   - Set read/write permissions on main script by running `sudo chmod -R 777 generatePicks.js`
3. **Run the model**
   - See the 'Commands' section above for the specific commands to run depending on which data you want to view.
