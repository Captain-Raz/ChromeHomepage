# ChromeHomepage
This is a sample Chrome Homepage with functioning bookmark links

READ-ME for 'Github Homepage.htm', and 'Github Scripts.js'
Please scroll down through each section.

##						                        ##
##						                        ##
##	READ-ME for 'Github Homepage.htm'	##
##						                        ##
##						                        ##

<header> ##This is the header section.
  <nav id="navbar" class="nav">
    <ul class="nav-list">
      <li onclick="lorem1()">lorem ipsum</li> 	##These are what I call 'All-Links' they open all the links within the called function
      <li onclick="lorem2()">Browsers</li> 	    ##This is the only one that is functioning in this setup
    </ul>
  </nav>
</header>

##These 'All-Links' only work after hitting 'allow pop-ups'; however, after a fresh Chrome startup they will not work again until you hit 'allow pop-ups' again.

<body>
  <div class="bookmarks">
    <div class="row top_row">
      <div class="lorem1">
        <ul class="text">
          <li>lorem ipsum</li>  ##Bookmark Title
        </ul>
        <ul class="links">
          <li><a href="" 
               target="_blank" rel="noreferrer noopener" style="color:#ffffff">lorem ipsum</li>   ##Bookmark link with small Description
        </ul>
      </div>
      <div class="lorem2">
        <ul class="text">
          <li>Google</li>   ##Title is Google
          <li>Bing</li>
          <li>Yahoo</li>
        </ul>
        <ul class="links">
          <li><a href="http://www.google.com" 
               target="_blank" rel="noreferrer noopener" style="color:#ffffff;">Link to Google</a></li>   ##Bookmark link with Description 'Link to Google'
          <li><a href="http://www.bing.com" 
               target="_blank" rel="noreferrer noopener" style="color:#ffffff;">Link to Bing</a></li>
          <li><a href="http://www.yahoo.com" 
               target="_blank" rel="noreferrer noopener" style="color:#ffffff;">Link to Yahoo</a></li>
        </ul>
      </div>
    </div>
  </div>
</body>

##						                        ##
##						                        ##
##	READ-ME for 'Github Scripts.js'		##
##						                        ##
##						                        ##

function lorem1() { 	##These are the functions that are associated with the 'All-Links' above.
    window.open(
      "", "_blank", "noreferrer noopener"
    );
    window.open(
      "", "_blank", "noreferrer noopener"
    );
    window.open(
      "", "_blank", "noreferrer noopener"
    );
};

function lorem2() {	##This one is for 'Browsers'
    window.open(
      "http://www.google.com", "_blank", "noreferrer noopener"    ##On click it should open Google in a new tab
    );
    window.open(
      "http://www.bing.com", "_blank", "noreferrer noopener"	    ##and it should open Bing in a new tab
    );
    window.open(
      "http://www.yahoo.com", "_blank", "noreferrer noopener"	    ##and it should open Yahoo in a new tab
    );
};

##However, as stated above, this only works if you have 'allowed pop-ups' for this page. But it doesn't quite work from a fresh opening of Chrome.
