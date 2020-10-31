# How to host a resume using github pages

# Purpose
To describe the practical steps of how to host and format a resume using Markdown, a markdown editor, github pages, jekyll

## Audience Profile
**Audience**: CS Student

**Venue**: README in Gihub Pages

**Additional purpose**: Introduce and demo principles of Andrew Etter's book Modern Technical Writing

**Desired reaction**: Encouraged, feeling that they can achieve the outcome and more

**Vocabulary**: Technical, jargon

**Tone**: Casual, yet cosice


## Basic fundamental documentation
### What is the product? why would anyone want it?
A resume is critical to computer science employment, every job applied for will require an accompanying resume that covers one's skills and abilities that are relevant to the position being applied for.

A simple, modern way to share and host a resume is through the use of a combination of technologies, namely:
1. Jekyll - A static site generator
2. Github Pages - Our webpage host
3. Markdown with editor? - The language in which we will write our resume in

##### Hosting a resume on github pages, using a static site generator such as Jekyll has the happy side effects of:

* Using a popular version control system (github)
    * making it easier for others to contribute if you so chose in your future website 
* Makes building and hosting a static website trivial
* A static site is fast, simple, portable and secure
    * nothing to install or hack and can be hosted with minimal resources
* Can be written in markdown languages (which is also simple, easy to learn and universal)
* lightweight markdown language, combined with Jekyll allows you to produce beatufiful looking static content with minimal effort
* It makes you look more "technical" to employers as you bring them to your github page
    * wherever you work, version control will be essential, this demonstrates some experience in that area


### How does this product fit into broader ecosystem, if at all? Does it have any dependencies
There are many options to host a website and just as many ways in which content and code can be written for those websites.
Authoring a webpage and hosting it can range in flexibility and complexity and one would be wise to match the tool to the task at hand. _Our_ task at hand is to create and host a resume. As such, we don't need to over-engineer a solution, we want a solution that is dead simple, easy to maintain and leaves us with easy ability expand on in the future or change technologies completely. With Github pages, in it's most simple form, all the dependecies are managed by Github. However, if you chose to expand, you can take the dependencies into your own hands (lots of room to grow).

#### Tools overview
> ##### Jekyll
>Is a Static site generator that Takes our lightweight markup language and turns it into a working website. Allowing you to apply styling, templates and configuration.

>##### github
>github is a distributed version control system(DVCS). It is popular and free. 
Github has a feature called github pages which allows one repository to act as a static website. DVCS allow for multiple people working on the same document, on or offline with versioning built in. For the purposes of this activity, it would allow you to keep a versioned history of your resume changes. It could potentially allow a colleage or friend to contribute to your resume, or provide feedback. If you don't have experience, it is an excellent tool to get your foot in the door. You will use some form of it for the rest of your career
>##### markdown
>lightweight markup language. Similar to html, is more focused on providing context to content but easy to learn, easy to read
>##### markdown editor
>Provides syntax highlighting, word completion, etx making it easier to read and write in markdown language. Often allowing for a live preview


### Where can I acquire this product? If there are multiple distribution packages, which should I choose and why?
#### github
One simply needs to create or use their existing github account, use a markdown editor of choice. 
>If you don't currently have a github account, it's an exellent time to [create one](www.github.com).

#### markdown editor
When just starting out learning it's important to keep it simple, therefore I recommend two options for markdown editors:
1. [VS Code](https://code.visualstudio.com) with associated markdown plugins
2. An online editor such as [Dillinger](https://dillinger.io)

If you are lacking confidence, Dilliger is the simplest way to get started and provides a live preview that will allow you learn quickly through experimentation.

Personally, I prefer VS Code, as it's a tool I am familiar with and is widely used in the computer science community.

#### Jekyll and markdown 
The ability to use Jekyll & markdown is build right into github pages! There is nothing we need to do, github takes care of the dirty work for us.



>![](woowoo.gif)
(Woo Woo! Told you it was simple!)
### How do I install the product? What are the basic configuration options if any?
Use VS and download some excellent plugins.
There are many different of flavors of markdown. Specifically we will be looking at and using [GitHub flavor markdown](https://github.github.com/gfm/)
The beautify of VS code if you are not already familiar with it, is that it is infininitely customizable through the use of extensions. One in particular I would recommend is [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles0)
## What does a simple, start to finish operation look like?


## Step by step
**prerequisite** :
* github account
* Basic knowledge of github version control
### Configure GitHub pages
In order for us to host a webpage, we need a place to host it. This can be done through the following steps: 
#### 1. Create a new \<accountname\>.github.io reposity
<img src="important.png" alt="Kitten" title="A cute kitten" width="25" /> The name of the repository is important. It **needs** to be prefixed with your Github account name: `<accountname>.github.io`

>![](host11.png)    
    
#### 2. Select a Jekyll style
Go to **Settings** for our newly created repository

>![](host3.png)    

scroll down to the *GitHub Pages* section.

Select '**Change theme**' 

>![](host32.png)

From here we are give the option to apply the specific theme of our chosing.
![](jekylltheme.gif)
Voila!
That is all we need for the basic configuration; I told you it was dead simple.
The address for your new webpage is `<accountname>.github.io`


Now when you go to resume you will view your resume in md

## How to get content onto github
### options:
* live / raw editor

    *   This is what we will be covering today. If you would like to use one of the tools listed below, I will assume you have enough experience to have that preference and that you know what you are doing
* terminal
* desktop client

### The basics
The basics would be to:

create a new file

edit that file through the edit menu

every change "save" to commit and be done with it

Note: it does take 
