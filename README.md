# ngx_http_dns_resolv_module
ngx_http_dns_resolv_module


```
  location ~ /dns/(.+) {
    resolver 8.8.8.8;
    dns_resolv_host $1;
  }
```

```
curl loclahost/dns/google.com
```
