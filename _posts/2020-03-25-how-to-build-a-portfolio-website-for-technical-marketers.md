---
title: 'How to Build a Portfolio for Technical Marketers using HTML, CSS, Jekyll, GitHub Pages, and Google Domains' 
date: 2020-03-25 00:00
description: Ongoing step-by-step on how to set up a personal portfolio site to not only host your achievements and projects, but show off your technical marketing skills
featured_image: '/images/other/bs-marketing-home.png'
---

![](/images/other/bs-marketing-home.png)

## Initial Development Setup
### Technologies used: GitHub, Git, Terminal, Text Editor, Jekyll, Ruby Gems


## Google Domain Setup & DNS Server
* Purchase your domain.

* Setup DNS record for GitHub servers 
```html
Create an A record, point your apex domain to the IP addresses for GitHub Pages.

185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

```

* Set a CNAME record on your domain provider

## Advanced Google Analytics Setup using Google Tag Manager to hit the ground running

* Create your Google Analytics account
* Create your Google Tag Manager account
* Install GTM container on your website
* Download Google Tag Assistant and enable on your browser
* Filter out localhost traffic on Google Analytics: 
```html
#How to exclude LocalHost traffic on Google Analytics: 
https://briefmetrics.com/articles/remove-localhost-from-referrers
```
* Filter out your home and work IP Addresses / Wifi Networks
```html
#How to exclude multiple IP Addresses using Regular Expressions, AKA RegEx

RegEx Tester Resource: https://regex101.com/
```



## SEO Setup

* Jekyll SEO Plug-In
* Update site-defaul social media images
* Update Title, Description, Feature Image for all pages, posts, projects, etc. Even your thank-you & 404 pages! 
* Create a Google Search Console account
* Link Google Search Console to Google Analytics using preferred verification method. GTM should be very easy if you have that setup already. 
* Generate a sitemap.xml file which lives at `domain.com/sitemap.xml`



## Helpful Git Commands

```html
#Check DNS Record for domain
$ dig EXAMPLE.COM +noall +answer
```

```html
#Run website on local server
bundle exec jekyll serve --watch
``` 
