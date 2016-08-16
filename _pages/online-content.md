---
title: "Online content"
excerpt: "Referencing online content from within the museum."
permalink: /patterns/online-content
---

Create a short URL which redirects to the content’s location. Things to consider with the URL:

* Use this format: __tepapa.govt.nz/unique-identifier__
* Should be memorable and uniquely associated to this specific exhibit/interactive
* Don’t include additional unnecessary branding or organisation jargon (eg, the user doesn’t should have to remember ‘Nga Toi, Arts Te Papa’ at this point)
* Use dashes (-) for spaces. If the URL does require these, create a duplicate URL without the spaces to catch people who forget.

Example of referring to an interactive’s specific content:

```__Watch these videos online at tepapa.govt.nz/anzac-prints__```


Google Analytics parameters should be added to the destination URL, example:

```__http://www.tepapa.govt.nz/visit/whats-on/exhibitions/nga-toi-arts/anzac-print-gallery?utm_source=APG&utm_medium=interactive&utm_campaign=APG__```


Use the parameters as follows:

* `Source`
  * Type of source, eg `museum-exhibit`
* `Medium`
  * ?   
* `Campaign`
  * Exhibition identifier, eg `anzac-print-gallery`


Consider the user journey:

* Where will the user land from this URL?
* Is it immediately obvious how it is linked to where they saw the URL?
* Is all relevant content grouped/related/easy to find from here?
* Will it date well or will this page become redundant before the exhibition is over?
