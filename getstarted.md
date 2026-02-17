<div class="gs-section-01" markdown="1">

### 1. Fork this project

Click on the __*Fork*__ button at the top right corner of this page. Forking means that you're copying this entire project and all its files into your account. Do not click on the __*Create fork*__ button on the next page yet.

</div>

<style>

.gs-section-01 h3 { 
     color: red }

.gs-section-01 p {
     font-size: 30px;
}

</style>

<div class="gs-section-01" markdown="1">

### 2. Rename the repository to `YOURUSERNAME.github.io`

You'll see the word "repository" used a lot in GitHub - it simply means "project". Under __*Repository name*__ you should see the name `beautiful-jekyll`, this is where you need to rename your project to `YOURUSERNAME.github.io` (replace `YOURUSERNAME` with your GitHub user name). It's important to use this exact name so that GitHub will recognize it and automatically create a website for this project.   

> Tip: If you want to use a different URL for your website, check out the [FAQ](https://beautifuljekyll.com/faq/#custom-domain)

</div>

<style>

.gs-section-02 h3 { 
     color: blue }

.gs-section-02 p {
     font-size: 45px;
}

</style>

<div class="gs-section-01" markdown="1">
 
### 3. Customize your website settings

Edit the `_config.yml` file to change any settings you want. To edit the file, first click on it to view the file, and on the next page click on the pencil icon to edit it (watch the video tutorial above if you're confused).  The settings in the file are self-explanatory and there are comments inside the file to help you understand what each setting does. Any line that begins with a hashtag (`#`) is a comment, and the other lines are actual settings. After changing the settings, click the green __*Commit changes*__ button to save these edits.

> Note: In the video above, only one setting in the `_config.yml` file is edited, but you should go through the rest of the settings as well.

</div>

<style>

.gs-section-03 h3 { 
     color: orange }

.gs-section-03 p {
     font-size: 35px;
}

</style>

### 4. Congratulations! You have a website!

If you named your project correctly and made an edit to the config file, your website should be ready in a minute or two at `https://YOURUSERNAME.github.io`. Every time you make a change to any file, your website will get rebuilt and should be updated in about a minute or so. Your website will be initialized with several sample blog posts and a couple other pages.

# Add your own content

To add pages to your site, you can either write a markdown file (`.md`) or you can write an HTML file. It's much easier to write markdown than HTML, so that's the recommended approach ([here's a great tutorial](https://markdowntutorial.com/) if you need to learn markdown in 5 minutes).

To see an example of a markdown file, click on any file that ends in `.md`, for example [`aboutme.md`](./aboutme.md). On that page you can see some nicely formatted text (there's a word in bold, a link, a few bullet points), and if you click on the pencil icon to edit the file, you'll see the markdown code that generated the pretty text. Very easy! 

In contrast, look at [`tags.html`](./tags.html). That's how your write HTML - not as pretty. So stick with markdown if you don't know HTML.

Any markdown or HTML file that you create will be available on your website under `https://<yourusername>.github.io/<pagename>`. For example, if you create a file `about.md` (or `about.html`) then it'll exist at `https://<yourusername>.github.io/about`.

Files you create inside the [`_posts`](./_posts) directory will be treated as blog entries. You can look at the existing files there to get an idea of how to write blog posts. Note the format of the blog post files - they must follow the naming convention of `YEAR-MONTH-DAY-title.md`. After you successfully add your own post, you can delete the existing files inside [`_posts`](./_posts) to remove the sample posts, as those are just demo posts to help you learn.
