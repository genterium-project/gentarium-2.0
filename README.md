Gentarium Core proof of stake wallet repository
================================================

<h3>Coin Specification</h3>

<table>
<tbody>
<tr><td><strong>NAME</strong></td><td>Gentarium</td></tr>
<tr><td><strong>TICKER</strong></td><td>GTM</td></tr>
<tr><td><strong>ALGORITHM</strong></td><td>Quark</td></tr>
<tr><td><strong>TYPE</strong></td><td>POS / MN</td></tr>
<tr><td><strong>TOTAL SUPPLY</strong></td><td> 14 200 000 GTM</td></tr>
<tr><td><strong>PREMINE</strong></td><td>40 000 GTM</td></tr>
<tr><td><strong>MASTERNODE COLLATERAL</strong></td><td>1 000 GTM</td></tr>
<tr><td><strong>BLOCKS PER DAY</strong></td><td>1440</td></tr>
<tr><td><strong>BLOCK TIME</strong></td><td>1 MINUTE</td></tr>
<tr><td><strong>STAKE MIN AGE</strong></td><td>6 HOURS</td></tr>
<tr><td><strong>REWARDS</strong></td><td>5 GTM MASTERNODE<br>1 GTM STAKING<br>0,5 GTM DEV FEE</td></tr>
<tr><td><strong>HALVING BLOCK</strong></td><td>160000</td></tr>
<tr><td><strong>PORT</strong></td><td>27117</td></tr>
<tr><td><strong>MASTERNODE HOSTING PLATFORM</strong></td><td><a href='https://mn.gtmcoin.io/'>mn.gtmcoin.io</a></td></tr>
</tbody>
</table>
<hr>

<h3>Official links</h3>

<table>
<tbody>
<tr><td><strong>Website:</strong></td><td><a href='https://gtmcoin.io/'>gtmcoin.io</a></td></td></tr>
<tr><td><strong>Explorer:</strong></td><td><a href='https://explorer.gtmcoin.io/'>explorer.gtmcoin.io/</a></td></tr>
<tr><td><strong>Discord:</strong></td><td><a href='https://discord.gg/vErwUSC'>discord.gg/vErwUSC</a></td></tr>
<tr><td><strong>Twitter:</strong></td><td><a href='https://twitter.com/gtm_gentarium'>twitter.com/gtm_gentarium</a></td></tr>
<tr><td><strong>Telegram:</strong></td><td><a href='https://t.me/gtmcoin'>t.me/gtmcoin</a></td></tr>
<tr><td><strong>Bitcointalk ANN:</strong></td><td><a href='https://bitcointalk.org/index.php?topic=4707019.0'>bitcointalk.org/index.php?topic=4707019.0</a></td></tr>
<tr><td><strong>CoinMarketCap</strong></td><td><a href='https://coinmarketcap.com/currencies/gentarium/'>coinmarketcap.com/currencies/gentarium/</a></td></tr>
<tr><td><strong>Binary wallets</strong></td><td><a href='https://github.com/genterium-project/gentarium-2.0/Releases'>Releases</a></td></tr>
<tr><td><strong>Masternode hosting platform</strong></td><td><a href='https://mn.gtmcoin.io/'>mn.gtmcoin.io</a></td></tr>
<tr><td><strong>Asic monitoring platform</strong></td><td><a href='https://asics.gtmcoin.io/'>asics.gtmcoin.io</a></td></tr>
</tbody>
</table>

<h3>Exchanges</h3>

<table>
<tbody>
<tr><td><strong>CryptoBridge</strong></td><td><a href='https://wallet.crypto-bridge.org/market/BRIDGE.GTM_BRIDGE.BTC'>wallet.crypto-bridge.org/market/BRIDGE.GTM_BRIDGE.BTC</a></td></td></tr>
<tr><td><strong>CoinExchange:</strong></td><td><a href='https://www.coinexchange.io/market/GTM/BTC'>coinexchange.io/market/GTM/BTC</a></td></tr>
<tr><td><strong>Cryptopia:</strong></td><td><a href='https://www.cryptopia.co.nz/Exchange/?market=GTM_BTC'>cryptopia.co.nz/Exchange/?market=GTM_BTC</a></td></tr>
</tbody>
</table>

<h3>Add nodes</h3>

```
# gentarium.conf

addnode=159.69.38.117:27117
addnode=95.216.150.152:27117
addnode=95.216.144.9:27117
addnode=95.216.145.168:27117
addnode=159.69.193.179:27117
addnode=116.202.24.242:27117
```

<h3>Disable auto zeromint</h3>
```
# grntarium.conf

zeromintpercentage=0
enablezeromint=0
```

<h3>Disable/enable staking</h3>
Enabled by default
```
#gentarium.conf

# Disable
staking=0

# Enable
staking=1
```

<h3>Licence</h3>
Gentarium Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.
