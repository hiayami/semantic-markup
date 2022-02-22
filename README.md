About this project:
    To improve a site to make it more accessible for users and in doing so will optimize it for search engines.

    The goal and challenge for this project was to add semantics and organize the code while keeping the functionality of the webpage.

Intro:
    HTML, or Hypertext Markup Language, is the standard markup language for creating Web pages. It's like the "building blocks" of a webpage (title of the page, heading, paragraphs, images, etc.) and labels it as such with elements. Elements are tags that tell the computer what the content is (2019, w3schools). 

    (https://www.w3schools.com/html/html_intro.asp)

    It is the "elements" that help make the webpage accessible. For example, individuals who are vision impaired may need to use a screen reader, and the screen reader parses the webpage to help the user know where a navigation bar is, what internal links are listed in the navigation, what an image looks like or consists of, etc. 

Process:
    I reviewed the HTML code and noticed that it was structured with mostly empty line breaks <div></div>

    While this structure still works, it does not meet accessibility standards. I replaced many of the <div> tags with elements such as <nav> (for navigation), <header>, <section>, <aside>, and <footer> in the appropriate areas.
    I also added alt names for the images, as descriptions of images can provide information for visually impaired or individuals who use screen readers.

    While the HTML is now made accessible, it's still important to have clean code for other users to review and understand the source if needed. 

    The CSS page was reorganized in an order of appearance alongside the HTML and appropriate comments were added.
    
    Repition was decreased. For example, the sections had a class for each section that described commands/changes. For example, class="search-engine-optimization", class="online-reputation-management", and class="social-media-marketing" were all changed to 'section' under the CSS page and put into one body instead of three.