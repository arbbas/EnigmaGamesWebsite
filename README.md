# example-jekyll-gitpod

Sample repository for a [Jekyll](https://jekyllrb.com/)-based website using the [Minima](https://github.com/jekyll/minima/) theme, with [Gitpod](https://gitpod.io/) support.

The resulting website is available at [https://bluezio.github.io/example-jekyll-gitpod/](https://bluezio.github.io/example-jekyll-gitpod/).

To use Gitpod to edit the site, install the [browser extension](https://www.gitpod.io/docs/browser-extension/) and click on the "Gitpod" button.

## Local editing

First, install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Bundler](https://bundler.io/).

Next, clone this repository, and install its dependencies:

```shell
bundle install
```

Start the live preview:

```shell
bundle exec jekyll serve
```

You can now preview the site at [http://localhost:4000](http://localhost:4000).
Feel free to make any changes and then reload your page in the browser.

## Publishing to Github Pages

If you have just created a new repository from this template, you will need to enable Github Pages for your repository to have the site built and served automatically.
Check Step 2 of [these instructions](https://dev.to/github/how-to-use-github-pages-to-host-your-website-even-with-multiple-repos-27k2).
