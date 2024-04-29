# https://iammohaiminul.medium.com/run-php-application-using-docker-with-apache-and-ssl-certificates-327a8ee2056b
# https://hub.docker.com/_/php
# https://github.com/FiloSottile/mkcert#installation
choco install mkcert

# instalar certificate authority para localhosr
mkcert -install
mkcert localhost 127.0.0.1 ::1