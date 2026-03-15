---
layout: splash
title: "Fang Desktop Newsreader"
header:
  overlay_image: /assets/images/header-placeholder.png
  overlay_filter: 0.6
  hero_screenshot:
    dark: /assets/images/screenshot-dark.png
    light: /assets/images/screenshot-light.png

excerpt: "Stay up to date with your favorite news websites and blogs.<br /><br />Currently in beta."

feature_row_feeds:
  - image_path: /assets/images/screenshot-feeds.png
    alt: "News feeds"
    title: "News Feeds"
    excerpt: "Wherever you get your news -- all in one place.<br /><br />Fang automatically checks for new content and remembers what you've read."

feature_row_platforms:
  - image_path: /assets/images/platforms.png
    alt: "Your news, your way"
    title: "Your News, Your Way"
    excerpt: "Windows, Mac, Linux, light mode, dark mode, online, offline?<br /><br />All of the above. On <i>your</i> desktop."
    
feature_row_folders:
  - image_path: /assets/images/screenshot-folders.png
    alt: "Folder organization"
    title: "Folder Organization"
    excerpt: "Group your feeds into folders to keep things tidy. Collapse and expand folders to quickly navigate your subscriptions."

feature_row_privacy:
  - image_path: /assets/images/screenshot-privacy.jpg
    alt: "Private and Secure"
    title: "Private and Secure"
    excerpt: "No accounts, no central server, no tracking cookies.<br /><br />All communication is between you and the sites where you get your news."
    
---

<div id="features" class="features-section">
<svg class="hero-wave" viewBox="0 0 1440 92" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <path d="M0,46 C130,10 230,10 360,46 S590,82 720,46 S950,10 1080,46 S1310,82 1440,46 L1440,92 L0,92 Z" fill="#eff1f5"/>
</svg>

{% include feature_row id="feature_row_feeds" type="left" %}

{% include feature_row id="feature_row_platforms" type="right" %}

<div class="feature-smaller-image">
{% include feature_row id="feature_row_folders" type="left" %}
</div>

<div class="feature-smaller-image">
{% include feature_row id="feature_row_privacy" type="right" %}
</div>

</div>

{% include releases.html %}

