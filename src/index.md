---
title: I deployed to Netlify!
layout: layouts/base.njk
---


<h2 id="tweet">I deployed this site so I can win a Nintendo Switch!</h2>


I‘m going to tweet out this link to win my Nintendo Switch at {{ details.event }}.

My kids will be crazy happy! This will be us: 

<img class="switch-image" src="images/switch-with-dad.jpg" alt="Kids playing swith with dad" />

<hr />

> {{ details.tweet }}
>
> <a href="https://twitter.com/intent/tweet?text={{ details.tweet | urlencode }}" class="btn" target="NEW" rel="noopener">Tweet to enter the prize draw</a>
>
><small>(You'll get the chance to inspect and edit this tweet before you post it)</small>


<h2>What next?</h2>

Try out a few more of the things that you can do with this once you've deployed to Netlify.

1. [Add your name](/next-steps/#add-your-name)
1. [Create a deploy preview](/next-steps/#deploy-preview)
1. [Add a form](/next-steps/#form)
1. [Define redirect rules](/next-steps/#redirects)



<h2 id="get-yours">Get your own</h2>

Oh hi! Admiring this site that {% if details.name %}{{ details.name }}{% else %}I{% endif %} deployed? Well, you can get one too.

To deploy your own copy of this site, and enter the prize draw at {{ details.event }}, just click the button below, follow the instructions, and then tweet the link.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify/my-first-netlify-deploys)


