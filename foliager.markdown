---
layout: page
title: 
permalink: /projects/foliager/
---

<a href="https://github.com/toddgr/foliager"><img src="/images/Page_Banners/foliager_banner.png" alt="Foliager"></a>

> A foliage generation system that uses real scientific data and artificial intelligence to generate realistic forest ecosystems.

For my Master's project, I'm currently working on a system that procedurally generates foliage for Unreal Engine by using real, scientific data and formulas from a growth model called [3-PG](https://3pg.forestry.ubc.ca/). Where 3-PG is only used with tree species that already exist in their database, my implementation aims to be more flexible, and uses statistical analysis to estimate different aspects of tree growth based on the existing database.

This means that my system can be used to generate ANY type of tree, not just the ones that have recorded data about them!

I have a lot of ideas for how this could be used-- in games, in movies, in forestry simulations-- but the primary goal for this project is to be able to specify a climate, and quickly be able to generate a forest of trees that would be found in that climate and grow in realistic patterns.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGL0G65x0Q&#x2F;2ugelMkEl1YF2mbjEV5POQ&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGL0G65x0Q&#x2F;2ugelMkEl1YF2mbjEV5POQ&#x2F;view?utm_content=DAGL0G65x0Q&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Foliager</a> by Gracey Todd

Here's some proof of concepts with where I'm at now:

[insert some of the simulation results here]

At the moment, I represent individual trees with stylized assets I created. They have the general shape of that tree species, and with the designated proportions of the specific tree. In the very near future I will be developing a tree asset system, where each individual tree is created branch-by-branch to be more accurate to how unique trees are in nature.

This project uses the OpenAI API to gather common knowledge about climates and tree species, and simulations are scripted in Blender. You can check out my repository for foliager [here](https://github.com/toddgr/foliager).