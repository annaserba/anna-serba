---
title: Event loop
date: '2021-03-10'
categories: []
tags:
  - src/data/tags/tag-su3sve3lk.json
  - src/data/tags/tag-klbeuh8dp.json
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

Some basics to remember in order to understand how the event loop works are how a stack and queue work. A stack, like a stack of pancakes, follow the order of LIFO: last in, first out. When you pile on the pancakes, the first one you can eat has to be the pancake on the top of the stack, the last one that was put on the stack. A queue follows another order, FIFO: first in, first out. Like a line at a movie theater, the first person on line is the first person to get a ticket.


The call stack is where functions that have been called are placed until they complete and return something. If you are familiar with recursion, you know how the call stack works. If a function is a callback in a setTimeout, the setTimeout starts a timer thread in the browser, a separate thread from the JS V8 engine runtime thread. Even if the timer is set to zero, setTimeout timer will start a thread with a timer in the browser. The timer will run and once it is finished it gets placed on the callback queue. Once the call stack is empty, the function in the setTimeout gets placed on the call stack.
