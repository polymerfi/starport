---
order: 1
title: v0.20.0
parent:
  title: Migration
  order: 3
description: For chains that were scaffolded with Ignite CLI versions lower than v0.20.0, changes are required to use Ignite CLI v0.20.0. 
---

# Upgrading a blockchain to use Ignite CLI v0.20.2

1. Upgrade your Cosmos SDK version to [v0.45.3](https://github.com/cosmos/cosmos-sdk/releases/tag/v0.45.3).

2. Update your `SetOrderBeginBlockers` and `SetOrderEndBlockers` in your `app/app.go` to explicitly add entries for all the modules you use in your chain.
