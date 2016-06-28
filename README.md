# Sheena-Marie.github.io
Personal Webpage

test

# Design Documentation

by Sheena Takkenberg

## Site audience
- The site's audience at this point in time is going to be for any potential employers. I want this site to be where I can show off my skills and what I know.


## Design decisions
- The navbar was one of the first things I designed. I wanted something simple that would be easy to navigate from. It evolved a bit over time, losing the dropdowns for a while, only to gain them back when the bar became too unweildy when seen in mobile view. I found it easier, and much cleaner, to move the social media icons into a dropdown menu. It works, and it keeps the navbar neat no matter what size it is.

- I see-sawed between using bootstrap and not using it so many times during the creation phase. I eventually decided not to use it, as it just didn't work for what I wanted.

- The hero photo is one of my own, taken by myself on my family's property a few years ago. It had the added advantage of matching the colour of the navbar perfectly, meaning that I didn't have to change the colour scheme.

- The Twitter widget was chosen to be the main feature on the landing page. I wanted something that showed my personality, but didn't take up too much space. I liked the scrollbox that it came with and decided to keep that same format throughout the rest of the page. I designed a scrollbox in css that would hold my work history and other information to match the Twitter widget on the landing page. This keeps the pages looking uniform (and limites the amount of CSS that is needed) on a desktop, and makes it much, much simpler to make the page mobile responsive.

## Usability considerations
#consistency and standards
  - I wanted to have a uniform look to the page. By keeping a scrollbox containing all the information of the site, it keeps the same look over multiple pages. This means that the user knows exactly where to look for information on every single page and saves scrolling.

#Aesthetic and minimalist designed
  - The design is simple, with only a scrollbox to the right of the page (centred on mobile) and no other elements to clutter the page. A user will know exactly where to look right away without having to search for what they're looking for.
  - Another advantage of this is that it reduces the amount of CSS needed as the scrollbox is the same for all the pages.



## Supporting documents

1. Style Guide
http://codepen.io/Sheena_Marie/pen/BKraew

2. Github
https://github.com/Sheena-Marie/Sheena-Marie.github.io

3. Favicon
https://github.com/Sheena-Marie/Sheena-Marie.github.io/blob/master/apple-touch-icon-180x180.png

4. Sitemap
http://sheena-marie.github.io/sitemap.xml

5. robots.txt
https://sheena-marie.github.io/robots.txt

#Page Tested and Working On:
- Firefox
- Internet Explorer
- Chrome
- Safari
- Qupzilla
- Konqueror
- Galaxy S5
- Nexus 5X
- Nexus 6P
- iPhone 5
- iPhone 6
- iPhone 6s Plus
- iPad
- Galaxy Note 4

#Progress Journal

#9 May 2016
- Finished the documentation.
- Tweaked a few small spelling errors spotted during my last look over the page.
- Had several friends test the page for me from different countries. Got the all clear back from all of them.
  - One Pointed out an issue with the navbar on mobile; it took a few hours, but that problem has been fixed.
    - problem required downloading the Font Awesome files and and removing the weblinks in the head. This enabled me to fiddle with the size of the icons down the the most minute amount, making it easier to change their size in a media query for phone screens. This fixed the problem and the social media dropdown now works on mobile phones.

#6 May 2016
- Had a friend in the US test the site for me. She was using Chrome with Ad Blocker and Disconnect running.
  - Ad Block hides the Twitter, LinkedIn and Facebook icons and will not display them.
  - Disconnect hides the Twitter feed on the Landing Page, but shows a link to my Twitter page on a tan background.
  - If both of these are turned off, then the site is perfectly viewable. Must research a way to get around this problem...is there a way to get around this problem?
- Have added content into the Education section. I'm not entirely happy with it, but that's something I can poke at over time as my skills improve.
- Added content to the Work History section. Again, this is something that I can poke at over time as my skills improve.

#5 May 2016
- Took a couple of days off, this page was starting to annoy me.
- FINALLY got the favicons working on all platforms. I'm very pleased about that. I even got it to work with the logo I designed way back in my first or second week!
  - Everything I've read recommended that I place the favicons in the root directory, so that's where they've been placed.
- Dropdowns are back in. I knew I kept that code in for a reason. It makes the navbar much more manageable
- favicons work in Konqueror and Qupzilla as well. Looks like I got it working on everything. Very happy about that! Works on IE, Firefox, Chrome, Safari will put up a tab with an 'S' on it when you pin the tab. Safari will show the large favicon on the page of a new tab when one is opened. Very, very happy that I've got it working.
- Added the 'Education' page. Decided that I wanted it looking like the Twitter widget on the homepage, so used some of the same classes and then googled how to do scrollboxes. Going to try and keep the page as uniform as possible.
- The site has been verified on Google, I'm just waiting for them to finish processing it so I can continue. Now I just need to work out how to do a robots.txt file and a sitemap.
- Changed the sitemap to an 'xml' format so that Google can read it. Also added a robots.txt file to the page.

#2 May 2016
- Figured out how to put a live updating twitter widget on my landing page. Quite pleased with that! The site's slowly coming together.

#1 May 2016
- Added a hero image to the page. Still playing around with the navbar and am trying to get the page to be responsive on mobile phone (headache of epic proportions). It's sort of responsive, but I really don't think the responsiveness is going to work properly by the due date.
- Deleted bootstrap completely because it was just not working the way I wanted to. I spend more time trying to get bootstrap to work than I do actually putting the page together. I thought bootstrap was supposed to be easy?!

#28 April 2016
- Have removed the dropdowns, but kept the divs for it as I may still put something in there at a later date (why recode if it's already there). I do have some plans for it.

- Still goofing around with Boostrap a bit.

#THINGS TO DO
- Get this thing fixed to the top without screwing everything up. Right now when I fix to to, it goes screwy and assumes my page is much smaller than it actually is.
- Add more content. It's looking pretty bare right now.
- Can I get a picture of me in the navbar? RESEARCH IT!!!

#27 April 2016
- Played with Bulma instead of Bootstrap. It appears to be set for smaller screen resolution and absolutely screwed with my settings (3 hours of frustration there alone). Have switched back to the customised Bootstrap that I set up yesterday.

#26 April 2016
- added CSS
- added googlefonts to the CSS file (so much easier than adding them to the html page every single time. Now they're all in the one place).
- added a navbar
- tried to do favicons (and failed. Something for another day)
- attempted my own grid system and failed. Downloaded and added customised bootstrap with just things like the grid system added. Own grid system to be added at a later date when I know a bit more about it.

#THINGS STILL TO DO
- work out how to get the navbar more responsive (it looks horrible on mobile right now >.<) (
  - DONE 5/5/16)
- put in content
  - (DONE 6/5/16)
- do I really need the dropdowns? They look cool, but they're not going anywhere right now
  - (5/5/16 - good thing I kept the dropdowns, as I'm now using them to keep the navbar in check)
