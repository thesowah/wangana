![favicon](https://raw.github.com/nadjetey/wangana/master/favicon.png) Wangana - Jekyll Theme
==============

Wangana is responsive [Jekyll](http://jekyllrb.com/) theme, perfect for powering your GitHub hosted blog. See this theme live at [nadjetey.github.io](http://nadjetey.github.io)

## Contributing
1. Fork it ( https://github.com/nadjetey/wangana/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Issues
[Open](https://github.com/nadjetey/wangana/issues/new) issues if you run into trouble or have suggestions. Pull Requests always welcome.

## Installation & Usage
[Download](https://github.com/nadjetey/wangana/archive/master.zip) package and run the following code:
``` bat
$ bundle install
# Install all dependencies and setup coding environment

$ jekyll serve --watch
# Serve site locally. Now browse to http://localhost:4000
```
_Note:  Requires Ruby version 1.9 or above_

## Configuration
Edit: _config.yml (general options), main.css (theme colors & fonts)
``` bat
wangana/
├── _config.yml
├── _assets/
    ├── css/
        ├── main.scss
```

## Publish to Github Pages
1. Add your domain to _CNAME_
2. Edit your repo address at _Rakefile_

Run rake task. **NOTE: It will deploy the generated site to _gh-pages_ branch overwriting it**
``` bat
$ rake site:publish
```
_Thanks to [ksaa](https://github.com/ksaa) for rake tasks_

## Screenshot
![screenshot](https://raw.github.com/nadjetey/wangana/master/assets/images/wangana_screenshot_index.png)

## Author
Made with love from [@_nadjetey](https://twitter.com/_nadjetey).

## Copyright & License
The MIT License (MIT), Copyright (c) 2014 Nii Adjetey Sowah. [Read full document.](LICENSE)
