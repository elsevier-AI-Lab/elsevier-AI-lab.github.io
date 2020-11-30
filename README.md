# website-dev
Repository holding the code that generates our static HTML website.


## Updating the website

You've made some changes in the markdown files that represent our static web pages. Once you are done, you'd like to see your changes appear on the official discovery lab website.

In order to do that follow the steps below:

1. Make sure you have installed Jekyll (see instructions at: https://jekyllrb.com/ )
2. Make sure you have the current static website cloned and up to date in `_site`
    * If this is the first time you edit the page:
        * In the root directory, make the directory `_site`.
        * In `_site`, clone the repository for the webpage ( `git clone git@github.com:elsevier-AI-Lab/elsevier-AI-lab.github.io.git .` ) 
    * Othewise
        * Run `git pull` to update your local version to what is on the current homepage.
3. From within the website-dev root fire the command : `bundle exec jekyll build`
    * This will generate the website locally so you can check your updates
4. Navigate to the `_site` folder. And add, commit, and push the changes to the repository
- `git add -u .`
- `git commit -m "message describing your updates"`
- `git push origin main`

5. Do not forget to also push the changes you made to the source repository.

After following these steps, your updates should appear on the official website shortly.
