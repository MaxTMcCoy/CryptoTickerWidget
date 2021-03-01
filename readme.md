# OBSCryptoTicketWidget

OBSCryptoTicketWidget is an OBS overlay that displays live crypto prices for any crypto currency you can think of!

![Alt Text](https://i.giphy.com/media/szOC6UR3CKInYjcUwS/giphy.webp)


## Installation

Place the entire OBSCryptoTickerWidget folder into your OBS installations /obs-plugins/64bit folder

Start OBS and add a new Browser source in OBS, give it a name and hit 'OK'

![image](https://user-images.githubusercontent.com/22139030/109432194-b19d4f80-79cf-11eb-9c7f-782ff932311f.png)

Select ```Properties``` for the new Browser source

![image](https://user-images.githubusercontent.com/22139030/109432314-27a1b680-79d0-11eb-9330-90a115642cc8.png)

In the URL field, put ```[your OBS installation folder]/obs-plugins/64bit/OBSCryptoTickerWidget/widget.html?theme=default&coin=dogecoin```

![image](https://user-images.githubusercontent.com/22139030/109432321-30928800-79d0-11eb-88a1-a37c35e51076.png)

Remove any text in the Custom CSS input box

![image](https://user-images.githubusercontent.com/22139030/109432325-38522c80-79d0-11eb-99e8-3169a78ed91c.png)

## Usage
### Themes
You can change the theme of your widget by changing the theme variable in the URL field from above ```theme=default```

![image](https://user-images.githubusercontent.com/22139030/109432367-6a638e80-79d0-11eb-9ae4-6da1f5b91315.png)

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

![image](https://user-images.githubusercontent.com/22139030/109432374-72233300-79d0-11eb-818e-cc0299dcdea6.png)

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
