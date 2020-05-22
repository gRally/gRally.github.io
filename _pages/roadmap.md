---
title: "Roadmap"
header:
  teaser: "/assets/images/stage02.jpg"
  overlay_image: "/assets/images/stage02.jpg"
  # overlay_filter: 0.75
  overlay_filter: rgba(226, 38, 52, 0.5)
  # overlay_color: "#e22634"
excerpt: "What's next?."
sitemap: false
author_profile: false
nclasses: wide
toc: true
toc_label: "What's next?"
toc_icon: "user-secret"
toc_sticky: true
permalink: /roadmap/
---
## Near term
The `Near term` stuff are things that we're working on or we plan to do shortly
{: .notice--success}

### Dynamic tyre models
<div id="container90" class="gRally-progress"></div>

This is a cool thing: with this feature the 3d tyre and texturizing is done automatically: the user will be
able to choose a different rim, different rim color, different caliper color and the core do everything.
Finally we'll have a different tyre shape when we choose the tyre for the stage.
There is also the opportunity to create a custom rim if the car needs it.

### New Engine physics
<div id="container82" class="gRally-progress"></div>
With the latest [gCarEditor](https://github.com/gRally/gCarEditor) release we started to code the Turbo and 4x4.. we're working to make it 'definitive'.



## Mid term
The `Mid term` stuff are things that we're plan to do but not immediately
{: .notice--warning}

### GH-40
<div id="container80" class="gRally-progress"></div>
We're working on a completely new car, a modern design inspired _(as usual)_ to a 70's great rally car: this car will be 4wd with a turbo engine, to let the people to play with the new physicsengine.

### Rain
<div id="container66" class="gRally-progress"></div>
In the pre-steam release we worked on the rain feature, but we preferred to release it when is 100% done, 
with the aquaplanning and different damp/wet zones.

### Game server
<div id="container60" class="gRally-progress"></div>
We decided to improve the online side using Steam to manage the game servers, so each driver will be
able to create and manage online rallies and championships.



### Surface usage
<div id="container96" class="gRally-progress"></div>

gRally will manage the surface usage in 2 ways, graphics and physics: this will be useful for live rallies
where the grip and the behaviour of the car into certain stage depends by the starting road position.

### UI for VR
<div id="container40" class="gRally-progress"></div>
At the moment gRally is shipped with a working VR management, but the VR is basic.
With this new step you can interact with the UI.

### Baitoni-Bondone
<div id="container36" class="gRally-progress"></div>
The stage where gRally runs its first kilometers. It's entered now the refreshing mode due to the sim and graphic engine developments.

### FMOD
<div id="container30" class="gRally-progress"></div>
We'll use [FMOD](https://www.fmod.com/) to manage all the sounds in game, this will be a great step for the
car modders, to create great audio behaviour especially for the car engine.



## Long term
The `Long term` stuff are things that we wish do but we don't know when
{: .notice--danger}

### Live rally championship
<div id="container20" class="gRally-progress"></div>
The main goal of gRally is the online rallies and championships, to recreate the incredible fun of the
WIRC rally championships on the past years: to complete this great milestone the way is long: we need
more cars and stages and some live test rallies to make the server stuff unbreakable.

### Rigged driver and codriver
<div id="container10" class="gRally-progress"></div>
At the moment the driver and the codriver are static and must be included in the car model..
Next step is make a rigged driver that is in the engine.



## Released
This section is to track all the stuff made linked with the build released
{: .notice--info}

### Build v1.1.0.0 of 21 May 2019

- **Controllers configuration** : This is a tricky stuff: we've completely rewrote the input management to make gRally more versatile to
  every controller the user has;
  unfortunately this took us more time than expected: but we're on the right way to fix definitively
  the controller issues. <br>We encourage everyone to report controller bugs, it's the only way for us to "test" the different hardware.
- **Unity 2018** : We want to be aligned with the Unity releases and this step should improve the framerate and the graphics.

### Build v1.0.17.13 of 21 Feb 2019

- **Dynamic tyre choice** : now changes dinamically the tyre 3d model if you use the *GRIP* tyre for tarmac or *FOREST* tyre for gravel surfaces.

### Build v1.0.16.18 of 24 Dec 2018

- **Ryggesbro** : A new gravel stage set in a swedish forest :evergreen_tree: built with the help of [Moose](https://holymooses.com/PRL/blog.php) procedural stage creator.

- **Steam Workshop** : After this, you're able to publish your mods directly with Steam using [gModsCreator](https://github.com/gRally/dev/wiki/Mods#mods-creation)
  In addition to the _classic_ mods like cars, stages and codrivers, we'll add also a **livery** mods section to share your creations!