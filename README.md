## Directions for Mr. Potato Head
![Imgur](http://i.imgur.com/Vy06FW3.gif)

1. find [instructor] on github.com and find the `Mr_Potato_Head` repository:

2. Fork the Repo


In Cloud 9:

1. Create a new workspace for this repository using the clone from Git URL from your repository.
2. Add your assigned body part to `potatohead.html`. Body parts can be found in the `assets` folder
3. Add the necessary CSS to your body part in the `potato.css` file.
3. Once you are complete with the html, do the following steps:


### Check that you modified the correct file
In Cloud 9 terminal:

```
 git status
```

You should see that potatohead.html and potato.css are modified, like this:

```
	modified:   potatohead.html
  modified:   potato.css
```

### Make a commit
Stage your changes in the index with `git add .`, then commit them.  The string after `-m` in `git commit` is the commit message. Don't use "Commit message" as your message!
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

look at your github: You should see the commit you just made!  If you click "Commits" you can see the all of the work that has been put into Mr Potato Head, and you are at the top!

### Make a pull request

From your GitHub create a "New Pull Request" (the green button) to send your changes to the instructor.  The instructor will merge all of the changes (everyone's body parts), and at the end hopefully we'll have a whole Mr. Potato Head.

### Bonus

1. Try to create a button the sits below Mr. Potato Head that when it is clicked your body part will show or hide.
