---
layout: page
title: MMP 460
week: 10
dek: Final project requirements
---

# Final project requirements

[Home]({{site.github.url}}/) > [Week 10]({{site.github.url}}/schedule.html#week-10)

Your final site should be finished and ready to deliver to the client with instructions for using the site, adding their own content and maintaining the site through the WordPress Dashboard.

To make sure your site will support any kind of content they may add, it’s a good idea to start with the [Theme Unit Test](https://codex.wordpress.org/Theme_Unit_Test), provided by WordPress.  This is basically a check list that you can use to make sure your theme will pass the WP guidelines to be added to the Themes Directory. You can download an XML file that will add some pages and menus to your theme, and then go through the pages and menus to make sure they look the way you want them to and also work.  Although we are not creating a theme for general use, this will be helpful for testing edge cases from any user.

## Final Breakdown

### Client Use (15)

Your site should be ready to go for use by the client.  I should be able to add any content I want and see where it is reflected in the site, and be aware of what I can change and update.  Each group should provide instructions within the dummy content of the theme (for example, posts should have titles like “Create a New post here” and content like “Add text and images here”).

### Dummy Content (10)

This is based on the content in the Theme Unit Test.  I want to see that each type of content is displayed and fits within the scheme of the site.

### Visual Design (20)

Overall Impression: does the visual design fit the client organization and it’s mission? This is about the atmosphere and feel of the site. Much of this is conveyed by the fonts, colors and images and graphic embellishments (icons, shadows, borders etc).  The most important part is consistency.  Your design choices should be applied consistently across all content.

Parts of the page are clearly visible: header, nav, content, footer etc. and the relative importance.

This will include support for responsive or mobile design.

### Template Files (35)

Most of these files should be provided by Bones, Reverie or another template, but these are the basic necessary files for your page to run.  If there are files you don’t need for one reason or another, explain in your comments.

Page Templates / Loop Content

Page templates have the loop in them. The loop content parts are an optional way to show the content in the loop. Either use them with content- in front like like content-home.php or add info directly to the loop. Be consistent with one or the other solution

- index.php: this is the default page. Required of all themes
- 404.php : Shows if a page or post is now found. the only one where you don’t need a content- because there is no loop
- search.php: shows the search results
- archive.php: shows list of category/tag/date/author posts
- single.php: shows a single post
- page.php: shows a page
- home.php: shows the list of posts on the homepage or the blog page if a static homepage is chosen.

Page Parts

- header.php: shows the top of the page. Includes doctype, opening html, head and opening body tags
- footer.php: shows the bottom of the page. Includes footer and closing body and html tags.

Functions

- functions.php: this is where you enable things like featured images, menus, widget areas

### Site Functionality (20)

These are functional elements you must implement

- Menus (Navigation)
- Featured Images
- Widget Areas (at least one)
- Search


### Extra Credit

I will consider giving extra credit (up to 10 points) to any template pages or functionality outside of the scope of the requirements, including things like slideshows, category pages, or other features.  Please document the extra features so I can look for them in the assignments notes.  I will determine whether the quality of the added elements is deserving of extra credit.

### Presentation

The client will come to class to view the finished work.  Your group should present the site including the design choices made by the team and the full functionality of the site.  

### Turning in the Final

If your project is hosted on Cloud9, make sure I am invited as a member to the workspace so I can launch the site and share it with the client.  

If hosting on the wpmmp server send a link along with a zip file of the theme contents and login information for the Dashboard.