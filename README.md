# awesome-nginx-security

A curated list of awesome links related to application security related to the environments with NGINX or Kubernetes Ingres Controller (based on NGINX)

## Articles

- [Building a Security Shield for Your Applications with NGINX](https://www.nginx.com/blog/build-application-security-shield-with-nginx-wallarm)
- [Pitfalls and Common Security Mistakes in NGINX configuration](https://www.nginx.com/resources/wiki/start/topics/tutorials/config_pitfalls/)
- [Let's Encrypt & Nginx](https://letsecure.me/secure-web-deployment-with-lets-encrypt-and-nginx/)
- [Installing the Nginx Plus with mod_security WAF](https://www.nginx.com/resources/admin-guide/nginx-plus-modsecurity-waf-installation-logging/)
- [CloudFlare's new WAF: compiling to Lua (based on Nginx)](https://blog.cloudflare.com/cloudflares-new-waf-compiling-to-lua/)
- [Tips to harden your nginx configuration](https://www.acunetix.com/blog/articles/nginx-server-security-hardening-configuration-1/#comment-16863)
- [How To Protect an Nginx Server with Fail2Ban on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-protect-an-nginx-server-with-fail2ban-on-ubuntu-14-04)
- [Important steps to take to make an Nginx server more secure](https://help.dreamhost.com/hc/en-us/articles/222784068-The-most-important-steps-to-take-to-make-an-Nginx-server-more-secure)
- [Building Security into Cloud Native Apps with NGINX](https://www.helpnetsecurity.com/2019/02/19/building-security-into-cloud-native-apps-with-nginx/)

## Talks

- [AppSecCali 2019 Lightning Talk - Building Cloud-Native Security for Apps and APIs with NGINX/Kubernetes](https://www.youtube.com/watch?v=xcjFgZ_FN4w) - super practical
- [Let's Encrypt TLS for Every (video)](https://www.youtube.com/watch?v=ac4tE4_4nU0)
- [Behavior Based Security with Repsheet: Aaron Bedra @nginxconf 2014 (video)](https://www.youtube.com/watch?v=9AyaVxzqYoA)
- [Scripting NGINX for Overload Protection (video)](https://www.youtube.com/watch?v=uFm-tp4t2mE)
- [Naxsi, a WAF for NGINX (video)](https://www.youtube.com/watch?v=JiJHCodn_PQ)

## Configuration

- [gixy](https://github.com/dvershinin/gixy) - a tool to analyze Nginx configuration to prevent security misconfiguration
- [nginxconfig.io](https://nginxconfig.io) - [GitHub](https://github.com/valentinxxx/nginxconfig.io) - Online nginx configuration generator for general purposes.

## WAF for NGINX. Protect APIs, applications and microservices

- [mod_security](https://github.com/SpiderLabs/ModSecurity-nginx) - mod_security for NGINX
- [naxsi](https://github.com/nbs-system/naxsi) - NAXSI is an open-source, high performance, low rules maintenance WAF for NGINX.
- [NGINX 3rd Party Modules](https://www.nginx.com/resources/wiki/modules/) -  a list of third-party modules (including security-related) for NGINX and NGINX Plus, created and maintained by members of the NGINX community
- [Wallarm](https://wallarm.com) - Advanced Cloud-Native WAF

## WAF for Kubernetes. Protect Cloud Native Apps

- [WAF for Kubernetes](https://wallarm.com/solutions/waf-for-kubernetes/) - Deploy WAF in Kubernetes on Ingeress Controller or as a sidecar proxy

## Bot mitigation / Anti-scrapping / Account take-over prevention 

- [testcookie-nginx-module](https://github.com/kyprizel/testcookie-nginx-module) - Simple robot mitigation module using cookie based challenge/response technique 

## NGINX forks

- [lua-resty-waf](https://github.com/p0pr0ck5/lua-resty-waf) - High-performance WAF built on the OpenResty stack
- [bunkerized-nginx](https://github.com/bunkerity/bunkerized-nginx) - nginx based Docker image secure by default.

## Other

- [Secure nginx config. GIST](https://gist.github.com/plentz/6737338) - nginx configuration for improved security and performance

