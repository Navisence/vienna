# Vienna

## Overview

Vienna is a simple and clean blog theme for [Hugo](http://gohugo.io/).
Notable features are:

- Simple and clean design
- Client side source code highlighting
- Social links (Twitter, Facebook, GitHub, LinkedIn, Google+, Instagram, Keybase)
- Comments with Disqus
- Support for tags
- Analytics with Google Analytics or Mixpanel
- Responsive design
- Font Awesome icons

## Installation

In your hugo site directory, run:

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/keichi/vienna
```

Vienna is also included in the `spf13/hugoThemes` repository.

## Configuration

You may specify following options in `config.toml` of your site to make use of
this theme's features.

```toml
baseurl = "Your site URL"
languageCode = "en-us"
title = "Your site title"
# Copyright notice. This is displayer in the footer.
copyright = "&copy; Copyright notice"

[params]
    # Social accounts. Link to these accounts are displayed in the header and
    # footer.
    twitter = "Your Twitter username"
    github = "Your GitHub username"
    linkedin = "Your LinkedIn username"
    googleplus = "Your Google+ user id"
    facebook = "Your Facebook username"
    stackoverflow = "Your Stackoverflow user id (number)"
    keybase = "Your keybase.io username"
    instagram = "Your Instagram username"
    # Disqus shortname
    disqus = "Your disqus shortname"
    # Google Analytics API key.
    ga_api_key = "Your Google Analytics tracking id"
    # Mixpanel API key.
    mixpanel_api_key = "Your Mixpanel API key"
    author = "Your Name"
    avatar = "/path/to/avatar"
    contact = "Your contact link (ex. mailto:foo@example.com)"
    bio = "Your short bio"
    # Short subtitle/tagline. This is displayed in the header.
    subtitle = "Short subtitle/tagline of your blog"
    themecolor = "#hexcolor" # Defines the tab color in Chrome for Android.
    # Add link to an info/about page
    info = "/page/about"
    # Show recent posts in footer
    recentPosts = true
    recentPostDisplayCount = 5 # Change as you wish
    # Show tags in footer
    tags = true
```

You may specify following options in `front matter` of your posts to make use of
this theme's features.

```toml
noshowdate = true # This will ensure that the date is not printed
```

## Usage

Use hugo's `-t vienna` or `--theme=vienna` option with hugo commands.
Example:

```shell
$ hugo server -t vienna -w -D
```

