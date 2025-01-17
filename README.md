## Token Resources By Cosmostation

We decided to use this repo for validators' images and token assets for our products.

- [Mintscan Explorer](https://mintscan.io)
- [Web Wallet](https://wallet.cosmostation.io)
- [Android Wallet](https://bit.ly/2BWex9D)
- [iOS Wallet](https://apple.co/2IAM3Xm)

## How to add your validator image

1. Fork this repo to your own github account
2. Clone fork and create new branch

```shell
git clone git@github.com:YOUR_ACCOUNT/cosmostation_token_resource.git
cd cosmostation_token_resource
git branch <branch_name>
git checkout <branch_name>
```

3. Add your image (.png) file to appropriate directory

4. Commit and push to your fork

```shell
git add -A
git commit -m “Add <YOUR VALIDATOR NAME>”
git push origin <branch_name>
```

5. From your repository, make pull requesrt (PR)

## Image Requirements

- file extension: `.png`. Note that uppercase `PNG` considered invalid
- file name: should be your `validator operator address.png`
- file directory: should be located in whichever network inside [moniker](https://github.com/cosmostation/cosmostation_token_resource/tree/master/moniker) directory



## dApp Link add for mobile wallets

1. Add your dapp information with /dapps/dapps.json

2. Commit and push to your fork for PR



## Cosmostation's Services and Community

- [Official Website](https://www.cosmostation.io)
- [Mintscan Explorer](https://www.mintscan.io)
- [Web Wallet](https://wallet.cosmostation.io)
- [Android Wallet](https://bit.ly/2BWex9D)
- [iOS Wallet](https://apple.co/2IAM3Xm)
- [Telegram - International](https://t.me/cosmostation)
- [Kakao - Koreans](https://open.kakao.com/o/g6KKSe5)



## To add asset data

- [Assets](https://github.com/cosmostation/cosmostation_token_resource/tree/master/assets/v2)
- [CW20](https://github.com/cosmostation/cosmostation_token_resource/tree/master/assets/cw20)
- [ERC20](https://github.com/cosmostation/cosmostation_token_resource/tree/master/assets/erc20)
