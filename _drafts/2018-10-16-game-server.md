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

Gli ultimi giorni li ho passati a studiare la gestione dei game server di Steam.
Non è un compito facile, in quanto le informazioni e la documentazione a disposizione non sono così semplici e immediati.

Dopo diversi tentativi sbagliati, sono finalmente riuscito ad ottenere degli ottimi risultati. Per il momento mi sono concentrato sulla creazione del programma server (al momento sviluppato in c#, quindi il server sarà disponibile solo per windows, ma spero di convertirlo per un servizio linux in modo da poterlo usare sui server vps più comuni).

![webserver](/assets/images/webserver.png){: .align-left}Al momento il server si occupa di creare il rally e di permettere ai client di collegarsi, leggendo le informazioni quali vetture utilizzabili, roadbook,
ecc...e permette di leggere le informazioni tramite un webserver in formato json

Il passaggio successivo sarà quello di effettuare dei test andando a sostituire il server attuale
(solamente web) con questo nuovo server.

Questo non è solo un aggiornamento relativo al nostro server 'ufficiale', ma permetterà ai piloti
di poter creare rally online a proprio piacimento.

Un'altra cosa che sto studiando molto interessante è il peer 2 peer networking, questo permetterà di
creare un collegamento [Steam's NAT-traversal and relay servers](https://partner.steamgames.com/doc/features/multiplayer/networking) tra il singoli client.. in modo
da poter eventualmente gestire dei rally live come i veri rallies, partendo uno dopo l'altro, vedendo
i piloti gareggiare prima di te.

Ci sono ancora tanti punti oscuri, come la connessione al server direttamente dalla sezione 'servers'
del client steam, l'anticheat, convertire il codice per linux _(se avete delle idee fatevi avanti!)_,
ma penso di essere sulla strada giusta, per permettere un'esperienza rallistica live come mai prima!
