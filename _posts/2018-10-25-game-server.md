---
title: "Game Server"
header:
  teaser: "assets/images/server.png"
  overlay_image: "assets/images/server.png"
  # overlay_filter: 0.75
  # overlay_filter: rgba(52, 38, 226, 0.5)
  overlay_filter: rgba(0, 50, 0, 0.55)
  # overlay_color: "#e22634"
categories:
  - multiplayer
tags:
  - steam
  - game-server
  - online
author: ghiboz
excerpt: "The next step of the online rallies has begun in the past nights"
classes: wide
comments: false
---

<blockquote class="twitter-tweet" data-lang="it"><p lang="en" dir="ltr">tonight I started learning <a href="https://twitter.com/steam_games?ref_src=twsrc%5Etfw">@steam_games</a> <a href="https://twitter.com/hashtag/gameServers?src=hash&amp;ref_src=twsrc%5Etfw">#gameServers</a> to use in <a href="https://twitter.com/gRallySim?ref_src=twsrc%5Etfw">@gRallySim</a> ... hard to find the right way <a href="https://twitter.com/hashtag/MadeWithUnity?src=hash&amp;ref_src=twsrc%5Etfw">#MadeWithUnity</a> <a href="https://twitter.com/hashtag/indiegames?src=hash&amp;ref_src=twsrc%5Etfw">#indiegames</a></p>&mdash; Paolo &#39;zoqıɥƃ&#39; Ghibaudo (@ghiboz) <a href="https://twitter.com/ghiboz/status/1050862131841814534?ref_src=twsrc%5Etfw">12 ottobre 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

I spent the last few days studying the management of Steam game servers. It is not an easy task, as
the information and documentation available are not so simple and immediate.

After several wrong attempts, I finally managed to get good results. For the moment I focused on
creating the server program _(currently developed in [c#](https://visualstudio.microsoft.com), so
the server will be available only for windows, but I hope to convert it to a linux service so you
can use it on the most common vps servers)_.

![webserver](/assets/images/webserver.png){: .align-left}At the moment the server is responsible for
creating the rally by reading information such as usable cars, roadbooks, etc. , allowing clients to
connect. It also provides REST functions to obtain information on the status of the rally in
progress, exported in [JSON](https://www.w3schools.com/js/js_json_syntax.asp) format.

The next step will be to perform tests by replacing the current server _(web only)_ with this new server.

This is not just an update on our 'official' server, but will allow riders to create online rallies
at will.

Another very interesting thing I'm studying is peer 2 peer networking; this will allow to create a
connection between Steam and [Steam's NAT-traversal and relay servers](https://partner.steamgames.com/doc/features/multiplayer/networking)
between individual clients, so you can possibly manage live rallies as the real rallies, starting
one after the other, seeing the pilots who are running before you by connecting directly to their
client.

There are still many obscure points, such as the connection to the server directly from the 'servers'
section of the steam client, the anticheat, converting the code to linux _(if you have any ideas get
ahead!)_ But I think I'm on the right track to allow a 'live rally experience like never before!
