---
title: "Language toggle"
excerpt: "The language toggle pattern creates a way to toggle the entire interactive to a different language."
---

Te Papa provides written content for all digital interactives in **Te reo Māori** and **English**.

![Language toggle](/images/language-toggle.png)

__Figure:__ The`language-toggle` component creates a simple way to display which languages are available (Māori and English) and allows users to switch from any screen with one touch.
{: .figcaption}

### Key features of the `language-toggle` component are:

- Māori should appear first (on the left), followed by English.
- The current convention is to place the `language-toggle` in the top right of the interactive in alignment with the `Home` button (if present).
- The `language-toggle` should be present on most, if not all, pages. An exception to this convention might be on a fullscreen **Gallery** or **Image Zoom** page. Using the component on such a page would detract from the fullscreen design. These pages are likely to be nested within a page on which the toggle was present.
- Selecting a language should change the language _on the current page_ (in other words, this should not change the page itself or return the interactive to Home, but should only change the language being displayed).

You might also be interested in the [Gloss](/_pages/patterns/gloss) component (inserting definitions of words into paragraph tet) and [UI control names](/_pages/patterns/ui-control-names) (Māori and English names for UI controls).
{: .notice}

![Language toggle](/images/language-toggle-in-use.png)

__Figure:__ An example of the `language-toggle` component in use on the Te Pahi Medal interactive, located in the top right of the screen. 
{: .figcaption}

If more langugages are required, other options might need to be explored to avoid cluttering the interface.
{: .notice--warning}
