---
title: "My First Pull Request on a FOSS project"
date: 2024-06-23T06:22:39+05:30
draft: false
---
## Updating the site 
This website was built on a earlier version of hugo and earlier version of PaperMod theme. 
It didn't work on the latest version of hugo for sometime now.

## The problem in the latest versions
I tried building the site with latest hugo. It worked without major issues. It did build but there was no output. There were some errors in the latest version of the theme.
 
I solved it in my local computer and pushed it to GitHub. But it didn't work in Netlify during the build. Since I configured git to download the submodule direclty from it's repository.

First, I tried to create a fork of the theme and then use it directly in Netlify. I was not very successful with this. 

## My first PR
In that process, I found that I could actually solve this issue also for others. So, I created a pull request to PaperMod. I will have to check for updates on this later. Whether I have to add any more details.

## How I solved it at last
At last, I solved the issue by removing the git submodule of the theme. And just adding the theme directly in the repository. And made the change direclty there.
I also created a new dev branch to test things out. I have also enabled a preview build for dev branch in Netlify. This will enable 

