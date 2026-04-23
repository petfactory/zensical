---
template: "work_single.html"
title: "Polestar 3 - 02"
date: 2024-10-15T00:00:00+01:00
draft: false
description: "Unreal Engine & Houdini"
poster: "polestar_2_tone_02_640.jpg"
tags: ["Unreal", "Houdini"]
info: ["Unreal", "Houdini"]
---

{{< youtube id="tzgUi-V_m80" class="media-youtube" >}}

![Unreal & Houdini](../assets/work/polestar_2_tone_01_640.jpg)
![Unreal & Houdini](../assets/work/polestar_2_tone_03_640.jpg)

This project is a mix of Houdini & Unreal. The road and parts of the environment were modeled in Houdini. The vehicle and cameras were also animated in Houdini. In Unreal I used Megascans for the cliffs, decals to the road and textures for the environment materials. I did the edit in sequencer. The scene is lit by an HDRI Backdrop. 

One thing I did in this project was to set the rotation of the HDRI Actor and skylight component per camera angle. This can be a quick way to get the lighting/background you want. To be able to set the rotation in sequencer just enable "Run Construction Script in Sequencer" on the HDRI Backdrop blueprint.

It was rendered with the path tracer in unreal 5.4 with 256 samples. The final color grade was done in DaVinci Resolve.



