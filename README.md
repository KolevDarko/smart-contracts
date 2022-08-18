# Web3 Blog Smart Contracts

This is the repository I'll be using for all the smart contracts I write on my blog [https://web3dev.blog](https://web3dev.blog)

## Subscription Manager

Location: contracts/SubscriptionManager.sol

The first project is Subscription manager which is a proof of concept for Recurring Payments using ERC20 tokens.
The main features are:

* Only the end user can create and cancel their own subscriptions.
* Perform payments with an allowance.
* Prevent spending more money than defined in the subscription.
* Prevent charging more recently than defined in the subscription.
* Anyone can execute the payment function but it will always send money to the correct recipient.
* Perform Batch payouts for multiple subscriptions and save Gas costs.