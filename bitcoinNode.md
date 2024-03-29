# Personal Bitcoin node  

## Requirements  
It is a device that you plug into your router. It has multiple use cases:  
- Running your own node gives the benefits:
  - connect your wallet to the node (no need to trust 3rd party servers)
  - create a cold wallet, without internet access
  - better "privacy"
  - [you are contributing to the network's security](https://bitcoin.stackexchange.com/questions/66261/how-can-i-benefit-by-running-a-full-bitcoin-node)
- Lightning node:
  - Manging and seting up lightning node is hard, they must be online 24/7. This device is plug&play
  - connect your mobile lightning wallet to this device
- BtcPayServer
  - If you are a merchant you can start accepting bitcoin payments with 0 fees -> you own your bitcoins. 
    - Connect to exchange and convert bitcoins to local currency at any time you want 
  - Connect to your website automaticly
- [Tor network](https://bitcoin.stackexchange.com/questions/70069/how-can-i-setup-bitcoin-to-be-anonymous-with-tor)
  - You can chose to operate this node over tor network
    - better privacy 
    - Easier lightning setup via tor or port forwarding
  - [https://en.bitcoin.it/wiki/Tor](https://en.bitcoin.it/wiki/Tor)
- Personal VPN
  - Browse web through this device
    - Ad blocking
    - Can browse and access TOR website (darknetmarkets?)
    - Connect when on public Wifis 

- BONUS
  - use this device as your own NAS by attaching more HDD devices* (nextcloud)
  - adblocker for your home network*
  - your own website (blog)
  - torrent
  - password manager
  - Todo


User setup this device by pluging it into electricity and wifi via ethernet cable.  Device should either have a display or a blinking led light that indicates it is booted. The admin dashboard should be "automagicaly" visible on local internet by accessing bitcoinnode.local or something similar. In worst case scenario it should be accessible by local IP address.  

**Admin dashboard needs the following:**  
- Device health (temparature, disk status, CPU usage, network usage)
- Block explorer for monitoring bitcoin blockchain
- Bitcoin wallet interface that has all capabilites of a modern wallet
- Lightning wallet interface with all capabilites
- BtcPayServer entry point for managing your web stores
- Personal VPN settings, approved devices etc..
- Tor network status

## Specifications: 
- General:
    - Bitcoin node -> 
    - Lightning node -> Sending, receiving, managing payment channels
      - lightning hub? (https://github.com/BlueWallet/LndHub)
    - BtcpayServer -> it should use bitcoin node and lightning node. 
    - Electrum node -> https://electrum.readthedocs.io/en/latest/faq.html
- Bonus:
  - Web interface for BTC & Lightning wallet wallet
    - all basic functinalities of a wallet
  - Web interface for blockexplorer
  - Optional Personal VPN -> use it when on public wifi's etc... 
  - Optional Tor node -> Support tor network


## Other
- copy something like tihs: https://lightbo.lt/#
- https://github.com/chris-belcher/electrum-personal-server
  - combination of electrum and bitcoin core
- https://lightninginabox.co/
- https://lightninginabox.co/product/raspiblitz-raspberry-pi-lightning-node/
- [samourai dojo](https://github.com/Samourai-Wallet/samourai-dojo)
- https://www.lopp.net/bitcoin-information/full-node.html
- https://shiftcrypto.ch/base/
- https://mynodebtc.com/products/community_edition
  - https://creativecommons.org/licenses/by-nc/4.0/!!!!!
- https://shop.fulmo.org/
- tor node. https://fastrelay.org/
- calibre -> ebook manager

## Costs:
- [RPI 4 4gb 50€](https://si.farnell.com/raspberry-pi/rpi4-modbp-4gb/raspberry-pi-4-model-b-4gb/dp/3051887)
- 1 TB 2.5" HDD 40-60€
- Case 20€
- ?? 20€
- https://www.aliexpress.com/item/4000059786966.html?spm=a2g0s.12269583.0.0.4081371eJ2oays
Final costs: ~150€
