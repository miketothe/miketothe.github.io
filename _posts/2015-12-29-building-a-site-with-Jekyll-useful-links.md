---
layout: post
title: "Building a site with Jekyll: useful links"
date: December 29, 2015
--- 

Hello world! I guess I won't be the first one who started blogging with writing a first post about... setting up a blog. Actually I feel like I owe this to the author of this brilliant static site generator called Jekyll. Let me explain why.

Right after I came up with an idea of running a web-related blog I started thinking what CMS I should use to make it happen. I've built a page based on Wordpress already so I wanted to try something new. The other thing was that I wanted to keep my blog neat and simple, and wordpress seemed a little too heavy for this purpose. The same thing with Joomla or Drupal. They are really great systems for regular people who have no knowledge about coding but still want to set up an own blog. Those systems have user-friendly graphic interface, admin panels and page building widgets. But to run all these features and build a page they require SQL database and server-side PHP interpreters. This means additional code and more requests to make a website visible for the end-user. I didn't need all of that just to share my thoughts and some snippets of code. So for me Jekyll was the best option. It is simple, light and really easy to maintain. It generates static pages with no PHP code inside and you don't have to care about any databases. You don't even have to pay for hosting. You can push all Jekyll files directly to your Github repo and have some space for your site completely for free!


So how to start with Jekyll? I don't want to rewrite other tutorials covering this topic, because this would be pointless. What I want to do is to share with you a couple of most useful links that helped me to set up a Jekyll-based site:

\- The most reliable and up-to-date position is of course the official website of Jekyll: [jekyllrb.com](https://jekyllrb.com/)

\- But if you're a newbie to Ruby (just like I was) and you need someone to guide you through all the installation steps then you'll probably find this course more useful: [pluralsight.com/static-websites-with-jekyll](https://app.pluralsight.com/courses/static-websites-with-jekyll)

\- If you install Jekyll on Windows then make sure you follow all the hints provided on this website: [jekyll-windows.juthilo.com](http://jekyll-windows.juthilo.com/)

\- If you'd like to have all of your post paginated (I bet you would), then here you'll find some really useful tips on this topic: [ericlagergren.com/blog/jekyll-pagination/](http://www.ericlagergren.com/blog/jekyll-pagination/)
Hint from me: remember to install on your system an additional gem which enables pagination. To do this simply run a console and type: `gem install jekyll-paginate`. Then add to your _config.yml file a line: `gems: [jekyll-paginate]`.

\- At the end you may want to deploy your site to the Github repo and build the blog straight from there. Github Pages service gives you 1GB server space and the domain of username.github.io for free.
All info needed to run your Jekyll site on Github you'll find here: [github.com/articles/using-jekyll-with-pages](https://help.github.com/articles/using-jekyll-with-pages/)

This is the end of setting up a site with Jekyll but the beginning of having fun with it. I bet you'll spend hours on making your blog looking unique and then days and months on filling it with a valuable content. Enjoy!