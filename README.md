# AiiDAlab landing page

Landing page for the AiiDAlab project.
The website is currently under development and can be reached at: https://aiidalab.net .

## Develop

This page is built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well and based on the [Hydra template](https://github.com/CloudCannon/hydra-jekyll-template).

Install `jekyll` and `bundler`:

```bash
sudo apt install ruby-dev
sudo gem install jekyll bundler
sudo gem install public_suffix -v '4.0.6' --source 'https://rubygems.org/'
```

Install the dependencies with [Bundler](http://bundler.io/):

```bash
$ bundle install
```

Run `jekyll` commands through Bundler to ensure you're using the right versions:

```bash
$ bundle exec jekyll serve
```

## Editing

Hydra is already optimised for adding, updating and removing pages, staff, advice, company details and footer elements in CloudCannon.

### Posts

- Add, update or remove a post in the _Posts_ collection.
- The **Staff Author** field links to members in the **Staff** collection.
- Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
- Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

- Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
- Sends email to the address listed in company details.

### Staff

- Reused around the site to save multiple editing locations.
- Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

- Exposed as a data file to give clients better access.
- Set in the _Data_ / _Navigation_ section.

### Footer

- Exposed as a data file to give clients better access.
- Set in the _Data_ / _Footer_ section.
