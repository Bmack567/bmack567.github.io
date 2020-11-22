---
layout: post
title: 3. Designing and Applying Image Recognition
---

This past week, we discussed the severely limited range of image recognition technology. Whereas text recognition relies on a handful of recognizable handwriting styles using repeated characters, handwriting recognition is much less reliable. How, then, could we expect a computer to recognize two different drawings intending to portray a house? 

Since these blog posts can serve as preparation for our final projects, I thought it would be useful to devote time to conceptualizing what a realistic project proposal might look like. We know already that image recognition technology is severely limited at the moment. What, therefore, can we realistically expect such a project to uncover? And how might knowledge of these limitations now benefit the proposal to be submitted next month?

Google's Quick, Draw! Application launched in 2016 is attempting to teach artificial intelligence to recognize shapes as referring to words. Users are asked to draw what they are told, then the machine attempts to guess what you drew using its knowledge of other user drawings. Because of this reliance on other examples, shapes that resemble the object but depict it in unfamiliar positions and proportions will not be recognized. The software is nevertheless fairly reliable with words that are drawn easily. 

But how would they do with the kinds of images seen in comics? Although some comics intentionally abstract their presentation of ordinary objects, we can predict that the average comic would draw objects AT LEAST as clearly as I did when I attempted the Quick, Draw! Game. To my surprise, the AI predicted all 6 of my words (bush, drill, vase, asparagus, water, and tennis racquet) within just a few seconds!

If computers can recognize drawings like these as objects, what would happen if we ran a page of *Peanuts* comics through a similar process? The problem with using a comics corpus is that the preexisting dataset used to make predictions would not be available. This means that a similar dataset including images in comics and corresponding names would be needed in order to teach the program how to read the *Peanuts* comics. Or, we could run it through image recognition software with a preexisting dataset, like the one compiled by Quick, Draw. This means that the next steps will be finding an appropriate database of images and captions.

Assuming we pass this stage and are able to run a comic through such image recognition software, we would need to determine what we want to find. In this case, we are looking for software that can recognize images and produce corresponding words based on resemblances to other images. Every scanned page of comics could then be translated into a series of words which are a computer's rough estimate of the different elements found in the page.

The problems continue, however. Google's Quick, Draw! Application attempts to read ONE image. If we feed a page of comics to this kind of software, it will attempt to read the entire page as one item. It will likely come up with something very different from the actual content of the page. This means that such a program would need to be trained recognize multiple elements of varying proportions, excluding the page as a whole and including overlap. It's a daunting challenge, but if broken into steps, it may be achievable using existing technology.

So what can we expect to see if we succeed? If we use Allie Brosh's webcomic *Hyperbole and a Half* as an example, the first image of her comic entitled "The Party" might read: tooth, frown, tooth, frown, tooth, frown, tooth, smile. It might even include something wrong like a blackbird instead of the smile at the bottom of the image. But this data could already be immensely useful. Such catalogued information could potentially benefit researches of images by allowing them access to a text-based searching system through their images. If a student or professor is working with many comics and thousands of pages, such software could allow them to find pages they require within seconds, simply by describing an element within the image. It could be programmed to immediately fetch all images which were encoded with this element, allowing the user to search through a far shorter list of options.

A generous person by the name of Michael "Bing" Yingling was patient enough to do exactly this with the text found in Bill Watterson's *Calvin and Hobbes* comics. Other databases like these can be found online for corpuses like television shows and other popular comics like *Peanuts*. What does NOT exist, however, is a database where users can search the CONTENTS OF IMAGES. In comics with less dialogue, databases like those made for *Calvin and Hobbes* are useless. The project is therefore clear: design an image recognition software that can recognize and record elements found in comics pages, in an effort to make these images searchable for future research.

Sources:
Google's Quick, Draw! - quickdraw.withgoogle.com
Hyperbole and a Half - hyperboleandahalf.blogspot.com/2010/09/party
C&H Database - michaelyingling.com

