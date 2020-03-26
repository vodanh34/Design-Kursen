---
---
Webpage Loading Time
=========================
The purpose of this research is to find out how fast the digital games distribution website loads.

Selection
----------------
For this research I have decided to continue with the sites from my previous research. Which are websites that distribute digital games online.

* **Good Old Games (GOG)**
* **Epic Games Store**
* **Steam**

As mention in my previous research, I have always love gaming and using those digital distribution websites to get hold of games has always been the way to since the early age of digital games distribution. Thus, it would be interesting to see how fast those sites are in todays standard.

Method
---------
The tools being used to analyse the speed of the website are:

* **PageSpeed Insights**
* **Chrome**
* **Chrome Developer Tools**

In order to analyse the speed of the website, they are first run through PageSpeed Insights to get the score of the website in question 3 times each page, every run is hit by ctrl + f5 to make sure it’s fresh and not cached.  Which analyse the score on both desktop and mobile devices.
After which using Chrome Network tab to see how long it takes for the site to load by using ctrl + r to make sure it doesn’t reload cached.

Result
------------
**Good Old Games (GOG)**

[FIGURE src="image/GOG.png"]
[FIGURE src="image/gog_about.png"]
[FIGURE src="image/gog_store.png"]

Check Mics section for result of the research. Based on PageSpeed Insight it looks like the website use image of great size, has a lot of DOM and use enormous network payload which result in much slower loading time. By using next gen image format or somehow reduce the image size as well as avoid using enormous network payload but also less DOM will greatly reduce load time of the site. 

**Epic Games Store**

[FIGURE src="image/Epic.png"]
[FIGURE src="image/epic_faq.png"]
[FIGURE src="image/epic_news.png"]

Just like GOG, Epic Games Store also uses excessive DOM and enormous network payload but also Epic delivering big JS payloads, by reducing DOM, network payload and delivering smaller JS payload will reduce load time greatly.

**Steam**

[FIGURE src="image/Steam.png"]
[FIGURE src="image/steam_about.png"]
[FIGURE src="image/steam_community.png"]

Steam also uses enormous network payload, a lot of DOM, older image format and image size of greater than its container. By optimizing and using next gen image format together with reduced DOM and network payload will reduces load time greatly.

Analyse
-----------------
Based on the research the common issues are that all the website use enormous network payload, has a lot of DOM, using older image format as well as having images of great size or images that’s bigger than its element container. And one of the three sites use big JavaScript payload.

All these issues combined increased the loading time greatly. Therefore, in order to decrease the load time those websites should use next gen images format as well as using right image size according to its element. Decrease the use of DOM, reduce network payload as well as JavaScript payload.

Also, it’s very common for those sites to load slowly on mobile devices, but then again, those websites are focusing in distributing digital copy of games on desktop platform. So maybe mobile devices are not their core focus since probably most of their users access their site while on computer. Not to mention they also have their own Desktop “app store” where user don’t even need to access the website.

Another thing to note is that the loading speed probably is related to the user’s internet connection as well. Since my internet connection is not great while perform the research, the result might be affected by it somehow and should be taken with a grain of salt.

Personal Verdict and Preferences
--------------------------------------
Based on the result from the research the final score is given by the following; Ranging from fastest to slowest. The score is based on the main page where users spent most of their time on browsing through different games on desktop version.

1. **Steam**
2. **Good Old Games**
3. **Epic Games Store**

From the finding of the research, I was shocked by how long it would take to completely load the page. However, I do not feel that the site is slow or being affected by it that much. This is mainly because the first meaningful drawing of content is about 1 second.

As for my absolute loading time is around 1 seconds, if it’s more than that I would feel like the page is slow. However, this was when I had very fast internet connection but right now my tolerance towards slower connect would be around 3-4 seconds, any other than that would annoy me.
 
Even though I have slow internet connection and from the shocking finding of the load time on those websites in questions I do not feel that they are slow per say. This is mainly because the important elements that when you first visit the site loads in about 1 second, while the later elements take a bit longer to loader the further down they are. I would only feel that they are slow when I skip the very first section and start scrolling down right away, then I would notice images and text haven’t been loaded yet for about 1 second. Overall, I’m fine with the loading speed given my slow internet connection and it feels all right.

Reference
---------
Null.

Mics
----------
This research is done by Hien Van Le.<br>
[Analyse Excel Arc](https://www.dropbox.com/s/m0sozmw07fzemjy/Design%20Kmom05.xlsx?dl=0)
