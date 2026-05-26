# snak-arenaindex

Companion package for **Snak**. Surfaces the live arena directory — joinable matches with current player counts, stake amounts, deadlines, and prize pools — across Celo + Stacks.

Pairs with [`@winsznx/snakboard`](https://github.com/winsznx/snakboard).

## Status

Scaffold for the directory builder. Real-world implementation reads `ArenaCreated` + `Joined` + `MatchSettled` over a sliding lookback window and reconciles state into a sorted index.

## License

MIT
