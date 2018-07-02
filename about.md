---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

 <div class="user-details">
  <h1> My Expertise </h1>
  <p> {{site.user_description}} </p>
</div>
  <div class="user">
    <div class="tech">
      <h2>Design</h2>
      <i class="devicon-html5-plain-wordmark"></i>
      <i class="devicon-bootstrap-plain-wordmark colored"></i>
      <i class="devicon-sass-original colored"></i>
      <p>Mumblecore hexagon kombucha, pitchfork four loko raclette intelligentsia master cleanse.
        Vinyl XOXO lumbersexual</p>
    </div>
    <div class="tech">
      <h2>Code</h2>
      <i class="devicon-javascript-plain colored"></i>
      <i class="devicon-react-original-wordmark colored"></i>
      <i class="devicon-nodejs-plain-wordmark"></i>
      <p>Mumblecore hexagon kombucha, pitchfork four loko raclette intelligentsia master cleanse.
        Vinyl XOXO lumbersexual</p>
    </div>
    <div class="tech">
      <h2>Tools</h2>
      <i class="devicon-git-plain"></i>
      <i class="devicon-gulp-plain colored"></i>
      <i class="devicon-atom-original-wordmark"></i>
      <p>Mumblecore hexagon kombucha, pitchfork four loko raclette intelligentsia master cleanse.
        Vinyl XOXO lumbersexual</p>
    </div>
</div>

## Some heading 

I'll alert the crew. Sure. You'd be surprised how far a hug goes with Geordi, or Worf. Did you come here for something in particular or just general Riker-bashing? You did exactly what you had to do. You considered all your options, you tried every alternative and then you made the hard choice. Your shields were failing, sir. Well, that's certainly good to know. A surprise party? Mr. Worf, I hate surprise parties. I would *never* do that to you. And blowing into maximum warp speed, you appeared for an instant to be in two places at once. How long can two people talk about nothing? I recommend you don't fire until you're within 40,000 kilometers. Congratulations - you just destroyed the Enterprise. Worf, It's better than music. It's jazz. Yes, absolutely, I do indeed concur, wholeheartedly! What's a knock-out like you doing in a computer-generated gin joint like this? I can't. As much as I care about you, my first duty is to the ship. Some days you get the bear, and some days the bear gets you.

</div>
