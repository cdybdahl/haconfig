# How to renew certificate:

*NOTE: It may be necessary to enable the ha_letsencrypt port forwarding rule on the router. Test next time and remove this note if appropriate*

1. cd certbot
1. sudo systemctl stop home-assistant.service
1. sudo ./certbot-auto renew
1. sudo-reboot