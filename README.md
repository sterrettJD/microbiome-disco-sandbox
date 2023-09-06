# Microbiome disco(very) sandbox

## TO DO:
### Getting comfy on Git
- Set up an ssh key for github [following this tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- Clone this git repository to your own computer (clone it in the file location that you want it to be located)
  - `git clone git@github.com:sterrettJD/microbiome-disco-sandbox.git`
- Move into the cloned repository (folder)
  - `cd microbiome-disco-sandbox`
- Look at the currently existing git branches
  - `git branch` 
- Create git branch to show that you're figuring out how to work on branches (name it something about adding your name to the readme
  - `git branch new_branch_name`
- Move yourself to the new branch, and make sure you're on the correct branch
  - `git checkout new_branch_name`
  - Running `git branch` should now show that you're on this new branch.
- Add your name to this file, right below this bullet point
  - John
  - NAME_2
  - NAME_3
  - You can do this from the command line by running `nano README.md`. This gets you working in a text editor. You can hit `Ctrl+X` to exit (make sure to hit `Y` to save your changes if you made any. It will prompt you for a file name. Just press `enter` to save with the current filename.
- Add and commit the changes you've made
  - `git add README.md`
  - `git commit -m "an informative message about the change you just made to this file"` (-m stands for message, and what you put in the quotes is a commit message to let people know what you changed)
- Push your changes to GitHub
  - `git push --set-upstream origin new_branch_name`
  - Normally, you can just run `git push`, but the first time you push a branch, you have to say `--set-upstream origin` to set the branch up.
- Create a pull request
  - On GitHub, open a pull request (see [these instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request))
  - Add some info about what changes you've made to the files.
  - Assign me to review your pull request, and I'll merge your branch into the main branch. Then your name will be part of the main branch!
- Create an Issue in the Issues tab on GitHub to let me know that you're impatiently waiting on me to review and accept your pull request.
- Congrats, you know all of GitHub! (or at least you know 99% of the things you'll use it for...)

### Watching Lectures
- Create a folder in this repository, named `yourname_disco_notes`.
  - You can use the command `mkdir` to do this from the command line
- For each lecture you watch, make a new branch.
- In that branch, jot down a few notes in a `.txt` (text) or `.md` (markdown) file. These notes could be something you find useful or cool or weird or counterintuitive. It's really more for you than me.
  - Markdown is what this file is written in, and it can be used to easily render some nice notes or instructions. [Here](https://www.markdownguide.org/basic-syntax/) is a guide to some basic syntax if you want to learn more about it. This is the same syntax used in `.Rmd` (R markdown) files.
- Once you're done, create a pull request. You can then request me to review it, and I'll make sure it looks good. If you want me to look particularly at a certain part of your notes (for example, if you found something confusing) you can add that to the pull request. You can also create issues with questions that you have.

**Dan Knights's Microbiome Discovery course can be found [here](youtube.com/watch?v=htbeJhtFAXw&list=PLOPiWVjg6aTzsA53N19YqJQeZpSCH9QPc).**
Lectures to watch:
1. Intro the the Microbiome
2. How microbiome data are generated
3. 16S Variable Regions
4. (4.5) UNIX Command Line (NO NEED TO WATCH 4 - QIIME, we use QIIME2 now, which makes this outdated)
5. Picking OTUs (some of this is outdate, but the concepts still stand)
6. Assigning Taxonomy
7. Alpha Diversity
8. Beta Diversity
9. UniFrac
10. Statistical testing (part 1)
11. Statistical testing (part 2)
12. Visualizing Microbiome Diversity, Ordination
19. Compositionality


