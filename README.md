# CMOOR Website Template

This is a template for C-MOOR students to use to create their own portfolio websites.  It enables students to create a professional website which they can manage through the GitHub GUI (no need to install or render anything locally).

- Uses the [Hugo setup](https://github.com/marketplace/actions/hugo-setup) and [GitHub Pages](https://github.com/marketplace/actions/github-pages-action) actions to render a Hugo static site hosted with GitHub pages.
- Theme was forked from [lxndrblz/anatole](https://github.com/lxndrblz/anatole/) and modified by Katherine Cox for use by C-MOOR learners.

This template uses the Hugo static site generator, so students interested in further customization can consult the [Hugo documentation](https://gohugo.io/) and dive as deep as they like into web development :)

## Create GitHub Account

To use this template, you must have a GitHub account.  If you do not yet have an account, this video ([video](https://link.c-moor.org/video-join-github))([slides](
https://docs.google.com/presentation/d/1c4sb5CLpvKjgnTVIuNGYTSr8WWNgeSfC8TUGrxktu64/)) shows you how to create an account.  You can follow along with the video, or follow the steps below.

1. Open [github.com](https://github.com/) in a web browser and click “Sign up”.
1. Choose a username and password.  It is a good idea to choose a username that you would not mind sharing with future employers, as they may view your GitHub profile.  Some good options include your name, or some variation of it, or something to do with the type of projects you’re working on.
1. GitHub will ask you a few questions and then ask you to choose a plan.  Unless you’re sure you need something from the paid plans, select the free plan.  You can always upgrade later.
1. Check your email and click on the verification link.
1. Update your GitHub profile.
    - You can access your GitHub profile from the dropdown menu on the right side of the screen, by clicking on your user icon.
    - It’s generally a good idea to add a little bit of information about yourself, so people can see who you are and verify they’re connecting with the right person.  From your profile page, you can upload a picture and enter some basic information about yourself.  This information will be public, so enter whatever information you’d like others to be able to see.

## Setup Website

The first steps in creating your website are to:

1. Create your own copy of this template,
1. Configure the settings so it runs in your GitHub repository
1. Confirm that when you make edits to the content, your website updates to reflect those changes

This video ([video](https://link.c-moor.org/video-student-website-setup))([slides](
https://docs.google.com/presentation/d/13chl2zYU1NbWCZmD_daqiKcLoJZAtILMqjXgew3TR6c/)) shows you how to set up your own copy of the website with some example content.  You can follow along with the video, or follow the steps below.

### Copy Template

First, you need to create your own copy of the website template.

1. Find the [C-MOOR website template](https://github.com/C-MOOR/cmoor_website_template/) on GitHub.  Click the green “**Use this template**” button  to make your own copy.
    - This will open up a page for setting up your new project.  On GitHub, projects are called “repositories”.
1. Choose a name for your new repository.  This name will be part of the URL for your website, so it’s a good idea to make it short and descriptive.
    - You can change it later, but it’s a bit of a pain, so try to pick something that you will stick with.  You can also add a short description if you would like.
1. If you are using the free GitHub plan, you must set the repository as **Public** for your website to work.
1. Click the “**Create repository from template**” button.

You should now have your own copy of the website repository (source code) that you can edit as you please, though it won't yet look like a website.  

### Configure Settings

The next step is to set things up so that this collection of files gets turned turn into a proper website.

There are two important settings you need to set up to get your website working:

1. Set up GitHub pages, which will tell GitHub to treat your repository as a website (so it will display properly)
1. Update the URL so it points to your copy of the site, rather than the C-MOOR template

#### Setup GitHub pages

1. In your repository, click on the “Settings” tab in the upper right.
1. Within the “Settings” tab, select “Pages” from the left menu.  You may have to scroll down to find it.
1. Check the “Source” for your site.  The branch should be `gh-pages` and the folder should be `root`.
1. Click Save.

While you’re here, copy the URL for your site (shown in the blue box).  You’ll need it for the next step.

#### Update URL

1. From the main page of your repository, click on the folder named `config/_default`.
1. Click on the file named “config.toml”
1. Click on the pencil icon in the upper right to edit this file
1. Update the `baseURL` (first line of this file)
    - Right now, this has the URL for the C-MOOR template website.  Replace the URL with the address of your website (the address you copied from the GitHub Pages Settings).  This should have your GitHub username followed by the name of your repository.
    - Make sure to keep the quotation marks around the new URL.
1. Save your changes by scrolling down to the “Commit changes” box.  Enter a brief description of the change, then click “Commit changes”.

It will take little while for your website to update, but shouldn’t take more than a minute or so.  From the main page of your repository, you can see an orange dot indicating that GitHub is working.  You can click on this dot to see more information.  When GitHub is done, the orange dot will change to a green checkmark.  If it’s been more than a minute and it hasn’t changed, try refreshing the page.  Sometimes the status indicator doesn’t update right away.

#### View Site

To view your website, you can either enter your website’s URL directly in your browser, or you can click on the github-pages Environment in the bottom right.

- If you clicked on github-pages, you will end up on the Deployments page.  This has information about every time your website gets updated.  There should be a recent new deployment.  Click “View deployment” to see your website.

If you don’t see a website or the website looks weird, the first thing you should do is to try clearing your browser cache.  Your browser may have stored an old version of the website instead of getting the latest version.


### Confirm You Can Edit

## Personalize Website

## Troubleshooting

### Clear browser cache

Sometimes when you make edits to your website, you won't be able to see them (even though they were successful) because your browser has stored the old version of the website and is showing you that instead of getting the latest version.  You can fix this and get the latest version of your website by clearing your browser cache.

This will look a little different depending which browser you are using, but generally, you will

1. Open your browser preferences / settings
1. Look for an option labeled something like "**clear browsing data**".  It will probably be located under **Privacy or Security** settings.
1. Select the option labeled something like "clear cached files and images" or "clear cached web content".
    - You do not have to clear your cookies or browsing history.  It won’t cause problems with your website if you do, but you may get logged out of other sites if you clear your cookies, so it can be inconvenient.  You only *need* to clear the cached version of the website.
1. Click the button to clear the data
1. Once you’ve cleared your browser’s cached files, try revisitng your website and check if you see the updates you expect.



