## s-ui-pro (s-ui + nginx) :octocat:	:open_file_folder:	
- Auto Installation (lightweight)
- Compatible with Cloudflare
- Auto SSL renewal (cronjob)
- Auto-reload nginx and s-ui
- Multi-domain and sub-domain support
- Handle WebSocket and GRPC via nginx.
- Multi-user and config via port 443
- Access to s-ui panel via nginx
- Compatible with Debian 10+ and Ubuntu 20+
- More security and low detection with nginx
- Random 150+ fake template!
  
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

**Install Panel**:dvd::package:

```
bash <(wget -qO- https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/s-ui-pro.sh) -install yes
```

> For the additional subdomain, New A,AAAA[VPSIP] Recorde , no any config in vps!!!
>
> SSL works for (yourdomain.com, *.yourdomain.com)
>
> No need to on/off CDN, during installation
>
**Add more domains**:heavy_plus_sign:	
```
bash <(wget -qO- https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/s-ui-pro.sh) -subdomain sub.newdomain.com
```

**Random fake html site**:earth_asia:	
```
bash <(wget -qO- https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/randomfakehtml.sh)
```

**Uninstall**:x:
```
bash <(wget -qO- https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/s-ui-pro.sh) -uninstall yes
```

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
### Server Configuration :wrench:🐧⚙️
![](https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/media/Server_Config.png)
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
### Client Configuration :white_check_mark:	:computer:🔌
![](https://raw.githubusercontent.com/GFW4Fun/S-UI-PRO/master/media/ClientUser_Config.png)
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
### Cloudflare Find Good IP (VPN off❗ during scanning)
Cloudflare IP Ranges: https://www.cloudflare.com/ips/

Cloudflare IP Scanner: [vfarid](https://vfarid.github.io/cf-ip-scanner/) | [goldsrc](https://cloudflare-scanner.vercel.app) | [ircfspace](https://ircfspace.github.io/scanner/)

##
[![Star History Chart](https://api.star-history.com/svg?repos=GFW4Fun/S-UI-PRO&type=Date)](https://github.com/GFW4Fun/S-UI-PRO)

