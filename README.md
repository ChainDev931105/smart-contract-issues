# smart-contract-issues

| |Issue|Example|
|-|:-|:-:|
| [H-1](#H-1) | DoS in Auction market on native token | [Immunefi / Oasys](https://github.com/oasysgames/oasys-ecosystem-contract/blob/f346dc9ae3e6f65c4e026687455fdb2eeff47ee8/contracts/tofuNFT/MarketNG.sol#L760-L762) |
| [H-2](#H-2) | Using dynamic variable in public view function | [Code4Rena / NeoTokyo](https://code4rena.com/reports/2023-03-neotokyo#h-01-updating-a-pools-total-points-doesnt-affect-existing-stake-positions-for-rewards-calculation)|
| [H-3](#H-3) | | |
| [H-4](#H-4) | | |
| [H-5](#H-5) | | |
| [M-1](#M-1) | Using front-running a malicious user can stop admin's activity | [Code4Rena / Wenwin](https://code4rena.com/reports/2023-03-wenwin/#m-01-undermining-the-fairness-of-the-protocol-in-swapsource-and-possibilities-for-stealing-a-jackpot) |
| [M-2](#M-2) | | |
| [M-3](#M-3) | | |
| [M-4](#M-4) | | |
| [M-5](#M-5) | | |

### <a name="H-1"></a>[H-1] DoS in Auction market on native token

[Immunefi / Oasys](https://github.com/oasysgames/oasys-ecosystem-contract/blob/f346dc9ae3e6f65c4e026687455fdb2eeff47ee8/contracts/tofuNFT/MarketNG.sol#L760-L762)

Useful link is [here](https://consensys.github.io/smart-contract-best-practices/attacks/denial-of-service/).

