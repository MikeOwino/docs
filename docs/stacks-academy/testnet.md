---
title: Testnet
description: Test your smart contracts and apps
sidebar_position: 12
---

## About testnet

The testnet is a separate blockchain from the Stacks mainnet analogous to a staging environnement. It's a network used by developers to test their apps, smart contracts, or changes to the protocol in a production-like environment.

It produces blocks at roughly the same rate as mainnet; about 1 block every 10 minutes on average. The Stacks testnet is rarely reset.

### Faucets

Testnet faucets provide you with free Stacks Token (STX) to test with. These are not the same as STX on mainnet and have no value. There are a couple of different options for getting testnet STX.

#### Hiro

You can get STX from the Hiro faucet on the [Hiro Explorer Sandbox](https://explorer.hiro.so/sandbox/faucet?chain=testnet), or using the [API](https://docs.hiro.so/api#tag/Faucets).

To get STX tokens from within the Explorer Sandbox, navigate to the "Faucet" tab on the left and click "Request STX" button.

![](/img/stx_faucet.png)

You can also try out [Stacking](./stacking) by clicking on `I want to stack`.

:::note
The Explorer Sandbox requires you to login with a Stacks wallet
:::

#### LearnWeb3

Alternatively, you can use the [LearnWeb3 faucet](https://learnweb3.io/faucets).

![Alt text](lw3-faucet.png)

### Testnet API

The hosted Stacks Blockchain API for the testnet is available at this base URL:

```shell
https://stacks-node-api.testnet.stacks.co/
```

![](/img/api_testnet_status.png)
