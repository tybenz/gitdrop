##GitDrop
Project Page [here](http://tylerbenziger.github.com/gitdrop)

### About

This Mac application is meant for using your GitHub Page as a file server. 
It behaves identically to [Dockdrop](http://dockdropx.com/) in that all you do is drag a file to the GitDrop icon. 
Gitdrop will then add your file into your local repository and push it up to the remote repo,
putting the link to the file in your clipboard. 


### Configuring the App
When you download the zip, you will get a .app file. Paste this file into your Applications directory and drag it to your dock. 
To configure the app, right click on the app in Finder and click \"Show Package Contents\". 
Then go to Contents/Resources and edit the file \"script\" in your favorite text editor. Edit the DIR and URL variables to the appropriate values and save.

```
$ DIR="/path/to/your/repo"
$ URL="yourdomain.com"
```

That's it! You're ready to start using GitDrop. Tell your friends!

### Contact
- Email: [tbenzige@adobe.com](mailto:tbenzige@adobe.com)
- Twitter: [@tybenz](https://twitter.com/#!/tybenz)