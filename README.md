Wangana
==============

Wangan is responsive Jekyll theme, perfect for powering your GitHub hosted blog.
<iframe src="http://ghbtns.com/github-btn.html?user=mdo&repo=github-buttons&type=watch"
  allowtransparency="true" frameborder="0" scrolling="0" width="62" height="20"></iframe>
<table><tr><td><iframe src="http://ghbtns.com/github-btn.html?user=_nadjetey&repo=wangana&type=watch&count=true" height="30" width="118" frameborder="0" scrolling="0" style="width:118px; height: 30px;" allowTransparency="true"></iframe></td><td><iframe src="http://ghbtns.com/github-btn.html?user=_nadjetey&repo=wangana&type=fork&count=true" height="30" width="118" frameborder="0" scrolling="0" style="width:118px; height: 30px;" allowTransparency="true"></iframe></td><td><iframe src="http://ghbtns.com/github-btn.html?user=_nadjetey&type=follow&count=true" height="30" width="168" frameborder="0" scrolling="0" style="width:168px; height: 30px;" allowTransparency="true"></iframe></td></tr></table>
## Screenshots
==============

## Installation

``` bash
- Install Jekyll: `gem install jekyll`
- [Fork this repository][fork]
- Clone it: `git clone https://github.com/YOUR-USER/lagom`
- Run the jekyll server: `jekyll serve`
```
You should have a server up and running locally at <http://localhost:4000>.

## Theme customization
---
### Folder Structure

``` bash
so-simple-theme/
├── _includes/
├── _layouts/
|    ├── page.html  #page layout
|    └── post.html  #post layout
├── _posts/
├── assets/
|    ├── css/  #preprocessed less styles
|    ├── fonts/  #icon webfonts
|    ├── js/
|    |   ├── _main.js  #main JavaScript file, plugin settings, etc
|    |   ├── plugins  #jQuery plugins
|    |   └── vendor/  #jQuery and Modernizr
|    └── less/
├── images  #images for posts and pages
├── _config.yml  #Jekyll site options
├── about.md  #about page
├── articles.html  #lists all posts from latest to oldest
├── index.html  #homepage. lists 10 latest posts
```
Next you'll want to change a few things. Most of them can be changed directly in
[_config.yml][config]. That's where you can add your social links, change the accent
color, stuff like that.

## Copyright License
The MIT License (MIT), Copyright (c) 2014 Nii Adjetey Sowah. [Read full document.](LICENSE)

## Contact
I'd love to hear from you, [send me a tweet](https:). Feel free to [open issues](https://) if you
run into trouble or have suggestions. Pull Requests always welcome.


``` yaml
# Links to include in top navigation
# For external links add external: true
links:
  - title: Theme Setup
    url: /theme-setup
  - title: External Link
    url: http://mademistakes.com
    external: true
```


