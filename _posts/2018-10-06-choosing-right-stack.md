---
layout: post
title: Choosing the right Stack for my portfolio.
cover: creating-a-website.jpeg
image: assets/images/creating-a-website.jpeg
permalink: choosing-the-right-stack-for-my-portfolio
---
Developers and non-technical people have now gazillion of options in building websites, Blogs, and even marketplaces. Ranging from drag n drop tools like Wix, , the popular WordPress and Magento for e commerce sites. With the options we have in our hands put a lot of dilemma in choosing the right tools and platform. 

Instead of  trying all this tools, I decided to create some criteria that should be meet for choosing the right tool for me.

-----

## Criteria in Choosing The Right Stack. 

### Speed
It's 2018, slow websites have no place in today's INTERNET.

### Maintenance
It should be easy to maintain. I have a morning job so keeping it up and running will be no easy task. I like to keep things simple and I dont need features that I dont plan on using. It should be easy to host and manage. Setting up a server is not a option.	Availability of free hosting plan is a plus.

### Security
Do I need to explain this. Just kidding. This will be my personal site and I dont want someone compromising it. I already experienced a site I made got infected by malware and was down for almost a month. This put a lot of headache and stress to me and my client. 

### Community and Plugins

Ready made extensions to the platform is a very welcome one. Extending the platform's functionalities without too much configuration would be a breeze.

------

## Static Site Generator.
With the criteria I made, I decided to go with static site generators. As the name implies this is a tool for creating static sites. Sites that does not require a database and too much resources. 

Choosen SSG for this project is **[Jekyl](https://jekyllrb.com/ "Jekyll Websit")**. There is alot of SSG available online bust I decide to go with this since it is natively supported by [Github Pages](https://pages.github.com/ "Github Pages"). Github Pages is a free hosting services offerd by Github for open source projects.

![Jekyll Website](/assets/images/jekyllrb.com-website.png "Jekyll Website")

### Installing Jekyll is easy

Installing jekyll as easy a just 4 commands.

```
$ gem install bundler jekyll
$ jekyll new my-awesome-blog
$ cd my-awesome-blog
$ jekyll serve
```

### Initial Jekyll Project Theme

![Jekyll Default Theme](/assets/images/default-jekyll-theme.png "Jekyll Default Theme")

[Minima](https://github.com/jekyll/minima "Minima Github Repository") is the default theme for Jekyll. 

------

## Does Jekyll meets my criteria?

Choosing the right stack for your personal website or project will depends on your needs, resources and preferences. Jekyll may not be the right tool for you and may find other options. For a complete list of SSG follow this [link](https://www.staticgen.com "Static Gen").

### Speed
Jekyll exceeds not only on developement time but also in performance and deployment. Since no back end processes happens serving site's content to user fast.

### Maintenace.
Jekyll can be deploy on a serverless environment reducing infrasture maintance. It can be hosted in free services like Github Pages.

### Security
Since no back end process and user input was required to run the application I can say that security in Jekyll is good. Of course you should always use difficulat password on your hosting provider.

### Community and Plugins
Themes and Plugin for Jekyll is endless. PlanetJekyll's [AwesomeJekyll](https://github.com/planetjekyll/awesome-jekyll "Awesome Jekyll") and [DrJekyllTheme](https://drjekyllthemes.github.io/ "Dr. Jekyll Themes") have a vast collection of open source themes and plugins.

## Conclusion
If you need a simple web developement tool that is easy to use, has a vast collection of themes and plugins, secured and fast, Jekyll maybe the right tool for your. This porfolio is also written using Jekyll. You may see the source [here](https://github.com/manuelubaldo/manuelubaldo.github.io).

This is my first writing a blog. Please bear with my grammar and writing style, if any. :) 

Cheers! Thank you for reading.

-------
