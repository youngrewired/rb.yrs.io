![](http://i.imgur.com/EjqIvTb.png)

# Ruby's Threads

**This is your chance to do something awesome with our mascot - Ruby.**

## Getting Started

You will only require [Git](http://git-scm.com/downloads) to contribute to this project. 

### Getting started with Git

Download [Git](http://git-scm.com/downloads) and install it. Then open up your Terminal and type in the following two commands to configure Git:

    $ git config --global user.name "firstName lastName"

    $ git config --global user.email your@emailaddress.com

### Forking this project

Forking allows you to edit the site away from the live-site. 

Go to the top-right of this page and locate these three buttons:

![](http://i.imgur.com/pVixcO1.png)

Click the **Fork** button

### Downloading this project

You can download this project from the Terminal once you've configured Git. The command `cd` allows you to move between folders. Navigate to the folder you wish to download this project to, and then type in the following command:

`$ git clone https://github.com/YOUR-GITHUB-USERNAME/rubys-threads.git`

To navigate inside the folder, then type:

`$ cd rubys-threads/`

### Branches in Git 

Git has a feature called 'branches', which allow you to store various parts of your project separately. The website, and all files associated to it can be found on the `gh-pages` branch. In order to switch to the correct branch, type the following command: 

`$ git checkout gh-pages`

## Making your changes

Our graphic for Ruby is a SVG file, and you can find it in `images/ruby.svg`. If you are not making a vector image, and instead a bitmap (.jpg, .png or .gif), then optimum size is 218x218. 

 1. Put your ruby images inside the `images` folder. 
 2. Locate the `<ul>`tag in `index.html`, at around line 32.
 3. Insert the following code snippet directly below the `<ul>` tag:
 
    <li>
          <img src="images/YOUR-RUBY.PNG">
         <div class="meta">
           <h1 class="name">YOUR-RUBYS-NAME</h1>
           <a class="twitter" href="http://twitter.com/YOUR-TWITTER-HANDLE">@YOUR-TWITTER-HANDLE</a>
         </div>
    </li>
  
 4. Save the file and check that the `index.html` file looks okay in your browser. 
 5. Go to your terminal, ensure you are in the rubys-threads directory and type the following commands
	 
    $ git add --all
    $ git commit -m "Added YOUR-RUBYS-NAME"
    $ git push origin gh-pages

## Merging your changes back to the main site

 1. Navigate to https://github.com/YOUR-GITHUB-USERNAME/rubys-threads
 2. Click on 'Pull Requests' on the right side of the screen
 3. Click on the green 'New Pull Request' button
 4. Click 'Create Pull Request'
 5. Write a comment describing your change and create the request

Once the commit is verified by the Young Rewired State team, they will be merged in and be visible on the site. 