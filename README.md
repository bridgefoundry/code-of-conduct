# Code of Conduct 

Published: [Code of Conduct](http://bridgefoundry.org/code-of-conduct/)

## TO DO

* Add License file (proposal sent to list for review)
* Add Contact Info


# Editing Instructions

Fork this repo -- this makes a copy in your github account

Edit markdown (.md) files at the root directory or functional/visual design in _layouts, javascripts, stylesheets.  

Do not directly edit anything in _sites

Send a pull request

## To make changes locally

We're using the [github-pages gem](https://github.com/github/pages-gem/blob/master/github-pages.gemspec#L16) to ensure we're using locally the same versions of gems that github uses when we publish. 

```
git clone git@github.com:yourname/code-of-conduct.git
cd code-of-conduct
bundle install
```

To run the site locally:
```
jekyll serve
```

View site at [http://localhost:4000](http://localhost:4000)

# Deploying 

This is deployed as part of the bridgefoundry.org website. People with org
permissions can trigger a build via Travis, if needed.

