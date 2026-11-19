# Awesome-Web-Server-Reverse-Proxy

# Top Web Server & Reverse Proxy Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on High-Performance HTTP/3 Web Servers, Cloud-Native Reverse Proxies, Load Balancers, API Gateways & Automatic TLS Termination*  
**Last updated: November 2026**

This repository (`Awesome-Web-Server-Reverse-Proxy`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Web Server & Reverse Proxy** — Top Web Server Reverse Proxy (Opensource) 🌟 Star if you like it! 🌟. These tools serve static and dynamic web traffic, terminate TLS/SSL certificates automatically via ACME, route L4/L7 traffic, load balance microservices, terminate HTTP/3 (QUIC), and protect origin servers behind Web Application Firewalls (WAF).

**Examples** include Caddy, Cloudflare, Fastly, Akamai, NGINX Plus, Envoy Gateway, Traefik Enterprise, HAProxy Enterprise, F5 BIG-IP, Kong Konnect, and `caddyserver/caddy` (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for modern automatic-HTTPS web servers, cloud-native Ingress/Gateway proxies, Rust memory-safe reverse proxies, Docker-integrated proxy managers, and high-throughput L4/L7 load balancers — ideal for DevOps engineers, platform architects, SREs, and self-hosters.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cloudflare](https://cloudflare.com)**  
  Global anycast edge reverse proxy, CDN, DDoS mitigation, Zero Trust tunnel, and serverless edge computing platform protecting millions of web properties.

- **[Fastly](https://fastly.com)**  
  High-speed edge cloud platform and programmable reverse proxy featuring instant cache purging, VCL/Compute@Edge routing, and next-gen WAF protection.

- **[Akamai](https://akamai.com)**  
  Enterprise content delivery network, intelligent edge routing, and cloud security reverse proxy platform powering global high-traffic applications.

- **[NGINX Plus (F5)](https://f5.com)**  
  Commercial enterprise web server, load balancer, and API gateway extending open-source NGINX with active health checks, JWT auth, and dynamic reconfiguration.

- **[F5 BIG-IP](https://f5.com)**  
  Enterprise application delivery controller (ADC), L4/L7 load balancer, SSL/TLS offload engine, and advanced web application firewall.

- **[Traefik Hub & Enterprise](https://traefik.io)**  
  Commercial cloud-native API management, Ingress controller, and distributed reverse proxy platform built on top of open-source Traefik Proxy.

- **[HAProxy Enterprise](https://haproxy.com)**  
  Enterprise-grade TCP/HTTP load balancer and reverse proxy adding real-time bot management, WAF modules, and multi-datacenter traffic steering.

- **[Kong Konnect](https://konghq.com)**  
  SaaS-managed unified API gateway, service mesh, and AI reverse proxy control plane built around Kong Gateway and Envoy.

- **[AWS Application Load Balancer & CloudFront](https://amazon.com)**  
  Managed cloud L7 reverse proxy and global edge delivery service offering path/host routing, ACM certificate management, and WAF integration.

- **[ngrok](https://ngrok.com)**  
  Unified cloud ingress-as-a-service platform providing instant secure reverse proxy tunnels, global load balancing, and identity-aware access to local or private services.

- **[Caddy Enterprise / Hosted Edge](https://caddyserver.com)**  
  Commercial support and enterprise fleet management extensions for Caddy's automatic-HTTPS web server and reverse proxy architecture.

## Open-Source GitHub Projects

- **[Caddy (caddyserver/caddy)](https://github.com)**  
  Fast, extensible open-source web server and reverse proxy written in Go that pioneered automatic HTTPS (Let's Encrypt / ZeroSSL), HTTP/3 support, and zero-downtime JSON/Caddyfile reloads.

- **[NGINX (nginx/nginx)](https://github.com)**  
  The world's most widely deployed open-source high-performance HTTP web server, reverse proxy, mail proxy, and L4/L7 load balancer built on an asynchronous event-driven architecture.

- **[Envoy Proxy (envoyproxy/envoy)](https://github.com)**  
  CNCF graduated open-source L7 edge and service proxy written in C++ designed for cloud-native microservices, gRPC routing, dynamic xDS APIs, and deep observability.

- **[Envoy Gateway (envoyproxy/gateway)](https://github.com)**  
  Open-source Kubernetes Gateway API implementation powered by Envoy Proxy, simplifying ingress routing, rate limiting, and TLS termination.

- **[Traefik Proxy (traefik/traefik)](https://github.com)**  
  Modern open-source cloud-native reverse proxy and load balancer written in Go that automatically discovers services from Docker, Kubernetes, Consul, and Etcd with built-in Let's Encrypt TLS.

- **[HAProxy (haproxy/haproxy)](https://github.com)**  
  Industry-standard open-source high-availability TCP/HTTP load balancer and reverse proxy renowned for extreme performance, low latency, and granular ACL traffic routing.

- **[Pingora (cloudflare/pingora)](https://github.com)**  
  Open-source, memory-safe Rust framework built by Cloudflare for constructing ultra-fast programmable HTTP/1, HTTP/2, and gRPC reverse proxies at internet scale.

- **[River (memorysafety/river)](https://github.com)**  
  Open-source memory-safe reverse proxy application built on top of Cloudflare's Pingora Rust library by the Internet Security Research Group (Prossimo).

- **[Nginx Proxy Manager (NginxProxyManager/nginx-proxy-manager)](https://github.com)**  
  Popular open-source Docker-based reverse proxy management interface wrapping NGINX with a clean web UI for one-click Let's Encrypt SSL certificates and access lists.

- **[Zoraxy (tobychui/zoraxy)](https://github.com)**  
  All-in-one open-source general-purpose reverse proxy and network forwarding manager written in Go featuring a modern web dashboard, automatic ACME TLS, GeoIP filtering, and ZeroTier integration.

- **[BunkerWeb (bunkerity/bunkerweb)](https://github.com)**  
  Next-generation open-source web server and reverse proxy built on NGINX that integrates a full Web Application Firewall (ModSecurity/CRS), bot protection, and automated TLS out of the box.

- **[SWAG — Secure Web Application Gateway (linuxserver/docker-swag)](https://github.com)**  
  All-in-one open-source container combining an NGINX web server and reverse proxy with built-in Certbot SSL automation, Fail2ban intrusion prevention, and hundreds of pre-built app templates.

- **[Cosmos Cloud (azukaar/Cosmos-Server)](https://github.com)**  
  Open-source self-hosted reverse proxy, container manager, and identity gateway offering built-in SmartShield anti-DDoS, SSO authentication, and automatic HTTPS.

- **[Pangolin (fosrl/pangolin)](https://github.com)**  
  Open-source tunneled reverse proxy and identity-aware access platform built on Traefik and WireGuard for securely exposing private homelab and enterprise services without opening firewall ports.

- **[OpenResty (openresty/openresty)](https://github.com)**  
  High-performance open-source web platform extending NGINX with LuaJIT scripting to build dynamic edge proxies, custom WAFs, and high-concurrency API gateways.

- **[APISIX (apache/apisix)](https://github.com)**  
  Apache Foundation cloud-native, dynamic, real-time open-source API gateway and reverse proxy built on NGINX and etcd with hot-reloading plugins.

- **[Kong Gateway OSS (Kong/kong)](https://github.com)**  
  Cloud-native, platform-agnostic open-source API gateway and reverse proxy built on OpenResty/NGINX for managing, securing, and extending microservices.

- **[FrankenPHP (php/frankenphp)](https://github.com)**  
  Modern open-source PHP application server built directly on top of the Caddy web server, featuring worker mode, Early Hints, and automatic HTTPS.

- **[RoadRunner (roadrunner-server/roadrunner)](https://github.com)**  
  High-performance open-source Go application server, load balancer, and process manager accelerating PHP and gRPC workloads with HTTP/3 support.

- **[Varnish Cache (varnishcache/varnish-cache)](https://github.com)**  
  High-speed open-source HTTP reverse proxy accelerator and caching engine programmable via Varnish Configuration Language (VCL).

- **[Apache HTTP Server (apache/httpd)](https://github.com)**  
  Foundational open-source HTTP web server and modular reverse proxy (`mod_proxy`) powering web infrastructure for over three decades.

- **[Apache Traffic Server (apache/trafficserver)](https://github.com)**  
  Scalable, modular open-source HTTP/1.1, HTTP/2, and HTTP/3 caching forward and reverse proxy capable of handling tens of thousands of concurrent connections.

- **[YARP — Yet Another Reverse Proxy (dotnet/yarp)](https://github.com)**  
  Microsoft-backed open-source reverse proxy toolkit for .NET designed for building customizable, high-throughput L7 proxies and load balancers.

- **[Sozu (sozu-proxy/sozu)](https://github.com)**  
  Open-source HTTP reverse proxy written in Rust supporting hot reconfiguration without dropping existing connections and memory-safe TLS termination.
