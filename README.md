# Evil Portals for Wifi Pineapple Pager

 This is a fork of [Evil Portals](https://github.com/kleo/evilportals). I created this fork to make these portal workable with the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) version for the Wifi Pineapple Pager. This means I changed the location of the collected credentials to the location `/root/logs/credentials.json` as described in the documentation of the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) module

This project requires you to install the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) captive portal module for the Pineapple Pager.

## Installation and Usage

Clone the repository

    git clone https://github.com/rndinfosecguy/evilportals_pager.git

Change directory

    cd evilportals_pager/portals/

Copy the portals you wish to use on the Tetra at `/root/portals/`

    scp -r * root@172.16.52.1:/root/portals/

I recommend to take care that the `credentials.json` file exists and has open permissions.

    touch /root/logs/credentials.json; chmod 777 /root/logs/credentials.json

How you should be abple to use Evil Portal as described on the repository by Hak5

## Screenshots

<img src="https://user-images.githubusercontent.com/13497504/88472836-bc7b9780-cf49-11ea-986e-9ff6c05abc01.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34363975-1d4b32ca-eabc-11e7-8532-2105a160c5c1.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34363977-1e8f4ca2-eabc-11e7-885e-e7dbd845e217.png" width="200"/>

<img src="https://user-images.githubusercontent.com/13497504/99083728-e643f180-2600-11eb-95b0-9d181001863b.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/99057411-b849b780-25d6-11eb-8e88-5e4d7dd32ee6.png" width="200"/> <img src="https://user-images.githubusercontent.com/13497504/34366525-bba03dc4-ead7-11e7-8bea-a3fa9ae33ef4.png" width="200"/>

## License

Evil Portals is distributed under the GNU GENERAL PUBLIC LICENSE v3. See [LICENSE](https://github.com/kleo/evilportals/blob/master/LICENSE) for more information.

## Disclaimer

* Usage of Evil Portals for attacking infrastructures without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. Authors assume no liability and are not responsible for any misuse or damage caused by this program.

---

Discussion thread - [Hak5 Forums](https://forums.hak5.org/index.php?/topic/39856-evil-portals/)
