---
layout: default
---

## About

This Mac application is meant for using your GitHub Page as a file
server. It
behaves identically to [Dockdrop](http://dockdropx.com/) in that all you
do is
drag a file to the GitDrop icon. Gitdrop will then add your file into
your
local repository and push it up to the remote repo, putting the link to
the
file in your clipboard. This will allow users to quickly share files
using a
GitHub Pages repository.

## Configuring the App

To get the most out of Gitdrop you should have a special GitHub Page
meant for
hosting files you need to share. If you don't already have one that will
work,
here's how you can create one:

1. Create a [new GitHub repository](https://github.com/new). Call it
   something like "Share"
2. Create a GitHub Page for it by following the instructions
   [here](http://help.github.com/pages/)
3. Clone the repo onto your local machine

Now to actually configure the app:

1. Paste the GitDrop.app file into your Applications directory and
   drag it to your dock.
2. Right click on the app in Finder and click "Show Package Contents"
3. Go to Contents/Resources and edit the file "script" in your
   favorite text editor.
4. Edit the DIR and URL variables to the appropriate values (see
   below) and save
   
{% highlight javascript %}
DIR="path/to/your/local/repo"
URL="yourgithubpage.com"
{% endhighlight %}

You now have a quick and easy way to share files by merely dragging a
file to
GitDrop and pasting the URL pointing to your GitHub Page.

That's it! You're ready to start using GitDrop. Tell your friends!

## Contact

* Email: [tabenziger@gmail.com](mailto:tabenziger@gmail.com)
* Twitter: [@tybenz](https://twitter.com/#!/tybenz)
