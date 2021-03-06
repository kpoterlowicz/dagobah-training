layout: true
class: inverse, large

---
class: special, middle
# NGINX as a (Proxy) Web Server

Introduction to NGINX

slides by @natefoo, @nsoranzo

.footnote[\#usegalaxy / @galaxyproject]

---
# Reverse Proxy

Retrieves resources on behalf of a client from one or more servers (in our case Galaxy)

Extra features:
- Serve static content
- Compress selected content
- Serve over HTTPS
- Serve byte range requests
- Serve other sites from the same server
- Can provide authentication
  - Covered in _Using and configuring external authentication services_

Some of these features are available directly in uWSGI (covered in _Improving the web serving experience with uWSGI_)

---
# nginx

- Designed specifically to be a load balancing reverse proxy
- Widely used by large sites (third most popular web server)
- Can offload both uploads and downloads

We recommend nginx unless you have a specific need for Apache

---
# nginx "flavors"

nginx plugins are dynamic shared objects since [1.9.11](https://www.nginx.com/blog/compiling-dynamic-modules-nginx-plus/)

Debian/Ubuntu provide multiple nginx "flavors":
- `nginx-light`: minimal set of core modules
- `nginx-full`: full set of core modules
- `nginx-extras`: full set of core modules and extras (3rd party modules)

There is also a "Galaxy" flavor<sup>[1]</sup> (includes [upload module](https://github.com/vkholodkov/nginx-upload-module)):
- [RHEL](https://depot.galaxyproject.org/yum/) (derived from EPEL nginx)
- [Ubuntu PPA](https://launchpad.net/~galaxyproject/+archive/ubuntu/nginx)

.footnote[
<sup>[1]</sup> Still working on the automation to keep this up to date, though
]

---
# Additional Tips and Resources

[Google's PageSpeed Tools](https://developers.google.com/speed/pagespeed/insights/) can identify any compression or caching improvements you can make.

If configuring SSL (out of scope for this training), out-of-the-box SSL settings are often insecure!

Use the [Mozilla SSL config generator](https://mozilla.github.io/server-side-tls/ssl-config-generator/) to create a default config and [Qualys SSL Server Test](https://www.ssllabs.com/ssltest/analyze.html) to check it.
