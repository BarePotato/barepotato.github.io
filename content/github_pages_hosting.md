+++
title = "Website hosting with Github Pages and Zola"
date = 2022-03-24

[taxonomies]
categories = ["Github"]
+++

If you are anything like me, you have from time to time wanted to host a website somewhere for various reasons. The problem I have ran in to time and time again is, it's expensive, even more so when you aren't fully sure on what you want to do with it. So today I bring you a solution for low/no cost website hosting you may not be familiar with, and some instructions on how to get it all set up.

<!-- more -->

While the method described here is built around Zola as the static website generator, it is worth noting that Github does offer Jekyll built in, and this can also work with most(common) generators as well. You will need to modify the Github Action to match.

#### First steps

The first thing you will need, if you have not set one up yet, is an account on [Github](https://github.com/).

Once you have your account created, you should be staring at your landing page, from here we can go ahead and start setting up our repo for hosting. What we need to do now is create a repository, if you account is brand new there will be a large button that says this on the left, if this is not, there will be a button near the top left that simply says "new".

![](https://i.imgur.com/Oz3fYJa.png)![](https://i.imgur.com/nag5vbJ.png)

Next you will be presented with

- repo for pages

- clone locally

#### Publishing with Zola

- zola init

- .gitignore

- local vs remote generation

#### Generating with Github Actions

- secret token

- environment var

- creating action

#### The right branch

- the public branch

#### Your own domain
