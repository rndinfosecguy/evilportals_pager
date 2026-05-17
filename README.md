# Evil Portals for Wifi Pineapple Pager

 This is a fork of [Evil Portals](https://github.com/kleo/evilportals). I created this fork to make these portal workable with the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) version for the Wifi Pineapple Pager.

Also I added a portal for X, as Twitter is legacy. However, I left the original version inside in case you want to use it.

 This means I changed the location of the collected credentials to the location `/root/logs/credentials.json` as described in the documentation of the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) module

This project requires you to install the [Evil Portal](https://github.com/hak5/wifipineapplepager-payloads/tree/master/library/user/evil_portal) captive portal module for the Pineapple Pager.

All the creds for the base project to [Kleo](https://github.com/kleo) of course!

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

## License

Evil Portals is distributed under the GNU GENERAL PUBLIC LICENSE v3. See [LICENSE](https://github.com/kleo/evilportals/blob/master/LICENSE) for more information.

## Disclaimer

* Usage of Evil Portals for attacking infrastructures without prior mutual consistency can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state and federal laws. Authors assume no liability and are not responsible for any misuse or damage caused by this program.

---

Discussion thread - [Hak5 Forums](https://forums.hak5.org/index.php?/topic/39856-evil-portals/)
