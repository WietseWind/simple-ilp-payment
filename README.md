# Send money over ILP

Tested with local `moneyd` instance on XRP livenet.

# How to use

1. `npm install`
2. `node index.js`

A total of `5000` drops will be sent to `$twitter.xrptipbot.com/WietseWind` ([`index.js`,  line ~ 80](https://github.com/WietseWind/simple-ilp-payment/blob/master/index.js#L80)).

![](https://aapbz55.dlvr.cloud/ilpay.gif)

# Credits

Based on:

- `ilp-protocol-spsp` (by [Ben Sharafian](https://twitter.com/Sharafian_), [Repo @ Interledger](https://github.com/interledgerjs/ilp-protocol-spsp))
- `ilp-spsp` (by [Ben Sharafian](https://twitter.com/Sharafian_), [Repo @ Interledger](https://github.com/interledgerjs/ilp-spsp))
