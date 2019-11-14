#### Why this project?

ngx_http_geoip_module does not support GeoIP2

see 

[NGINX ngx_http_geoip_module, support for MaxMind .dat and .mmdb IP databases](https://stackoverflow.com/questions/43817973/nginx-ngx-http-geoip-module-support-for-maxmind-dat-and-mmdb-ip-databases)

[NGINX Dynamic Modules: How They Work](https://www.nginx.com/blog/nginx-dynamic-modules-how-they-work/)

[Nginx and geoip lookup with geoip2 module](https://echorand.me/posts/nginx-geoip2-mmdblookup/)

[dynamic module is not binary compatible with nginx 1.10.3](https://github.com/fdintino/nginx-upload-module/issues/103#)

surely, you don't want build nginx on server.

#### Features

- build ` ngx_http_geoip2_module.so` and `ngx_stream_geoip2_module.so`


#### Problems

- modify `NGINX_BUILD_ARGS` mostly needed change for `binary compatible`