# The Oppia Foundation

## Purpose
The Oppia Foundation website, located at [OppiaFoundation.org](http://OppiaFoundation.org), exists to communicate Oppia's mission and story to potential strategic partners. An individual who knows little to nothing about Oppia should come away from a visit to this website with a solid understanding of the problem Oppia aims to solve, how it aims to solve it, and why solving it is so important. In contributing to the Foundation site, please keep this purpose in mind at all times.


## Working w/ Jekyll
The Oppia Foundation website is built with Jekyll, a Ruby gem that compiles a bunch of stuff (HTML, CSS, YAML, Markdown, Liquid, etc.) into a nice static website that can be served from GitHub pages. It's very straightforward, especially if you've ever worked with a templating engine before. If you'd like to learn more about Jekyll, [you can do so here](https://jekyllrb.com).


### Getting Started

1. To begin, you'll need to have Ruby installed on your device. Mac computers come with Ruby preinstalled, but if you're on Linux or Windows [you can get it here](https://www.ruby-lang.org/en/documentation/installation).
2. You'll also need the "bundler" gem, which you can install by typing `gem install bundler` in terminal.
3. Once you have Ruby and Bundler, the next step is to fork and clone this repo.
4. `cd` into the repo and type `bundle install` to install all of the dependencies listed in the Gemfile.
5. You're all ready to go! Now, just type `bundle exec jekyll serve` to compile and serve the site locally at http://localhost:4000.

Jekyll comes with a nifty hotreloader, so the site will be recompiled and reserved locally every time you save any changes (with a few exceptions).


### Content Modifications

If you're modifying the site's content, there are a few primary places you'll want to know about.

If you're adding new images, please put them into the `/images` directory. If you're modifying copy, most of that will be located in the markdown file associated with the page the copy is on (e.g. `mission.md`). In cases where we have multiple pieces of copy in a similar format, that will generally be found in a YAML file under the `_data` directory. Finally, content in the header, footer, or head can be modified in the associated partial file under the `_includes` directory. (JavaScript currently lives in `_includes/_head.html`.)

### Style Modifications

We're using a modified version of the Minima theme, which comes as the default shipped with Jekyll. All of our modifications live in the `_sass/minima.scss` file, which overwrites the default Minima style. Please use the existing variables that are denoted at the top of the file when possible, and alphabetize attributes within a block of SASS.

## Questions? Comments?

Please let Jared know if you have any questions, comments, or concerns. The best way to get in touch with him is via email at jared@jaredsilver.name.
