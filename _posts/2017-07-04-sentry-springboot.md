---
layout: post
title: Sentry - Spring Boot
categories: []
tags: [java, log4j]
description: 
comments: true
---

You must have some programming experience if you are reading this. So recalling that experience, you will remember one common pattern in your development process, which is inserting debug statements in your code in order to remain informed of where current execution is.

For example in C++ you might have used printf or cout, similarly alert in JavaScript, echo in PHP, trace in ActionScript and similar output statements in other languages.

So what do you use for printing out debug information in Java? … System.out.println(“my message”);

What, then what is Log4j? … You can say Log4j is improved version of System.out.println.

Logging is the process of writing log messages during the execution of a program to a central place. This logging allows you to report and persist error and warning messages as well as info messages so that the messages can later be retrieved and analyzed.

The object which performs the logging in applications is typically just called Logger.

By using these you can log the debugging messages and check what's happening in your application. But to do this I should check the log files very often and check if any errors have occured. And I am bored of this process.

How about a person to alert you if any error occured? Hmmm that is cool.

* Stop hoping your users will report errors.
* Know when things break - Get notifications via email, sms, or chat when new errors occur or old ones resurface.
* See the impact of each release - If things break, you’ll know where errors are happening, how often they happen, and who is affected.
* Quickly diagnose and fix issues - Know what’s breaking and how to reproduce the problem, without waiting for user reports.

Who will provide this?

And the answer is 
-----------Sentry-----------


Below is the link for an example to achieve this

<a href="https://shreyasrh9.github.io/spring-boot-sentry/">Sentry - Springboot</a>

Reference :

https://sentry.io/welcome/
