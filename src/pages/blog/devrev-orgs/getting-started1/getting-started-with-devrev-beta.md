---
templateKey: blog-post
title: "[Update] Getting Started with DevRev Beta"
date: 2017-01-04T15:04:10.000Z
description: Lorem Ipsum is simply a dummy text of the printing and typesetting
  industry. Lorem Ipsum has been the industry's standard dummy text ever since
  the 1500s.
featuredpost: false
featuredimage: /img/devrevday-2021-bg.png
tags:
  - work-management
  - ai
---
![devrev](/img/devrevday-2021-bg.png)

This week we’ll **take** a look at all the steps required to make astonishing coffee with a Chemex at home. The Chemex Coffeemaker is a manual, pour-over style glass-container coffeemaker that Peter Schlumbohm invented in 1941, and which continues to be manufactured by the Chemex Corporation in Chicopee, Massachusetts.

In 1958, designers at the [Illinois Institute of Technology](https://www.spacefarm.digital) said that the Chemex Coffeemaker is *"one of the best-designed products of modern times"*, and so is included in the collection of the Museum of Modern Art in New York City.

## Basic Concepts & Terminologies

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Onboarding to DevRev

The Chemex Coffeemaker consists of an hourglass-shaped glass flask with a conical funnel-like neck (rather than the cylindrical neck of an Erlenmeyer flask) and uses proprietary filters, made of bonded paper (thicker-gauge paper than the standard paper filters for a drip-method coffeemaker) that removes most of the coffee oils, brewing coffee with a taste that is different than coffee brewed in other coffee-making systems; also, the thicker paper of the Chemex coffee filters may assist in removing cafestol, a cholesterol-containing compound found in coffee oils. Here’s three important tips newbies forget about:

1. Always buy dedicated Chemex filters.
2. Use a scale, don’t try to eyeball it.
3. Never skip preheating the glass.
4. Timing is key, don’t forget the clock.

```javascript
/**
* Please do not delete [used for Intellisense]
* @param {ServerRequest} request The incoming webhook request
* @param {Object.<string, any>} settings Custom settings
* @return void
*/
async function onRequest(request, settings) {
  const body = request.json()
  var evt = request.headers.get("X-Github-Event")

  if (body.action) {
    evt += ` ${body.action}`
  }

  Segment.track({
    event: evt,
    userId: `${body.sender.id}`
  })
}
```

The most visually distinctive feature of the Chemex is the heatproof wooden collar around the neck, allowing it to be handled and poured when full of hot water. This is turned, then split in two to allow it to fit around the glass neck. The two pieces are held loosely in place by a tied leather thong. The pieces are not tied tightly and can still move slightly, retained by the shape of the conical glass.

For a design piece that became popular post-war at a time of Modernism and precision manufacture, this juxtaposition of natural wood and the organic nature of a hand-tied knot with the laboratory nature of glassware was a distinctive feature of its appearance.