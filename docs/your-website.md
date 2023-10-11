---
layout: default
title: Your website
nav_order: 4
permalink: /docs/your-website
---

# GitHub Pages and Markdown

{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## why build a website?
You
- own the content
- can have full control over its functions and design
- can disseminate a URL to a specific page in different corners of the Web e.g. on social media platforms, forums, emails, business cards, etc.
- can give people an overview of your past and current work and provide an outlook e.g. to help seek collaborators
- can redesign it whenever you feel it needs a new feel (you can create a different feel for each page if you want)
- can add website skills to your CV e.g. web design, web hosting and programming
- ,with these new skills, can build websites for others (for money)

### types of websites
1. project website  
   - 1.1 short/simple project website e.g. 
  https://khofstadter.com/sonic-art  
  https://endaksi1.github.io/sonicart/

   - 1.2 complex/longer project website e.g  
  https://bcmi.khofstadter.com/

  <br>
  
2. portfolio website
   - can feature multiple projects/themes
   - a bit like a CV e.g.  
  https://khofstadter.com/ and https://storylabresearch.com/

<br>

## website builders
There are two main types:
1. [static site generators](https://staticsitegenerators.net/) (SSG) e.g. [Jekyll](https://jekyllrb.com/) which is used with GitHub Pages when turning Markdown files into a website
2. [web content management systems](https://en.wikipedia.org/wiki/Web_content_management_system) (WCMS) e.g. [Wordpress](https://wordpress.org/), Wix, Squarespace and [other website builders](https://websitebuilder.org.uk/) with which it is easier to create more dynamic websites
- SSGs are usually free while WCMSs often have a monthly subscription fee
- both types have free and paid themes e.g. [here](https://jekyllthemes.io/) and [here](https://duckduckgo.com/?q=wordpress+themes&t=brave&ia=web)
- both types can use plugins to do a specific function. SSG plugins e.g. [Jekyll plugins](http://www.jekyll-plugins.com/) are usually free, while plugins for WCMSs can vary e.g. while many of them are free, some can be expensive
- there are many more plugins for WCMSs than for SSGs (because more people use WCMSs than SSGs)
- SSGs, in general, need more textual programming skills while WCMSs, in general, are more visual and therefore need less textual programming skills

<br>

### textual vs visual programming examples

SuperCollider (audio):

![](assets/img/textual-vs-visual-programming-supercollider.png)

<!-- todo: change image to Markdown (left) and HTML (right) -->

Max (audio):

![](assets/img/textual-vs-visual-programming-max.png)

WordPress backend (WCMS):

![](assets/img/textual-vs-visual-programming-wordpress-backend.png)

WordPress frontend (WCMS):

![](assets/img/textual-vs-visual-programming-wordpress-frontend.png)

<br>

### some free WCMSs
- https://youtu.be/myM1H_jAyzI

<br>

### Wordpress.com vs WordPress.org
- WordPress is an open-source WCMS available at [WordPress.org](WordPress.org)
- the website [WordPress.com](wordpress.com) is owned by a hosting company called Automattic, where you can set up the WordPress WCMS (not too technical)
- you can set up this WCMS with different hosting providers as well e.g. [TSOHost](https://www.tsohost.com/) (which can be more technical, but maybe more economic e.g. if you own many websites). You could [compare them](https://duckduckgo.com/?q=best+hosting+providers&t=brave&ia=web). 
- more info [here](https://wordpress.org/support/article/wordpress-vs-wordpress-com/)

<br>

### custom domain
- with free websites, you often get a long domain name containing the name of the company you set your website up with e.g.
  - https://krisztian-hofstadter-tedor.github.io/CS220-AU-navigating-the-digital-world/
  - https://mywebsite.wordpress.com
- if you want to have your own ‘custom domain’, register it with a domain registrar (which costs around £10/year)
  - the https://github.com/krisztian-hofstadter-tedor/khofstadter.com repository is linked to the custom domain [https://khofstadter.com/](https://khofstadter.com) which I registered with [NameCheap](https://www.namecheap.com/). GitHub's GitHub Pages fuction turnes my Markdown, HTML and CSS files in this repository into a static website that costs around £10/year to run.
- I built the website [https://storylabresearch.com/](https://storylabresearch.com/) using WordPress, and are  hosing it with TSOHost, where its custom domain is registered as well (costs around £400/year to run; this cost includes a faster VPN server and an additinal extra security packages)
- websites built with other WCMSs would also [cost above £100/year](https://www.websitebuilderexpert.com/website-builders/comparisons/) to run

<br>

### my tedor.info to khofstadter.com
Using the Wayback Machine on [archive.org](https://archive.org/):
- [2013](https://web.archive.org/web/20130624224549/http://tedor.info/) with [Indexhibit](https://indexhibit.org/)
- [2018](https://web.archive.org/web/20181130174711/http://www.tedor.info/) with WordPress
- [2021](https://khofstadter.com/) with Jekyll and GithHub Pages

<br>

### Brief WordPress demo
- https://storylabresearch.com/admin (I need to log in)

<br>

### GitHub Pages
- [intro video](https://youtu.be/2MsN8gpT6jY)
- [documentation](https://docs.github.com/en/pages)

<br>

## SSG vs WCMS
- a static site generator pre-creates the webpages e.g. the Markdown files are converted into HTML files (instead of creating the page when someone visits a WordPress site)
- the data with the static site is stored in the website files with the WCMS the user data e.g. blog article, images, etc. are stored in a separate database file. It looks like [this](https://duckduckgo.com/?q=wordpress+data+base+file&t=brave&iax=images&ia=images).
- a static site loads much faster as the files are pre-created (and no database is used)
- the pre-creation of the webpages makes the site more secure as malicious code while loading the pages cannot be injected (or is more difficult to do)
- a good comparison: https://youtu.be/_NZJW7IoGR4
- main advantages of static site generator: fast, more secure
- main disadvantages: you need some coding experience
- you can add CMS (a more visual environment i.e. a graphical user interface (GUI) to some static sites e.g. with [https://jamstack.org/](https://jamstack.org/) as demonstrated in [https://youtu.be/4wD00RT6d-g](https://youtu.be/4wD00RT6d-g)

<br>

## more resources
- [free website builders](https://youtu.be/myM1H_jAyzI)
- a [collection](https://github.com/collections/github-pages-examples) of nice GitHub Pages
- [colour psychology](https://www.verywellmind.com/color-psychology-2795824)
- https://marksheet.io/introduction.html
- https://www.flatfilecmslist.com/
- https://developers.google.com/web/fundamentals/
- https://devhints.io/jekyll
- https://ogp.me/
- https://moz.com/learn/seo/what-is-seo
- https://www.leadfeeder.com/blog/google-analytics-alternatives/
- https://talk.hyvor.com/blog/disqus-alternatives/
- https://www.codementor.io/
- https://www.vandelaydesign.com/beautiful-minimalist-websites/
- https://docs.github.com/en/pages
- https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize
- GitHub Desktop (backup and version control, can edit online or local, both there can be conflicts if not synced well) 
- https://html.com/
- https://www.webisland.agency/blog/

## GitHub 
1. Sign up to GitHub
 - you will need an email address (perhaps use your student email address)
 - your username must be your student number (ask me if you are unsure!)
 - use a good password (check the [pw.md](password-management.md) file for ideas)
2. Create a private repository
  - for your private notes
  - name it 'private notes'
  - initialise it with `README.md` file 
3. Fork my '[CS220AU-DP-2022](https://github.com/khofstadter/CS220AU-DP-2022)' repository
  - this will be the digital portfolio (your assignment to submit)
  - this repository will host your website as well

### Markdown language
Familiarise yourself with [Markdown language](https://guides.github.com/features/mastering-markdown/). A link to this guide can be found in the editor:

![](assets/img/github-editor-link-to-markdown-guide.jpg)

### thoughts
- choose 'soft wrap' instead of 'no wrap' in the GitHub editor
- there are slightly different Markdown styles, but in general they all work the same (stick to the above link with GitHub)
- we can monitor each other's progress in the public repositories. Please update it at least once a week. <!-- TODO: make example repo for private and public. Perhaps show examples of sonic art students from ARU. -->
- [is GitHub safe to use](https://youtu.be/vAfBW1_AZkU?t=597) (e.g regarding tracking and cookies)?

### GitHub-Markdown combo for project management

GitHub's advantages:

- free
- provides version backup
- accessible and editable on mobiles via browser
- repositories can be synced to your computer (cross-platform) and then you can use desktop software to edit your files (e.g. Visual Studio Code)
- you can drag and drop images to the editor (but I think it's better to upload it them to your `assets` folder to stay organised)
- can have [project boards](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards) similar like [Trello](https://trello.com/) if needed
- you can turn your files into a very fast website for free (can be static or more complex e.g. with [Jekyll themes](https://jekyllthemes.io/free).)


GitHub's disadvantage:

- might look unfamiliar (but it's easy to learn, and will look good on your CV too)

Markdown advantages:

- its simplicity helps focus on content
- if you can't find a Markdown function for your needs, you can extend your writing with HTML/CSS and even JavaScript


<!-- #todo
- how to embed/create graphs in the markdown files in the repository e.g. in the `readme.md` file?
- we can give feedback on each work in GitHub in different ways e.g. by raising an 'Issue' or collaborating and suggesting changes <!-- #todo make screencast -->

### some shortcuts in the editor
- CTRL+b makes the highlighted words **bold**
- CTRL+i makes the highlighted words _italic_
- if you have many files, hit the letter 't' and search for the file you want to edit

<!--
## Visual Code Studio
You can find a short screencast where I introduce how VSC [here](https://youtu.be/taFSpPeHs0o) can be used with GitHub repositories.
  
You can edit your files in both, your GitHub account via a browser or in VSC on your computer. The main advantages of using VSC on your computer are that
 - you can use VSC's extensions e.g. [Foam](https://foambubble.github.io/foam/) to help organise your thoughts in a more creative, systematic way (see more info about Foam below) [1]
 - VSC's editor itself provides further clarity e.g. with colour syntax an other tools e.g. search and replace for repetitive amendments
 - generate a table of contents from headings with the 'Markdown All in One' extension
 - export in PDF with a customisable CSS stylesheet
 - once you have more notes you can use Jekyll (a static website generator) to create a novel website from your thoughts, writings and assets (e.g. images, links)
-->

## further resources
- https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages
- https://www.markdownguide.org/getting-started/
- https://grantwinney.com/cool-markdown-tricks-for-github/
- [Google Docs has Markdown support](https://support.google.com/docs/answer/12014036?hl=en-GB)
- https://www.joshuarudd.com/typeset.css/
