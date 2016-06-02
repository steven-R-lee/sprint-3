what happens to the layout when you resize the screen to less than 550px?

  The 'getskeleton.com' webpage operates on a 12-column fluid grid with a max width of 960px that shrinks with the browser.

  However, when the screen width is reduced to a size of 550px or less the fluid grid collapses onto a singular column, thus changing the layout of the page.


how do you think that works?

  It works because Skeleton uses 'media queries'.

  These media queries are mobile-first, meaning that they target min-width.

  Essentially, the single-column layout of content is styled in a reduced fashion upto and including a browser width of 550px, smartphones and phablets.

  Then for larger devices, Desktops, Latops and Tablets, styles are targeted for enhancement. This prevents small devices from having to parse tonnes of unused CCS.