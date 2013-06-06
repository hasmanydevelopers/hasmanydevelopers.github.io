---
layout: posts
author: p1nox
image: "/images/posts/jekyll-ghp.png"
excerpt: 
  Use [Github Pages](http://pages.github.com/) automatic generator and [Jekyll](http://jekyllrb.com/) to boost your own personal/project static website.
---

There comes a time when a developer wants to share his knowledge, or just speak a few words to the world, but as a developer you don't want a "mainstream" solution.

Lets take WordPress for example, it dosen't cover any of those, it's too mainstream, too basic, too insecure and it has nothing of a developer's style ;)

There are some original and simple choices to test out:

* [Scriptogr.am](http://scriptogr.am/) or [Calepin.co](http://calepin.co/): where you can just sign in with your Dropbox account and create some files in your Dropbox directory with your favorite text editor on markdown. Very original, it's easy to edit and create posts (even in your phone with the dropbox app I think), but it's not configurable enough.

* [Github Gist](https://gist.github.com): gists works on many ways ;) you can create one even with a plugin in your text editor ([Sublime Text](sublimetext.com)), but a blog or a project website isn't the target of Github's Gist.

Here is where [Github Pages](http://pages.github.com/) shines and the coolest thing yo do is using it with [Jekyll](http://jekyllrb.com/) :D

![jekyll + github pages](/images/posts/jekyll-ghp.png)

It uses your Github account (every developer has one) with a repository for this purpose and processes the content of a given branch with Jekyll to generate your site pages.

### How to create Personal website?

* Create a repository with a name like **YOUR_GH_USER_NAME.github.io**
* Go to the home of this repository *github.com/YOUR_GH_USER_NAME/YOUR_GH_USER_NAME.github.io* and click on the **Settings** option.
* Go to **GitHub Pages** section and click on **Automatic Page Generator**, follow the instructions.
* Done! Now you got a repository with a master branch that will be used for the deployment of your **YOUR_GH_USER_NAME.github.io** site.

### How to create project website?

* In the home of your project's repository click on the **Settings** option.
* Go to **GitHub Pages** section and click on **Automatic Page Generator**, follow the instructions.
* Done! Now you got a repository with a gh-pages branch that will be used for deployment of your **YOUR_GH_USER_NAME.github.io/PROJECT_NAME** site.

### Tuning your site!

* Go to your terminal and install the Jekyll gem
    
      gem install jekyll

* Clone your site's repository, go to it's directory and run

      jekyll serve -w

* Done, now you have your site running on [http://localhost:4000](http://localhost:4000).

* Any change that you push to the master or the gh-pages branch it will be like a deployment to your site's production environment.

BTW this site was built with Github pages and Jekyll combination :)

Here I leave you some interesting links:

* [Github Pages Documentation](https://help.github.com/categories/20/articles)
* [Discus Jekyll Installation Instructions](http://help.disqus.com/customer/portal/articles/472138-jekyll-installation-instructions)
* [Generating html meta data with Jekyll](http://paradigmatic.streum.org/2011/02/generating-html-meta-data-with-jekyll/)
* [Adding AngularJS search in Jekyll blog](https://gist.github.com/RainerAtSpirit/3076150)
