Eduardo Parkinson de Castro			
D17126897
20 April 2018


Phase II Report
Web and User Interface and Design



 CSS 

All of the CSS in index.css file is my own. Most of the CSS for the footer is not mine, it is only slightly modified. Most of the CSS (70% to 90%) for the nav bar is mine own.  It is hard to exact how much of the nav.css file is exactly mine because I have used the nav bar before in a previous website I built and have modified it over time to fit my needs. All of the css in news.css is mine. I used a contact template from https://mdbootstrap.com/components/bootstrap-contact-form and modified it for my website. The javascript is my own. Total lines of my own CSS: 200 approximately. Modified CSS: 100 approximately.

I used bootstrap as my CSS framework. Bootstrap allows me to create a grid-style website that adjusts itself based on columns that range in size from one to twelve. A lot of my website is built using a 4 by 3 grid. That is, the column size of each grid (column) in the row inside my container is 4 and I typically have 3 of them side by side. I can also create empty columns to place things where I want them to be. I use this technique when modifying my contact form, because I wanted it to look symmetrical to the rest of the website. I can access bootstrap by linking it in the head of the html. Bootstrap also comes with in-built CSS that can be accessed by using classes that are in-built to the bootstrap package. This in-built CSS can be over-run using your own CSS. I often used to inspect tool on chrome to test my CSS changes and make sure they were appropriate and to find out what CSS file (if it was bootstrap or my own) was changing the html. 

I used bootstrap because it is convenient. It has a grid system that is intuitive and once you become familiar with it, it becomes easy to make responsive content. Some media will require queries to be adjusted but overall the bootstrap does a good job in ensuring that the content inside the containers adjusts well when scaled into different device sizes. One way that bootstrap makes it easy is by ensuring that media (video, images, iframes, etc.)  scales well when placed next to media that is of the same size. That’s why I adjust most of my media so that they are of symmetrical size (e.g., 624x382 for my large images).


Testing

For speed testing I used www.webpagetest.org. My results are as follows:

My homepage:

Load time - 2.341s
Visually Complete time - 2.500s
Fully loaded time -  2.474s (after 26 requests and 567KB)

 
My news page:

Load time - 14.183s
Visually Complete time - 8.200s
Fully loaded time - 21.191s (after 384 requests and 5,132KB)

My index page scored an ‘A’ across all credentials except for the cache static content. In order to improve on this, I used googles web crawler 


Responsiveness 

In order to test for responsiveness I used googles developer tools and responsive web tester tool for chrome. I made sure to test it as I wrote my CSS and HTML. Once I had my website deployed online, running on heroku I tested it by opening my website across different devices, for instance on the iMac, iphone and the ipad. The results were different from when I checked it using the developer tools and the responsive web tester tool. For instance, my news page wasn’t scaling because I was getting an X-frame options error. This error was due to the fact that the website I was choosing to link into my iframe did not allow me to change the X-frame options (which occurs when you link it into an iframe) meaning that I was prevented from loading any resources from the website. Only when you testing it online that I notice that this error and that for some websites it either doesn’t render at all or renders incompletely. It was very important for me to check it physically on real devices because as I have learnt in the past the tools we use to test responsiveness are sometimes incapable of depicting the full picture.

Evaluation Method - Interview

What was your first impression when you entered the website?

How likely are you to recommend this website to a friend?

Is there anything you think is missing from the page?

Is it easy to get around the website?

Did you find it resourceful? 

How would you rate the website?

How could you improve the website?

What do you like most/least about the website?

What made you exist the website?



The website faired well in terms of speed and responsiveness. After doing SEO tests I noticed that I could optimise the website by adding some meta descriptions. The website was also optimised by reducing  the size of my media files hence increasing rendering speed. I also had a few JS scripts that were being blocked so I removed them. The website looks fine in both to be responsive across mobile, tablet and pc. In some older versions of Opera and Firefox , however, I noticed that there are a few inconsistencies and CSS bugs. The bugs were primarily with the nav bar so If I were to develop it further I would focus on cleaning up the nav bar HTML and CSS. In terms of the mobile version, I had a few issues with CSS when it came to aligning my picture and the about me section in the centre of the page. I think this has to do with the way I structured my column div’s for the large screen version. I would change that to make sure it looks symmetrical. If I were to recreate the website I would start by first designing the mobile version and then scaling up rather than doing the opposite (from large to small) like I did.