---
title: Software Design - Final Project
author: Elena Abou Mrad
date: April 29, 2020
---

# Food Poetry: a blog of recipes and poems

My final project [*Food Poetry*](https://eaboumrad.github.io/foodpoetry/) is a recipe blog with a twist. Every post represents a recipe, but it also contains a poem about one of the ingredients. I built this website with Jekyll and GitHub Pages, and wrote my posts in HTML and CSS.

## Motivations
Food is a complex cultural phenomenon and it can evoke feelings and memories in everyone of us. Poetry can often feel inaccessible, but there are plenty of writers who expressed their love of food in verse. Therefore, I decided to pair every recipe with a poem for a double purpose. On the one hand, the website makes poetry - which is often considered an elite literary form - accessible because the subject is something everyone can relate to: food. On the other hand, the poem that opens the post places the recipes under a new light, which elevates the food to something more than a household chore.
During the COVID-19 epidemic, many people are spending their free time cooking and reading. Therefore, I though that Food Poetry could be a good resource for the ones who, like me, are stuck at home during quarantine.

## Responsive Design and Mobile Friendliness

According to the Pew Research Center's survey *Mobile Technology and Home Broadband 2019* [^1], 37% of US adults say they mostly use a smartphone when accessing the internet. People are using the internet with all sorts of devices, so websites need to adapt to different browsers and screens.
My blog *Food Poetry* is built using responsive design and is mobile friendly on iPhone and Android.

## Accessibility: Designing and Testing

I decided to design my website in HTML and CSS, to make sure that it would work:

* On old browsers
* With screen readers
* With a slow connection

The second step towards an accessible website was consulting the [Accessibility Principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/) enunciated by the [WAI (Web Accessibility Initiative)](https://www.w3.org/WAI/) and the [Standford guide for accessibility testing](https://soap.stanford.edu/tips/screen-reader-testing). These sets of principles guided me in a series of edits:

1. I made sure that the Language in the posts was set to English, so that screen readers could recognize the text more easily.

2. I removed abbreviations for clarity: for example, I changed "tbsp" to "tablespoon"

3. I repeated the measurements in the recipe so that the reader doesn't have to go back and forth. This is a trick I learned from an episode of the podcast [The Sporkful](http://www.sporkful.com/) entitled [*The Art - and Joy - of Recipe Writing*](http://www.sporkful.com/the-art-and-joy-of-recipe-writing/), where the host interviews Chandra Ram, an expert in recipe books. This is an example of how universal design helps everybody.

4. I inserted alt text for all my images.

5. I added a Navigation Bar with Home, Conversions, and About buttons

6. I installed [NVDA](https://webaim.org/articles/nvda/) on my PC and tested if I could navigate and read my website with a screen reader.

## My experience

This is the first website I ever made, and I was surprised at how relatively easy it was. I set up my website on GitHub Pages by following the [Jekyll tutorial on *Programming Historian*](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages) and I worked from there, writing my posts in HTML and CSS. 

 For this project, I used GitHub Desktop as recommended in the Programming Historian tutorial. This software is very easy and convenient to use and it makes it easy to see the different commits. However, it was a little frustrating that once I pushed my commits to GitHub, I had to wait for a while before the updates were visible on the website.

 I think that the hardest part was trying to understand the structure of the website and what the different files in the repository did. The most complicated part to grasp intellectually was the concept of paths and how they work: it was a bit of a trial and error process to understand how to insert the images in the posts and the links in the Navigation Bar. It felt like learning a new language, where you intuitively start understanding the underlying structure after studying the grammar and doing a lot of excercises.

Before taking this class, I thought that coding was something obscure and not accessible to me. Now, I know that with a lot of practice and a lot of online tutorials I can learn how to code in different languages, according to the project I'm working on.

[^1]: (Anderson, Monica. “Mobile Technology and Home Broadband 2019.” Pew Research Center: Internet, Science & Tech, 13 June 2019, https://www.pewresearch.org/internet/2019/06/13/mobile-technology-and-home-broadband-2019/.)