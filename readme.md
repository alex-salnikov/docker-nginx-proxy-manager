#  Nginx Proxy Manager
https://nginxproxymanager.com


Docker
- https://github.com/jlesage/docker-nginx-proxy-manager


# Renewal
dns_cloudflare_api_token
- /config/workspace/docker/nginx-proxy-manager/config/letsencrypt/renewal/npm-16.conf
- /config/workspace/docker/nginx-proxy-manager/config/letsencrypt/credentials/credentials-16
- /config/workspace/docker/nginx-proxy-manager/config/log/letsencrypt/letsencrypt.log
```sh
cat /config/workspace/docker/nginx-proxy-manager/config/letsencrypt/renewal/npm-14.conf
cat /etc/letsencrypt/credentials/credentials-14
# # Cloudflare API token
# dns_cloudflare_api_token = ZZZZZZZZ
```

dns_cloudflare_api_token
- https://github.com/NginxProxyManager/nginx-proxy-manager/blob/master/global/certbot-dns-plugins.js