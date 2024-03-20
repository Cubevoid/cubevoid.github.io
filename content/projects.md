+++
title = "Projects"
date = "2021-05-08"
aliases = ["projects","instances"]
+++

## GitHub projects

- [Atari Object Prediction](https://github.com/Cubevoid/atari-obj-pred): **Transformer** + **CNN**-based model to predict future object locations in Atari games using masks from foundational models like **Segment Anything** or **YOLO**, in order to improve performance of general RL-based agents.
- [Feeling Hungry](https://github.com/SachaGoldman/FeelingHungry?tab=readme-ov-file#feelinghungry): web app using an **NLP** model to recommend healthy alternatives to cravings. Uses embeddings from **spaCy** , with custom vector database using **FAISS** for speed. Uses DuckDuckGo and Google Maps APIs to quickly return rich search results. Categorizes food options with similar vector embeddings using nutrition facts like fat and sodium levels.
- [SuperMarAI](https://github.com/Cubevoid/SuperMarAI): AI trained using NEAT, a genetic algorithm, to play Super Mario. Emulates the game using gym; similar to **reinforcement learning**.
- Contributions to various **open-source** projects such as [pkg2appimage](https://github.com/AppImageCommunity/pkg2appimage), a tool for generating Linux versions of apps, or GNOME (Linux desktop) extension [audio-output-switcher](https://github.com/adaxi/audio-output-switcher)
- [Mathler solver](https://github.com/Cubevoid/mathler-solver): finds solutions for Mathler, a Wordle-like game. Improves on brute-force by constraining search space

## Other projects

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

## Ulti.js

Javascript library for creating sports visualizations for Ultimate Frisbee. Scroll to the bottom for demo ↓

!! **Change to light theme to view properly** !!

### Features:
- Vertical and horizontal field arrangements
- Addition and removal of players
- Getting and setting a player’s location
- Jersey numbers
- Name and type (offense/defense) of players
- Showing and hiding the disc
- Giving ownership of the disc to a player
- Getting and setting the disc’s position
- Presets for common configurations
- Tooltips on hover

{{< rawhtml >}}

<script src="../ulti.js"></script>
<link rel="stylesheet" type="text/css" href="../ulti.css" />
<link rel="stylesheet" type="text/css" href="../docs.css" />

<script src="../examples.js"></script>


  <p>
  <img src="/img/github.png" style="display: inline-block; vertical-align: middle; margin: 10px" width="32" height="32" />
    Check out my <a href="https://github.com/Cubevoid">GitHub</a> to see more of my projects!
  </p>
{{< /rawhtml >}}
