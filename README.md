# modern-resume-theme [![Gem Version](https://badge.fury.io/rb/modern-resume-theme.svg)](https://badge.fury.io/rb/modern-resume-theme) [![Build Status](https://travis-ci.org/sproogen/modern-resume-theme.svg?branch=master)](https://travis-ci.org/sproogen/modern-resume-theme)

*A modern simple static resume template. Powered by Jekyll and GitHub pages.*  

Based on [this repo](https://github.com/sproogen/modern-resume-theme)

## Usage

Before starting it might be useful to familiarise yourself with [Jekyll](https://jekyllrb.com/docs/home/), [Markdown](https://www.markdownguide.org/getting-started) and [GitHub pages](https://pages.github.com/).

#### Customization
##### _config.yml
This will contain all the of the main configuration for resume such as your name, email, social media links and about me content. It will also allow you to change the titles of some of the content sections.

##### _data/education.yml
A list of all your education

##### _data/experience.yml
A list of all your experience

## Development

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally.

1. Fork and or clone this repository locally
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

*Note: You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*
