BuzzCoin v3.0.1

Copyright (c) 2013 NovaCoin Developers Copyright (c) 2011-2012 PPCoin Developers
Copyright (c) 2017 BUZZ Developers Distributed under the MIT/X11 software
license, see the accompanying file license.txt or
http://www.opensource.org/licenses/mit-license.php. This product includes
software developed by the OpenSSL Project for use in the OpenSSL Toolkit
(http://www.openssl.org/). This product includes cryptographic software written
by Eric Young (eay@cryptsoft.com).

# Intro

BuzzCoin is a free open source project derived from Bitcoin, with the goal of
providing a long-term energy-efficient scrypt-based crypto-currency.

Built on the foundation of Bitcoin, PPCoin and NovaCoin, innovations such as
proof-of-stake help further advance the field of crypto-currency.

# Development

## Useful debugging command utilities

### OS X

```
./BuzzCoin-Qt.App/Contents/MacOS/BuzzCoin-Qt --debug # debug
cd ~/Library/Application Support/BuzzCoin && tail -f debug.log # live debug output
/usr/local/opt/qt/bin/qmake -o Makefile buzzcoin.pro RELEASE=1 USE_QRCODE=1 # proper qmake using pro
```
