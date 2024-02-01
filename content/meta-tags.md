---
title: Meta tags
---

As always, read the MDN documentation if you want a comprehensive guide to what each tag does and how they can be configured. I've simply grouped them according to common functionality


## The Essentials

Great for blogs, personal websites, any kind of content-first site.

```html
<title> Title Visible in the Tab </title>
<meta name="description" content="A description of your site that will show up in places like Google search results.">
<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="apple-touch-icon" sizes="180x180"  href="/your-icon-180x180.png"> 
<link rel="apple-touch-icon" sizes="152x152" href="/your-icon-152x152.png">
<link rel="apple-touch-icon" sizes="167x167" href="/your-icon-167x167.png">
<link rel="icon" type="image/png" sizes="32x32" href="/your-icon.png"> 
<link rel="icon" type="image/png" sizes="16x16"  href="/your-icon.png"> 

<!-- Facebook Open Graph tags -->
<meta property="og:url" content="https://your-website.com" />
<meta property="og:title" content="Site title for link previews" />
<meta property="og:description" content="The text that will appear in link previews." />
<meta property="og:image" content="https://website.com/card.png" />

<!-- Twitter Card (large image card) tags -->
<meta name="twitter:card" content="summary">
<meta name="twitter:creator" content="@twitter_username">
<meta name="twitter:title" content="Title of your Twitter card">
<meta name="twitter:description" content="The text that will appear in your Twitter card description." />
<meta name="twitter:image" content="https://your-website.com/card.png" />

<!-- If your site has an RSS feed -->
<link rel="alternate" type="application/rss+xml" 
  title="RSS Feed for Your Site." 
  href="/index.xml" />

<!-- Example stylesheet link -->
<link rel="stylesheet" type="text/css" href="/css/shared.css"/>

<!-- Example script link -->
<script src="/scripts/index.js"/>
```


## For web apps

The first tag prevents users from using pinch to zoom on mobile, making your app feel more native (perhaps at the cost of accessibility). The others help add it as a home screen shortcut on smartphones.

```html
<meta name="viewport" content="width=device-width, initial-scale=1 maximum-scale=1, user-scalable=0, viewport-fit=cover"/>
<meta name="application-name" content="App Name">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<meta name="apple-mobile-web-app-title" content="App Name">

<meta name="mobile-web-app-capable" content="yes">
<meta name="msapplication-TileColor" content="#FFFFFF">
<link rel="shortcut icon" href="/your-icon.png" data-rh="true">
```