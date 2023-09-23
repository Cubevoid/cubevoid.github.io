+++
title = "Projects"
date = "2021-05-08"
aliases = ["projects","instances"]
+++

My longest ongoing project has been my server which I run at home.

I bought some ten-year-old HP Enterprise server on eBay and simply slapped in some new hard drives!

On it, I run my personal Nextcloud instance, multiple Minecraft servers connected using Bungeecord, a Spotify statistics tracker, a photo library, and more.

{{< rawhtml >}}
  <img src="/img/cloudflare.png" style="display: inline-block; vertical-align: middle; margin: 10px object-fit: none" width="32" height="32" />
  <img src="/img/nginx.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
  <img src="/img/nextcloud.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
  <img src="/img/minecraft.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
  <img src="/img/photoprism.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
{{< /rawhtml >}}

I use Nginx to reverse-proxy the public-facing web services like Nextcloud, but the traffic first passes through Cloudflare as a proxy.

The benefit to using decade-old hardware is that RAM is very cheap :)

I also use Cloudflare for my domain (colindv.xyz) and DNS -- I have dynamic DNS set up so that when my home's IP address changes, the services stay accessible.
When I am not home, I use a Wireguard VPN to manage my server remotely.

{{< rawhtml >}}
  <p>
  <img src="/img/github.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
    Check out my <a href="https://github.com/Cubevoid">GitHub</a> to see more of my projects!
  </p>
{{< /rawhtml >}}
