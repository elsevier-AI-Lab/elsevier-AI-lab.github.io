# website-dev
Repository holding the code that generates our static HTML website.


## Updating the website

You've made some changes in the markdown files that represent our static web pages. Once you are done, you'd like to see your changes appear on the official discovery lab website.

In order to do that follow the steps below:

- Make sure you have installed Jekyll (see instructions at: https://jekyllrb.com/ )
- From within the website-dev root fire the command : `bundle exec jekyll serve`
- This will generate the website locally so you can check your updates
- Once you are done, navigate to the `_site` folder.
- `git add -u .`
- `git commit -m "message describing your updates"`
- `git push origin main`

After following these steps, your updates should appear on the official website shortly.
