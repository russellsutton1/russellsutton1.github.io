# Minimal Mistakes remote theme starter

Originally forked from [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).
My version just configured the home page as a splash page and added my information.

## Basic Setup
- Create a github account. Make your username what you want your domain to be. For this example, I will use HostName.
- Install git-scm on your computer. You do not need the GUI.
- Fork this repository, or the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes) and rename it as "yourUsername.github.io". for example, HostName.github.io
- Create a folder on your computer, open it via command line and clone in your forked branch. 
- Edit the _config.yml file to change global site settings. index.html changes homepage settings. Webposts are found in the posts folder. Place images in the assets/images folder.
- If you forked my repo, there are some images in the root with names like favicon. Delete these and generate your own on [Favicon](https://favicon.io/). Extract the folder and copy the images to the root of the webpage.
- Refrence for text formatting [here](https://kramdown.gettalong.org/quickref.html).
- Visit yourUsername.github.io to see your work!

## Update files
If you have made changes to your site files, you need to push those changes on to the github.io servers. Do this by updating your repository on github!
- Navigate to your site's root folder.
- `git add --all`
- `git commit -m "some comment here"`
- `git push -u origin master`

All up to date! Your site should be ready in a few seconds.
There are more involved ways to develop jekyll sites, but this is the quickest and easiest for me, with no additional software required. (everyone should have git)

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.
- Homepage as splash page

[Documentation](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
