# holi-high
Static site for HHC - theme camp at Burning man

## How this site works
This is a static site which means there's no login or host to pay. The website is just generated from files. The only file we update regularly is the [_config.yml](https://github.com/emilymcmahon/holi-high/blob/gh-pages/_config.yml). That file controls the year, location, cannon information, etc.

Kristen Berman owns the CNAME holihighcamp.com. I have set it up so that CNAME points to this github pages. 

## How to update information
The only information we should be updating without a total revamp are [these settings](https://github.com/emilymcmahon/holi-high/blob/gh-pages/_config.yml#L5-L17). 
1. Get a github account and have Emily, John, or another admin add you as a collaborator
1. At the top right there's an "edit" button. Click it and make the changes you want.
2. Commit the changes to the `gh-pages` branch.![Screen Shot 2023-08-11 at 1 27 29 PM](https://github.com/emilymcmahon/holi-high/assets/541913/b36b38d6-74ca-4aea-8ea2-f437c168df91)

4. Once the change is merged, the magic of github pages will deploy the changes and they should be viewable within 5 minutes. If not, your browser might be caching so try hitting with an incognito window. 
