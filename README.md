# holi-high
Static site for HHC - theme camp at Burning man

## How this site works
This is a static site which means there's no login or host to pay. The website is just generated from files. The only file we update regularly is the [_config.yml](https://github.com/emilymcmahon/holi-high/blob/gh-pages/_config.yml). That file controls the year, location, cannon information, etc.

Kristen Berman owns the CNAME holihighcamp.com. I have set it up so that CNAME points to this github pages. 

## How to update information
The only information we should be updating without a total revamp are [these settings](https://github.com/emilymcmahon/holi-high/blob/gh-pages/_config.yml#L5-L17). At the top right there's an "edit" button. Click it and make the changes you want. Then commit the changes and create a PR. Emily or John (or whoever is added as a repo admin) will approve the changes (note: this gating is required b/c the repo is public so we don't want anyone to be able to change this willy nilly). Once the change is merged, the magic of github pages will deploy the changes and they should be viewable within a minute. If not, your browser might be caching so try hitting with an incognito window. 
