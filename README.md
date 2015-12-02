## Directions for Mr. Potato Head
![Imgur](http://i.imgur.com/Vy06FW3.gif)

1. find slackhappy on github.com and find the `Mr_Potato_Head` repository:
[`https://github.com/slackhappy/Mr_Potato_Head`](https://github.com/slackhappy/Mr_Potato_Head)


2. Fork their Repo
3. From the new Repo on your GitHub, copy the clone from https url to your clipboard.

In Cloud 9:

1. Create a new workspace using the "Clone from URL" option
2. Add your assigned body part to `potatohead.html`
3. Once you are complete with the html, do the following steps:
  - Check that you modified the correct file with `git status`
  - Make a commit with `git add` and `git commit`
  - Send this commit up to github
  - Make a pull request to tell the instructor to include your changes.



### Check that you modified the correct file
In Cloud 9 terminal:

```
 git status
```

You should see that potatohead.html is modified, like this:

```
	modified:   potatohead.html
```

### Make a commit 
Add your changes to the index, then commit them.  Don't use "Commit message" as your message!
Instead, say what you did, for example "added body part [your assigned body part]"

```
 git add .
 git commit -m "Commit message"  <<< but change the message!
```


### Send this commit up to github
Push your local commit up to github

```
 git push origin master
```

look at your github: `http://github.com/[myusername]/Mr_Potato_Head`  You should see the commit you just made!  If you click "Commits" you can see the all of the work that has been put into Mr Potato Head, and you are at the top!

### Make a pull request

From your GitHub create a "New Pull Request" (the green button) to send your changes to the instructor.  The instructor will merge all of the changes (everyone's body parts), and at the end hopefully we'll have a whole Mr. Potato Head.


