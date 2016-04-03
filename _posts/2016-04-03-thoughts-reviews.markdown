---
layout: post
title:  "Thoughts on the Tutorial"
date:   2016-04-03 14:48:00 -0400
categories:
---
Well, if you're viewing this on the web, then my following of [this tutorial] (programminghistorian.github.io/ph-submissions/lessons/building-static-sites-with-jekyll-github-pages/) has been a success.

I chose this particular tutorial (and was particularly excited for it) because there were explicit instructions for Windows users, a group of which I am contentedly a part. Wherever else I have found mentions of Windows and Jekyll in the same breath, it sums up to:

1. Jekyll does not work on Windows, full stop.
2. Jekyll works on Windows, but you need a full grasp of arcaninma to make it so.

I found neither to be true, and in fact was probably easier and quicker than the instructions gave for the Mac (no 4-hour Xcode downloads for me). However as a disclaimer: I had both Ruby and chocolatey already installed, albeit separately. I think it's a good idea to let chocolatey handle the installation of Ruby for new users but for me Ruby actually came first.

From there, nearly everything was explained in a straight-forward and friendly manner. I ran into a bit of trouble with one of the bundler dependencies because MalwareBytes did NOT like one of its required files, but a temporary disable solved that issue. I appreciated being shown how to run the server locally because this was not something I had previously known how to do in any capacity, although I knew it was somehow possible. Seeing it in action was very helpful. I would have liked a little bit more of a primer on Markdown, but I understand that is technically outside the scope of the tutorial.

I ran into the biggest problem during the section on hosting on Github Pages. Whereas up until this point there wasn't a huge challenge in extrapolating from the Mac screenshots, the introduction of native apps for Windows 10 has changed the UI. GitHub Desktop for Windows is a pleasant experience to use but the functionality does not match the instructions. I was able to figure it out with a bit of trial and error but wound up creating a repo somewhere on my computer and then maybe deleting it? The biggest changes were:

1. "Create & Add Repository" is just "Create Repository", while "Add Repository" is a separate function designed to add an existing local repo.
2. It seemed necessary to "Commit to Master" once before continuing and adding a branch. I don't think this is strictly true, and I don't think this did anything bad, just mirrored the master to GitHub? Maybe?

While neither is particularly huge, they threw me a bit until I was able to accomplish the instructions by playing around. Regardless, it seems successful (and way quicker than editing html by hand every time I update something). More importantly I feel like this is easy enough to do on my own in the future and play around, which is a good feeling with which to come out of a tutorial.

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
