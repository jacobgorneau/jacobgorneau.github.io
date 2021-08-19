---
permalink: /
title: "Welcome!"
author_profile: true
layout: single
---

I'm currently a master's student at the California Academy of Sciences working on arachnids. I graduated with my B.S. in Entomology at Cornell in 2020. I'm incredibly passionate about all arthropods, but my previous and current work centers on moths and arachnids in the context of museum-based biodiversity work. I'm also incredibly passionate about outreach and have been involved in several projects involving communicating science and preparing scientific displays. Thank you for your patience as I get this site up and running!

<script type="text/javascript" src="instafeed.js"></script>

<div id="instafeed"></div>

<script type="text/javascript">
    var feed = new Instafeed({
      accessToken: '${{secret.INSTA_TOKEN}}'
    });
    feed.run();


var feed = new Instafeed({
            get: 'user',
            userId: '${{secret.INSTA_NUMBER}}',
            template: '<a href="{{link}}"><img class="insta-image" src="{{image}}" /></a>',
            accessToken: '${{secret.INSTA_TOKEN}}'
        });
        feed.run();
</script>


