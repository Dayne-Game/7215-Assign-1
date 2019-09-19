# Content Management Systems

# CMS Comparison

## Wordpress

Wordpress was born from the desire for an elegant, well-architectured personal publishing system

# CMS Installation

## Wordpress

### Pre-Setup

Installing Wordpress is quite straight forward and pretty easy to do if you have a docker installed. Docker allows you to pull Wordpress straight down onto your local machine and start developing in no time. All of the downloading and setup is all done through the terminal so make sure that is open.

To Install Docker if you haven't got it installed Click <a href="https://docs.docker.com/docker-for-windows/install/">Here</a>

If you are on Windows you should install Git Bash, its by far the best and easiest Terminal to use on Windows: To download Git Bash Click <a href="https://git-scm.com/downloads">Here</a>

**_Note:_** _Keep the same terminal open at all times to make installation easier_

I'll be using the term **Terminal** this is to either reference Git Bash for Windows or Terminal for macOS.

### Installation Process

**_Note:_** _This process is far easier on a Apple Computer running macOS. Its actually better if you through your Windows PC away and buy a Mac!_

Go to https://github.com/Dayne-Game/Wordpress-Demo and fork the respository.

Once you have forked the repository copy the url (of your forked repository, not the link above), open up your terminal navigate to your desktop using the command `cd ~/Desktop` and type in the command `git clone <repository url>` and wait for the repo to be cloned onto your desktop.

Once the repo is cloned navigate into the folder uisng the same terminal. To do so type the command: `cd Wordpress-Demo`

Once you're inside the **Wordpress-Demo** folder via terminal type in the command `docker-compose up -d` now you have wordpress installed and running! Go to https://localhost:8080 and create your account and get started with wordpress!

### Acquiring and Installing a Theme

Here is a Video showing how to acquir and install a theme in Wordpress!

<video width="650" height="340" controls>
  <source src="Theme.mp4" type="video/mp4">
</video>

To change the theme of your Wordpress website you will need to be in the admin section of the website.

**Standard Steps of Changing your Theme**

When you are in the admin side (Dashboard) of your Wordpress website, you want to click on the word **Appearance** on the left sidebar at about halfway down from the top.

When you click on **Appearance** a new page will load (show) that by default will display the themes section, where you can change your theme.

<img src="Theme-Example.png" alt="Themes Section Example">

In this Theme's Section you can add new themes, which allows you to search through Wordpress database for free and or paid themes that you can build your site on.

To change your current theme you just need to section the one you want to change to and click **Activate** its that easy!

## Adding / Installing a Plug-in

Installing a plugin is pretty much the same process that you do fro installing a theme in Wordpress.
