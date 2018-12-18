# ReviewMonkey.org

This is the GitHub repo for [ReviewMonkey.org](http://reviewmonkey.org). This site is honest on GitHub, and uses Jekyll for static website content creation.  
    
### Contributing to ReviewMonkey.org

If you are interested in contributing to ReviewMonkey.org you will need to be familiar with using git. You will need to make a fork of this repository and then make a pull request to add your review.  Before you take the time to do this, email reviewmonkey.org@gmail.com and tell us a little about yourself and why we should add you as a monkey.

A review is made up of an markup post file, and images.

#### Directories ####
**assets/images** - Images go in here.
**_posts folder** - Reviews go here.

Images should include a reference to the post they are used in.  For example, if the review is titled "Surfacebook 2", the images should be named:  Surfacebook_2_name.ext.  For example, lets say you have an image of a mouse that you want to include in this review, some example names could include:

Surfacebook_2_mouse.jpg
Surfacebook_2_1.png

etc.  You get the idea. 

### Post Naming Format ###
All review post files must use the following naming format:
YYYY-MM-DD-PostName.md

Example:
2018-12-12-surfacebook.md
    
### Post Base Heasder Format ###
ReviewMonkey.org supports standard Jekyll markup and HTML in the review posts. All reviews should start with the following header.  The Banana rating is to be adjusted by you, the example below shows a Banana rating of 4.5 bananas.  The review text starts immediately after the double breaks (br). 

This is a little janky we know, we are looking into a better method.

```
---
---
layout: post
title:  "Title of Post"
author: AuthorName
categories: [ keyword1, keyword2, keywork3 ]
image: assets/images/Surfacebook_2_mouse.jpg
hidden: false
featured: false
---
**Bananas:** ![banana]({{site.baseurl}}/assets/images/banana.png)![banana]({{site.baseurl}}/assets/images/banana.png)![banana]({{site.baseurl}}/assets/images/banana.png)![banana]({{site.baseurl}}/assets/images/banana.png)![banana]({{site.baseurl}}/assets/images/half-banana.png)<br><br>This is the beginning of your review, an excerpt of approximately twenty five worfd
---
```

Add to images to float left or right:
````
{: .pull-right}
{: .pull-left}
````

