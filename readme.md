# OBSCryptoTicketWidget

OBSCryptoTicketWidget is an OBS overlay that display live crypto prices for any crypto currency you can think of!

## Installation

Place entire OBSCryptoTickerWidget folder into your OBS installations /obs-plugins/64bit folder

Start OBS and Add a new Browser source in OBS and give it a name hit 'OK'

![name-browser](https://user-images.githubusercontent.com/47755826/109430595-c970d580-79c7-11eb-9a3f-6b384429e743.PNG)

Select ```Properties``` for the new Browser source

![properties-button-ind](https://user-images.githubusercontent.com/47755826/109430451-2cae3800-79c7-11eb-99c7-8ee466c95003.png)

In the URL field put ```[your OBS installation folder]/obs-plugins/64bit/OBSCryptoTickerWidget/widget.html?theme=default&coin=dogecoin```

![properties-url](https://user-images.githubusercontent.com/47755826/109430641-03da7280-79c8-11eb-9258-8df635142384.png)

Remove any text in the Custom CSS input box

![properties-ccss](https://user-images.githubusercontent.com/47755826/109430684-41d79680-79c8-11eb-92a1-3d7a5d34a8e0.png)

## Usage
### Themes
You can change the theme of your widget by changing the theme variable in the URL field from above ```theme=default```

![properties-theme](https://user-images.githubusercontent.com/47755826/109430744-7a777000-79c8-11eb-8bd0-ddacf0795650.png)

to any of the following:

```
default
retro
easter
tron
fishy
accessible
```
### Coins
You can change the coin your widget is tracking by changing the coin variable in the URL field ```coin=dogecoin```

![properties-coin](https://user-images.githubusercontent.com/47755826/109430752-86fbc880-79c8-11eb-9741-4ea0cb7cdd58.png)

any of the below (and more):

```
bitcoin
ethereum
binancecoin
tether
cardano
polkadot
ripple
litecoin
chainlink
bitcoin-cash
stellar
usd-coin
uniswap
dogecoin
wrapped-bitcoin
okb
nem
cosmos
aave
solana
crypto-com-chain
eos
monero
bitcoin-cash-sv
huobi-token
tron
theta-token
iota
havven
neo
terra-luna
vechain
ftx-token
tezos
dash
the-graph
avalanche-2
dai
binance-usd
cdai
kusama
compound-ether
maker
leo-token
filecoin
elrond-erd-2
celsius-degree-token
compound-governance-token
sushi
decred
compound-usd-coin
fantom
pancakeswap-token
ethos
ravencoin
zcash
zilliqa
ethereum-classic
uma
nexo
yearn-finance
thorchain
0x
huobi-btc
near
icon
blockstack
zkswap
republic-protocol
waves
amp-token
mdex
hedera-hashgraph
bittorrent-2
xsushi
iostoken
renbtc
swissborg
digibyte
paxos-standard
matic-network
algorand
ontology
nano
basic-attention-token
loopring
husd
omisego
bancor
terrausd
pundi-x
venus
holotoken
zencash
qtum
arweave
bmax
lisk
siacoin
enjincoin
```
