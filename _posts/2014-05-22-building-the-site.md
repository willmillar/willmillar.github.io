---
layout: post
category: blog
title: "Building willmillar.com 4.0 with Jekyll"
subtitle: My process
permalink: building-the-site
picture: /images/website-and-pizza.jpg
---

Goodbye CMS! The new willmillar.com is built with code using [Jekyll](http://jekyllrb.com/). This means I can design from sketches instead of starting from someone else's page templates. Divorcing the content from design was a very powerful change, and I had a great time getting back into code!

<!--more-->

## Designing in code

"Design tools" have been defined to me as the page layout programs like InDesign, OmniGraffle, Photoshop, Sketch. These are great for preliminary high-level concepting, but I often find them to be a significant hindrance once your high-level design system is set. I was really excited for a design project where I can **ditch static comps early in the process**.

Jekyll processes my posts into the templates I designed with HTML and [Liquid](https://github.com/Shopify/liquid). This is ideal for my writing workflow because I can write in human-readable [Markdown](http://daringfireball.net/projects/markdown) in any text editor. No HTML tags to muck up the prose, and no stupid CMS WYSIWYG text editor to fight with.

The process improved my writing, workflow, and throughput. And it was fun and I learned a lot! The site built from [Poole](http://demo.getpoole.com/) with [Jekyll](http://jekyllrb.com/) on [GitHub Pages](https://pages.github.com/) with typography from [Typekit](https://typekit.com/). No extra plugins or hidden gems.

While not technically responsive, the site uses **single-column design** with a few media queries to render a speedy and attractive experience on almost any device.

![](/images/willmillar-com-4-0-graph.png)

<small>Commits to the [willmillar.github.io](https://github.com/willmillar/willmillar.github.io) repo over the six weeks of spare time it took to learn Jekyll and Liquid, design and build the site, and write the content</small>

## Getting started was the hardest part

The biggest challenge in the process was getting the plane off the ground! I had whipped up some designs in OmniGraffle for a new site late one night. They sat on my desktop for a couple weeks while I looked into WYSIWYG-style CMSs like SquareSpace, new blogging engines like [Ghost](https://ghost.org/), and traditional CMS systems like Wordpress. Eventually, I decided on Jekyll:

1. **Jekyll made me get my hands dirty with code.** Given my hangups with the traditional design process of developing detailed mockups, I figured I should try a project where I design in code to see if the grass is really greener. It's time to eat my own dogfood, right?

- **Working in code gives a designer superpowers.** Every layer of abstraction is a layer of control that you give up as a designer. This is not to say that high-level design tools make poor designs, but they should be considered as limited. Conducting the ebb and flow of a live site is a much different skill than making a polished static mockup. My experience has found code skills to be more relevant and reusable for a web designer than being really good at Photoshop.

- **It looks like Jekyll is here to stay** (at least for a while). [GitHub Pages](https://pages.github.com/) uses Jekyll, and there is a very active community.

## Inspiration & references

- **["Refuse to Create a UX Portfolio"](https://medium.com/digital-product-design/a44f802fee11)** by Timothy Gaeger via Medium
- Portfolios, blogs, personal sites I referenced: [bradfrostweb.com](http://bradfrostweb.com/) [jonwiley.com](http://www.jonwiley.com/index.html), [marco.org](http://www.marco.org/), [daringfireball.net](http://daringfireball.net/), [veen.com/jeff](http://veen.com/jeff/), [adactio.com](http://adactio.com/), [markdotto.com](http://markdotto.com/), [jeffvlahos.com](http://jeffvlahos.com/), [nathanhass.com]("http://nathanhass.com/"), [jpboneyard.com](http://jpboneyard.com/), [emilybrick.me](http://emilybrick.me/)

Also thanks to my friends and colleagues for their input during the design process!