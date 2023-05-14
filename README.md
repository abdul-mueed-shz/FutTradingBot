# Fut Trading Bot

Fut Trading Bot is a game-changing tool designed to enhance your trading experience in FIFA Ultimate Team (FUT). This powerful bot automates sniping and selling processes, providing you with lightning-fast search capabilities and lucrative trading opportunities that may otherwise go unnoticed. By utilizing the Fut Trading Bot, you can maximize your coin earnings and take control of your trading endeavors in FUT.

## Key Features

- **Automated Sniping**: The bot performs quick and efficient searches on the FUT Web App, identifying valuable trading opportunities for you.
- **Selling Automation**: Seamlessly sell your items at optimal prices, saving you time and effort.
- **Real-time Notifications**: Get instant alerts when the bot finds profitable trading opportunities or completes a successful trade.
- **Seamless Integration**: The Fut Trading Bot is seamlessly embedded within the underlying Fifa 23 Fut Web App, providing a smooth and integrated experience.
- **Efficient Data Handling**: State management is implemented using Pinia to ensure efficient data handling within the bot.
- **Communication with Fut Web App**: The bot establishes communication with the Fut Web App using Quasar Bridge Calls, allowing seamless message passing.

## The Fut Trading Bot provides various configuration options to customize its behavior and optimize your trading strategy. Below, you will find a detailed explanation of each configuration property:

### Delay Settings
- `delayBwSearches`: The delay time (in seconds) between consecutive searches.
- `purchaseDelayTime`: The delay time (in milliseconds) before the bot purchases a player after a successful snipe.
- `pattern`: A custom search pattern for filtering players based on specific attributes. Currently not configured.

### Rest Settings
- `minBeforeRest`: The minimum number of searches to perform before the bot takes a rest.
- `restDuration`: The duration (in minutes) of each rest period.
- `minBeforeRestTimeOut`: The minimum number of searches to perform before the bot triggers a timeout during rest.
- `restDurationTimeOut`: The duration (in minutes) of each rest period during a timeout.

### Bid Prices
- `macr`: The maximum bid price for players.
- `micr`: The minimum bid price for players.

### Buy Now Prices
- `minb`: The minimum buy now price for players.
- `maxb`: The maximum buy now price for players.

### Additional Settings
- `safeSniping`: Enables or disables safe sniping, which avoids risky sniping situations.
- `reslitUnsoldItems`: Enables or disables relisting unsold items.
- `clearSolidItems`: Enables or disables clearing solid items.
- `playSounds`: Enables or disables playing sounds during trading activities.

### Pricing Settings
- `sellUsingFutbinPrices`: Enables or disables using Futbin prices for selling players.
- `sendToTransferList`: Enables or disables sending purchased players to the transfer list.
- `sendToClub`: Enables or disables sending purchased players to the club.
- `sellPlayerPrice`: The price at which the bot sells players.
- `buyPlayerPrice`: The price at which the bot buys players.

### Purchase Info
- `successfulPurchases`: The number of successful purchases made.
- `failedPurchases`: The number of failed purchase attempts.
- `activeTransfers`: The number of active transfers.
- `soldItems`: The number of items sold.
- `unSoldItems`: The number of unsold items.
- `totalProfit`: The total profit earned.

### Rating Filter
- `minimumCardRating`: The minimum rating of cards to consider in searches.
- `maximumCardRating`: The maximum rating of cards to consider in searches.

### Break Settings
- `searchesBfrBreak`: The number of searches to perform before taking a break.
- `breakDuration`: The duration (in minutes) of each break.
- `currentSuccessfulBreaks`: The current number of successful breaks taken.
- `breakTimeOutId`: The identifier of the timeout during a break.
- `secondsBfrResuming`: The remaining seconds before resuming trading.
- `secondsBfrResumingInterval`: The interval for updating the remaining seconds before resuming.

### Limit Settings
- `purchaseLimit`: The maximum number of purchases allowed.
- `searchFallLimit`: The maximum number of search failures allowed before taking action.
- `maxPurchasesPerSearch`: The maximum number of purchases allowed per search.
- `currentFailedSearches`: The current number of failed searches.
- `currentPurchasesPerSearch`: The current number of purchases made per search.
- `purchasePerSearchIntervalId`: The identifier of the inte

## Technologies Used

- **Quasar Browser Extension**: The bot is developed using JavaScript and Vue.js with the Quasar framework, enabling seamless integration within the Fifa 23 Fut Web App.
- **Pinia**: Implements state management for efficient data handling within the bot.

## Getting Started

To get started with Fut Trading Bot, follow these steps:


1. Load the extension in your browser:
- For Chrome: Open the Extensions page (`chrome://extensions/`), enable Developer mode, and load the unpacked extension from the project's build directory.
- For Firefox: Open the Add-ons Manager (`about:addons`), click the gear icon, select "Install Add-on From File," and choose the extension zip file generated in the build directory.

2. Open the Fifa 23 Fut Web App and enjoy the enhanced trading experience!


## Contributing

Contributions to Fut Trading Bot are welcome! If you encounter any issues, have ideas for improvements, or would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name: `git checkout -b feature/my-awesome-feature`.
3. Make the necessary changes and commit them: `git commit -m "Add my awesome feature"`.
4. Push your changes to the branch: `git push origin feature/my-awesome-feature`.
5. Open a pull request on the main repository.


## Acknowledgements

- The Fut Trading Bot project was inspired by the passion for FIFA Ultimate Team and the desire to enhance the trading experience for all FUT enthusiasts.
- Special thanks to the Quasar Framework community for their invaluable contributions to the tools and libraries used in this project.

## Contact

For inquiries or further information about Fut Trading Bot, please contact [abdulmueedshahbaz@gmail.com](mailto:abdulmueedshahbaz@gmail.com).

## Demo



https://github.com/Abdul-Mueed-Shahbaz/FutTradingBot/assets/52679916/2d739462-295f-4e00-9f0d-d41deae6a828




