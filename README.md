# Bootstrap-SPA-Sidebar-Menu
Simple example of a web client with sidebar menu for Single Page App using Bootstrap

The intent of this repo is to test a simple client for a single page app, with 'fakey' pagination functioning.  We need a functional navigation system that works well on mobile devices without a lot of overhead.

## [Click for Demo](https://zipzit.github.io/bootstrap_SPA_sidebar_menu/)

Use case:  
 - We're working with small and medium sized businesses to help them manage their internal operations.  
 - We want to take advantage of their employees' mobile phones.  (Bring your own device -- BYOD)
 - Progressive Web Apps work great for this.  No app store involved.  Link saved on user's home screen.  App like functionality.
 - We've been using jQuery Mobile for this, but alas, it appears that system is no longer being supported for current and future updates.
 - We want a single page application to accommodate our authentication process. 
 - After authentication, different users get different content.  This is way easier in Single Page App via Ajax calls.
 - We like page navigation with 'fake' page base content delivered on a simple index.html file.  
 - This menu use aligns with how users think. Mobile scroll down doesn't work so well for business activities.  

We happen to like a left hand, slide out menu, activated by three bar menu icon on mobile devices.  Its a nice alternative to the more common Bootstrap top menu bar.

To make deployment simple, we want a single server for API calls, AJAX calls and serving up browser/client content.  [NodeJS / Express preferred... ]  Bootstrap with this navigation proposal supports that well.

I suspect using this navigation system (and Bootstrap) offers a relatively painless alternative to (existing) jQuery Mobile applications.  This proposal uses virtually no additional libraries... The key functioning elements are native to Bootstrap and just a few lines of plain javascript.  

 # References:
   The initial inspiration for this work came from [this SoloDev posting.](https://www.solodev.com/blog/web-design/adding-pagination-to-your-website.stml)  Unfortunately pagination isn't really what we want.

   The basic navigation structure of the final sample here came from [this posting at BootStrapious[(https://bootstrapious.com/p/bootstrap-sidebar)  I will say, while I was searching for alternatives to my jQuery Mobile dilemma, I did come across the [Bootstrapious Creative Portfolio template](https://bootstrapious.com/p/creative-portfolio).  Very nicely done. And hey, the [Bootstrapious blog](https://bootstrapious.com/blog) is pretty awesome.   

   Many thanks to Ondrej Svestka and the folks at Bootstrapious for their work...
   
 # Search Terms
 label:Single Page App - SPA
 label:jQuery Mobile alternatives
 label:Bootstrap Menu, Bootstrap Nav
 label:Bootstrap Tab Navigation, Bootstrap Pill Navigation 
 label"Progressive Web App - PWA
