# PixCoin PXD

### [pixcoin.org](http://pixcoin.org)

![http://pixcoin.org](http://i.imgur.com/IiaS1J1.png)

Follow us [@PIXDOapp](http://twitter.com/PIXDOApp)

Like us on [Facebook](http://facebook.com/PIXDOApp)

Copyright (c) 2009-2013 Bitcoin Developers

Copyright (c) 2011-2013 Litecoin Developers

Copyright (c) 2013 Dogecoin Developers

Copyright (c) 2014 PixCoin Iftach Orr

## What is PixCoin?

Pixcoin is a cryptocurrency for the community of [Pixdo](http://pix.do). It is based on litecoin and is 8.75% premined. The premined coins are distributed to the users of Pixdo to allow also non savvy users to 'mine' Pixcoins.


## Community

[Reddit](http://www.reddit.com/r/pixcoins)

[Pixdo community](http://pix.do/leaderboard)

[Facebook](http://facebook.com/PIXDOApp)

[Twitter](http://twitter.com/PIXDOApp)

[Chat](http://twitter.com/PIXDOApp)





## Developers

Created by Iftach Orr, the creator of [Pixdo](http://pix.do).

Want to chat with me on skype/hangout? email me at info<_at_>pix.do

## More information:

- RPC: 40307
- NET: 40302
- Total coins: 200 million
- Block every 1 minute
- Coins mature after 40 blocks
- 90% change for block with 5 coins
- 9% change for block with 10 coins
- 0.9% change for block with 25 coins
- 0.1% change for block with 100 coins
- Rare jackpot blocks with 4,000 coins
- 8.75% of coins are 'mine-able' without CPU/GPU - [more info](http://pix.do)



## Contributors

Special thanks for the amazing guys from the community for their help

- [pingu](http://www.pingu.net/official_pingu_website_flag_page.htm)
- [Cupcake](https://twitter.com/TheAltCupcake) (Jacob Squires)
- [Plazmaz](http://github.com/Plazmaz) (Dylan Katz)
- [TadeoKondrak](http://github.com/TadeoKondrak)
- [vosjes22](http://www.reddit.com/user/vosjes22/)
- [Arm1stice](https://github.com/Arm1stice)
- [Arshvein](http://twitter.com/arshvein)


## Known pools

- http://pool.mycryptoco.in (Netherlands)
- http://poollo.com (USA)
- http://pool.pixcoin.org (USA) by [Arshvein](http://twitter.com/arshvein)
- http://pix.dgbpool.com (China)
- http://pix.5limi.com (China)


## Chain explorer

- http://explore.pixcoin.org by [Arshvein](http://twitter.com/arshvein)

## How to compile:
#### Here is an overview on how to compile the QT wallet on 3 major OSs
##### If you find any mistakes please contact me

### Mac

- sudo port install boost db48 qt4-mac openssl miniupnpc git
- git clone https://github.com/PIXDO/pixcoin.git
- cd pixcoin
- qmake pixcoin-qt.pro BDB_INCLUDE_PATH=/opt/local/include/db48 BDB_LIB_PATH=/opt/local/lib/db48 macx:BOOST_LIB_SUFFIX= BOOST_INCLUDE_PATH=/opt/local/include BOOST_LIB_PATH=/opt/local/lib OPENSSL_INCLUDE_PATH=/opt/local/include/openssl OPENSSL_LIB_PATH=/opt/local/lib/openssl MINIUPNPC_LIB_PATH=/opt/local/lib/miniupnpc MINIUPNPC_INCLUDE_PATH=/opt/local/include/miniupnpc QMAKE_CC=gcc QMAKE_CXX=g++
- make

### Ubuntu

- sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb4.8 qt-sdk libdb5.1-dev ibdb++-dev libminiupnpc-dev qrencode libqrencode-dev qt4-dev-tools qt4-qmake
- git clone https://github.com/PIXDO/pixcoin.git
- cd pixcoin
- qmake-qt4 pixcoin-qt.pro  (In some linux version I do: qmake pixcoin-qt.pro “USE_UPNP=-”)
- make

### Windows

- Install all dependencies and mingw as explained on [this guide](https://bitcointalk.org/index.php?topic=149479.0)
- qmake “USE_UPNP=-” “USE_QRCODE=-” pixcoin-qt-win.pro
- mingw32-make  -f Makefile.Release USE_QRCODE=- USE_UPNP=-



