# WOWRig Proxy
Extremely high performance Wownero (WOW) Stratum protocol proxy, can easily handle over 100K connections on cheap $5 (1024 MB) virtual machine. Reduce number of pool connections up to 256 times, 100K workers become just 391 worker on pool side. Written on C++/libuv like [WOWRig](https://github.com/duggavo/wowrig) miner.

## Download
* Binary releases: https://github.com/duggavo/wowrig-proxy/releases
  
## Usage
:boom: If you use Linux and want handle more than **1000 connections**, you need [increase limits of open files](https://github.com/xmrig/xmrig-proxy/wiki/Ubuntu-setup).

Set your wallet address and spend key in the config.json file, then run wownerod with `--zmq-rpc-bind-port 34569` for the best performance.

## Donations

Default donation fee is 0.7% (7 per mille)