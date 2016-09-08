---
title: "Layout"
excerpt: "Layout guidelines for digital outputs."
---

## Natural mapping

Where possible, represent the digital content in response to the layout of its related physical object. This doesn’t require an exact 1:1 relationship, but consider how it can reduce the cognitive load of the user to map them in similar layouts (see the example of the stove top controls).

![Natural mapping example](/images/mapping-stoves.png)

Example of natural mapping: The stove top on the left is not using natural mapping; there is no obvious relationship between the controls and the burners. The stove top on the right utilises the natural mapping principle: the relationship between each control and burner is obvious and requires no written instruction or ‘trial-and-error’ approach from the user.
{: .figcaption}

A [skeuomorphic result](https://en.wikipedia.org/wiki/Skeuomorph) is not the intention, but to make the interface intuitive and obvious so the user doesn’t have to “learn” the interface.
{: .notice--warning}

An example of natural mapping in an interactive can be taken from the _Anzac Print Gallery_ screen. The screen housed 10 videos, each one directly linked to one of the 10 artworks displayed on the four walls. The 10 videos were displayed in the same order on four separate menu pages of the interactive to create a strong link between the physical artwork hung on the wall and the digital video content about each piece.

![A menu page from the Anzac Print Gallery interactive screen](/images/anzac-print-gallery-screen.png)

One of the four menu screens from the _Anzac Print Gallery_ interactive, demonstrating the principle of natural mapping. Note, touching on the artwork, artist’s picture or name, or the Play button triggered the video. The screen looped between the four menu screens removing the need for a screensaver.
{: .figcaption}

## Avoid instructions

Avoid the tendency to explain your interface.

> __Don’t do this:__ Touch the screen to play the video

Avoid instructions like this by creating a clear call-to-action. If an element on the screen is interactive, it should signal that it is interactive by way of colour, icon and style.

* __Next / Previous:__ Use the titles of the next and previous objects if possible.
* __Toggle:__ If an action has only two states possible (such as two languages available), it can be simpler to put the alternative option on screen as a way to toggle with the interface.
    * For example, if English and Te reo Māori are available on an interface and English is currently displayed, using `Language options` would not tell a user which other language optoins are available. A user would required to press `Language options` to then see that Te reo Māori is available. Alternatively, displaying `Te reo Māori` as an interactive element would signal to a user that they can switch the language to this if they choose. (Note: If the screens do not have a substantial amount of English present, this tactic could be too confusing. An alternative approach would be to use the label `Switch to Te reo Māori`.)
* __Touch here to...:__ Always avoid this. Don’t talk about the interface or how to use it, but instead describe what will happen (eg `Play` or `Read more` or `Share on Facebook`).

![Hotspot labels](/images/hotspot.png)

The top example screen clearly demonstrates how content can be hidden by obscure icons or labels. The bottom example contrasts by stating what other language is available, the titles of the next and previous items and by bringing a snippet of content to the fore. A user can more easily expect what each action will do and choose accordingly.
{: .figcaption}

## Accessibility

If your screen is wall-mounted, position interactive hotspots below the centre line. See [accessibility considerations](/_pages/foundations/accessibility/) for more detail.