---
title: Event loop
date: '2021-03-10'
categories: []
tags: []
excerpt: What is the JavaScript Event Loop?
thumb_image_alt: lorem-ipsum
image_alt: lorem-ipsum
image_position: top
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
template: post
subtitle: What is the JavaScript Event Loop?
---
To understand how JavaScript runs in the browser, and to create web apps that run smoothly and quickly, it is important to understand the event loop.

JavaScript as a programming language is single threaded, asynchronous, and non-blocking.

Javascript is a single threaded language. This means it has one call stack and one memory heap. As expected, it executes code in order and must finish executing a piece code before moving onto the next. It's synchronous, but at times that can be harmful. For example, if a function takes awhile to execute or has to wait on something, it freezes everything up in the meanwhile.

A good example of this happening is the window alert function. alert("Hello World")

You can't interact with the webpage at all until you hit OK and dismiss the alert. You're stuck.





