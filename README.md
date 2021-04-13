<a href="https://aimeos.org/">
    <img src="https://cashback.cash/img/logogit.png" alt="Caskback logo" title="Caskback" align="right" />
</a>

Caskback (CASH) integration/staging repository
======================
> Official Repository - PoS/MN

:star: Caskback is an experimental digital currency that enables anonymous, instant payments to anyone, anywhere in the world. Caskback uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Caskback is the name of the open source software which enables the use of this currency.

<p align="center"><a href="https://github.com/cashback-coin/cashback-2.0/releases"><img src="https://cashback.cash/img/wallet.png" /></a></p>
<hr>

|Specifications		   		| 					  |						|					  |
|:-------------------- 		| :------------------ | :------------------ | :------------------ |
|Name  		                | `Caskback`             |Blocks per Day   	| `1440`              |
|Ticker 				    | `CASH`               |Block Time  			| `1 MINUTE`          |
|Algorithm					| `Quark`             |Stake Min Age		| `2 HOURS`           |
|Type 						| `PoS/MN`            |Halving Block  		| `394200`            |
|Total Suply 			    | `18,000,000 CASH`    |Port 			    | `17773`    		  |
|Masternode Collateral      | `5,000 CASH`         |Datadir			    | `.cash`			  |

<p align="center"><img src="https://cashback.cash/img/gitblocks.png" /></a></p>

Add nodes
======================
```
# cashback.conf

addnode=104.238.133.126:17773
addnode=140.82.44.143:17773
addnode=104.238.134.207:17773
addnode=140.82.1.119:17773
addnode=45.32.249.115:17773
addnode=108.61.96.132:17773
addnode=45.32.139.101:17773
addnode=8.9.36.25:17773
```

Staking
======================
Enable
```
# cashback.conf
staking=1
```

Disable
```
# cashback.conf
staking=0
```

<h3>Licence</h3>
Caskback is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.
# cashbackcoin
