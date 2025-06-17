# Thunderbolt Networks

The collection of all Thunderbolt forks (Devnet, Testnet, Mainnet, etc.)

This repository contains the configuration files for Thunderbolt networks.

Please refer to the [Nubit Docs](https://docs.nubit.org) for guides on running your own node. The configuration files `genesis.json` and `peers.txt` are intended for use by Consensus nodes and should be placed in the node's home directory (by default `$HOME/.thundeboltd/config` and added to `$HOME/.thundeboltd/config/config.toml` accordingly).

More `persistent_peers` and `seed` nodes are setting now.

## Networks

| Name    | Type         | Chain ID             | Configs                                    |
| ------- | ------------ | -------------------- | ------------------------------------------ |
| devnet  | Testnet      | `thunderbolt-devnet` | [thunderbolt-devnet](./thunderbolt-devnet) |
| mainnet | Mainnet Beta | `thunderbolt`        | [thunderbolt](./thunderbolt)               |
