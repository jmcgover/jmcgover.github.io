# Reminders

Below are a list of reminders for you.

## Jekyll Commands

### Run Local Instance
```bash
bundle exec jekyll serve
```

### Help
```bash
bundle exec jekyll help
```

Output:
```bash
jekyll 3.9.3 -- Jekyll is a blog-aware, static site generator in Ruby

Usage:

  jekyll <subcommand> [options]

Options:
        -s, --source [DIR]  Source directory (defaults to ./)
        -d, --destination [DIR]  Destination directory (defaults to ./_site)
            --safe         Safe mode (defaults to false)
        -p, --plugins PLUGINS_DIR1[,PLUGINS_DIR2[,...]]  Plugins directory (defaults to ./_plugins)
            --layouts DIR  Layouts directory (defaults to ./_layouts)
            --profile      Generate a Liquid rendering profile
        -h, --help         Show this message
        -v, --version      Print the name and version
        -t, --trace        Show the full backtrace when an error occurs

Subcommands:
  docs
  import
  build, b              Build your site
  clean                 Clean the site (removes site output and metadata file) without building.
  doctor, hyde          Search site and print specific deprecation warnings
  help                  Show the help message, optionally for a given subcommand.
  new                   Creates a new Jekyll site scaffold in PATH
  new-theme             Creates a new Jekyll theme scaffold
  serve, server, s      Serve your site locally
  draft                 Creates a new draft post with the given NAME
  post                  Creates a new post with the given NAME
  publish               Moves a draft into the _posts directory and sets the date
  unpublish             Moves a post back into the _drafts directory
  page                  Creates a new page with the given NAME
  rename                Moves a file to a given NAME and sets the title and date
  compose               Creates a new document with the given NAME
```


## Useful Articles
- [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)
- [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/)
- [A Beginner's Guide to SEO optimization in a Jekyll static website](https://jsinibardy.com/optimize-seo-jekyll)
    - [x] Use **HTTPS** (plus it’s so easy to enforce HTTPS with Github Pages!)
    - [ ] Declare the **HTML doctype** at the beginning of the page, along as the `<lang>` attribute
    - [ ] Have a valid **robots.txt** file
    - [ ] Use **consistent URLs**_ (either `/my_link` or `/my_link/` but not a mix of both)
    - [ ] Use the `alt` **attribute** on your images, both for ranking and accessibility reasons
    - [ ] Choose a discernable name for your **links**
    - [ ] Make all **external links** `_blank` and `nofollow` `noopener`
    - [ ] Create a **netlinking** strategy, to improve your pagerank and enhance the Internet user’s journey
    - [ ] Frequently run [Lighthouse audits](https://developers.google.com/web/tools/lighthouse/) on your pages and fix every problematic item
    - [ ] …and a bunch of other stuff **(LIKE WHAT)**
- [Jekyll::Compose](https://github.com/jekyll/jekyll-compose)


## TODO
### Posts
- [ ] First Post

#### Jeff Does the Math
- [ ] Finishing games before the Game Awards
- [ ] How long to beat all of my games

#### Reviews
- [ ] Super Mario RPG (1996)
- [ ] Starfield (2023)
- [ ] Baldur's Gate 3 (2023)
- [ ] Super Mario RPG (2023)
- [ ] Super Mario Wonder (2023)
- [ ] Tears of the Kingdom (2023)
- [ ] God of War (2018)

### Documentation
- [ ] Update / Install Jekyll stuff
- [ ] Post using that Jekyll extension
- [x] Serve locally
### Features
- [ ] Last Modified
    - [ ] Link to latest commit
    - [ ] Figure out what makes GitHub Pages' way of loading websites incompatible with running commands
    - [ ] Play with some ideas to use `git log` to create a log file that the HTML can lookup
    - [ ] Create a changlist at the bottom of each page, assuming we can use the above point
    - [x] Show "Page Last Modified"
- [ ] Social Links
    - [ ] Make them dynamic in my setup thingy somehow?
    - [ ] Discord
    - [ ] Bluesky
    - [ ] Threads
    - [ ] Untappd
    - [ ] Mastodon
    - [x] GitHub account
    - [x] RSS Feed
- [ ] Webpage Icon
    - [ ] Get it to work on Google search results
    - [ ] Make it randomize itself or something
    - [x] Make it a ghost
