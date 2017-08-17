---
layout: docs
title: Getting started with AppVeyor Enterprise
---

# Getting started with AppVeyor Enterprise

## Introduction

AppVeyor Enterprise is a downloadable version of popular hosted [AppVeyor CI](https://www.appveyor.com) service - Continuous Integration service for Windows developers.

You may choose AppVeyor Enterprise over hosted AppVeyor if:

* You need more powerful build worker VMs
* You need a custom build worker image with proprietary or 3rd-party licensed software
* You need scalable workers when you have different number of workers at different times and don't have to pay for concurrent jobs when you are not using them. Check [this blog post](http://www.mindkin.co.nz/blog/2017/8/8/scale-your-ci-by-the-minute) from our customer.

## The process

AppVeyor Enterprise deployment process consists of the following steps:

3. Configuring build workers cloud
4. Creating "master" image for build worker VMs
5. Configuring AppVeyor