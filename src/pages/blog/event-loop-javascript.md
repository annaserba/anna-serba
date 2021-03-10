---
title: Event loop
date: '2021-03-10'
categories: []
tags: []
thumb_image_alt: event loop javascript
image_alt: lorem-ipsum
image_position: right
seo:
  title: ''
  description: ''
  robots: []
  extra: []
  type: stackbit_page_meta
template: post
thumb_image: images/unique-eucalyptus.png
excerpt: What is the JavaScript Event Loop?
---
What is the JavaScript Event Loop?

To understand how JavaScript runs in the browser, and to create web apps that run smoothly and quickly, it is important to understand the event loop.

JavaScript as a programming language is single threaded, asynchronous, and non-blocking. What do these terms mean? JavaScript is single-threaded because it executes one process at a time, and those processes cannot be interrupted until they are completed. For example, if you have three functions, JS will call those functions in order, although they may not execute or finish in order. Non-blocking simply means that one function will not block another from being processed, and this is because JS can be asynchronous. The asynchronicity of JavaScript exists because of the event loop; functions can be put on hold until they are ready to be processed while other functions are running.

There are three parts to the JavaScript event loop: (1) the stack, (2) the background threads, which could be Web APIs, and (3) the callback queue.

![](/images/unique-eucalyptus.png)
