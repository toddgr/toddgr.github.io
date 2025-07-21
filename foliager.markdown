---
layout: page
title: 
permalink: /projects/foliager/
---

<a href="https://github.com/toddgr/foliager"><img src="/images/Page_Banners/foliager_banner.png" alt="Foliager"></a>

> A foliage generation system that uses real scientific data and artificial intelligence to generate realistic forest ecosystems.

<img src="/images/foliager/teaser.jpg" alt="Teaser Photo">

# Masters Project

For my Master's project, I made a system that procedurally generates foliage by using real, scientific data and formulas from a growth model called [3-PG](https://3pg.forestry.ubc.ca/). Where 3-PG is only used with tree species that already exist in their database, my implementation aims to be more flexible, and uses statistical analysis to estimate different aspects of tree growth based on the existing database.

<img src="/images/foliager/northernredoak.png" alt="Northern Red Oak" style="height: 350px; vertical-align: middle; margin-right: 10px;">
<img src="/images/foliager/northernredoak_closeup.png" alt="Northern Red Oak Closeup" style="height: 350px; vertical-align: middle;">

> The generated trees are not only grown in a scientifically realistic way, but they also LOOK scientifically realistic.

This means that my system can be used to generate ANY type of tree, not just the ones that have recorded data about them!

# SIGGRAPH 2025
<img src="/images/foliager/SIGGRAPH_POSTER.png" alt="SIGGRAPH Poster">

I have a lot of ideas for how this could be used-- in games, in movies, in forestry simulations-- but the primary goal for this project is to be able to specify a climate, and quickly be able to generate a forest of trees that would be found in that climate and grow in realistic patterns.


This project uses the OpenAI API to gather common knowledge about climates and tree species, and simulations are scripted in Blender. You can check out my repository for foliager [here](https://github.com/toddgr/foliager).

