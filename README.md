# the-modern-web-via-git-and-vercel
Fourth installment of the modern web development series. Describes how to deploy our website using git and vercel.

## Where we left off
In the previous lessons, we learned how to create a website using Vue.js and Nuxt. Now that we have created this site, it's time to deploy it so that it can be accessed by anyone. We will be doing this by setting up a github repository and using a service called Vercel which allows us to deploy simple websites for free!

Link to our masterpiece: 

https://stackblitz.com/edit/nuxt-starter-5gyfh8?file=package.json

So far our site has existed entirely within Stackblitz, which is not exactly ideal if we want people in the real world to use it. In this lesson we will start by moving the code for our website to a GitHub repository. 

## What is GitHub?
GitHub is a platform which allows enables programmers to work as a team using version control. Because of how team-oriented the site is, there is likely some form version control being used at any company involved with software development. As a Kent State student you may be familiar with subversion, which is somewhat similar in nature to GitHub.

The idea is that a timeline of a project's development can be established by tracking what changes are made to it over time. Github will track who, what, when, and why (assuming proper documentation is uploaded) any given change was made to a project's code.  

## What is Vercel?
Vercel is a tool that allows us to quickly deploy a website from our github repository without the need for an in-house data center, or a subscription to some cloud service such as AWS or Digital Ocean. It takes the pain out of server management and is perfect for a broke college student who experiences enough pain already. 

In addition to just getting our website online, Vercel lets you do really cool things like generate analytics about your site, and work collaboratively with a team. These features are outside the scope of this lesson, but it's worth mentioning that the possibilities are virtually endless. 

## Downloading the Project
Start by opening the site in Stackblitz link provided above. This should load up the project we were working on previously. 

Once the project is loaded, click the download button in the project pane on the left of the page (the one that looks like a cloud with an arrow). This will download a zip folder to your computer containing all of the code that we will be uploading to GitHub. Once this f is downloaded, unzip it and put it somewhere cozy. 

## Creating a GitHub Repository
If you haven't already, you're going to want to create a GitHub account. Assuming you are viewing this file on GitHub, you can get started by clicking the "Sign Up" button in the upper right corner of this page. 

Once you've created an account, you can navigate to your profile by clicking your profile photo in the upper right corner and selecting "Your profile". To create a new repository, click the "Repositories" tab and then click on "New".

This will take you to a page with all of the options to set up your new repository. According to the Oxford dictionary, a repository is "a place, building, or receptacle where things are or may be stored." In this case, the repository is where we are going to store the source code for our website, and we will eventually give vercel access to this repository so that it can run the code we upload to it. 

You'll start by giving your repository a name and an optional description. For example, you could use the name `my-website` and the description `This is my website :3`. 

Once you've found an available name you have a few more options. The first is to select whether the repository will be public or private. Public repositories are best for code that you intend to share with the world. This could be a cool open source project, or a HacKSU lesson. Private repositories are only accessible to users who are given access to a repository by the owner. Sort of like locking a drawer on a desk and only giving the key to those you trust. Except your drawer has a virtual petting zoo inside of it instead of whatever people put in locked drawers.

Next you are tasked with the decision of whether or not to add a README to your project. If selected, GitHub will automatically put a file called `README.md` in your repository, and display it's contents on your repositories page. In fact, this lesson is a README file that was created using this checkbox. This file is often used to display information about the project such as setup instructions. Writing a README is outside the scope of this project, but is a super cool and awesome skill to develop!

The next two dropdown menus offer the option to add a .gitignore file and to choose a license. The .gitignore file serves as a list of files and file types that should probably not be publicly available on the internet. Examples include, but are not limited to: API keys, configuration files, and anything that is absolutely gigantic (databases etc). Choosing a license allows you to put your project under a number of open source licenses. More information about open source licenses can be found here: https://opensource.org/licenses/

For this project, we will be ignoring both of the dropdown boxes. 

Once you've clicked the button to create your repository, you'll be presented with a page full of intimidating instructions to set up your repository locally using the command line. If you are a Mac user, you may have done something similar with subversion in the past. In this case, we should be able to upload the files from our folder using the link under Quick Setup which says "uploading an existing file". 

After clicking this link, you will be redirected to a page where you can drag and drop the files from the folder we downloaded earlier. Once these files have finished uploading you can click "commit changes" to add them to yur repository. 

We 
