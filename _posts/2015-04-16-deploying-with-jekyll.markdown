---
layout: post
title: "Deploying with Jekyll using FTP"
date: 2015-04-16
categories: jekyll
---
Jekyll is known for it's ease of use, maintainability, and easy deployment. But what if it's your first time on the block, and you run into a few issues. Well here's a simple guide:

After you have your jekyll blog developed and ready for launch, simply enter the root of it using terminal. After you're at the terminal type <$ jekyll> This will create a new folder in the root of your site called "_site". This is the folder you will use to deploy your website.

Next, find a host and a domain. For this example we will use HostGator. Launch your favorite FTP application, I recommend 'Transmit' for mac, and 'FileZilla' for Windows. Navigate to the 'public_html' (may also be 'httpdocs') folder and copy over the content of _site. That's it!

You should now see your new website on the domain you chose. Great job!
