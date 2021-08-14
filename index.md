---
permalink: /
title: "About"
author_profile: true
layout: single
---

Hey! My name is Jacob Gorneau and I am a master’s student in Lauren Esposito’s lab at the California Academy of Sciences. I received my B.S. in Entomology in May 2020 from Cornell University. Cornell has provided with me the wonderful opportunity to receive a broad education in basic and applied entomology in the classroom and lab work relevant to my fields of interest.v

#add inat widget

<script type="text/javascript" src="instafeed.js"></script>

<div id="instafeed"></div>

<script type="text/javascript">
    var feed = new Instafeed({
      accessToken: '${{secret.INSTA_TOKEN}}'
    });
    feed.run();
</script>

var feed = new Instafeed({
            get: 'user',
            userId: '{{secret.INSTA_NUMBER}}',
            template: '<a href="{{link}}"><img class="insta-image" src="{{image}}" /></a>',
            accessToken: '{{secret.INSTA_TOKEN}}'
        });
        feed.run();



