# OBSCryptoTicketWidget

OBSCryptoTicketWidget is an OBS overlay that displays live crypto prices for any crypto currency you can think of!

![Alt Text](https://i.giphy.com/media/szOC6UR3CKInYjcUwS/giphy.webp)


## Installation

Extract/unzip CryptoTickerWidget folder and copy the the path to CryptoTickerWidget/widget.html

Start OBS and add a new Browser source in OBS, give it a name and hit 'OK'

![image](https://user-images.githubusercontent.com/22139030/109432194-b19d4f80-79cf-11eb-9c7f-782ff932311f.png)

Select ```Properties``` for the new Browser source

![image](https://user-images.githubusercontent.com/22139030/109432314-27a1b680-79d0-11eb-9330-90a115642cc8.png)

In the URL field, paste the full path to CryptoTickerWidget/widget.html and add ```?theme=default&coin=dogecoin``` to the end
If you extracted/unzipped in your downloads folder it will look something like this ```C:/downloads/CryptoTickerWidget/widget.html?theme=default&coin=dogecoin```

![properties](https://user-images.githubusercontent.com/47755826/111018387-1c5e6b80-837e-11eb-8a20-5003ed2d90e3.PNG)

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

You can also make your own by changing the theme variable in the URL field from above ```theme=custom``` 
![urlcustom](https://user-images.githubusercontent.com/47755826/109591898-00cca880-7ad4-11eb-8df9-14de43f451f6.PNG)

and pasting the following code into the Custom CSS field I told you to delete everything from earlier :)

![custom](https://user-images.githubusercontent.com/47755826/109591965-1b068680-7ad4-11eb-879e-b0e5418831e0.PNG)

Change the rgba values to what ever you'd like.

```
.widget.custom {
	--text-color: rgba(255,91,91, 1);
	--line-up-color: rgba(255,91,91, 1);
	--line-down-color: rgba(255,91,91, 1);
	--background-color: rgba(91,255,157, .8);
	--chart-up-fill-color: rgba(216,255,91, .6);
	--chart-down-fill-color: rgba(216,255,91, .6);
	--border-color: rgba(0, 0, 0, 0);
	box-shadow: 0 0 0 0;
}
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
