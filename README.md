# GitGood-GitPush
Here we'll walk through a simple example of pushing to GitHub!

## Step 1: Forking this repository!

We'll need to fork this repository so we can add changes to it!

If you need to, you can follow the instructions in this [repo](https://github.com/chris-alexiuk/GitGood-Forking), or check out [this video](https://youtu.be/aV7Y6cLD9wQ) if you prefer a video walkthrough!

## Step 2: Making some changes, and getting ready to push!

We'll need to add a file, or make changes to a file (I'd suggest adding your name to the README.md, or something similar!)

I'd recommend these steps: 

  1. Open the README.md in your favourite text editor - I'd use `nano README.md` if you're not sure!
  2. Add your name to the bottom of the README.md under the "## Your Names Here" heading.
  3. Use the commands `CTRL+O`, press enter/return to save the file with the same name, and then `CTRL+X` to exit!
  4. After that, you're good to `git add README.md` to stage the changes you just made!
  5. Once you've staged the changes (you can use `git status` and verify the README.md appears in green text to confirm the changes are staged) you can commit them using the command `git commit -m "Adding my name to the README.md!"
  6. Now we're ready to move on to pushing those changes!
  
## Step 3: Push! Push! Push!

All that is left to do is push those changes - you can do this by following these steps:

  1. Since we cloned our forked repository, it'll already have a reference to our remote fork - which will be called `origin`. Thanks to how clever the `git` tool is, all we need to do is: `git push` and our changes will appear on GitHub.com on our fork! That's really it!
  2. If you prefer to be specific (and it's never a bad thing to want to be!) you could also use the full command: `git push origin main`!
  
  
## Conclusion :tada:

That's it! You're done! You just forked a repo, made a change, and then pushed it to GitHub.com!

# Sweet Soundtrack

[Push It to the Limit](https://www.youtube.com/watch?v=Olgn9sXNdl0&ab_channel=UniversalPictures)
