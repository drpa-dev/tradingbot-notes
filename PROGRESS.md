# Trading bot: progress notes

A beginner's hobby project: learning Python by building a crypto trading bot.
It uses public price data and pretend money only. No real trading.

## Done so far

- **Replay bot:** replays past prices and tests simple buy/sell rules with pretend money.
- **Rule testing:** tried 9 simple rules on BTC, ETH and SOL using daily and weekly
  price history, with a settings sweep and a check for overfitting
  (rules that only look good on past data by luck).
- **Price watcher:** a small script that records live prices, now running around
  the clock on a small cloud server.
- **Backups and version history:** the server is backed up daily, and the code
  now lives in a private GitHub repo.

## Next up

- Test the rules on more coins, including some that crashed.
- Add a filter that skips coins with too little trading.
- A live paper-trading bot (live prices, pretend money).
- Charts showing prices with the bot's trades marked.

## Not planned yet

- Real-money trading. If it ever happens, it will be much later, after a full
  review, with small limits.
