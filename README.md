This repo contains:

1. Token lending program cloned from SPL on 4th oct (inside program folder)
2. Cli that I've updated that actually works with it, as of 4th oct (inside js folder)

Every now and then you get the {42} error, which means the oracle goes stale. Dunno how to solve. For now just keep re-running the cli until succeeds.

Note that you can't really run this on localnet coz you'd need to setup your own Pyth oracles which I  cba. Hence running on devnet. Don't forget to update program ID if you redeploy it in `constants.ts`.
