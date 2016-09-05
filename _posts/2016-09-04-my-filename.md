---
layout: post
published: false
description: In this video I explain the other side of the coin
date: '2016-09-04 21:00 EST'
categories: Digital-Education
img: Endless-Games-may-be-the-door-to-Online-Gambling-Addiction.jpg
permalink: /how/
title: How to write a post
---
Where is everything?

Posts: Inside '_posts' folder.
Pages: Inside '_pages' folder which includes 
                1. About
                2. Contact
                3. Articles
                4. Tags
                5. Sign up
                6. thank-you
                7. 404 
                
                
Sidebar items: root > _includes > sidebar.html - New pages will be automatically added to sidebar(use 'inmenu:false' if you don't want a page to show up on sidebar)           
Home page chapters: root > _includes > chapter-links.html
Images: root > images
CSS: root > sass - these files are in .scss format (normal css can be used inside them)
Comments: root > _includes > disqus.html



## Adding a new post or editing.

Make sure you mention all the front matter without miss. For example

      ---
      layout: post
      title: 'Digital Parenting Tips: Wrong Practices'
      description: Teenagers and Adult Parents perceive Technology in different ways, so we adults often make wrong moves while having good intentions. Here I explain how.
      date: 2016-03-23 21:00 EST
      categories: Digital-Education 
      tags: Digital-Education Parenting
      img: Digital-Parenting-Tips-Wrong-Practices.png
      permalink: /digital-parenting-tips-wrong-practices/
      ---

## Adding featured image in post

For 'img:' variable, keep the image inside images folder and just provide the name with extension (jpg, png etc..). For example
img: Digital-Parenting-Tips-Wrong-Practices.png - this is case sensitive. So 'something.png' is different from 'something.PNG' and 'Something.png' .  Make sure you enter the proper extension as well.

## Inserting Link 
			[Text](path to the link)

## Inserting Image
			![alt text](path to the img)

## Inserting Youtube video

			<iframe class="youtube-video" src="https://www.youtube.com/embed/dYPaypp4dG0" frameborder="0" allowfullscreen></iframe>


## Markdown syntax
If you are in doubt please refer to: [This article](https://daringfireball.net/projects/markdown/syntax)