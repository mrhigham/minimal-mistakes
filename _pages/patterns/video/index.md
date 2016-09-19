---
title: "Video"
excerpt: "Use these patterns and guidelines when creating a video object in your interactive. The patterns generally apply to an interactive with a single video, or to video used as part of a bigger interactive."
---

{% include toc %}

<a class="btn btn--info btn--large"><i class="fa fa-download"></i> Download all video assets (.ai, .sketch, .png)</a>

## Poster

![Basic video poster template](/images/video-poster.png)

The graphic representation of a video before a user has selected to watch it is referred to as its ‘poster’. A poster should have the following components:

* __Icon__
    * Standard play icon centered over the image
* __Title__
    * Left-aligned
* __Duration__
    * mm:ss format
    * Less prominently styled than the title
* __Image__
    * Best with subtle motion or a small loop of 2–3 stills
    * Image(s) should reveal key aspects of the video. For example, if the video involves an interview with an artist, showing a moment of this interview will help the user understand what content is available.
* __Gradient overlay__
    * Used to keep text readable regardless of the background
    * Recommended color: black 60% opacity ➝ 0% opacity
* __Hotspot__
    * Entire image is a hotspot to activate the video (not just the play button)

Note, it is a deliberate action to partially obscure the image with a large play icon. This reinforces the need for interaction from the user to prevent users from mistaking the screensaver for ambient content.
{: .notice--warning}

![Video poster examples](/images/video-poster-examples.png)

__Figure:__ Examples of how this standardised poster works with various content.
{: .figcaption}

## Playback interface

![Video playback UI example](/images/video-playback-ui.png)

__Figure:__ Basic video interface layout. Note the position of the buttons to the bottom left, the equal spacing between the side and bottom of the screen and the alignment with the subtitles.
{: .figcaption}

The interface for video playback consists of a few key items:

* __Back button__
* __Subtitle button__
    * When there is a single language available, use the `toggle` version
    * When there are multiple languages available, use the `flyout-menu` version
* __Subtitles__

The interface elements (Back and Subtitle buttons) should remain onscreen during playback so that they remain discoverable to visitors.

### Subtitle toggle button

![Video interface buttons](/images/video-ui-toggle.png)

__Figure:__ The `toggle` version of the subtitle button.
{: .figcaption}

### Subtitle flyout menu button

![Video interface buttons](/images/video-ui-flyout-menu.png)

__Figure:__ The `flyout-menu` version of the subtitle button for multiple languages.
{: .figcaption}

__Important:__ The button should read `Subtitles ON` when the subtitles are currently active. It reveals the current state of the subtitles, not the resulting action.
{: .notice--danger}

## Subtitles

### Design

![Video subtitle design](/images/video-subtitles-design.png)

The design for subtitles should follow:

* Helvetica Neue Bold
* White `rgba(255, 255, 255, 1)` on a semi-transparent black background `rgba(0, 0, 0, 0.5)`
* Centred horizontally and positioned at the bottom of the screen
* Background box clipped to the width of the text

### Editorial

Follow BBC's extensive guidelines for creating subtitles:

__[Online Subtitling Editorial Guidelines v1.1](http://www.bbc.co.uk/guidelines/futuremedia/accessibility/subtitling_guides/online_sub_editorial_guidelines_vs1_1.pdf)__

A few notable features from the guidelines:

* The __maximum line length__ should be roughly 34 characters long.
* The __maximum number of lines__ displayed at one time should be 3, but ideally only 1 or 2.
* Place __line breaks__ only when necessary and at logical points, for example, at the end of a clause or phrase.
* __Be cautious with editing__ the transcription. It can be condescending to deaf or hearing impaired people and confusing to lip readers. It might be appropriate, however, to edit the text for a particularly busy sequence where quickly changing subtitles would be too difficult to follow.

Retrieved from [BBC’s Future Media Standards and Guidelines site](http://www.bbc.co.uk/guidelines/futuremedia/accessibility/subtitling.shtml), licenced under the Open Government Licence v2.0.
{: .notice}