# ERC20 Token

> The code required for a basic ERC20 Token.

## What Is ERC-20?
One of the most significant Ethereum tokens is known as ERC-20. ERC-20 has emerged as the technical standard; it is used for all smart contracts on the Ethereum blockchain for token implementation and provides a list of rules that all Ethereum-based tokens must follow.

ERC-20 is similar, in some respects, to bitcoin, Litecoin, and any other cryptocurrency; ERC-20 tokens are blockchain-based assets that have value and can be sent and received. The primary difference is that instead of running on their own blockchain, ERC-20 tokens are issued on the Ethereum network.

Additional description about the project and its features.

## Built With

- [Solidity](https://docs.soliditylang.org/en/v0.8.3/)

## Getting Started

To get your own ERC20 Token up and running follow these simple example steps.

### Prerequisites

- Have [MetaMask](https://metamask.io/) installed in your broswer and get some fake ETH in your Ropsten Test Network account by going to [Ropsten Faucet](https://faucet.ropsten.be/).

### Setup

- Download or clone this repo.
- Rename the TOKEN-SYMBOL.sol file to whatever you want.

### Usage

- Inside of the TOKEN-SYMBOL.sol file you will see commented out code at the top. Here you can use your text/code editor to change all occurences of your symbol and name of token. Also change the total supply of the token to how many you want created. Then change how many decimal places you want. This can be up to 18. Zero would mean you can either have or don't have 1 whole token. Lastly, change the owner address to your account address. Which ever account you use needs to have some ETH to pay the transfer fee. This is why we used a TEST account with some FAKE ETH. 

### Deployment

- Once you code is ready and you have made sure to change all occurance of the variables I mentioned above, move on.
- Go to [Remix](https://remix.ethereum.org/).
- Create a new file here by clicking on the `+` button near the `browser` folder on the left panel. There are already a few files in there now, but you can ignore them. You can name the file to whatever you like.
- Paste the code you have been working on into this file.
- Look from the icon on the left of the screen called  `Solidity Compliler`.
- Hit `Compile`. If everything is working you should see some options appearing in the `CONTRACT` drop downfield, one of them being your token contract. It should say `Token Symbol + “Token”` like `BTCToken`.
- Now go to the icon of the left that is called `Deploy & Run Transactions.`
- Next we need to change the “Environment” from `JavaScript VM` to `Injected Weg3`. When you do that, MetaMask will prompt you to confirm that you want to connect your MetaMask wallet to Remix, hit `confirm`. After you do that, your account will automatically populate the `Account` field below with the account number and your current balance in ether.
- Lastly, we need to specify we want to deploy. Make sure you select your contract `ERC20Interface` from the `CONTRACT` dropdown field. Your token contract is your `Token Symbol + “Token”`, like `BTCToken`. Last, hit “Deploy.”
- The deployment process may take a few minutes.

### See your token on MetaMask
- Go to the `Deployed Contracts` section right below where you clicked `Deploy` before.
- Click the copy button to copy the contract address.
- On MetaMask click `Add token`.
- Click `Custom token` and paste the address.
- You should now be able to add your tokens to your wallet.


## Authors

👤 **Ryel Banfield**

- GitHub: [@RyelBanfield](https://github.com/ryelbanfield)
- Twitter: [@RyelBanfield](https://twitter.com/ryelbanfield)
- LinkedIn: [Ryel Banfield](https://www.linkedin.com/in/ryel-banfield/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](LICENSE) licensed.
