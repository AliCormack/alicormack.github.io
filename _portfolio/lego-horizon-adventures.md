---
title: "LEGO® Horizon Adventures™"
categories: Portfolio
excerpt: "Building detailed LEGO visuals brick by brick"
header:
  # image: /assets/images/portfolio/lego-horizons/LegoHorizons1.jpg
  overlay_image: /assets/images/portfolio/lego-horizons/LegoHorizons4.jpg
  overlay_filter: 0.5
  teaser: /assets/images/portfolio/lego-horizons/LegoHorizons1.jpg
  actions:
    - label: "Playstation Store Page"
      url: "https://www.playstation.com/en-gb/games/lego-horizon-adventures/"
sidebar:
  - title: "Role"
    # image: http://placehold.it/350x250
    # image_alt: "logo"
    text: "Principal Graphics Programmer"
  - title: "Platforms"
    text: "Playstation 5, Nintendo Switch, PC\n\nReleased November 2024"
gallery-ps5:
  - url: /assets/images/portfolio/lego-horizons/LegoHorizons1.jpg
    image_path: /assets/images/portfolio/lego-horizons/LegoHorizons1.jpg
    alt: "placeholder image 1"
  # - url: /assets/images/portfolio/lego-horizons/LegoHorizons2.jpg
  #   image_path: /assets/images/portfolio/lego-horizons/LegoHorizons2.jpg
  #   alt: "placeholder image 2"
  - url: /assets/images/portfolio/lego-horizons/LegoHorizons3.jpg
    image_path: /assets/images/portfolio/lego-horizons/LegoHorizons3.jpg
    alt: "placeholder image 3"
  - url: /assets/images/portfolio/lego-horizons/LegoHorizons4.jpg
    image_path: /assets/images/portfolio/lego-horizons/LegoHorizons4.jpg
    alt: "placeholder image 3"
gallery-switch:
  # - url: /assets/images/portfolio/lego-horizons/switch/switch1.png
  #   image_path: /assets/images/portfolio/lego-horizons/switch/switch1.png
  #   alt: "placeholder image 1"
  - url: /assets/images/portfolio/lego-horizons/switch/switch2.jpg
    image_path: /assets/images/portfolio/lego-horizons/switch/switch2.jpg
    alt: "placeholder image 2"
  - url: /assets/images/portfolio/lego-horizons/switch/switch3.png
    image_path: /assets/images/portfolio/lego-horizons/switch/switch3.png
    alt: "placeholder image 2"
  - url: /assets/images/portfolio/lego-horizons/switch/switch4.jpg
    image_path: /assets/images/portfolio/lego-horizons/switch/switch4.jpg
    alt: "placeholder image 2"
classes: wide
---

For LEGO Horizon Adventures the goal was to raise the visual quality bar of LEGO games, and achieve movie quality on console hardware. Working with the excellent art team at Studio Gobo, we got pretty close to that goal, and managed to launch simultaneously on all platforms, including Switch.

As principal graphics programmer I was involved in many areas of this effort:

* Leading internal and external graphics teams, and co-ordination with other departments
* Design of highly scalable rendering pipeline for target platforms, with minimal additional development cost
* Identification and resolution of performance bottlenecks across CPU and GPU
* Mesh drawing modifications for runtime LEGO model recoloring
* Resolution of low-level PC GPU vendor specific crashes
* Improved tracking post-launch of GPU crashes
* Reduction of shadow cache invalidations
* HDR and ACES tonemapping improvements
* Ensuring Nintendo Switch GPU performance best-practices
* Efficient per-fragment SH baked Global Illumination on low end devices
* Improvements to GPU based light baking
* Baked bent-normal skylight diffuse and specular occlusion
* Additional debug visualisations (draw calls, GBuffer targets)
* Modification to depth-stencil tests for post-procesing techniques
* Resolved platform-specific shader compilation issues

{% include gallery id="gallery-ps5" caption="Playstation 5 Screenshots" %}

{% include video id="VJE4hQetwRg" provider="youtube" %}

{% include gallery id="gallery-switch" caption="Nintendo Switch Screenshots" %}

{% include video id="IJLdXNhGQ-Q" provider="youtube" %}