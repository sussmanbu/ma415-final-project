# MA[46]15 Final Project

For your final project, your team will be 

* finding data, 
* cleaning the data,
* performing an exploratory data analysis, 
* using statistical models and other techniques to draw conclusions, and
* communicating what you learned on website.

We'll be using the `blogdown` package to maintain our website. `blogdown` makes things easier but there are still some snags that you might run into. 
You will be working with your group to maintain the website, providing weekly blog posts and culminating with the deployment of pages detailing your analysis.

Here are the steps you'll need to take today.

0. Your team will share a Github repository for the final project. Accept this assignment and make sure to pick your team.
1. Choose a team leader. They will be in charge of the _Netlify_ account which is used to host the web site.

## Steps for your team leader

2. The team leader will go to [https://www.netlify.com/](https://www.netlify.com/). Click _Sign Up_ and use your Github account. Follow the steps to sign up.
3. Once you are set up and logged in, click _New site from Git_. Click _Github_ and authorize Netlify to access your account.
4. Find your teams repository using the _Search repos_ field and select it from the list.
5. You shouldn't have to adjust any options so click _Deploy Site_. Your site is now being deployed.
6. In the meantime, click _Site Settings_ and then _Change site name_ and use your team name (or something close) as the site name.
7. You should now be able to go back to _Overview_, see that "Your site is deployed", and click on the link to see your site. 


## Steps for Everyone

2. Clone your repository to your laptop and open the project file.
3. Install the blogdown package using `install.packages("blogdown")`. 
4. Run `blogdown::install_hugo()`. _Hugo_ / _blogdown_ are the tools for transforming your site from Markdown/RMarkdown into the structure of the website.
5. Run the command `blogdown::serve_site()`. If all goes well you will see a preview of the site in the RStudio Viewer.

## Steps for the Group

Everyone should now have their computer set up with blogdown, hugo and your team should have their netlify account up.
In turn do the following.

0. Press Pull in the Git tab to get the latest changes.
1. Open the `about.md` file and add your name, write a quick introduction, and include a link to your Github account page.
2. Commit the changes to `about.md` and Push your changes.
3. Check that your changes are showing up on netlify.
4. Make sure to wait until one team member is done before the next person starts again at 0.

Finally, the last person to update the about page will update the `config.toml` file.
The only change you need to make is to update the `title` to be your group name.
Again, commit and push your changes.

You should be all set and see the changes again on netlify.

Read through the posts on your website to learn a bit about how things work. Look at the structure of the `content` folder and compare it to the website structure.
