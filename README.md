# BitTube 3 - End of Life

- the bittube 3 blockchain will enter end-of-life mode at block 654000 (~ 07/29/2020 @ 4:03pm GMT)
- no mining reward will be created after block 654000
- further blocks will be mined centrally to ensure transactions are processed for another year

BitTube Release 3.1 introduced the "sweep_tube4" cli and rpc commands, the gui wallet also added this functionality.

# BitTube 4 - Launch

- bittube 4 will launch soon tube3 reached block 654000
- tube4 will launch with a reduced total supply and the current emission of tube3 is premined for distribution to current tube3 holders
- the tube4 mainnet is already in place with 301 blocks premined, the block 301 is checkpointed but not released to the public until launch
- soon block 301 has been released tube4 can be mined
- tube4 introduces cuckaroo mining and a new stratum protocol, reference pool implementation: https://github.com/BitTubeCash/cryptonote-cuckoo-js-pool
- a stagenet is available here: Pool: https://mining.bittube.app/tube4_stagenet/ ; Explorer: http://139.162.211.9:6672/ ; Webwallet: http://139.162.211.9:6651/#!/
- current bittube4 release: https://github.com/BitTubeCash/bittubecash/releases
- tube4 has a differend wallet address prefix, differend default rpc/p2p ports and differend default blockchain folders, tube3 and tube4 can be run in parallel

# BitTube 3 -> BitTube 4 Coinswap

- tube3 balances can be sent to the swap service using the "sweep_tube4" cli/rpc commands or the "Convert to BitTubeCash 4" GUI Wallet button
- balances can be sent any time and until 1 year after tube4 launch
- after tube4 has been launched balances received at the swap service will be payed to a tube4 wallet restored using the tube3 private keys or mnemonic (public wallet address prefixes differ)
- the conversion process can be tested using tube3 / tube4 stagenets
