# paginationSlider
As a reaction upon the job agency pagination buttons, where one can't jump freely as the number of pages increase, I coded this.

It's for navigating between pages (on a web page), defined as a result of 'pagination' - that a list of data is split into pages.

I wanted all the pages be reachable at once, not admitted after 20 seconds of clicking.

So, I embarked upon the pagination-menu at hand, having a "prev" and a "next" button with some numbered buttons inbetween, and a link-button for the very last page.

I removed the "last-page" button/idea from my workdesk, and forced the whole range of page-button-links to reside between the prev- and next-buttons.

(To try a big amount of buttons/pages - please set the variable addedExtraButtonsCount to a big number)

To make it simple and natural to use (as natural as a interface could be - maybe like a video game), a added a "slider" that would be feathering back to it's initial
position (the middle), every time I dragged it sidewise. This wouldn't be needed on a touch screen...
