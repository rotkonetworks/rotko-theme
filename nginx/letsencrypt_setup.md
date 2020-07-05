# create RSA and ec256 certificates for HTTPS use of domains/subdomains
# https://devopscraft.com/how-to-enable-brotli-in-nginx/

sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d cloud.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d matrix.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d anon.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d neurovidas.com --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d magento.neurovidas.com --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d pass.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength 2048

sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d cloud.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d matrix.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d anon.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d neurovidas.com --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d magento.neurovidas.com --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
sudo /etc/letsencrypt/acme.sh --issue --standalone --home /etc/letsencrypt -d pass.rotko.net --accountemail tommi.niemi@pm.me --ocsp-must-staple --keylength ec-256
