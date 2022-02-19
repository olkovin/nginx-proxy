# NGINX

Here be useful Nginx configs, security hardening, object or service related optimizations, etc.

## Installation

Almost in all cases, simply put it into your `/nginx/conf.d/` or `/conf-enabled/` directory.
If you need some help with this, let me know, I try to make some detailed instructions for you.

## Configs
  - pve.conf — hardened and secured Nginx configuration for your ProxmoxVE WebUI.
    > Tested on version 7.1-7 and 6.3-3
  - unifi.conf - hardened and secured Nginx configuration for your Unifi Cloud Controller.
    > Test on version 6.5.55
  - default-server.conf - Miniature config that disables direct access to a web server by ip address
    > Returns 444, but you can change it to a 404 or whatever.

## Subconfig
Some regularly used configuration parts, usually included in my configs.
\n I recommend downloading them with the main config parts.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Donation
If u wanna buy me a coffee or something else, you can do it in several ways:

- BTC: `1GFEEWZwM4xLsvjyC4DZhuHS3BT6r5uwPj`
- ETH: `0x8477951edc39d0936803d9bec82963e88da86fe4`
- PayPal: [Click](https://www.paypal.com/donate/?hosted_button_id=DCB42BR7KBRN6)

## License
[GPL 3.0](https://choosealicense.com/licenses/gpl-3.0/)
