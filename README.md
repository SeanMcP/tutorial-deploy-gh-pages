# Tutorial: How to deploy to GitHub Pages

Tutorial to deploy a static site to GitHub Pages

## Step 1: Create/go to a repo

GitHub Pages is a great hosting option for static web pages. Create a repo with some HTML, CSS, and JS or navigate to another that you wish to deploy. For the purpose of this tutorial, I'm going to use this repo: `seanmcp/tutorial-deploy-gh-pages`.

## Step 2: Go to "Settings"

Click on "Settings" to the far-right of your repo's tab menu.

![Click "Settings"](/images/go-to-settings.png)

Then scroll down to the "GitHub Pages" section.
    
![GitHub Pages settings](/images/find-gh-pages.png)

## Step 3: Select your source

GitHub Pages can be deployed from any branch on your repo. For the purpose of this tutorial, we'll be using the `master` branch, but it is also common to use a dedicated `gh-pages` branch.

Select your branch you want to deploy from the dropdown.

![Select the branch you want to deploy](/images/select-branch.png)

Finally, click "Save".

## Step 4: 🎉 Celebrate!

That's it; you're done! You should see a confirmation banner at the top of the screen.

![Confirmation that the branch has been set](/images/confirmation.png)

Your repo should be up and running at `https://<username>.github.io/<repo>`.

In our case, [https://seanmcp.github.io/tutorial-deploy-gh-pages](https://seanmcp.github.io/tutorial-deploy-gh-pages).
