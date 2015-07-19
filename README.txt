-------------------------------------
               README
-------------------------------------

Current Version : v 1.0.0
 
 ---------------------
| GENERAL INFORMATION |
 ---------------------

1. What is this?
------------------
  The source code and required packages for the Dartmouth College Fencing Club (DCFC) website. 


2. What is this built with?
----------------------------
  The DCFC website was built using the Foundation 5 framework. Information about Foundation 5 can be found at [ http://foundation.zurb.com/ ]. Aside from that, the website uses standard
  HTML5, CSS, SASS, and Javascript.


3. What do I need to maintain the webpage?
-------------------------------------------
  For simple updates and changes, such as swapping out text and images, regular upkeep, and minor design changes, nothing at all! Make all changes in the respective HTML files, and put all relevant images in the pictures folder.


4. What if I want to make significant changes?
-----------------------------------------------
  As mentioned before, this website was built using the Foundation 5 framework. Aside from an understanding of how Foundation 5 works, this project also uses SASS, which is a powerful
  CSS extension that does much more than regular CSS. To configure SASS for Foundation 5, please refer to [ http://foundation.zurb.com/docs/sass.html ]. Git, NodeJS, and Ruby 1.9+ are required for SASS to work with Foundation 5. 


5. Who do I credit for this website?
-------------------------------------
  This website was originally designed and coded by Tristan L. Chu '16 for the Dartmouth College Fencing Club.


 ---------------------
|  PROJECT STRUCTURE  |
 ---------------------

  For the purpose of this README, ignore the following folders and files :

  .sass-cache
  bower_components
  .bowerrc
  bower
  config.rb
  Gemfile
  Gemfile.lock
  humans.txt
  robots.txt

  These files are all dependencies and libraries that Foundation 5 + SASS need to run. No changes should be required in any of these folders or files to run or maintain the
  DCFC website.

  CSS / SASS / JAVASCRIPT
  ------------------------

  js        
    app        : file that contains the default javascript settings for the project

  scss        
    app        : file with necessary SASS information
    _settings  : file that contains the default SCSS / SASS settings for the project. SASS related changes are made in this file

  stylesheets 
    app        : file that contains the default CSS settings for the project

  CUSTOM FOLDERS
  -----------------------

  news_articles      : contains the individual HTML files for the "news" section of the DCFC website
  pictures           : contains the pictures currently being used on the DCFC website 
  pictures_originals : contains the original version of photos currently being used on the DCFC website
  pictures_reserves  : contains backup photos / alternate photos for use on the DCFC website

  HTML
  -----------------------
  
  about.html         : contains the HTML for the "About Us" section of the DCFC website
  competition.html   : contains the HTML for the "Competition" and "Results" sections of the DCFC website
  faq.html           : contains the HTML for the "FAQ" section of the DCFC website
  index.html         : contains the HTML for the main page of the DCFC website
  media.html         : contains the HTML for the "Media" and "Photo Gallery" sections of the DCFC website
  news.html          : contains the HTML for the "News" section of the DCFC website. Links to the HTML pages found in "news_articles"
  practice.html      : contains the HTML for the "Practice", "Armory", and "Policies" sections of the DCFC website. 
  prospie.html       : contains the HTML for the "Prospective Students" and "Contact Us" sections of the DCFC website
  roster.html        : contains the HTML for the "Team Roster" section of the DCFC website
  support.html       : contains the HTML for the "Support Us" and "Friends of Dartmouth Fencing" sections of the website

  If further clarification regarding each files is needed, please refer to the comments within each file

 ---------------------
|      CHANGELOG      |
 ---------------------

July 19, 2015 : V 1.0.0 Released



