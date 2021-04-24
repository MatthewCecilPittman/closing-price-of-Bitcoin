# closing-price-of-Bitcoin
closing price of Bitcoin using PINE in the Pine editor on trading view
// This source code is subject to the terms of the Mozilla Public License 2.0 at https://mozilla.org/MPL/2.0/
// © MatrixDivinity

//@version=4
study("price of Bitcoin")
security("BTCUSD","D", close)
BTC_price = security("BTCUSD","D",close)
plot(BTC_price)
