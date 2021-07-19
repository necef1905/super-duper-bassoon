# Cross-chain Token Management

The dual-chain architecture of Binance Chain & Binance Smart Chain empowers you to build your own decentralized apps while also taking advantage of the fast trading performance offered on Binance DEX (decentralized exchange). The native cross-chain communication mechanism allows tokens to be transferred between BC and BSC easily.

Binance Smart Chain and Binance Chain work together to ensure that one token can circulate in both formats with confirmed total supply and be used in different use cases.


## BEP2/BEP8 Token Owner

If you are BEP2/BEP9 token owner, please follow this [guideline](./bind-tokens.md) to complete `Bind` process when you wish to migrate to BSC.

You can also use this [tool](https://github.com/binance-chain/token-bind-tool).



## BEP20 Owner


If you are BEP20 token owner or anybody else, please follow this [guideline](./mirror.md) to complete `Mirror` process when you wish to migrate to BC or get listed on Binance DEX.


## Comparision Between Bind and Mirror

|                   | Bind          | Mirror                    |
| ----------------- | ------------- | -------------------------------------- |
| Initiator         | BEP2/BEP8 Token Owner  | Anyone, including BEP20 Token Owner and others    |
| Fee               | less than 1BNB         | about 100 BNB, `mirrorFee` is a governable parameter |
| How long will it take    | several minutes       | ~30s                                    |
| Supply Distribution   | Customized between BC & BSC | All supply are on BSC|



