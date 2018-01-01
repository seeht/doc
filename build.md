# yarn
- curl -O -L https://nightly.yarnpkg.com/latest.tar.gz

# postgresql
- curl -O -L https://ftp.postgresql.org/pub/snapshot/dev/postgresql-snapshot.tar.bz2

# nginx
- ./configure --prefix=/g/nginx --with-http_v2_module --with-http_ssl_module --with-mail_ssl_module --with-stream_ssl_module --with-stream_ssl_preread_module
- make -j 4 && make install

