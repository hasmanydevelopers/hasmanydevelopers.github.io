---
layout: posts
author: p1nox
image: "/images/posts/jekyll-ghp.png"
excerpt: 
  Use [Github Pages](http://pages.github.com/) automatic generator and [Jekyll](http://jekyllrb.com/) for boost your own personal/project static website.
---

There is a time when a developer want to share his knowledge, or just say a few words, but you realise of a developer's things, originality, simplicity and freedom xD (is it just me?).

You take Wordpress, for example, dosen't cover any of those, it's too mainstream, too basic, and let say that got no developer's style ;).

There are some original and simple choices to test out:

* [Scriptogr.am](http://scriptogr.am/) or [Calepin.co](http://calepin.co/): where you can just sign in with your Dropbox account and create some files in your Dropbox directory with your favorite text editor on markdown. Very original, easy to edit and create posts (even with your phone with the dropbox app I think), but not configurable enough.

* [Github Gist](https://gist.github.com): gists works on many ways ;), you can create one even with a plugin in your text editor ([Sublime Text](sublimetext.com)), but a blog or a project website it isn't the target of Github Gist.

Here is where jumps [Github Pages](http://pages.github.com/) and the coolest thing is the using of [Jekyll](http://jekyllrb.com/) for it :D

![jekyll + github pages](https://dl.dropboxusercontent.com/u/4282792/jekyll-ghp.png)

Uses your Github account (every developer has one) creating a repository for this purpose and interpreting the content of a given branch with Jekyll to load your page.

### Personal website 

* Create a repository with a name like **YOUR_GH_USER_NAME.github.io**
* Go to the home of this repository *github.com/YOUR_GH_USER_NAME/YOUR_GH_USER_NAME.github.io* and click on **Settings** option.
* Go to **GitHub Pages** section and click on **Automatic Page Generator**, follow the instructions.
* Done! Now you got a repository with a master branch that will be used for deployment of your **YOUR_GH_USER_NAME.github.io** site.

### Project website

* In the home of your project's repository click on **Settings** option.
* Go to **GitHub Pages** section and click on **Automatic Page Generator**, follow the instructions.
* Done! Now you got a repository with a gh-pages branch that will be used for deployment of your **YOUR_GH_USER_NAME.github.io/PROJECT_NAME** site.

### Tuning your site

* Go to your terminal and install the Jekyll gem
    
      gem install jekyll

* Clone your site's repository, go to it's directory and run

      jekyll serve -w

* Done, now you have your site running on [http://localhost:4000](http://localhost:4000).

* Any change that you push to the master or the gh-pages branch it will be like a deployment to your site's production environment.

BTW this site was built with Github pages and Jekyll combination.

Here you can read some interesting things about this theme:

* [Github Pages Documentation](https://help.github.com/categories/20/articles)
* [Discus Jekyll Installation Instructions](http://help.disqus.com/customer/portal/articles/472138-jekyll-installation-instructions)
* [Generating html meta data with Jekyll](http://paradigmatic.streum.org/2011/02/generating-html-meta-data-with-jekyll/)
* [Adding AngularJS search in Jekyll blog](https://gist.github.com/RainerAtSpirit/3076150)
