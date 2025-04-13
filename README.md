# An Example of self signed Root CA for setup https on NGINX 

base on https://resonant-cement-f3c.notion.site/Self-Signed-Certificates-Create-your-own-Certificate-Authority-CA-for-local-HTTPS-sites-536636144b124904a52e4ac68973bb2c


* put `./cert/MyOrg-RootCA.crt` to your computer's trusted root certificates store.
* edit `/etc/hosts` for myserver.local to 127.0.0.1
* run `docker compose up`
* Than open https://myserver.local on your browser