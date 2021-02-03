# ChromeHomepage
This is a sample Chrome Homepage with functioning bookmark links

I built this as a 'homepage' where all my important daily bookmarks can be found without the annoying use of the bookmark bar,
  or by adding in an extension that manages my bookmarked tabs into groups for easy access.

It is rather easy to insert your own bookmarked urls into the HTML file.
# <li><a href="https://Your.URL.here" 
                   target="_blank" rel="noreferrer noopener" style="color:#262626">Your URL Link name</li>
This is a sample of where to insert your own URL, what color the link is displayed in, and what to call your link.

If you need more or less in a particular section, then simply copy and paste more, or delete the entire <li></li> that you no longer require.

In addition to this, the header at the top of the page will open all links associated with said group. 
The function to open all the links associated with a header link is located in the Scripts.js file.
If you plan to use said function, make sure to add your URL to the respective function in the Scripts.js file, otherwise that tab will not open.

It is important to delete any <li></li> not in use in the HTML file, otherwise the HomePage will be opened in a new tab.
Correspondingly, every instance of window.open() in the Scripts.js file must be deleted, 
  otherwise the HomePage will be opened in a new tab equal to the amount of empty window.open() there are in the designated function.
  
In the Styles.css there are spots to add in background pictures to each element.

Essentially this was just a personal project of mine and wanted to share with anyone interested.

If you have any questions, or things aren't working please let me know. Or if you need any help setting up links and pictures, please let me know too.
I'm happy to help with what I can!
