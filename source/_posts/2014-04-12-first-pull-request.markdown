---
layout: post
title: "First pull request"
date: 2014-04-12 16:57:46 +0200
comments: true
categories: ['opensource', 'spring boot']
---

Well, it isn't really my first pull request.  I've done pull request on friend's projects on GitHub or even on GitLab working in corporate environment.  This was really my first pull request on an open source project.  Ever since I saw Zack Holman's [presentation](http://zachholman.com/talk/product-is-the-byproduct/) at Mix-It 2013 I knew I had to be a part of it.  And there I am contributing to Pivotal's [Spring Boot](http://projects.spring.io/spring-boot/) project.

I made this change because I was using Spring Boot for a corporate project.  The bootstrapping made it really easy to build, the convention over configuration aspect had the advantage of reducing the amount of overhead code to get the app up and running.  But maybe the convention wasn't fully what I needed.  Spring Boot 1.0.0.RELEASE had support for ActiveMQ, which worked great, but in my company, where the queuing system was relatively new, they decided to secure it by adding credentials.  Unfortunatly, Spring Boot did not provide out-of-the-box support for credentials.

Adding this functionality was terribly easy (35 lines added and 4 removed).  I had modified the Spring Boot project I had cloned and builded it and deployed it as SNAPSHOT on my local repository.  Everything worked on first try.  As this is a common feature I guessed I wouldn't be the first and last to want it.  I commited this feature on a new branch on my GitHub fork and made a [pull request](https://github.com/spring-projects/spring-boot/pull/618).

The Spring Boot team was really quick as to check the pull request and accepted it after my signing Pivotal's legal papers.  It got integrated into Spring Boot 1.0.1.RELEASE.

This may seem as not a big deal to many readers, but I'm sure you had the same excitement on your first major pull request.

I am now a part of the open source community.