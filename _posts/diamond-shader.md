---
layout: post
title: "Diamonds"
description: "A diamond shader created in blender."
date: 2024-04-10
feature_image: images/teapot.jpg
tags: [blender, shader]
---

A diamond shader, rendered and animated in Blender.

<!-- more -->

This project was a lot of fun to make! I really enjoyed applying this shader to different shapes and seeing what it looked like. While the diamond shader itself was fairly straightforward to implement (after all, the we know the index of refraction of a diamond, and with a little bit of RGB dispersion, the rest is history), I put more of my energy into setting up the scene and adjusting the lighting to make those ray bounces really noticeable. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/gHqmAotWmpE?si=j6TYFZtK0mfm94oT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My favorite part about this shader was how much rainbow is visible as each object rotates around the scene. After receiving some feedback from some real diamond professionals, though, I was able to tweak my shader a bit to reduce the rainbowy-ness (i.e. the RGB dispersion) and have a little bit more contrast:

<iframe width="560" height="315" src="https://www.youtube.com/embed/vHO_qRCaemA?si=KdXNeZkb0zpdBpCH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

So, I guess comparing the two, the initial shader gives more of a sun-catcher effect than an actual diamond effect.

![Suncatcher](images/suncatcher.jpg)
Photo from [Adobe Stock](https://www.google.com/url?sa=i&url=https%3A%2F%2Fstock.adobe.com%2Fsearch%2Fimages%3Fk%3Dsuncatcher&psig=AOvVaw2pQKHK5NsNgXOo-D4FSLaB&ust=1713480503239000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCJC0qreqyoUDFQAAAAAdAAAAABAg)

![Real Diamond](images/real-diamond.jpg)
Photo by [Arjiv Exports](https://www.pexels.com/photo/round-diamond-5362404/)