Eduardo Parkinson de Castro			
D17126897
20 April 2018


Phase II Test & Evaluation
Web and User Interface and Design

My Personal website: https://eduardo-website.herokuapp.com/home.html
Deployed using Heroku (https://www.heroku.com) from my github pipeline (https://github.com/puzzle91/Web-InterfaceProject)

				 CSS, HTML and Javascript

All of the CSS in news.css and index.css file is my own. Most of the CSS for the footer is not mine, it is only slightly modified. Most of the CSS (70% to 90%) for the nav bar is mine own.  It is hard to exact how much of the nav.css file is exactly mine because I have used the nav bar before in a previous website I built and have modified it over time to fit my needs. I used a contact template from https://mdbootstrap.com/components/bootstrap-contact-form and modified it for my website. The javascript is my own. Total lines of my own CSS: 200 approximately. Modified CSS: 100 approximately. Total CSS = 300 (approximately)

I used bootstrap as my CSS framework. Bootstrap allows me to create a grid-style website that adjusts itself based on columns that range in size from one to twelve. A lot of my website is built using a 4 by 3 grid. That is, the column size of each grid (column) in the row inside my container is 4 and I typically have 3 of them side by side. I can also create empty columns to place things where I want them to be. I use this technique when modifying my contact form, because I wanted it to look symmetrical to the rest of the website. I can access bootstrap by linking it in the head of the html. Bootstrap also comes with in-built CSS that can be accessed by using classes that are in-built to the bootstrap package. This in-built CSS can be over-run using your own CSS. I often used to inspect tool on chrome to test my CSS changes and make sure they were appropriate and to find out what CSS file (if it was bootstrap or my own) was changing the html. 

I used bootstrap because it is convenient. It has a grid system that is intuitive and once you become familiar with it, it becomes easy to make responsive content. Some media will require queries to be adjusted but overall the bootstrap does a good job in ensuring that the content inside the containers adjusts well when scaled into different device sizes. One way that bootstrap makes it easy is by ensuring that media (video, images, iframes, etc.)  scales well when placed next to media that is of the same size. That’s why I adjust most of my media so that they are of symmetrical size (e.g., 624x382 for my large images).

						   Testing

For speed testing I used www.webpagetest.org. All speed tests were made from location New York, NY, USA and on the chrome browser. My results are as follows:

My homepage:

Load time - 2.341s
Visually Complete time - 2.500s
Fully loaded time -  2.474s (after 26 requests and 567KB)

 
My news page:

Load time - 14.183s
Visually Complete time - 8.200s
Fully loaded time - 21.191s (after 384 requests and 5,132KB)

My index page scored an ‘A’ across all credentials except for the cache static content. In order to improve on this I could use googles web crawler. In order to optimise my website’s speed I reduced  the size of my media files. I also had a few JS scripts that were being blocked so I removed them. Furthermore, I compacted my HTML code by removing any JS scripts that were in the html file and moving them to a separate file. I also compacted my CSS code by removing any redundant or duplicate CSS. Total CSS lines are now: 100+54+83+14=251. Total HTML lines are: 361 for index page and 99 for news page. 

Here are my results after these changes:

My homepage:

 

New load time - 2.332s
New visually complete time - 2.400s
Fully loaded time - 2.477s (after 26 requests and 567 KBs)

My news page:

New load time - 2.438s
New visually complete time - 2.500s
Fully loaded time - 2.569s (after 26 requests and 566 KBs)

					Responsiveness 

In order to test for responsiveness I used google’s developer tools and the responsive web tester tool (add-on) for chrome. I made sure to test it as I wrote my CSS and HTML. Once I had my website deployed online, running on heroku I tested it by opening my website across different devices, for instance on the iMac, iphone and the ipad. The results were different from when I checked it using the developer tools and the responsive web tester tool. For instance, my news page wasn’t scaling because I was getting an X-frame options error. This error was due to the fact that the website I was choosing to link into my iframe did not allow me to change the X-frame options (which occurs when you link it into an iframe) meaning that I was prevented from loading any resources from the website. Only when you testing it online that I notice that this error and that for some websites it either doesn’t render at all or renders incompletely. It was very important for me to check it physically on real devices because as I have learnt in the past the tools we use to test responsiveness are sometimes incapable of depicting the full picture.

			Evaluation Method - Interview

(Interviewee Niamh Grogan Interviewed by Eduardo Parkinson testing the website on iPhone 6)
Q. What was your first impression when you entered the website?

A. My first impression is that I like the colour contrast. It is very clear and laid out nicely. It was eye-catching. 

Q. How likely are you to recommend this website to a friend?

A. Sure, I am likely.

Q. Is there anything you think is missing from the page?

A. Not that I know of.

Q. Is it easy to get around the website?

A. Yes because you can scroll through it quickly and read over it. And if you want to get to an area quickly you can press the top buttons and it takes me to that section straight away. It also has links to social media accounts which is handy.

Q.  How would you rate the website?

I would give it a 8/10. I would like if the name in the logo were straight across as opposed to one in one line and the rest in the other.  But overall visually it is very appealing and has everything you need to know in a simple form. I liked the picture and the quick links to the social media were clever. Its good that you don’t have to scroll down to the bottom of the page and that they are constantly there.

Q. How could you improve the website?

A. Making the name at the logo for the top header not be split into parts. I would also put the photo in the middle or put the about me beside the photo so that it is neater.

Q. What do you like most/least about the website?

A. What I like the most is the diagram in the photos. I think they are very eye catching and artistic. I also like the layout it is very minimalistic and simplistic. What I don’t like most is that it needs more content and the photo could be placed better. 

Q. What made you exist the website?

A. I exited the website when I finished looking at everything on it. 

Evaluation Method Appropriateness: 

I chose to use an interview for my evaluation method because I think it provides me with unbiased information on what the user thinks of the website and how the user interacts with the website and what his feedback is. Instead of using a survey or a grading system, I believe that the interview allows me to gain better insight into understanding what a user wants from a website and what it is that he/she appreciates or dislikes. By creating these specific questions I was able to learn what the user enjoyed aesthetically and what I need to improve on(for instance, the lack of symmetry on mobile for my picture). I was also able to learn how the user navigated the website and what the user appreciated (for instance, the simple design, the fixed footer, and the clear header, etc.). Based on the feedback I received, I went back to my CSS and HTML and altered some things that the user reported would be an improvement. Thanks to my interview I was able to dedicate my efforts to changing the things that would improve the UX and the website’s usability.  

			Outcome of Test and Evaluation

The website faired well in terms of speed and responsiveness. After doing SEO tests I noticed that I could optimise the website by adding some meta descriptions. The website looks fine in both to be responsive across mobile, tablet and pc. I used http://browsershots.org/ to check for compatibility with different browsers. It seems to generally be compatible with all browsers with the exception of some older versions of Opera and Firefox and other smaller browsers Konqueror and SeaMonkey where I noticed that there are a few inconsistencies with the CSS. The bugs were primarily with the nav bar so If I were to develop it further I would focus on cleaning up the nav bar HTML and CSS. In terms of the mobile version, I only had a few issues with CSS when it came to aligning my picture and the about me section in the centre of the page. I think this has to do with the way I structured my column div’s for the large screen version. After some careful CSS adjustments I was able to get it to work. Now it looks a lot more mobile friendly.

 My recommendations for future development are that further adjustments could be made o make ensure that it looks symmetrical in particularly small devices (i.e. devices with max-width equal to 500px or less). Although my website passed all the mobile-friendly tests, if I were to recreate the website I would start by first designing the mobile version and then scaling up rather than doing the opposite (from large to small) like I did. Furthermore, I started working on a python implementation to get my contact form to email me messages using an API from the Sendgrid add-on for Heroku. This still needs to be worked on as it's not functional at the moment. 