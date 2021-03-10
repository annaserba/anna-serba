---
title: >-
  JavaScript as a programming language is single threaded, asynchronous, and
  non-blocking
date: '2021-03-10'
categories: []
tags: []
excerpt: lorem-ipsum
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
---
### Javascript is a single threaded language

This means it has one call stack and one memory heap. As expected, it executes code in order and must finish executing a piece code before moving onto the next. It's synchronous, but at times that can be harmful. For example, if a function takes awhile to execute or has to wait on something, it freezes everything up in the meanwhile.

A good example of this happening is the window alert function. alert("Hello World")

You can't interact with the webpage at all until you hit OK and dismiss the alert. You're stuck.

### Javascript is a asynchronous language

So how do we get asynchronous code with Javascript then?

Well, we can thank the Javascript engine (V8, Spidermonkey, JavaScriptCore, etc...) for that, which has Web API that handle these tasks in the background. The call stack recognizes functions of the Web API and hands them off to be handled by the browser. Once those tasks are finished by the browser, they return and are pushed onto the stack as a callback.

Open your console and type window then press enter. You'll see most everything the Web API has to offer. This includes things like ajax calls, event listeners, the fetch API, and setTimeout. Javascript uses low level programming languages like C++ to perform these behind the scenes.

### Javascript is a non-blocking language

Non-blocking simply means that one function will not block another from being processed, and this is because JS can be asynchronous.
